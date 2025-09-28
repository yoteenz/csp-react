# Coming Soon Page - Production Ready

A responsive coming soon page with mobile, tablet, and desktop layouts, featuring a professional loading screen and email subscription form.

## 🚀 Quick Start

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start development server:**
   ```bash
   npm run dev
   ```

3. **Open in browser:**
   ```
   http://localhost:3000
   ```

## 📁 Project Structure

```
coming-soon-export/
├── src/
│   ├── components/
│   │   └── SubscribeNow.tsx      # Email subscription form
│   ├── pages/
│   │   └── ComingSoonPage.tsx    # Main page component
│   ├── styles/
│   │   └── coming-soon.css       # All styles and responsive breakpoints
│   └── main.tsx                  # App entry point
├── public/
│   └── assets/                   # Place your assets here
├── package.json                  # Dependencies and scripts
├── vite.config.ts               # Vite configuration
├── tailwind.config.ts           # Tailwind CSS configuration
├── tsconfig.json                # TypeScript configuration
└── index.html                   # HTML template
```

## 📋 Required Assets

Place these assets in the `public/assets/` directory:

- `load-screen.gif` - Loading animation
- `CS header.svg` - Mobile header background
- `m1.webp` - Mobile footer background  
- `CS desktop-background.webp` - Desktop background
- `coming soon-header.png` - Additional header asset

## 🎯 Features

- ✅ **Responsive Design** - Mobile, Tablet, Desktop layouts
- ✅ **Loading Screen** - Professional loading animation with asset checking
- ✅ **Email Subscription** - Functional form with validation
- ✅ **Modern Styling** - Glass-morphism effects and blur
- ✅ **Performance Optimized** - Asset loading and optimization
- ✅ **TypeScript Support** - Full type safety
- ✅ **Tailwind CSS** - Utility-first styling

## 🔧 Customization

### Change Colors
Update color values in `src/styles/coming-soon.css`:
- `#EB1C24` - Red accent color
- `#7b7a78` - Background color
- `#909090` - Text color

### Update Text Content
Modify text in `src/components/SubscribeNow.tsx`

### Change Background Images
1. Replace assets in `public/assets/` directory
2. Update image paths in `src/styles/coming-soon.css`

### Add API Integration
Replace the setTimeout in `handleEmailSubscriptionFunction` with your actual API call in `src/components/SubscribeNow.tsx`

## 📱 Responsive Breakpoints

- **Mobile:** < 768px
- **Tablet:** 768px - 1199px
- **Desktop:** ≥ 1200px

## 🚀 Deployment

### Build for Production
```bash
npm run build
```

### Preview Production Build
```bash
npm run preview
```

### Deploy to Vercel
```bash
npx vercel
```

### Deploy to Netlify
```bash
npm run build
# Upload dist/ folder to Netlify
```

## 🛠️ Development

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

### Tech Stack
- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool
- **Tailwind CSS** - Styling
- **CSS Custom Properties** - Advanced styling

## 📄 License

This project is ready for production use. Customize as needed for your specific requirements.
