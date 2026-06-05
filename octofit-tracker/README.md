# OctoFit Tracker

A modern multi-tier fitness tracking application built with GitHub Copilot agent mode.

## Architecture

### Frontend
- **Framework**: React 19
- **Build Tool**: Vite
- **Port**: 5173
- **Location**: `octofit-tracker/frontend`

### Backend
- **Runtime**: Node.js
- **Framework**: Express
- **Language**: TypeScript
- **Port**: 8000
- **Database**: MongoDB (via Mongoose)
- **Location**: `octofit-tracker/backend`

### Database
- **Type**: MongoDB
- **Port**: 27017
- **Default URI**: `mongodb://localhost:27017/octofit-tracker`

## Getting Started

### Prerequisites
- Node.js 18+ installed
- MongoDB running locally or accessible at `mongodb://localhost:27017`

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

The frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
cp .env.example .env
npm run dev
```

The backend API will be available at `http://localhost:8000`

### Backend Build for Production

```bash
npm run build
npm start
```

## API Endpoints

- `GET /api/health` - Health check endpoint

## Environment Variables (Backend)

See `.env.example` for required environment variables.
