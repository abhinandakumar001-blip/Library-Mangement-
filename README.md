# Leafline — Library Management Website

A responsive library management dashboard built with **HTML, CSS and vanilla JavaScript**. No framework or backend is required.

## Run it
1. Download and extract the ZIP.
2. Open `index.html` in a modern browser.
3. Try adding books and members, issuing a book, and recording a return.

## Features
- Modern responsive dashboard with collection, loan, member and overdue stats
- Book catalog with search, category and availability filters
- Add, edit and delete books
- Register and remove members
- Issue books to members with issue and due dates
- Return workflow and automatic overdue status
- Browser `localStorage` persistence
- Dark mode
- Mobile navigation and toast feedback
- Seeded sample data so the dashboard is populated on first launch

## Project structure
- `index.html` — page structure and modal
- `styles.css` — layout, visual design, responsive styles and dark mode
- `script.js` — data, rendering, forms, filters and interactions

## Important limitations
This is a front-end learning project. Data is stored only in the current browser using `localStorage`; it is not shared across devices or users, and there is no real login, server, database, fine calculation or email notification. A production system would need a backend, authentication, authorization, and a database.

## Suggested extensions
1. Add a member dashboard and member login.
2. Add book cover uploads or external book-cover APIs.
3. Add CSV export for books and loan records.
4. Add reservation/waitlist support when all copies are borrowed.
5. Add backend persistence with a REST API and database.
