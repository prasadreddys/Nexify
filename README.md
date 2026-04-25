# Nexify

A starter Web3 platform for wallet login, tasks, rewards, referrals, and Base network compatibility.

## Features

- Next.js App Router frontend with Tailwind CSS
- Wallet connect via wagmi + viem
- Coinbase OnchainKit support for Base ecosystem flows
- Express API with Prisma + PostgreSQL
- Wallet signature login and JWT auth
- Task tracking, reward claiming, and referral tracking

## Getting started

1. Install dependencies:

   ```bash
   npm run setup
   ```

2. Configure environment variables:

   - `frontend/.env.local`
   - `backend/.env`

3. Run locally:

   ```bash
   npm run dev
   ```

4. Build for production:

   ```bash
   npm run build
   ```

## Project structure

- `frontend/` — Next.js UI and wallet integration
- `backend/` — Express API, Prisma schema, and authentication

## Deploy

- Frontend: Vercel
- Backend: Railway / Fly.io / Node host
- Database: PostgreSQL

## Notes

This starter includes a clean dashboard, referral UI, task and reward endpoints, and Base ecosystem support. Extend it with NFT minting, staking, or advanced analytics.
# Nexify
