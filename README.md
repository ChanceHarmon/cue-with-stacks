Queue With Stacks

# Challenge Summary
Use stacks to code an enqueue and dequeue

## Challenge Description
Using a queue, represent a fifo structure using 2 lifo structure Stacks.

## Approach & Efficiency
In the first stack, pop off and push the nodes to the 2nd stack. when the operation is complete, pop off the top of stack 2, and return the nodes value, effectively reversing the lifo operation of stacks into a fifo operation of a queue.

## Solution
see assets directory