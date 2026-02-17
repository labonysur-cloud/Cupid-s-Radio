# 💘 Cupid's Radio

<div align="center">

![Cupid's Radio](https://img.shields.io/badge/Love-Radio-darkred?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=for-the-badge)

*A romantic, secure web app for recording voice messages and love letters with encrypted sharing*

[Live Demo](#-demo) • [Features](#-features) • [Getting Started](#-getting-started) • [Usage](#-usage) • [Technology](#-technology-stack)

</div>

---

## 📸 Demo

<div align="center">

![Cupid's Radio Screenshot](https://github.com/labonysur-cloud/Cupid-s-Radio/blob/main/cupid's%20radio.jpg)

*Create encrypted voice messages and love letters with a beautiful vintage interface*

</div>

---

## 📖 Overview

**Cupid's Radio** is a unique Valentine's Day-themed Progressive Web Application (PWA) that combines the nostalgia of love letters with modern audio messaging. Send encrypted romantic messages to your loved ones in a beautifully designed, mobile-friendly interface with a vintage radio aesthetic.

Perfect for:
- 💝 Valentine's Day surprises
- 💌 Long-distance relationships
- 🎂 Anniversary celebrations
- 🎁 Romantic gestures any day

---

## ✨ Features

### 🎙️ **Voice Recording**
- Record audio messages directly in the browser
- Cross-platform microphone support (iOS, Android, Desktop)
- Automatic format detection (WebM/MP4)
- Built-in audio filters for a "vintage radio" sound effect

### 🖼️ **ASCII Art Studio**
- Convert photos into vintage text portraits
- Customizable density, contrast, and brightness
- create unique art using your own text/characters
- Export as beautiful digital postcards

### 📝 **Love Letters**
- Beautiful lined paper textarea for writing messages
- Character-unlimited text support
- Elegant typography with vintage styling

### 🎀 **Sticker Studio**
- Drag and drop vintage stickers onto your letters and cards
- Customize sticker position, rotation, and size
- Curated collection of romantic assets (hearts, cupids, roses)
- Fully interactive touch support for mobile devices

### 🔒 **Secure Encryption**
- XOR-based encryption for privacy
- Custom secret code protection
- Messages can only be unlocked with the correct code

### 📤 **Easy Sharing**
- Native mobile share integration
- Fallback download for all devices
- Android-optimized file sharing
- Generates compact `.json` files

### 🎨 **Beautiful UI/UX**
- Vintage Valentine's Day aesthetic
- Gingham pattern background
- Smooth animations and transitions
- Fully responsive mobile-first design
- Heart-themed interactive elements

### 🔊 **Audio Playback**
- Custom "radio" audio filters (highpass/lowpass)
- Visual playback animations
- Start/stop controls
- Web Audio API integration

---

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Microphone access (for recording features)

### Installation

**Cupid's Radio** is a standalone HTML file with no dependencies or build process required!

1. **Clone the repository**
```bash
   git clone https://github.com/labonysur-cloud/Cupid-s-Radio.git
```

2. **Navigate to the project**
```bash
   cd Cupid-s-Radio
```

3. **Open in browser**
```bash
   # Simply double-click index.html or use a local server
   python -m http.server 8000
   # or
   npx serve
```

4. **Visit** `http://localhost:8000` in your browser

---

## 📱 Usage

### Sending a Message

1. **Launch the App**
   - Open `index.html` in your browser
   - Click **"Record Signal"** to create a new message

2. **Record Voice (Optional)**
   - Click **"START RECORDING"** and allow microphone access
   - Speak your message
   - Click **"STOP RECORDING"** when done
   - Preview with the **"PLAY ME"** button

3. **Write a Letter**
   - Type your message in the lined paper textarea
   - Both voice and text can be included, or just one

4. **Seal & Share**
   - Enter a **SECRET CODE** (e.g., "LOVE", "2026", "VALENTINE")
   - Click **"SEAL CAPSULE"**
   - Click **"SHARE FILE"** to send via messaging apps
   - Or download the `.json` file to send manually

### Receiving a Message

1. **Open the App**
   - Click **"Open Signal"** on the home screen

2. **Upload File**
   - Select the received `.json` file
   - Enter the **SECRET CODE** provided by the sender

3. **Unlock & Enjoy**
   - Click **"UNLOCK"**
   - Listen to the voice message
   - Read the letter
   - Feel the love! ❤️

---

## 🛠️ Technology Stack

| Technology | Purpose |
|-----------|---------|
| **HTML5** | Structure and markup |
| **CSS3** | Styling with custom properties and animations |
| **React 18.2** | UI components and state management |
| **Babel Standalone** | JSX transformation in-browser |
| **Web Audio API** | Audio effects and playback |
| **MediaRecorder API** | Voice recording functionality |
| **File API** | File upload/download handling |
| **Web Share API** | Native mobile sharing |

### Key Features

- ✅ **No Build Process**: Single HTML file application
- ✅ **No Backend Required**: All encryption happens client-side
- ✅ **Progressive Web App Ready**: Works offline after first load
- ✅ **Cross-Platform**: iOS, Android, Windows, macOS, Linux
- ✅ **Privacy First**: Messages never touch a server

---

## 🎨 Design Philosophy

### Visual Design
- **Color Palette**: Dark red (#8B0000) with cream/paper backgrounds
- **Typography**: Courier New for a typewriter aesthetic
- **Patterns**: Gingham background pattern for vintage charm
- **Animations**: Subtle pulse effects and smooth transitions

### User Experience
- Mobile-first responsive design
- Touch-optimized buttons and interactions
- Clear visual feedback for all actions
- Intuitive navigation flow
- Error handling with user-friendly messages

---

## 🔐 Security & Privacy

### Encryption Details
- **Algorithm**: XOR cipher with user-provided passphrase
- **Encoding**: Base64 encoding of encrypted data
- **Key Derivation**: Direct passphrase usage (uppercase normalized)
- **Storage**: No data is stored on any server

> ⚠️ **Note**: This encryption is designed for casual privacy, not military-grade security. For highly sensitive communications, use established secure messaging platforms.

### Privacy Features
- ✅ All processing happens locally in the browser
- ✅ No analytics or tracking
- ✅ No external API calls (except CDN for libraries)
- ✅ No cookies or local storage
- ✅ Audio/text never leaves your device unencrypted

---

## 🌐 Browser Compatibility

| Browser | Desktop | Mobile | Notes |
|---------|---------|--------|-------|
| Chrome | ✅ | ✅ | Full support |
| Firefox | ✅ | ✅ | Full support |
| Safari | ✅ | ✅ | Full support (iOS 14.5+) |
| Edge | ✅ | ✅ | Full support |
| Opera | ✅ | ✅ | Full support |

---

## 📂 Project Structure

```
Cupid-s-Radio/
├── index.html          # Main application file (everything in one!)
├── screenshot.png      # App screenshot for README
├── LICENSE            # Apache 2.0 License
└── README.md          # This file
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Ideas for Contributions
- 🎨 Additional themes (Christmas, Birthday, etc.)
- 🔐 Enhanced encryption options
- 🎵 More audio effects
- 🌍 Internationalization (i18n)
- ♿ Accessibility improvements
- 📱 Native mobile app wrapper

---

## 🐛 Known Issues

- Audio playback on older iOS versions may not support Web Audio API filters
- Very large audio files (>10MB) may cause performance issues on low-end devices
- File sharing on some Android versions requires fallback to download

---

## 🗺️ Roadmap

- [ ] Add multiple themes (dark mode, Christmas, etc.)
- [ ] Support for image attachments
- [ ] Password strength indicator
- [ ] Multiple recipient support
- [ ] Self-destructing messages
- [ ] PWA manifest for "Add to Home Screen"
- [ ] Offline functionality with service workers

---

## 📜 License

This project is licensed under the **Apache License 2.0** - see the [LICENSE](LICENSE) file for details.

```
Copyright 2026 labonysur-cloud

Licensed under the Apache License, Version 2.0
```

---

## 👨‍💻 Author

**labonysur-cloud**

- GitHub: [@labonysur-cloud](https://github.com/labonysur-cloud)
- Repository: [Cupid-s-Radio](https://github.com/labonysur-cloud/Cupid-s-Radio)

---

## 💖 Acknowledgments

- Inspired by vintage love letters and old-time radio
- Built with ❤️ for Valentine's Day 2026
- Icons designed with SVG paths for minimal footprint
- Thanks to the React team for the amazing library

---

## 📞 Support

Having issues? Have questions?

- 🐛 [Report a bug](https://github.com/labonysur-cloud/Cupid-s-Radio/issues)
- 💡 [Request a feature](https://github.com/labonysur-cloud/Cupid-s-Radio/issues)
- 📧 Contact the maintainer via GitHub

---

<div align="center">

### Made with 💘 by labonysur-cloud

**Star ⭐ this repo if you found it helpful!**

</div>
