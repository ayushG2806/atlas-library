# Atlas Library — Library Management System

**RDBMS academic project | Manipal University Jaipur**

## Overview

Atlas Library is a browser-based interface for common library-management tasks, including maintaining book and member records, searching the catalogue, and recording book issue and return activity.

## Features

- Dashboard with book, member, issued-book, and overdue counts
- Add, search, and delete book records
- Register and manage library members
- Issue books and record returns
- Filter the loan register and browse the catalogue
- Export records from the interface
- Save changes in browser `localStorage`
- Responsive layout for desktop and smaller screens

## Run locally on macOS

1. Clone this repository or download the ZIP archive.
2. Open the `atlas-library` project folder.
3. Double-click `index.html`.
4. Open it in Safari or Chrome if prompted.
5. Use **Books**, **Members**, **Issue & Return**, and **Catalogue** to try the main workflows.

Alternatively, run this command from Terminal:

```bash
open index.html
```

No Node.js, npm, build step, or local server is required for this frontend.

## Project files

- `index.html` — interface, styles, sample records, and JavaScript logic.
- `README.md` — project overview and setup instructions.

## Data storage and database scope

The current version stores changes in the browser's `localStorage`. It does not connect to MySQL or a backend API. The Categories, Books, Members, and Loans schema described in the project report is a proposed relational design, not a live database in this version.

## Possible future improvements

- Implement the proposed schema in MySQL.
- Add a backend API and connect the interface to it.
- Enforce foreign keys and server-side validation.
- Use database transactions for issue and return operations.
- Add authentication and role-based access.

## Repository

https://github.com/ayushG2806/atlas-library
