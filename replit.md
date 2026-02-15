# MD Sadek Ali - Cyber Security & Digital Growth Expert

## Overview
Personal portfolio/landing page for MD Sadek Ali, a Cyber Security & Digital Growth Expert based in Qatar. Built with React, TypeScript, Vite, and Tailwind CSS (via CDN).

## Project Architecture
- **Framework**: React 19 + TypeScript + Vite 6
- **Styling**: Tailwind CSS (loaded via CDN in index.html)
- **Icons**: lucide-react
- **Entry**: index.html -> index.tsx -> App.tsx

## Structure
- `/` - Root config files (package.json, vite.config.ts, tsconfig.json, index.html)
- `/components/` - React components (Navbar, Hero, Services, About, Portfolio, etc.)
- `constants.tsx` - Data constants (services, testimonials, blog posts, portfolio items, contact info)
- `types.ts` - TypeScript interfaces

## Development
- Dev server: `npm run dev` (port 5000)
- Build: `npm run build` (outputs to `dist/`)
- Deployment: Static site (dist/ directory)
