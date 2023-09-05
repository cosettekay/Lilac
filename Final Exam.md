## BST (Binary Search Trees)

## Queues
- Array Implementation
	- Problem with letting queue[0] be the queue's front
		- inefficient; would need to shift each array element by one position toward the beginning of the array
	- Using a circular array
		```java
		backIndex = (backIndex + 1) % queue.length

		// however, frontIndex equals backIndex + 1 both when the queue is empty and when it is full
```
Solution: Circular Array with One Unused Location
- Leaving unused the array location that follows the back of the queue

- When the queue is full
```java
frontIndex equals (backIndex + 2) % queue.length
```

- When the queue is empty
```java
frontIndex equals (backIndex + 1) % queue.length
```
- When the array is full, we need to resize array by doubling its size

Linked Implementation
- Adding to the back
	- Situation 1: an empty chain
	- Situation 2: a non-empty chain
- Removing the front entry
	- Situation 1: a chain with more than one entry
	- Situation 2: a chain with only one entry
- It is possible to use Circular Linked Implementations of a Queue