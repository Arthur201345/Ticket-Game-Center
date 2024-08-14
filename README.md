# Ticket-Game-Center-Management-System
The Game Center Ticket Management System is a versatile web-based application designed for managing tickets in a gaming facility. This system facilitates the creation, modification, viewing, renewal, and deletion of tickets for both clients and workers, streamlining the management process.

Key Features:
Add Tickets:

Clients: Create tickets for clients with a 3-year validity period. Each ticket includes a user name, a unique ticket ID (no real id needed just copy id from ticket or test it), and the ticket type. The system will automatically calculate and display the expiration date.
Workers: Create tickets for workers that do not expire. Provide a user name, a unique ticket ID, and specify the ticket type.
Modify Tickets:

Edit Existing Tickets: Update ticket details such as user name, ticket ID, and type. The form automatically switches to "Edit Ticket" mode, allowing for easy modifications. Changes are saved and reflected in the list immediately.
View Tickets:

Ticket List: A comprehensive table displays all tickets with columns for user name, ticket ID, type, status, and actions. Each ticket’s status is color-coded to indicate whether it is valid or expired.
Ticket Status:

Clients: For client tickets, the status shows whether the ticket is valid or expired. If valid, the remaining time until expiration is displayed. Expired tickets are marked in red.
Workers: Worker tickets are marked with "No Expiry" since they do not have an expiration date.
Renew Tickets:

Client Tickets: Expired client tickets can be renewed for an additional 3 years. The renew button is only enabled when the ticket has expired, ensuring it cannot be renewed prematurely.
Delete Tickets:

Removal: Tickets can be permanently deleted from the system. This action removes the ticket from the display table and local storage.
Local Storage Integration:

Persistent Data: Tickets are saved in local storage, ensuring that data persists across page reloads and browser sessions.
User-Friendly Interface:

Responsive Design: The interface is designed to be clean and easy to navigate, with buttons for adding, editing, renewing, and deleting tickets.
Action Buttons: Clear and distinct buttons for each action, with appropriate spacing and hover effects for improved usability.
Usage:
Adding Tickets: Enter the user name, ticket ID, and select the ticket type to add a new ticket.
Modifying Tickets: Click the "Edit" button next to a ticket to update its details. Submit the form to save changes.
Viewing Tickets: Check the list of tickets to monitor their status and manage them as needed.
Renewing Tickets: Renew expired client tickets to extend their validity for another 3 years.
Deleting Tickets: Remove tickets from the system when they are no longer needed.
Technical Details:
Technologies Used: HTML, CSS, JavaScript
Local Storage: Utilized for data persistence
The Game Center Ticket Management System is an essential tool for any game center or similar venue, providing efficient ticket management and a user-friendly experience.

Feel free to adjust the description further based on specific features or requirements.













