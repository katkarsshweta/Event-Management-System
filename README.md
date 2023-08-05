# Event Management System

### Problem Statement :

Our mini project is an online event management system project that serves the functionality 
of an event manager.
The system allows only the event manager to login on the application. The system helps in the 
management of dates of events .
The project provides most of the basic functionality required for an 
event type[Marriage,Parties,Conference meetings,etc.]
The system then allows you to enter the date and venue of the event. 

### The key features and functions of the project are :
1. Entering customer details which mainly includes date ,venue of event.

2. The customers are stored in a queue based on the date of the event.

3. Takes full payment once the event is done.

4. The customer is given an invoice once the booking is done.

5. Displays the list of upcoming events.

6. Keeps the record of the payments till date.

7. Displays all the successful events done.

8. Calculates average ratings given by customers.

### List of all the data structures 

Data structures

1. Queue using linked list

A Queue is a linear data structure. This data structure follows a particular order in which the operations are performed. The order is First In First Out (FIFO). It means that the customer whose date of event is first will enter first in queue and will also be leaving the queue first, once the event is done.

2. Linked List

A Linked list is a dynamic arrangement that contains a access link to the structure containing the subsequent items. Every node contains some data and a pointer to the next node of the same data type. The node contains a pointer to the next node means that the node stores the address of the next node in the sequence. To line up all the events we have used a linked list. Also the events which are done are stored in a linked list. Time complexity of search:O(n)

3. Arraylist (Collection framework)

The main advantages of ArrayList is, if we declare an array then it is needed to mention the size but in ArrayList, it is not necessary to mention the size of 
ArrayList if you want to mention the size then you can do it.As the number of customers is not fixed. We have used arraylist to store payments and ratings.
