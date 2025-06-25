# Usage Guide

## Backend

1. Navigate to `backend/`.
2. Install Python dependencies (if any).
3. Run scripts as needed:
   - `python bot/bot_script.py`
   - `python wallet/final_Hybrid_wallet.py`

## Frontend

1. Navigate to `frontend/` (was `webapp/`).
2. Install dependencies:
   - `npm install`
3. Run the development server:
   - `npm run dev`
4. Access the app at `http://localhost:3000`

## Database

- Migrations and schema are managed in `frontend/prisma/`.
- Use Prisma CLI for migrations:
  - `npx prisma migrate dev` 