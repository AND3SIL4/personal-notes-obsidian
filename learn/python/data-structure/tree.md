concepts:
- node
- edges: lines that link the nodes
- leaf nodes: nodes with any children node
- root node
- parent node
- length: the most distance of the tree
	- node height: the most distance of the node


- binary tree:
	- only have 2 values for each node
	- there is not sorting order in the nodes
	- can be one of two types:
		- unbalanced trees
			- insertion and search: O(log n)
			- ![[Pasted image 20250529212901.png]]
		- balanced trees
			- insertion and search: O(n)
			- ![[Pasted image 20250529212811.png]]
		- traversing trees:
			- inorder: left + root + right
			- preorder: root + left + right
			- postorder: left + right + root
	- Full binary tree: 0 or 2 children each node
	- Complete binary tree: 2 children each node
	- 