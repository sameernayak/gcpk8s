# GCP K8s React Application

A modern React application with Tailwind CSS, designed for deployment on Google Kubernetes Engine (GKE).

## Prerequisites

Before you begin, ensure you have Node.js and npm installed on your system. You can download them from [https://nodejs.org/](https://nodejs.org/).

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm run dev
```

3. Open your browser and navigate to the URL shown in the terminal (usually http://localhost:5173)

## Project Structure

- `src/App.tsx` - Main application component
- `src/main.tsx` - Application entry point
- `src/index.css` - Global styles and Tailwind CSS imports
- `tailwind.config.js` - Tailwind CSS configuration
- `postcss.config.js` - PostCSS configuration
- `vite.config.ts` - Vite configuration
- `tsconfig.json` - TypeScript configuration
- `Dockerfile` - Production Docker configuration
- `Dockerfile.dev` - Development Docker configuration
- `docker-compose.yml` - Docker Compose configuration

## Features

- React 18 with TypeScript
- Tailwind CSS for styling
- Vite for fast development
- Docker containerization
- Kubernetes deployment ready
- Modern and clean design

## Docker Development

To run the development environment:
```bash
docker compose up dev
```

## Production Build

To create a production build:
```bash
docker compose up prod
```

The built files will be served through Nginx on port 80. 