# Support Ticket Assistant

A portfolio project for helping support agents classify incoming tickets,
find relevant help-center evidence, and prepare response drafts for human review.

## Project status

Repository setup is complete. Application features will be added and tested in
stages; this README will be expanded as those features are implemented.

## Planned stack

- Backend: Python and FastAPI
- Frontend: React and TypeScript
- Database: PostgreSQL with pgvector
- Backend tests: pytest
- Local development: Docker Compose

## Safety and review

The application is designed to prepare drafts for a support agent to review.
It must not send customer responses automatically. The demo dataset will use
fictional articles and tickets.

Do not commit API keys, passwords, `.env` files, or real customer information.
Use `.env.example` for variable names and safe sample values only.
