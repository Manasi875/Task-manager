# WorkPilot

A responsive Task & Ticket Management System interface for **Vertex Consulting**.

## Run it

Open `index.html` in any modern browser. No installation or server is required.

## Authentication

| Role | Email | Password |
| --- | --- | --- |
| Manager | manager@vertexconsulting.com | workpilot |
| Employee | employee@vertexconsulting.com | workpilot |

The sign-in flow is intentionally client-side because this is a browser-only prototype. For production, authenticate through a Flask backend, securely hash passwords, use server-side sessions or signed tokens, and store users and tickets in PostgreSQL.

Use **Create an account** on the sign-in screen to register with your own name, email address, password, and role. New accounts and created tickets are saved in that browser using local storage.

## Source files

- `index.html` — application structure and sign-in interface
- `styles.css` — responsive visual design
- `app.js` — browser-local authentication, ticket data, filters, Kanban board, and interactions
- `enhancements.js` — employee management, ticket editing, and three-dot ticket actions

## Management actions

- Add, edit, or remove employees from the Team members page.
- Click any ticket title/card to edit its details.
- Use the three-dot menu on a ticket to edit, submit for review, complete, or delete it.
