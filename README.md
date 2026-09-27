# Electron Linux App Template 🚀

A lightweight starter template to build and package desktop applications for Linux using Electron and `electron-builder`.

> [!NOTE]
> The project is currently being improved.

> [!TIP]
> You can use `npm run build:fast` to speed up the bundling process.

> [!IMPORTANT]
> Ensure Node.js v18+ is installed before installing dependencies.

> [!WARNING]
> Use test API keys in the production environment.

> [!CAUTION]
> This operation overwrites existing files.

## 📦 Getting Started

   Clone or use this repository as a template:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/electron-linux-template.git](https://github.com/YOUR_USERNAME/electron-linux-template.git)
   cd electron-linux-template
   ```
1. Install dependencies:
   ```bash
   npm install
   ```
   2. Run in development mode:
   ```bash
   npm start
   ```
## 🛠️ Build & Package for Linux

Generate `.AppImage`:
```bash
npm run build:appimage
```

Generate `.deb` package:
```bash
npm run build:deb
```

Generate both:
```bash
npm run build:all
```
