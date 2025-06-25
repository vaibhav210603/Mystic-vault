# Architecture

## Overview
Mystic Vault consists of two main components:

- **Backend**: Python scripts for wallet management and automation.
- **Frontend**: Next.js web application for user interaction and wallet management.

## Backend
- Located in `backend/`
- Handles wallet creation, automation, and blockchain interactions.
- Contains:
  - `bot/`: Automation scripts (e.g., `bot_script.py`)
  - `wallet/`: Wallet logic (e.g., `final_Hybrid_wallet.py`)

## Frontend
- Located in `frontend/` (was `webapp/`)
- Built with Next.js
- Handles user authentication, wallet management UI, and API calls to backend services.

## Database
- Managed via Prisma in the frontend directory.
- Stores user, wallet, and transaction data. 