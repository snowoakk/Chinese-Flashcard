# Chinese Flashcards PWA

This is a Progressive Web App (PWA) version of the Chinese Flashcards application. It can be installed on your device and works offline.

## Features

- 📱 **Installable**: Add to home screen on mobile devices
- 🔌 **Offline Support**: Works without internet connection
- 🎨 **Interactive Drawing**: Practice writing Chinese characters
- 📚 **150 Essential Words**: Traditional Chinese with pinyin and English meanings
- 📱 **Responsive Design**: Works on all devices

## How to Use

### Installation

#### Desktop (Chrome, Edge):
1. Open `flashcards.html` in your browser
2. Click the install icon (➕) in the address bar
3. Click "Install"

#### Mobile (iOS Safari):
1. Open `flashcards.html` in Safari
2. Tap the Share button
3. Tap "Add to Home Screen"

#### Mobile (Android Chrome):
1. Open `flashcards.html` in Chrome
2. Tap the menu (⋮)
3. Tap "Add to Home screen"

### Using the App

- **Toggle Character**: Show/hide the Chinese character guide
- **Clear Drawing**: Erase your drawing to start over
- **Next Word**: Load a random word from the list

### Keyboard Shortcuts

- **Space/Enter/Right Arrow**: Next word
- **T/V**: Toggle character visibility
- **C/E/Escape**: Clear drawing

## Files

- `flashcards.html` - Main application (self-contained with CSS and JS)
- `words.json` - 150 Chinese words database
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline functionality
- `icon-192.svg` - App icon (192x192)
- `icon-512.svg` - App icon (512x512)

## Adding More Words

Edit `words.json` and add entries in this format:

```json
{"character": "新詞", "pinyin": "xīn cí", "meaning": "new word"}
```

The app will automatically load new words on refresh.

## Technical Details

- Pure HTML, CSS, and JavaScript (no dependencies)
- Service Worker caching for offline support
- Canvas API for drawing functionality
- Touch and mouse event support
- Responsive design with media queries
- PWA manifest for installation

## Browser Support

- Chrome/Edge: Full support
- Safari: Full support (iOS 11.3+)
- Firefox: Full support
- Other modern browsers: Should work

Enjoy learning Chinese! 中文學習愉快！
