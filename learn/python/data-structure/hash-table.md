It is also called a map, hash map or a dictionary, key and value structure. It can be use with different types of data, (string, number, float, etc)

- complexity: n(1)
- to store the values, the hash table should pass for a concept called hashing function and then the hashing function will assign a index to store its value depends on the key.
- the hash table can have collisions and to fix it we should apply:
	- separate chaining -> if the value has the same index -> we use linked list
	- open addressing
