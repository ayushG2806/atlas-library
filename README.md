# Atlas Library — Library Management System

**Student:** Ayush Garg  
**Registration Number:** 2502050843  
**Section:** F4  
**Course project:** RDBMS

## About the project

Atlas Library is a browser-based library management interface I developed as part of my RDBMS project. It provides a simple interface for working with book and library records.

## Technology

- HTML
- CSS
- JavaScript
- Browser `localStorage` for client-side persistence

> **Database scope:** The current version is a frontend prototype and stores its data in the browser. It does not connect to a live MySQL server. The relational schema discussed in the report is a proposed database design.

## Run locally on macOS

1. Download or clone this repository.
2. Open the project folder in Finder.
3. Double-click `index.html` to open it in your browser.

Alternatively, from Terminal, change to the project directory and run:

```bash
open index.html
```

No package installation or build step is required for this static frontend.

## Project files

- `index.html` — the application interface and client-side logic
- `README.md` — project overview and setup instructions

## Notes

Data saved using browser `localStorage` remains in the same browser profile on the same device and is not a shared multi-user database. A production version would require a backend and a configured database.

## Repository

https://github.com/ayushG2806/atlas-library
