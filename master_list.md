#### HTML
##### Rules of HTML
- Almost all html elements has an opening and closing tag 
- There are some elements that are self closing tag 
- The html page should be named index.html as web servers will look for this homepage in a website

-Q1) What is HTML? <br/>
- It is the structure of a webpage.


#### Lesson Takeaway
- Line break
- navigation bar
- todo list
- table (v impt)
- form (v impt)


  
<img src="/assets/html_example.PNG" alt="MarineGEO circle logo" width="50%"/>  
-Q2) Identify the html elements in the above webpage

- Search Bar 
- Navigation bar  
- Images 
- Text 
- Shortcut menu 
- Page structure 
- Hyperlinks 
- Lists 
    
-Q3) Identify the css elements in the above webpage 

- Background color 
- Font color 
- Font size 
- Font style 
- Borders 

-Q4) What is the purpose of an opening and closing tags 
- It informs the browser the start and end of an element in a webpage <br/>

#### CSS
-Q1) What is CSS? 
- It creates the styling of a webpage 

#### Lesson Takeaway
- background color  <br/>
- inline style  <br/>
- font size  <br/>
- font color  <br/>

#### Javascript
-Q1) What is Javascript ? 
- It makes the website interactive 

-Q2) What makes a website interactive ? 
- If a user is able to change the shape of a website by an action, it is considered interactive

#### Lesson Takeaway
- Javascript is case sensitive <br/>
- Every line must be closed with a semicolon ; </br>
- Javascript makes a webpage dynamic and responsive </br>
- Variables: container to store something  <br/>
- var, let: declaring a variable
- Data types: string,double,float,integer,boolean  <br/>
- Operators:  <br/>
- document.write: able to show x value in the document <br/>
- document.element id: getting an element by its id to use it <br/>
- Alert window: shows an alert window in the browser <br/>
- prompt: prompt the user to input a value. the value will be a string <br/>
- parse(): converts one data type to another <br/>
- fixed: round off the number to specified decimal places <br/>
- If else: do x if it meets the criteria, otherwise do y <br/>
- while loop: while this condition is true, repeat action till condition is false <br/>
- function: re=reuns the code everytime it is called </br>
- Function can be activated by various way such as by event such as mouse click or by loading webpage </br>
- Example of events are mouse click , keypress trigger <br/>

#### Java Server Pages



### CE212
#### Lesson 1 - 4 
###### Data Structures and Algos 

### Lesson 3
- Q1) What is a Binary Tree data structure? 
- It is a tree like data structure. <br/>

- Q2) Example of a binary tree data structure <br/>
<img src="/assets/binary_tree.png" alt="Binary Tree Example" width="15%"/> 

- A is the root 
- Each entry is a node 
- Every node is connected by links called edges which defines the relationships between 
- Every node has a parent above it except the root 
- Each node has a left or right child or none or both 
- Every node can have a maximum of 2 nodes hence it is called a binary tree 
- A node with no children is called a leaf 
- A node contains a value or data 
- There are two subtrees in the example above (b,d,e and c,f,g) 
- The height of a tree is the length of the longest path to the leaf 
- In the example above, the height of a tree is 4 
- The size of a tree is the number of nodes 
- In the example above, the size of a treee is 9
- The depth of a node is the length of the path from the root that particular node 
- In the example above, the depth of node 3 is 3 
- The height of a node is measured from the node to the deepest leaf 
- In the example above, the height of node 2 is 4
- Formula to calculate height of tree and max nodes in the tree are 
- Height: h 
- Max nodes in the tree: 2^h+1 - 1

-Q3) Definition of tree traversal ?
- Tree traversal is a process where it visits all the nodes in the tree 
- There are two types of tree traversal 
- Type 1: Depth first search (PreOrder,InOrder,PostOrder)
- Type 2: Breadth first search (LevelOrder)

-Q4) How do we traverse a tree ? <br/>
- Method 1: PreOrder
- Steps: Visit parent first and left children first then right children.
- In the example above, the preorder output is 8,5,9,7,1,12,2,4,11,3

  - Method 2: InOrder
  - Steps: Visit left children then the parent then right children.
  - In the example above, the inorder ouput is 9,5,1,7,2,12,8,4,3,11

    - Method 3: PostOrder
    - Steps: Visit left children then the right child then the parent.
    - In the example above, the postorder output is 9,1,2,12,7,5,3,11,4,8

      - Method 4: LevelOrder
      - Steps: Visit the nodes at the same level from left to right before moving on to the next level
      - In the example above, the levelorder output is 8,5,4,9,7,11,1,12,3,2

-Q5) Binary Search <br/>
- Binary Search is a search algorithm for finding an element's position in a sorted array <br/>
- Binary Search can only be implemented only on a sorted list of items. <br/>
- You would like to find the value 4 in the example bellow <br/>
<img src="/assets/binary_search.png" alt="Binary Search Example" width="15%"/> 

- Step 1: Set two points low and high at the lowest and highest positions 
- Low: 3 
- High: 9
- Step 2: Find the middle array which is 6
- If x is greater than middle value, compare with the middle elements on the right side of the array </br>
- If x is smalller than middle value, compare with the middle elements on the left side of the array </br>
- Step 3: Repeat the previous steps till there is middle element between low and high value </br>

-Q) What affects the speed and efficiency of an algorithm? <br/>
- Asymptiotic notations help to measure the efficiency of an algorithm
- Examples: Big O Notation, Omega notation and Theta notation </br>

-Q) What is the Heap property ?
- It is a complete tree.
- Levels are filled from left to riht
- Nodes are fillled from the left to right
- Value of node is greater than or equal (Heap property


-Q) What are the types of heap complete tree
- Max Heap: Root node has the largest value and the value gets smaller as we progress in each level of the tree <br/>
- Min Heap: Root has the smallest value <br/>


##### Useful Resources 
- https://www.programiz.com/dsa/selection-sort
- https://www.cs.yale.edu/homes/aspnes/pinewiki/BinaryTrees.html
- https://www.andrew.cmu.edu/course/15-121/lectures/Trees/trees.html
- http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html#trees
- https://opendsa-server.cs.vt.edu/ODSA/Books/CS3/html/BinaryTree.html
- https://people.orie.cornell.edu/snp32/orie_6125/data-structures/binary-tree.html
