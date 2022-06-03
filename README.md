# MyLinkedList
creating own link list
In this reposotory, I will create a class that partially reimplements the LIST class from C++ standard library. This class called MyLinkedList. MyLinkedList must store data in a linked list.

Create a class called MyLinkList which stores ints. MyLinkList have three constructors:

a default constructor that creates a MyLinkList that can contain 10 ints, 
a one-parameter constructor that takes one int and creates a MyLinkList that can contain that number of ints
a two-parameter constructor that takes two ints. The first is used to determine the number of elements the MyLinkList can initially store, the second is used to initialize those values. (so MyLinkList(2, 3) creates a two-element array with both elements initialized to 3
MyLinkList have the following member functions:


A function called pushBack which adds a new element to the end of the list
A function called popBack which returns the last element of the list and also removes it from the list.
A function called insert which takes two parameters -- an int to insert, and the index to insert it at. If the insertion is past the current end of the list, place it at the end of the list. Shift all elements past the insertion point to accommodate the new item.
A function called remove which takes one parameter (an index) and removes the element at that index. Shift all elements past the removal point down to avoid leaving gaps in your list
A function called at which takes an int as parameter and returns a reference to that index of the array. Print an error message and use exit(0) to end the program if the index is not in the list
Note: since it returns a reference, .at() can be used to both print values in the array and assign values to the array.
A destructor to delete when your MyLinkList goes out of scope.
certainly have to declare a number of private instance variables to implement this class.

implement a copy constructor -- a constructor that takes a reference to another MyLinkedList as a parameter, and produces a new MyLinkedList with the same contents as the original. 

implement the following overloaded operators:

operator<< 

operator[]

Note that implementing a full linked list can be tricky! Insertion and deletion from the middle of a linked list can require thinking about a number of edge cases -- you will have to write functions that work when there's 0 items in the list, when there's 1 item in the list, and when there's many items in the list. I very, very, very strongly recommend drawing the list out on paper and thinking through the steps required to insert items, instead of just diving straight in to writing code.
