# Reading notes class 5

## Teach something that you learned from the readings listed below

Some ideas for how you might want to teach:

- Use an analogy
- Explain a detail in depth
- Use WHY, WHAT, HOW structure
- utorial / walk through an example
- Write a quiz
- Create a vocabulary/definition list
- Write a cheat sheet
- Create a diagram / visualization / cartoon of a topic
- Anthropomorphize the concepts, and write a conversation between them
- Build a map of the information
- Construct a fill-in-the-blank worksheet for the topic

## Resources

[Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html) (Up through the section titled “Linear Complexity Growth”)

[Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

[What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

[What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
<br/>
<br/>

I decided to create an analogy to explain a linked list:

Imagine a train with multiple cars. Each car represents a node in the linked list, and they are connected by linking each car to the next one. In this analogy, the train itself represents the linked list. The train engine, which pulls the train, is similar to the head of the linked list. It serves as the reference point to the first node. Each train car (node) contains some cargo (data) and a link (reference) to the next train car. This link indicates the connection between the current car and the next car in the sequence.

To traverse the linked list, we start from the engine (head) and move to the next car by following the links between the cars. We keep moving until we reach the end of the train (null reference), indicating that we have reached the end of the linked list.

Adding a new node to the linked list is like adding a new train car to the existing train. To add a car, we create a new car (node) and link it to the next car in the list. We then update the link of the previous car to point to the new car, effectively inserting the new car into the sequence.