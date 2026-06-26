# TaskForge

A powerful to-do app with reminders and focus modes.

## 🚀 Quick Start

### Web/PWA
1. Open `index.html` in your browser
2. Or run: `npm install && npm start`
3. Deploy to Netlify/Vercel by uploading this folder

### Mobile App (Capacitor)
```bash
npm install
npx cap init
npx cap add android
npx cap add ios
npx cap sync
npx cap run android    # For Android
npx cap run ios        # For iOS (Mac only)
```

### Desktop App (Electron)
```bash
npm install -g electron
electron .
```

## 📦 Deployment Options

### Web/PWA (Recommended)
- **Netlify**: Drag & drop this folder
- **Vercel**: Connect Git repo
- **GitHub Pages**: Push to gh-pages branch

### Mobile App Stores
1. Build with Capacitor (above)
2. Android: Generate APK/AAB from Android Studio
3. iOS: Archive and upload to App Store Connect

### Desktop
- Package with Electron or Tauri for Windows/Mac/Linux

## ✨ Features
- Task management with categories and priorities
- Browser notifications for reminders
- Focus modes (Normal, Epic, Immersive)
- PWA - installable on mobile/desktop
- Offline support with service worker
- Local storage persistence

## 📱 PWA Installation
1. Open app in Chrome/Safari
2. Click "Install" or "Add to Home Screen"
3. Works offline after installation
