# deep-research

## Project Context

This repository contains a full-stack chatbot application with the following structure:

- **Frontend:** Built with [Remix](https://remix.run/) and React, located in the `app/` directory. The frontend is responsible for the user interface and will communicate with the backend via HTTP requests.
- **Backend:** A Python FastAPI server located in the `chatbot_server/` directory. This server will handle chatbot logic and API endpoints.
- **Dependency Management:**
	- **Node.js/Remix:** Managed via `package.json`.
	- **Python/FastAPI:** Managed via Poetry (`pyproject.toml`).

## Initial Setup (as of August 2025)

- Created the basic Remix app structure with entry points, root layout, and a placeholder Chatbot component.
- Configured the Remix dev server to run on port 3000.
- Added a FastAPI backend with CORS enabled and a root endpoint for health checks.
- Added Poetry for Python dependency management.
- Installed all required dependencies for both frontend and backend.
- Confirmed that the frontend builds and runs, and documented the favicon warning as non-blocking.

## Next Steps
- Implement the actual chatbot logic in the FastAPI backend.
- Connect the Remix frontend to the backend via API calls.
- Add styling and improve the Chatbot UI.

---

> This README is intended to provide context for future development and for AI assistants to understand the project structure and history.
