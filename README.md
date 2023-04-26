# Queue using array

A queue in C is basically a linear data structure to store and manipulate the data elements. It follows the order of First In First Out (FIFO).

In queues, the first element entered into the array is the first element to be removed from the array.

A queue is open at both ends. One end is provided for the insertion of data and the other end for the deletion of data.

# Operations Associated with a Queue in C
A queue being an Abstract Data Structure provides the following operations for manipulation on the data elements:

isEmpty(): To check if the queue is empty

isFull(): To check whether the queue is full or not

dequeue(): Removes the element from the frontal side of the queue

enqueue(): It inserts elements to the end of the queue

Front: Pointer element responsible for fetching the first element from the queue

Rear: Pointer element responsible for fetching the last element from the queue

![image](https://user-images.githubusercontent.com/70435939/234463253-41e8a17b-1747-44e1-9849-10a82a058fee.png)

# Algorithm

Step 1: IF REAR = MAX - 1
Write OVERFLOW
Go to step
[END OF IF]

Step 2: IF FRONT = -1 and REAR = -1
SET FRONT = REAR = 0
ELSE
SET REAR = REAR + 1
[END OF IF]

Step 3: Set QUEUE[REAR] = NUM

Step 4: EXIT

# Applications of queue

1. Batch Processing: Queues can be used to handle batch processing jobs, such as data analysis or image rendering.

 2. Message Buffering: Queues can be used to buffer messages in communication systems, such as message queues in messaging systems or buffers in computer networks.
 
3. Event Handling: Queues can be used to handle events in event-driven systems, such as GUI applications or simulation systems.

4. Traffic Management: Queues can be used to manage traffic flow in transportation systems, such as airport control systems or road networks.
