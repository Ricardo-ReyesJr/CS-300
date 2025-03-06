# CS-300 DSA

Create a node
Assign an input to the node
If the head of the list is empty, assign another node to the head and the tail.
Else make the tail point to the node
Make the new node the tail.

Create a new node assign an input to this node
If the head is empty assign to the head and the tail
Else make a node point it to the head, them make it a new node to the head.

Start the head node 
While the element is exists, output attributes. 
Increment the element to the next point in the list

If item that has been selected is the head node remove it.
While the elements exists, and while the elements are not equal
Check if the element is the key,
If it is, assign to a temp value
If not check next
Delete temp
Assign new node
While element exists
If the element equals the key return the element.
Increment to the next
If not element matches the key return empty


¬¬¬
Create a public hash table.
Define the method for insert, print, remove and the search.
Resize the hash to a tableSize
Create the keys for the table.
Create the insert method.

Assign the current bid node to key.
Search node with key value
If no node for key assign current key
Else
While loop to find another node.

Create the print method.
Assign user entry to the key.
Erase the node. 
Create search.
Assign user entry to key.
If the list is not empty point key
Iterate through the table till the key is found.
Return value.
Read file;
Use fstream to open file
Call to open file
If the value returns -1 
Return file not found
Else return file found

While != EOF
Read each line
If the value is less than two lines return ERROR
Else read parameters
If there is 3 or more parameters
And if the 3 or more parameters in first else where continue
Else ERROR
Close file

Object structure;
Initialize course structure
Loop file while not EOF
For each line
For first and second value 
Add ID and course name
 If 3 continue
Else ERROR

Tree and Node;
Define class
Create root point to null
Create insert method
If root null course is root
Else course is num less than root
If left is null add course num
Else if num < add leaf left
If num > add leaf right
Else ERROR

Runtime Analysis

Code	Line Cost	# Times Executes	Total Cost
for all elements	1	n	n
     if the element is the same as currentElement	1	n	n
         print out the Value	1	1	1
         for each prerequisite of the Element	1	n	n
           print the prerequisite Value 	1	1	1
Total Cost	3n+2
Runtime	O(n^2)

