# Recommended Tech Stack

This document records the proposed direction for implementation. The
repository is currently a small Node.js and TypeScript starter; it has not yet
been migrated to this stack.

## Application

- **Framework:** Next.js, recommended as a popular TypeScript framework that
  supports server-rendered pages and server-side application logic.
- **Language:** TypeScript for application code, including server-side code.
- **UI:** React, provided by Next.js, for the agent and staff experiences.
- **Database:** SQLite for clinic data such as agents, ailments, therapies,
  and appointments.

## Guiding choices

- Keep the initial application small and easy to run for students and demos.
- Use server-side code for database access; do not expose database access to
  the browser.
- Favor a responsive, accessible interface that works in modern browsers.
- Add supporting libraries only when a concrete implementation need is clear.
