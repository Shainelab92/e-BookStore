# e-BookStore

Minimal fullstack TypeScript example (Vite + React frontend, Express backend).

Setup (PowerShell):

```powershell
# from project root
npm install

# Run both frontend and backend in dev mode
npm run dev

# Or run individually
npm --workspace=backend run dev
npm --workspace=frontend run dev
```

Backend: `http://localhost:4000/api/books`
Frontend: `http://localhost:5173`

Remote development (Gitpod / Codespaces)
-------------------------------------

Quick start (Gitpod):

1. Push this repository to GitHub.
2. Open Gitpod with the repo URL, for example:

	`https://gitpod.io/#https://github.com/<your-username>/<your-repo>`

Gitpod will run `npm install` then `npm run dev` and open the frontend preview for port 5173.

Codespaces / Dev Container (VS Code):

1. Push this repository to GitHub.
2. In GitHub choose **Code → Open with Codespaces → New codespace** (or open in VS Code and choose "Reopen in Container").
3. Codespaces will provision the container using `.devcontainer/devcontainer.json`, run `npm install`, and forward ports `5173` and `4000` for the frontend and backend.

Manual start (after the remote environment is ready):

```powershell
npm run dev
```

Notes:
- Ensure the repo branch you open is `main` (or change the Gitpod/Codespaces branch accordingly).
- The dev containers forward ports so you can use the Codespaces preview or the browser preview in Gitpod.

