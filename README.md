# CRASH GAME — Full Stack Setup Guide
# FOR DEMO/ENTERTAINMENT ONLY — No real money

## Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)

## Installation

```bash
cd crash-game
npm install
```

## Environment Variables (optional)
Create a `.env` file:
```
PORT=3000
MONGO_URI=mongodb://127.0.0.1:27017/crashgame
JWT_SECRET=your_strong_secret_here
```

## Run

```bash
# Development (auto-restart)
npm run dev

# Production
npm start
```

Open: http://localhost:3000
Admin: http://localhost:3000/admin.html

## Admin Credentials
- Username: Mehediazx
- Password: mehediazx@#£

## File Structure
```
crash-game/
├── server.js          ← Express + Socket.io + MongoDB
├── package.json
├── .env               ← (create yourself)
└── public/
    ├── index.html     ← Cyberpunk player UI
    └── admin.html     ← Admin dashboard
```

## Features
- Real-time multiplayer via Socket.io
- MongoDB persistence (balances, deposits, rounds)
- JWT authentication
- Server-controlled crash point (3% house edge algorithm)
- Admin: set manual crash, approve deposits, manage users
- Auto-cashout support
- Bkash/Nagad deposit submission flow

## DISCLAIMER
This is a demo/entertainment platform only.
Operating real-money gambling requires legal licensing.
