# Coming Soon Page - Setup Instructions

## What Was Missing
The original export was missing the `public/assets/` folder containing all the images and media files that the coming soon page depends on.

## Required Assets (Now Included)
- `load-screen.gif` - Loading screen animation
- `CS desktop-background.webp` - Desktop background image
- `CS header.svg` - Mobile header image
- `m1.webp` - Mobile footer background

## Setup Instructions for Developer

### 1. Install Dependencies
```bash
npm install
```

### 2. Development Server
```bash
npm run dev
```
The site will be available at `http://localhost:3000`

### 3. Build for Production
```bash
npm run build
```
This creates a `dist/` folder with the production-ready files.

### 4. Preview Production Build
```bash
npm run preview
```

## Project Structure
```
coming-soon-export/
├── public/
│   └── assets/          # All images and media files
├── src/
│   ├── components/      # React components
│   ├── pages/          # Page components
│   └── styles/         # CSS styles
├── index.html          # Main HTML file
├── package.json        # Dependencies and scripts
└── vite.config.ts      # Build configuration
```

## Features
- Responsive design (Mobile, Tablet, Desktop)
- Loading screen with 6-second minimum display
- Email subscription form
- Background images for all screen sizes
- Tailwind CSS for styling

## Deployment
The `dist/` folder (created after `npm run build`) contains all files needed for deployment to any web server.
