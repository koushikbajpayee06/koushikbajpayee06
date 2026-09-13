# Koushik Bajpayee

**Full-Stack Developer building AI applications with React, Python, and FastAPI.**

I build web interfaces, backend APIs, and document retrieval workflows. My current projects focus on connecting these layers through clear data contracts, validation, and useful loading and error states.

**Explore my work:** [DocuMind AI](https://github.com/koushikbajpayee06/documind-ai) · [BookBazaar](https://github.com/koushikbajpayee06/BookBazaar)

[LinkedIn](https://www.linkedin.com/in/koushikbajpayee07/) · [Email](mailto:kbajpayee06@gmail.com) · [All repositories](https://github.com/koushikbajpayee06?tab=repositories)

Open to Full-Stack, Backend, and AI Application Developer opportunities.

## Selected Projects

### DocuMind AI — Document Ingestion and Semantic Search

A document application being developed toward retrieval-augmented question answering. The current implementation extracts document text, creates chunks, generates embeddings, and retrieves relevant passages.

**Implemented**
- PDF, TXT, and Markdown text extraction.
- Recursive text splitting with source metadata.
- OpenAI embeddings and a persistent Chroma vector store.
- Semantic-search API returning matching content and metadata.
- React interface with document upload and backend health feedback.

**Technical highlight:** Chunk indexing attaches source information, chunk indices, and SHA-256-derived document IDs. Retrieval returns this metadata alongside the matching text.

**Current boundary:** Semantic retrieval is implemented. Generated answers grounded in retrieved context remain a next step.

**Stack:** React, FastAPI, Python, LangChain integrations, OpenAI embeddings, ChromaDB, Pydantic Settings.

[Source and setup](https://github.com/koushikbajpayee06/documind-ai)

### BookBazaar — Online Bookstore

A React storefront connected to a FastAPI and SQLite backend for browsing books and managing catalogue entries.

**Implemented**
- API helpers for book listing and individual book retrieval.
- Combined title/author search, category filtering, and minimum rating.
- Ordered pagination using limit and offset.
- Backend JWT authentication and reusable role checks.
- Book creation, partial updates, and deletion.
- Ownership checks: authors manage their own listings; admins can manage all books.
- Frontend registration with submission and error states.
- Redux cart persisted in browser localStorage.

**Technical highlight:** The backend combines role authorization with record ownership checks. Frontend API helpers map backend field names to the existing component data shape.

**Current boundary:** Frontend login/logout, authenticated cart synchronization, and order workflows remain in progress. The cart currently lives in the browser.

**Stack:** React, Tailwind CSS, Redux Toolkit, FastAPI, SQLAlchemy, Pydantic v2, SQLite.

[Source and setup](https://github.com/koushikbajpayee06/BookBazaar)

## Technologies Used in These Projects

| Area | Technologies |
| --- | --- |
| Frontend | React, JavaScript, Vite, Tailwind CSS |
| Client state and routing | Redux Toolkit, React Redux, React Router |
| Backend | Python, FastAPI, SQLAlchemy |
| Validation and configuration | Pydantic v2, Pydantic Settings |
| Authentication | JWT, python-jose, Passlib, bcrypt |
| Document retrieval | LangChain integrations, OpenAI embeddings, ChromaDB |
| Data storage | SQLite, Chroma persistence, browser localStorage |
| Development tools | Git, GitHub, npm, uv |

## Engineering Topics I Am Practising

- Frontend/backend integration and API data contracts.
- Authentication, role authorization, and resource ownership.
- Input validation and partial-update semantics.
- Combined filtering and predictable pagination.
- React state, request handling, and browser persistence.
- Document chunking, embeddings, and retrieval metadata.

## Current Focus

- Complete BookBazaar's frontend authentication and order workflows.
- Extend DocuMind AI from retrieval to grounded answer generation.
- Add automated tests and reproducible deployment steps.
- Deepen my understanding of retrieval evaluation, LangGraph workflows, and Transformer fundamentals.

## Explore and Run

Each project repository contains its own README with setup instructions, dependencies, and implementation details. Start with the source links above to inspect or run a project.

This repository contains my GitHub profile presentation; it is not a standalone application.
