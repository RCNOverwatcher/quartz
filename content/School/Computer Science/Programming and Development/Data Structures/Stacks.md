---
banner: "![[computerscience.jpg]]"
---
<div class="title">​</div>
<div class="title">​</div>

# Stacks

### Main info
·         Can be implemented within an array

·         Dynamic data structure

·         Data cannot be directly accessed.

### Properties of a stack

·         If a stack is empty, TOP = 0

·         The TOP variable defines how many elements there are in a stack

·         Items are pushed (added) to a stack

·         Items are popped (removed) from a stack

·         If the stack becomes full, no more data can be added to it without first removing some data (overflow error)

·         E.G. If you try and store the value 384 in a byte, which is impossible because a byte can only hold a maximum value of 255

### How stacks are used in computers

·         If an interrupt happens in a CPU, then the CPU needs to drop all the tasks it is doing and complete the interrupt handling routine

·         The tasks it is doing beforehand need to be continued after the interrupt, and therefore it needs to store these instructions before they are dropped by the CPU

·         In this case, a stack is used to store the important instructions (in registers)

·         When the interrupt handling routine is finished, it pops all the instructions back into the registers and the CPU carries on what it was doing beforehand

### Reversing a stack

·         In a queue, elements are added to the back and removed from the front like a supermarket queue

·         To reverse a queue, push all the elements in the queue onto the stack

·         Then, pop all the elements out of the stack and onto the queue, one by one

·         The queue is now reversed
