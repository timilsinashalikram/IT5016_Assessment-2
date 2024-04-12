Explanation of the code:

The code defines two classes: Ticket and TicketSystem.

Ticket class:
The Ticket class is responsible for creating ticket objects. These objects have attributes such as number, creator, staff_id, email, description, response, and status. The __init__ method is used as a constructor to initialize these attributes when a new Ticket object is created.

TicketSystem class:
The TicketSystem class is used to manage a list of tickets. When a new TicketSystem object is created, the __init__ method initializes an empty list called tickets. The add_ticket method is used to add a new ticket to this list. The display_tickets method iterates over each ticket in the list and prints out their details, including number, creator, staff ID, email, description, response, and status. The display_statistics method calculates and displays statistics about the tickets, such as the total number of tickets created, resolved, and the number of tickets that are yet to be solved.

Ticket objects:
In this code, three Ticket objects (ticket1, ticket2, ticket3) are created with different attributes. Each ticket represents a specific issue or request and has details such as the ticket number, creator, staff ID, email, description, response, and status.

TicketSystem object:
An instance of the TicketSystem class called ticket_system is created. The add_ticket method is called three times to add the three ticket objects to the list of tickets in the ticket_system object. The display_tickets method is then called to print out the details of each ticket in the system.

Finally, the display_statistics method is called to show the overall statistics of the tickets in the system, including the total number of tickets created, resolved, and the number of tickets that are yet to be solved.

#Here are the used attributes and their description:
Attributes:
    - number: The unique identifier for the ticket.
    - creator: The name of the person who created the ticket.
    - staff_id: The ID of the staff member assigned to the ticket.
    - email: The email address associated with the ticket.
    - description: The description of the issue or request.
    - response: The response provided by the staff member.
    - status: The current status of the ticket.
