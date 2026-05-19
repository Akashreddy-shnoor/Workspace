# Shnoor Workspace Project

This repository combines the Frontend and Backend components of the Shnoor project into a unified monorepo structure.

## Repository Structure

```
workspace-project/
├── backend/      # Node.js / Express backend service
└── frontend/     # React / Vite / Tailwind frontend application
```

## Getting Started

Follow the instructions below to run both services locally.

### 1. Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/) or another package manager of your choice

---

### 2. Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure your environmental variables:
   Create a `.env` file in the `backend/` directory and configure the database and other credentials.
4. Run the development server:
   ```bash
   npm run dev
   ```

---

### 3. Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure your environmental variables:
   Create a `.env` file in the `frontend/` directory with any specific API URLs.
4. Run the development server:
   ```bash
   npm run dev
   ```
