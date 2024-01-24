# This is the monty project


# C - Stacks, Queues - LIFO, FIFO
## Learning Objectives 
* What do LIFO and FIFO mean
	* Those means to the way a list, which is a sequencial array of items are introduce or extracted in a list LIFO (Last In, First Out) and FIFO (First in, First out)
* What is a stack and when to use it.
	* A stack is a sequence of items that the In and Out proccess are done trought the same door called `TOP`, It is usually used when we want to reverse the order of the items that are added, Being the first item entry also the last to exit.
* What is a queue and when to use it.
	* A queue is used to set the items in the order we put it, being the first item entry the last to exit 
* What are common implementations of stacks and queues.
	* Stack `Task that require backtraking like parsing expressions or undo functionalities`
	* Queue `It is used when we want to preccess elements in a specific order like handling requests or schedualing tasks`.
* The most common used cases of stacks and queues
	* Stack: 1. Back and forward buttons in web browser.<br />
		 2. UNDO/REDO function on text editors.<br />
		 3. Memory management in computer programming.<br />
		 4. Delimiter checking.<br />
		 5. Implementing recursion in programming
	* Queues: 1. Schedualing jobs and ensure execution.<br />
		  2. Queues can be used to manage the order in which print jobs are send to the printer.
		  3. Queues are used to implement the breadth-first search algorithm.
* What are the proper ways to used a global variable.
	* Variables should always have as small a scope as possible. The argument behind this is that every time you increase the scope, you have more code that potentially modifies the variable, thus more complexity is induced in the solution.

It is thus clear that avoiding using global variables is preferred if the design and implementation naturally allow that. Due to this, I prefer not to use global variables unless they are really needed. 
Some good examples where global variables are used are singleton pattern implementations or register access in embedded systems.
