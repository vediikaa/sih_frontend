# SIH Frontend

This is a small React + Vite + Tailwind frontend wired to:
API_BASE = https://sih-backend-rp57.onrender.com

## To deploy on Render (no local installs required)
1. Create a new GitHub repository.
2. Upload these files (browser upload).
3. On Render, create a **Static Site**:
   - Connect the GitHub repo.
   - Build Command: `npm run build`
   - Publish Directory: `dist`
   - Environment: Node (default)
4. Deploy — Render will run `npm install` and build for you.

## To run locally (optional)
If you want to run locally, install Node.js and run:
```
npm install
npm run dev
```
