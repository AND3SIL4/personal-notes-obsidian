Three based data structure, is related with the trees data structure
To access the minimum or maximum value quickly
- Complete binary tree: 
- One of two types: 
- Min heap: each parent node is less than the children value(parent) <= value(child)
- Max heap: each parent node is less than the children value(parent) >= value(child)
- Insert: top to bottom and left to right
	- Min heap: top to bottom and left to right and compare the node with the parent and bubble
	- Max heap: top to bottom and left to right and compare the node with the parent and bubble
- Delete:
	- delete the root node
		- move the last node to the root
		- compare and bubble down if needed
	- Min heap: delete the smaller item
	- Max heap: delete the greater value