# Ticket-Game-Center-Management-System
The Game Center Ticket Management System is a web-based application designed to streamline the management of tickets for a gaming facility. This tool allows you to efficiently handle tickets for both clients and workers, offering functionalities for adding, viewing, renewing, and deleting tickets.

Features:
Add Tickets:

Clients: Tickets for clients are issued with a 3-year expiration period. When adding a client ticket, you provide a user name, a unique ticket ID, and specify the ticket type as 'Client'.
Workers: Tickets for workers do not expire. When adding a worker ticket, you provide a user name, a unique ticket ID, and specify the ticket type as 'Worker'.
View Tickets:

The website displays a list of all tickets in a table format. Each ticket shows:
User Name
Ticket ID
Type (Client or Worker)
Status (Valid or Expired with appropriate color coding)
Actions (Renew or Delete)
Ticket Status:

Clients: For client tickets, the status indicates whether the ticket is still valid or has expired. If valid, it shows the remaining time until expiration. If expired, it is marked in red as 'Expired'.
Workers: Worker tickets are marked as having 'No Expiry' since they do not expire.
Renew Tickets:

Clients: Once a client ticket has expired, you can renew it for an additional 3 years. The renew button becomes enabled only after the ticket has expired.
Workers: No renewal option is available as worker tickets do not expire.
Delete Tickets:

Tickets can be removed from the system using the delete button. This action removes the ticket from both the display table and local storage.
Local Storage Integration:

The website uses local storage to save and retrieve ticket information, ensuring that your ticket data persists across page reloads and browser sessions.
Usage:
Add Ticket: Use the provided form to input the user name, ticket ID, and ticket type, then submit the form to create a new ticket.
Manage Tickets: View the list of tickets, check their status, renew expired client tickets, or delete tickets as needed.
Technical Details:
Technologies Used: HTML, CSS, JavaScript
Local Storage: Utilized to persist ticket data
This system provides an efficient and user-friendly way to manage and track ticket statuses, making it an essential tool for any game center or similar venue where ticket management is required.

Feel free to modify or expand this description based on additional details or features specific to your implementation.






