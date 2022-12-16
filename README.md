Project monty 
by
KudraDube
Earthunes
What do LIFO and FIFO mean

LIFO :- (Last in, First Out)
A method used to account for inventory that records the most recently produced items as sold first.

FIFO :-(First in, First out)
Is an asset-management and valuation method in which assets produced or acquired first are sold, used or disposed of first

What is a stack, and when to use it
STACK :- A stack is an array or list structure of function calls and parameters used in modern computer programming and CPU architecture. Similar to a stack of plates at a buffet restaurant or cafeteria, elements in a stack are added or removed from the top of the stack, in a “last in first, first out” or LIFO order.

What is a queue, and when to use it
Queue :- Queue is an abstract data structure, somewhat similar to Stacks. Unlike stacks, a queue is open at both its ends. One end is always used to insert data (enqueue) and the other is used to remove data (dequeue). Queue follows First-In-First-Out methodology, i.e., the data item stored first will be accessed first.

What are the common implementations of stacks and queues
You can perform the implementation of stacks in data structures using two data structures that are an array and a linked list.

Array: In array implementation, the stack is formed using an array. All the operations are performed using arrays. You will see how all operations can be implemented on the stack in data structures using an array data structure.

Linked-List: Every new element is inserted as a top element in the linked list implementation of stacks in data structures. That means every newly inserted element is pointed to the top. Whenever you want to remove an element from the stack, remove the node indicated by the top, by moving the top to its previous node in the list.

To implement a queue using an array, 

create an array arr of size n and 
take two variables front and rear both of which will be initialized to 0 which means the queue is currently empty. 
Element 
rear is the index up to which the elements are stored in the array and 
front is the index of the first element of the array. 

Now, some of the implementations of queue operations are as follows: 

Enqueue: Addition of an element to the queue. Adding an element will be performed after checking whether the queue is full or not. If rear < n which indicates that the array is not full then store the element at arr[rear] and increment rear by 1 but if rear == n then it is said to be an Overflow condition as the array is full.
Dequeue: Removal of an element from the queue. An element can only be deleted when there is at least an element to delete i.e. rear > 0. Now, the element at arr[front] can be deleted but all the remaining elements have to shift to the left by one position in order for the dequeue operation to delete the second element from the left on another dequeue operation.
Front: Get the front element from the queue i.e. arr[front] if the queue is not empty.
Display: Print all elements of the queue. If the queue is non-empty, traverse and print all the elements from the index front to rear.

What are the most common use cases of stacks and queues

Generally, a common usage of the stack data structure is for a quick forward/backwards navigation within an app.
Let’s take for example an internet browser, on which we get a back navigational button. Keeping track of the URLs a user has visited is a good use case for a stack. With the URL of the current site a user is viewing, to be on the top of the stack we can move backwards by popping URLs from the stack.
Another cool usage is implementing an undo feature in text editors. We store previous text edits in a stack and go back through it.
Additionally, take a look at the code below that reverses a given string by utilizing a simple java stack data structure

Generally, we use a queue whenever we want to process items in the same order as they requested processing.
Some common usages of a queue data structure are when, for example, an application implements a first in first serve principle such as IO buffers and files IO asynchronous requests.
Other similar use cases we may want to use a queue, is when we share resources with other apps or systems such as CPU (i.e. multithreading) and DISK scheduling.
Queues are also used in searches such as a Breadth-First Search method of a graph or tree as well as in CACHE systems.
In general, it is a good practice to use a queue data structure when you have multiple requests to serve at once but not the ability to do so. It is fair to serve them in a FIFO principle.
To show you a practical example where we can use a queue, I wrote below a java method that searches a tree if it has a path to a given node.

What is the proper way to use global variables

Global Variables can be used in:

Automations,
Email templates,
Pop-ups,
Bot messages,
Tickets,
HTML blocks.

