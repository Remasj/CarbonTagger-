# 🌱 Carbon Tagger

A web-based tool that automatically shows the real carbon footprint of everyday items, purchases, and habits.

## ✨ Features

### 🔍 Search Items
Search for any item (food, clothes, electronics, travel) and instantly see its carbon footprint with an intuitive score system.

### 📸 Receipt Scanner
Upload a photo of your receipt and automatically tag items with carbon scores using OCR technology. Perfect for tracking shopping trips!

### 📂 Browse Categories
Explore products organized by category (Food, Clothing, Electronics, Travel) to discover carbon footprints across different product types.

### 🔄 Carbon Swap Recommendations
After viewing an item's carbon footprint, get instant recommendations for greener alternatives with savings calculations.

### 📊 Carbon Summary Dashboard
Track your weekly and monthly carbon footprint with:
- Total carbon footprint
- Daily averages
- Period-over-period comparisons
- Category breakdowns
- Interactive charts
- Recent events log

### ⚡ Quick Add Event
Fast and easy way to log daily activities:
- Pre-built templates (Uber rides, coffee, meals, flights, pets)
- Custom event creation
- One-click logging

### 🌐 Chrome Extension
See carbon impact while shopping online! The extension automatically detects products and shows carbon badges on supported shopping sites.

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ and npm

### Installation

1. **Install dependencies:**
```bash
npm install
```

2. **Run the development server:**
```bash
npm run dev
```

3. **Open your browser:**
Navigate to [http://localhost:3000](http://localhost:3000)

### Building for Production

```bash
npm run build
npm start
```

## 🌐 Chrome Extension Setup

1. Open Chrome and navigate to `chrome://extensions/`
2. Enable "Developer mode" (toggle in top right)
3. Click "Load unpacked"
4. Select the `chrome-extension` folder
5. The extension is now active!

The extension works on:
- Amazon
- Etsy
- Target
- Walmart
- (More sites can be added in `manifest.json`)

## 📁 Project Structure

```
carbon-tagger/
├── app/                    # Next.js app directory
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── SearchItems.tsx    # Search functionality
│   ├── ReceiptScanner.tsx # OCR receipt scanning
│   ├── CategoryBrowser.tsx # Category browsing
│   ├── QuickAddEvent.tsx  # Quick event logging
│   └── CarbonSummary.tsx # Dashboard & analytics
├── lib/                   # Utilities & data
│   ├── carbonDatabase.ts # Carbon footprint database
│   └── storage.ts         # LocalStorage helpers
└── chrome-extension/      # Chrome extension files
    ├── manifest.json      # Extension manifest
    ├── content.js        # Content script
    └── content.css       # Extension styles
```

## 🛠️ Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Icons:** Lucide React
- **OCR:** Tesseract.js
- **Charts:** Recharts
- **Date Utils:** date-fns

## 💡 How It Works

1. **Carbon Database:** Pre-built database with carbon footprint data for hundreds of items across multiple categories
2. **Intuitive Scoring:** Items are scored from 1-10 with color-coded labels (Very High to Minimal)
3. **Local Storage:** All events are stored locally in your browser
4. **Real-time Updates:** Dashboard updates automatically as you add events
5. **OCR Processing:** Receipt scanning uses Tesseract.js to extract text and match products

## 🎯 Use Cases

- **Personal Carbon Tracking:** Track your daily carbon footprint
- **Shopping Decisions:** Compare products before purchasing
- **Receipt Analysis:** Understand the environmental impact of shopping trips
- **Habit Tracking:** Monitor recurring activities (coffee, commute, etc.)
- **Educational:** Learn about carbon footprints of everyday items

## 🔮 Future Enhancements

- User accounts and cloud sync
- Expanded carbon database
- Social sharing features
- Carbon offset recommendations
- Integration with shopping apps
- Mobile app version

## 📝 License

This project is open source and available for hackathons and educational purposes.

---

**Made with 🌱 for a greener future**

