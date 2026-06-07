# OctoFit Tracker

A modern multi-tier fitness tracking application built with React 19 (frontend), Node.js + Express + TypeScript (backend), and MongoDB (database).

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   ├── package.json
│   └── vite.config.js
└── backend/           # Node.js + Express + TypeScript API
    ├── src/
    ├── package.json
    └── tsconfig.json
```

## Services & Ports

- **Frontend**: http://localhost:5173 (Vite dev server)
- **Backend API**: http://localhost:8000 (Express)
- **MongoDB**: mongodb://localhost:27017 (MongoDB instance)

## Getting Started

### Prerequisites
- Node.js 18+
- MongoDB running on localhost:27017

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at http://localhost:5173

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

The API will be available at http://localhost:8000

## Available Scripts

### Frontend
- `npm run dev` - Start Vite development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run lint` - Run ESLint

### Backend
- `npm run dev` - Start development server with hot reload
- `npm run build` - Compile TypeScript to JavaScript
- `npm run start` - Run compiled application
- `npm run lint` - Run ESLint

## Technology Stack

- **Frontend**: React 19, Vite, JavaScript
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB, Mongoose ODM
- **Development**: ESLint, tsx (TypeScript executor)

## License

MIT
