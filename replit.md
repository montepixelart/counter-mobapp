# Gym Tap Counter

## Overview
A Progressive Web App (PWA) for tracking gym exercises and workouts. Built with React, TypeScript, and Vite, this app provides a simple tap counter interface for counting reps, sets, or any other gym-related activities.

## Project Structure
- Frontend-only React application
- Uses Vite as the build tool and development server
- TypeScript for type safety
- Tailwind CSS (via CDN) for styling
- PWA features with service worker and manifest

## Key Features
- Tap counter with large tap button
- Custom increment values (default: +5)
- Decrement and reset functionality
- Workout history tracking (stored in localStorage)
- Named counter entries
- Counter log view with delete functionality
- Mobile-optimized with vibration feedback
- PWA installable on mobile devices

## Configuration
- **Dev Server**: Runs on port 5000 (configured for Replit)
- **Build Tool**: Vite 6.x
- **React Version**: 19.2.0
- **TypeScript**: 5.8.2

## Recent Changes (November 14, 2025)
- Imported from GitHub and configured for Replit environment
- Updated Vite config to use port 5000 with HMR settings
- Installed all dependencies
- Set up development workflow
- Configured deployment for autoscale

## Environment Setup
- Node.js 20 installed
- All npm dependencies installed
- Workflow configured to run `npm run dev` on port 5000

## Deployment
- Type: Autoscale (stateless frontend)
- Build: `npm run build`
- Run: `npx vite preview --host 0.0.0.0 --port 5000`
