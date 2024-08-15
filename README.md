# Ticket-Game-Center-Management-System
The Game Center Ticket Management System is a web-based application designed to manage and track tickets for a game center facility. This system supports both user authentication and ticket management, providing functionality for both clients and workers. Users can create accounts, log in, and manage tickets, while client tickets automatically expire after 3 years unless renewed.

Key Features:
User Authentication:

Landing Page: Users are presented with a choice to either sign up for a new account or log in to an existing one.
Sign-Up Page: Users create an account by providing their email, password, and company name.
Login Page: Users log in with their registered email and password.
Profile Page: After logging in, users are redirected to their profile page where they can view their company name, email, and log out.
Ticket Management:

Add Tickets: Users can create tickets for clients or workers. Client tickets are valid for 3 years, while worker tickets do not expire.
View Tickets: A table displays all created tickets with user name, ticket ID, type (client or worker), and status (valid, expired, or no expiry for workers).
Ticket Status: For client tickets, the system automatically tracks expiration. Expired tickets are marked in red, while valid tickets show the remaining time until expiration.
Renew Tickets: Users can renew client tickets for another 3 years, but only after they have expired.
Delete Tickets: Tickets can be removed from the system when they are no longer needed.
Profile & Persistence:

Profile Management: Users can view their profile, including company name and email, after logging in.
Local Storage: All user accounts, login sessions, and tickets are stored in local storage to persist data across sessions.
User-Friendly Interface:

Responsive Design: The system features a clean and simple interface that works seamlessly across devices.
Navigation: Clear buttons and inputs guide users through the process of managing their profile and tickets.
Session Management: Logged-in users stay authenticated across sessions until they log out, and their data is retained.
Usage:
Sign Up: Users create an account by entering their email, password, and company name.
Login: Returning users log in to manage their tickets.
Ticket Management: Once logged in, users can create, view, renew, or delete tickets, with clients being able to track their ticket's expiration status.
Technologies Used:
HTML, CSS, JavaScript: The entire system is built using web technologies, ensuring easy accessibility from any browser.
Local Storage: Used to store user and ticket data, providing persistent login and ticket status tracking.
This description highlights the user authentication, ticket management system, and how clients and workers can manage their tickets within the application.

(no real id needed just copy ticket id and put the type of ticket)

feel free to change the code how ever you want
