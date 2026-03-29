# KRM Game Fest 2026 - Sponsorship Proposal

A React + Vite web application showcasing the sponsorship proposal from K R Mangalam University to Om Sweets & Snacks for KRM Game Fest 2026.

## 🚀 Quick Start

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

```bash
# Install dependencies
npm install

# Run development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Deployment to Vercel

This project is ready to deploy on Vercel:

### Option 1: Deploy via Vercel CLI

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

### Option 2: Deploy via Vercel Dashboard

1. Push your code to a Git repository (GitHub, GitLab, or Bitbucket)
2. Go to [Vercel Dashboard](https://vercel.com/dashboard)
3. Click "New Project"
4. Import your repository
5. Vercel will auto-detect the Vite configuration
6. Click "Deploy"

### Option 3: Deploy from local directory

```bash
vercel --prod
```

## 🔧 Configuration

- **Framework**: Vite
- **Build Command**: `npm run build`
- **Output Directory**: `dist`
- **Install Command**: `npm install`

The project includes a `vercel.json` configuration file for optimal deployment settings.

## 🛠️ Tech Stack

- React 19.2.4
- Vite 8.0.1
- Tailwind CSS (via CDN)
- ESLint for code quality

## 📁 Project Structure

```
Pitch/
├── public/          # Static assets
├── src/
│   ├── App.jsx     # Main application component
│   ├── main.jsx    # Application entry point
│   └── index.css   # Global styles
├── dist/           # Production build (generated)
├── index.html      # HTML template
├── vercel.json     # Vercel configuration
└── package.json    # Project dependencies
```

## 🌐 Environment

The application uses Tailwind CSS via CDN and custom color configuration for the KRM Game Fest branding.
