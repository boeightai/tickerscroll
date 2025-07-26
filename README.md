# TickerScroll

A collection of scrolling ticker widgets designed for use in eCamm Live streaming software.

## Files

- `ticker.html` - Third-party TradingView ticker widget for financial market data
- `sponsor_call_widget.html` - Custom sponsor call widget for seeking sponsors
- `sponsor_logos/` - Directory containing sponsor logo assets

## TradingView Ticker Widget

The `ticker.html` file contains a TradingView widget that displays real-time financial market data including:

- **S&P 500 Index** (FOREXCOM:SPXUSD)
- **NASDAQ Composite** (NASDAQ:IXIC)
- **Bitcoin** (CRYPTO:BTCUSD)
- **Ethereum** (CRYPTO:ETHUSD)
- **Solana** (CRYPTO:SOLUSD)
- **Google** (NASDAQ:GOOG)
- **Meta** (NASDAQ:META)
- **Nvidia** (NASDAQ:NVDA)

### Features

- **Real-time Data**: Live market prices and changes
- **Dark Theme**: Matches financial/trading aesthetics
- **Adaptive Display**: Responsive design for different screen sizes
- **Symbol Logos**: Visual representation of each asset
- **Professional Styling**: Clean, modern interface

### How to Use

1. Open `ticker.html` in eCamm Live as a widget
2. The widget will automatically display live market data
3. Customize symbols by modifying the "symbols" array in the script
4. Adjust display settings through the widget configuration

## Sponsor Call Widget

The `sponsor_call_widget.html` file is a custom scrolling ticker designed to display sponsor opportunities and contact information during live streams.

### Features

- **Infinite Scroll**: Seamless looping animation with duplicated content
- **Responsive Design**: Adapts to different screen sizes and eCamm Live widget dimensions
- **Professional Styling**: Dark theme matching financial/trading aesthetics
- **Multiple Message Types**: Call-to-action, urgent, and contact variations
- **Logo Support**: Displays sponsor logos with intelligent fallback system
- **Interactive Elements**: Clickable items that copy email to clipboard or open email client
- **Accessibility**: Full keyboard navigation and screen reader support
- **eCamm Live Optimized**: Designed specifically for eCamm Live's widget system

### Recent Improvements (v2.0)

- **Fixed CSS Conflicts**: Resolved logo display issues with proper fallback system
- **Enhanced Error Handling**: Improved image loading with graceful degradation
- **Accessibility Features**: Added ARIA labels, keyboard navigation, and focus styles
- **Interactive Functionality**: Click to copy email addresses or open email client
- **Performance Optimizations**: Lazy loading and better animation handling
- **Better UX**: Hover effects and visual feedback for user interactions

### How to Use

1. Open `sponsor_call_widget.html` in eCamm Live as a widget
2. The widget will automatically start scrolling after a 500ms delay
3. Click on any sponsor item to copy the email address to clipboard
4. Customize sponsor messages and contact information as needed
5. Add actual sponsor logos to the `sponsor_logos/` directory

### Customization

- **Contact Information**: Update the email addresses in the HTML
- **Sponsor Messages**: Modify the title and subtitle text
- **Logos**: Replace placeholder.svg with actual sponsor logos
- **Colors**: Adjust the CSS color scheme as needed
- **Animation Speed**: Change the animation duration in the CSS (currently 30s)
- **Message Types**: Add new CSS classes for different message styles

### Technical Details

- **Dimensions**: Responsive (100% width/height) with minimum 36px height
- **Animation**: 30-second linear infinite scroll with seamless looping
- **Compatibility**: Works in eCamm Live's iframe environment
- **Fallbacks**: Intelligent logo loading with graceful degradation
- **Performance**: Optimized for smooth scrolling without external dependencies
- **Accessibility**: WCAG 2.1 compliant with keyboard navigation and screen reader support

### Message Types

- **Call-to-Action**: Green text with pulsing animation
- **Urgent**: Orange text for time-sensitive opportunities
- **Contact**: Blue subtitle for contact information
- **Standard**: Default styling for general messages

## Sponsor Logos

See `sponsor_logos/README.md` for detailed instructions on adding and managing sponsor logos.

### Logo Requirements

- **Format**: SVG preferred, PNG/JPG accepted
- **Size**: 20x20px (will be scaled automatically)
- **Naming**: Use descriptive filenames (e.g., `company-name.svg`)
- **Fallback**: Placeholder.svg provides default styling when logos fail to load

## Browser Compatibility

Both widgets are compatible with:
- Modern browsers (Chrome, Firefox, Safari, Edge)
- eCamm Live's widget system
- Mobile devices (responsive design)
- Screen readers and assistive technologies 