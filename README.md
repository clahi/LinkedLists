# Singly Linked List.
A singly linked list, in its simplest form, is a collection of nodes that collectively
form a linear sequence. Each node stores a reference to an object that is an element
of the sequence, as well as a reference to the next node of the list

## Circularly Linked Lists.
A circularly linked list provides a more general model than a standard linked
list for data sets that are cyclic, that is, which do not have any particular notion of a
beginning and end.

# Doubly Linked Lists.
To provide greater symmetry, we define a linked list in which each node keeps
an explicit reference to the node before it and a reference to the node after it. Such
a structure is known as a doubly linked list. These lists allow a greater variety of
O(1)-time update operations, including insertions and deletions at arbitrary positions within the list.

# Positional List.
To provide for a general abstraction of a sequence of elements with the ability to
identify the location of an element, we define a positional list ADT as well as a
simpler position abstract data type to describe a location within a list. A position
acts as a marker or token within the broader positional list. A position p is unaffected by changes elsewhere in a list; the only way in which a position becomes
invalid is if an explicit command is issued to delete it
