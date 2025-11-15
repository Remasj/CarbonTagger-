# 🚀 Quick Start Guide

## How to View the Carbon Tagger Demo

### Step 1: Install Node.js (if not already installed)

Check if you have Node.js installed:
```bash
node --version
npm --version
```

If not installed, download from: https://nodejs.org/ (LTS version recommended)

### Step 2: Install Dependencies

Open a terminal in the project directory and run:

```bash
cd /Users/remasaljifri/demo
npm install
```

This will install all required packages (Next.js, React, Tailwind CSS, etc.)

### Step 3: Start the Development Server

```bash
npm run dev
```

You should see output like:
```
▲ Next.js 14.x.x
- Local:        http://localhost:3000
- Ready in X seconds
```

### Step 4: Open in Browser

Open your web browser and navigate to:
```
http://localhost:3000
```

### Step 5: Explore the Features!

1. **Search Tab** - Try searching for "beef", "smartphone", "jeans", or "flight"
2. **Scan Receipt Tab** - Upload a receipt image to see OCR in action
3. **Browse Tab** - Explore items by category
4. **Quick Add Tab** - Log daily activities quickly
5. **Summary Tab** - View your carbon footprint dashboard

## Troubleshooting

### Port 3000 already in use?
```bash
# Use a different port
PORT=3001 npm run dev
```

### npm command not found?
- Install Node.js from https://nodejs.org/
- Or use a Node version manager like `nvm`

### Build errors?
```bash
# Clear cache and reinstall
rm -rf node_modules package-lock.json
npm install
```

## Chrome Extension (Optional)

To use the Chrome extension:

1. Open Chrome and go to `chrome://extensions/`
2. Enable "Developer mode" (top right toggle)
3. Click "Load unpacked"
4. Select the `chrome-extension` folder
5. Visit a shopping site (Amazon, Etsy, etc.) to see carbon badges!

## Need Help?

- Check the main README.md for detailed documentation
- All features are ready to use immediately
- Data is stored locally in your browser (LocalStorage)

---

**Enjoy exploring Carbon Tagger! 🌱**

