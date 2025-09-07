# 🎄 Christmas Name Drawing App

A simple, password-protected web app for organizing family gift exchanges. No server required - runs entirely in the browser and saves data locally.

## 🚀 Quick Start

1. **Download**: Save `index.html` to your computer
2. **Deploy**: Upload to GitHub Pages or any web host
3. **Access**: Open in browser, enter password: `christmas2024`
4. **Setup**: Add participants, last year's results, and spouse pairs
5. **Draw**: Switch to Drawing tab and start the fun!

## ✨ Features

- **🔐 Password Protected**: Keep your drawing private
- **📱 Mobile Friendly**: Works on phones, tablets, and computers
- **🎲 Smart Drawing**: Prevents drawing yourself, your spouse, or last year's recipient
- **✅ Name Validation**: Catches typos and mismatches between tables
- **💾 Auto-Save**: Data persists between sessions
- **📄 PDF Export**: Download results when complete
- **🔄 Easy Reset**: Copy results to "last year" and start fresh

## 🛠️ Setup

### Tables to Fill Out:
1. **Participants** (15 slots): Everyone drawing this year
2. **Last Year's Results** (15 pairs): Who bought for whom last year
3. **Spouse Pairs** (6 pairs): Married couples who can't draw each other

### Drawing Process:
- Names are randomly ordered when you first enter the Drawing tab
- Each person draws one at a time using the "Draw" button
- Smart exclusions ensure fair and fun results
- Download PDF when complete

## ⚙️ Customization

**Change Password**: Edit line 289 in the HTML file:
```javascript
const APP_PASSWORD = "your-new-password";
```

**Adjust Limits**: Modify table sizes by changing loop limits in the `generateTables()` function.

## 🔧 Technical Details

- **Single File**: No dependencies (except jsPDF for downloads)
- **Local Storage**: Data saved in browser, no server needed
- **GitHub Pages Ready**: Upload and go!
- **No Database**: Perfect for small family groups

## 📋 Requirements

- Modern web browser
- JavaScript enabled
- Internet connection (only for initial PDF library load)

## 🎁 Perfect For

- Family Christmas exchanges
- Office Secret Santa
- Friend group gift swaps
- Any group gift drawing with history tracking

---

*Built with ❤️ for hassle-free holiday planning*
