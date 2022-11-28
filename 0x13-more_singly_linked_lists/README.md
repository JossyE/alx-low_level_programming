0x13. C - More singly linked lists
How to use linked lists
File: 0-print_listint.c
A function that prints all the elements of a listint_t list.
Return: the number of nodes

File: 1-listint_len.c
A function that returns the number of elements in a linked listint_t list.

File: 2-add_nodeint.c
A function that adds a new node at the beginning of a listint_t list.
Return: the address of the new element, or NULL if it failed

File: 3-add_nodeint_end.c
A function that adds a new node at the end of a listint_t list.
Return: the address of the new element, or NULL if it failed

File: 4-free_listint.c
A function that frees a listint_t list.

File: 5-free_listint2.c
A function that frees a listint_t list.
The function sets the head to NULL

File: 6-pop_listint.c
A function that deletes the head node of a listint_t linked list, and returns the head node’s data (n).
if the linked list is empty return 0

File: 7-get_nodeint.c
A function that returns the nth node of a listint_t linked list.
where index is the index of the node, starting at 0
if the node does not exist, return NULL

File: 8-sum_listint.c
A function that returns the sum of all the data (n) of a listint_t linked list.
if the list is empty, return 0

File: 9-insert_nodeint.c
a function that inserts a new node at a given position.
where idx is the index of the list where the new node should be added. Index starts at 0
Returns: the address of the new node, or NULL if it failed
if it is not possible to add the new node at index idx, do not add the new node and return NULL

file: 10-delete_nodeint.c
a function that deletes the node at index index of a listint_t linked list.

where index is the index of the node that should be deleted. Index starts at 0
Returns: 1 if it succeeded, -1 if it failed

File: 100-reverse_listint.c
a function that deletes the node at index index of a listint_t linked list.
where index is the index of the node that should be deleted. Index starts at 0
Returns: 1 if it succeeded, -1 if it failed

File: 101-print_listint_safe.c
a function that prints a listint_t linked list.
Returns: the number of nodes in the list
This function can print lists with a loop
You should go through the list only once
If the function fails, exit the program with status 98

File: 102-free_listint_safe.c
a function that frees a listint_t list.
This function can free lists with a loop
You should go though the list only once
Returns: the size of the list that was free’d
The function sets the head to NULL

File: 103-find_loop.c
a function that finds the loop in a linked list.
Returns: The address of the node where the loop starts, or NULL if there is no loop
