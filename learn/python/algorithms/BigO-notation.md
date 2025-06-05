How to calculate the time complexity to execute any algorithm using the worse case to avoid it

Allows to take decisions about what algorithm use, aim the most efficient for the performance and scalability in real systems.
![[Pasted image 20250604205406.png]]
Recommended complexity order 
![[Pasted image 20250604205452.png]]

- Calculate the number of statements into a function:
```python
def function():
	print("messsage")
	print("messsage")
	print("messsage")
	print("messsage")
```
- Complexity: O(4)
	- Does not depends on the number of imports
	- Called  constant complexity represented -> 1(0)
```python
def function(items):
	for i in items:
		print(items)
```
- Complexity: O(4)
	- items -> 1
	- print -> 2
	- items printed -> 3
	- i -> 4
	- Complexity depends on the number of items gave -> linear complexity

- Complexities
	- Linear
![[Pasted image 20250604205018.png]]
	- Quadratic
![[Pasted image 20250604205100.png]]
	- Constant
![[Pasted image 20250604205131.png]]
	- Exponential
![[Pasted image 20250604205201.png]]
	- Logarithmic
![[Pasted image 20250604205241.png]]