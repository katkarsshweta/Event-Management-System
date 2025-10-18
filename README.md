# Event Management System
**Technology:** Java, Java Collections Framework

## Problem Statement
This project is an **online event management system** that serves the functionality of an event manager. The system allows only the event manager to log in to the application. It helps in managing the dates of events and provides basic functionalities required for different event types such as Marriage, Parties, Conference meetings, etc. The system allows the event manager to enter the date and venue of each event.

---

## Key Features and Functions
- Enter customer details, including the date and venue of the event.  
- Store customers in a **queue** based on the date of the event.  
- Take full payment once the event is completed.  
- Generate an invoice for the customer after booking.  
- Display a list of upcoming events.  
- Maintain a record of payments to date.  
- Display all successfully completed events.  
- Calculate average ratings given by customers.  

---

## List of Data Structures

### Queue using Linked List
A Queue is a linear data structure that follows the **First In First Out (FIFO)** principle.  
- The customer whose event date is first enters the queue first and leaves first once the event is completed.  

### Linked List
A Linked List is a dynamic structure where each node contains data and a pointer to the next node.  
- Used to line up all events and store completed events.  
- **Time Complexity of Search:** O(n)

### ArrayList (Collection Framework)
ArrayList allows dynamic resizing, unlike arrays where the size must be predefined.  
- Used to store payments and ratings since the number of customers is not fixed.  
- Supports flexible operations without specifying size in advance.  

---

## How It Works
1. The event manager logs into the system.  
2. Customer details (event date and venue) are entered.  
3. Customers are queued based on event dates.  
4. Payments are recorded once events are completed.  
5. Invoices are generated for customers.  
6. Upcoming events, completed events, and payment records can be viewed.  
7. Average ratings are calculated for events.  

---

## Future Enhancements
- Add support for multiple event managers.  
- Implement notifications for upcoming events.  
- Integrate a GUI for easier user interaction.  
