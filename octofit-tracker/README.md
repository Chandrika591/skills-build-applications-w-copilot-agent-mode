# 🐙 OctoFit Tracker

A modern multi-tier fitness tracking application built with GitHub Copilot Agent Mode.

## Architecture

- **Frontend**: React 19 + Vite (Port 5173)
- **Backend**: Node.js + Express + TypeScript (Port 8000)
- **Database**: MongoDB (Port 27017)

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 application with Vite
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── tsconfig.json
│   └── vite.config.ts
└── backend/           # Express API server with TypeScript
    ├── src/
    ├── package.json
    ├── tsconfig.json
    └── .env.example
```

## Getting Started

### Prerequisites
- Node.js (v18+)
- MongoDB (v5.0+)

### Installation

#### Frontend
```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

#### Backend
```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

## Environment Setup

Create `.env` file in the backend directory:
```
PORT=8000
MONGODB_URI=mongodb://localhost:27017/octofit-tracker
NODE_ENV=development
```

## Available Ports

- Frontend: http://localhost:5173
- Backend API: http://localhost:8000
- MongoDB: localhost:27017

## Features

🚀 Built with GitHub Copilot Agent Mode
✨ Modern React 19 with Vite
🗄️ MongoDB with Mongoose ODM
🎯 TypeScript for type safety

## License

ISC
