# Linked Lists

## Notes

- Sequence of nodes, each node references the next node in the link
- Starts at the head, first node in the list
- When traversing each node has a reference to the next node (and previous in doubly linked)
- Unlike arrays which are static in size, linked lists are dynamic
- Types:
  - Singly: each node points to the next, one direction
  - Doubly: each node has a reference to the next and previous, both directions
  - Circular: the last node (tail) points to the head instead of null as in other types

## Lesson

| Array | Linked List |
|-------|-------------|
| Static Size | Dynamic Size |
| Creates a new array when size changes| Same list can grow or shrink |
| Faster Search | Slower Search |
| Searching by index is faster | Searching requires traversing the list |
| Access by Index | Traversal of List |
| Can access elements by their index | Can access elements by traversing the list |
| Use Cases: | Use Cases: |
| Known list size | Unknown list size |
| Fixed list size | Dynamic list size |
| Access to all elements | Access to beginning and end |
| Iterate through elements | Traverse through nodes |

## References

- [Code Fellows: Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)
- [Medium: What’s a Linked List, Anyway? Part 1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)
- [What’s a Linked List, Anyway? Part 2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)
