# FlexboxStudyProject
Study Flexbox

# Reference
Flexbox Crash Course
https://www.youtube.com/watch?v=3YW65K6LcIA

- Flex container
	- properties
		- flex-direction
			- can be column and row
		- flex-wrap 
			- use for wrap element to next line
		- flex-flow
		- justify-content
			- the main axis
		- align-items
			- the cross axis
		- align-content
- Flex items
	- properties
		- order
			- can be 1, 2, 3 and etc, it changes the order of element
		- flex-grow
			- can be 1, 2, 3 and etc, it changes the ratio with them get enlarge
		- flex-shrink
			- can be 1, 2, 3 and etc, it changes the ratio with them get smaller
		- flex-basis
		- align-self
			- can be start, end, center, just like align-items and justify-content

- to use flexbox is css
	- we use keyword display:flex
     - e.g.

    ```
    .container{
      display:flex;
    }
    ```
     
- by default it will put all child element in "row"
- if you want column, you add flex-direction: column
  - e.g.
     
    ```
    .container{
      display:flex;
      flex-direction: column;
    }
    ```
		
the Axes
- there are two properties in flexbox that control main axis and cross axis
	1. justify-content
			- justify-content means main
	2. align-items
			- align-items means cross
			
	- What is main and cross
	- image you have a container
	- and you are using flex with direction row
		- Main = Horizotal
		- Cross = Vertical

	
	- when you are using flex with direction column
		- Main = Vertical
		- Cross = Horizotal
		
- you can set alignment in main and cross
	- e.g.
   ```
  .container{
    display:flex;
    flex-direction: row;
    justify-content: space-between; //seperate items to start and end
    justify-content: center; // items in the center
    justify-content: start; //items in the start
    justify-content: end; //items in the end
    justify-content: space-evenly; //seperate items with same space
  }
  ```
