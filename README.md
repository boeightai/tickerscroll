# TickerScroll - Financial Market Ticker Widgets

A collection of rolling ticker widgets for financial platforms and trading websites. This project provides both third-party market data integration and custom sponsorship call-to-action displays.

## 📊 Project Overview

TickerScroll consists of two main components:
- **TradingView Market Ticker**: Real-time financial market data display
- **Custom Sponsor Widget**: Animated sponsorship call-to-action ticker

## 🚀 Features

### TradingView Market Ticker (`ticker.html`)
- **Real-time market data** from TradingView
- **Multiple asset classes**: Stocks, indices, cryptocurrencies
- **Professional styling** with dark theme
- **Responsive design** with adaptive display mode
- **Company logos** for visual identification

**Supported Symbols:**
- S&P 500 Index (SPXUSD)
- NASDAQ Composite (IXIC)
- Bitcoin (BTCUSD)
- Ethereum (ETHUSD)
- Solana (SOLUSD)
- Google (GOOG)
- Meta (META)
- Nvidia (NVDA)

### Custom Sponsor Widget (`sponsor_call_widget.html`)
- **Animated scrolling** ticker tape effect
- **Professional financial platform styling**
- **Multiple call-to-action messages**
- **Interactive hover effects**
- **Responsive design** (1280px × 36px)
- **Contact integration** with email links

## 🛠️ Technical Details

### Dependencies
- **TradingView Widget**: External JavaScript from TradingView
- **Custom CSS**: Pure CSS animations and styling
- **No build process**: Direct HTML/CSS implementation

### Browser Compatibility
- Modern browsers with CSS3 support
- TradingView widget requires internet connection
- Responsive design for various screen sizes

### Performance
- Lightweight implementation
- CSS-based animations for smooth performance
- No heavy JavaScript dependencies

## 📁 File Structure

```
tickerscroll/
├── README.md                 # Project documentation
├── ticker.html              # TradingView market data widget
└── sponsor_call_widget.html # Custom sponsorship ticker
```

## 🎯 Usage

### Quick Start
1. **Market Ticker**: Open `ticker.html` in any web browser
2. **Sponsor Widget**: Open `sponsor_call_widget.html` in any web browser

### Integration
Both widgets can be:
- Embedded in existing websites
- Used as standalone displays
- Customized for specific branding needs
- Integrated into financial dashboards

### Customization Options

#### TradingView Ticker
```javascript
{
  "symbols": [...],           // Add/remove financial instruments
  "showSymbolLogo": true,     // Toggle company logos
  "isTransparent": false,     // Background transparency
  "displayMode": "adaptive",  // Display mode
  "colorTheme": "dark",       // Light/dark theme
  "locale": "en"             // Language setting
}
```

#### Sponsor Widget
- Modify sponsor messages in the HTML
- Adjust animation speed in CSS (`animation: scroll-left 30s`)
- Change colors and styling in the CSS section
- Add/remove sponsor items as needed

## 🎨 Styling

### Color Scheme
- **Background**: #131722 (Dark financial theme)
- **Borders**: #2a2e39 (Subtle separators)
- **Text**: #d1d4dc (Primary), #787b86 (Secondary)
- **Accents**: #4caf50 (Success), #ff9800 (Warning), #2196f3 (Info)

### Typography
- **Font Family**: -apple-system, BlinkMacSystemFont, 'Trebuchet MS', Roboto, Ubuntu, sans-serif
- **Font Sizes**: 11px (titles), 10px (subtitles), 9px (attribution)

## 🔧 Development

### Prerequisites
- Any modern web browser
- Text editor for modifications
- Internet connection (for TradingView widget)

### Local Development
1. Clone or download the project files
2. Open files directly in your browser
3. Make modifications using any text editor
4. Refresh browser to see changes

### Customization Workflow
1. **Backup original files**
2. **Make incremental changes**
3. **Test in browser**
4. **Iterate and refine**

## 📞 Contact & Sponsorship

For sponsorship opportunities or technical support:
- **Email**: sponsors@bonam.com
- **Project**: TickerScroll Widget Collection

## 📄 License

This project is open source and available for modification and commercial use. The TradingView widget is subject to TradingView's terms of service.

## 🤝 Contributing

Contributions are welcome! Areas for improvement:
- Additional widget themes
- More customization options
- Performance optimizations
- New animation effects
- Additional financial data sources

## 📈 Roadmap

- [ ] Add light theme option
- [ ] Implement configurable animation speeds
- [ ] Add more financial instruments
- [ ] Create widget configuration interface
- [ ] Add mobile-responsive optimizations
- [ ] Implement widget state management

---

**Built for financial platforms and trading websites** 🚀 