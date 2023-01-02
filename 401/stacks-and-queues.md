# Stacks and Queues

## Stacks and Queue

Stacks and queues are types of ways to structure data. Common operations for stacks are

- push, which pushes a node or item in a stack,
- pop, which takes a node/item out of a stack,
- top, which is the top of the stack,
- peek, which allows you to see the top node value and
- isEmpty to return true if the stack is empty.

A main concept is FILO and LIFO,

- First In, Last Out meaning the bottom of the stack is the first item and is pushed out last

- Last in, First Out meaning the last item in, which should be at the top of the stack is pushed out first

Pushing top out, pop.top and set next top as top.next.

Push O(1) = same amount of time no matter the n when pushing/popping each item 

`node = new Node(value)`

`node.next -> Top`

`top -> Node`

Pop O(1)

`Node temp -> top`

`top -> top.next`

`temp.next -> NULL`

`return temp.value`

Peek O(1)

`return top.value`

isEmpty O(1)

`return top = NULL`

Queue is similar to a linked list

- Enqueue node/item added to a queue

- Dequeue node/item removed from queue

- Front is first/front node

- Rear is rear/last node

- Peek will view the value at the front

- isEmpty returns when queue is empty

Similar functionality between the stack calls 

## Things I want to know more about

## Resources 

[Stacks and Queues](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-10/resources/stacks_and_queues.html)
