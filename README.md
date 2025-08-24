# 🎵 Rhythmix - Your Music, Your Way

A sleek and modern Spotify clone built with vanilla JavaScript, HTML, and CSS. Experience seamless music streaming with an intuitive interface that brings your favorite tunes to life.

![Rhythmix Preview](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## ✨ Features

### 🎧 Core Functionality
- **Play/Pause Control**: Smooth audio playback with visual feedback
- **Track Navigation**: Skip forward/backward through your playlist
- **Progress Bar**: Interactive seek bar for precise playback control
- **Dynamic Song Display**: Real-time updates of currently playing track
- **Responsive Design**: Optimized for desktop and mobile devices

### 🎨 User Experience
- **Modern UI**: Clean, Spotify-inspired interface with dark theme
- **Visual Feedback**: Animated GIF indicator for playing status
- **Song Library**: Curated collection of NCS (No Copyright Sounds) tracks
- **Thumbnail Display**: Album art for each track
- **Smooth Transitions**: Elegant hover effects and animations

### 🎵 Music Collection
- **10 Handpicked Tracks** including:
  - Warriyo - Mortals [NCS Release]
  - Cielo - Huma-Huma
  - DEAF KEV - Invincible [NCS Release]
  - Different Heaven & EH!DE - My Heart [NCS Release]
  - And more amazing tracks!

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional but recommended)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rhythmix.git
   cd rhythmix
   ```

2. **Set up your music library**
   ```
   rhythmix/
   ├── songs/
   │   ├── 1.mp3
   │   ├── 2.mp3
   │   └── ... (up to 10.mp3)
   ├── covers/
   │   ├── 1.jpg
   │   ├── 2.jpg
   │   └── ... (up to 10.jpg)
   ├── logo.png
   ├── bg.jpg
   └── playing.gif
   ```

3. **Launch the application**
   - **Option A**: Open `index.html` directly in your browser
   - **Option B**: Use a local server (recommended)
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

4. **Access Rhythmix**
   - Direct: `file:///path/to/rhythmix/index.html`
   - Server: `http://localhost:8000`

## 🛠️ Project Structure

```
rhythmix/
├── 📄 index.html          # Main HTML structure
├── 🎨 style.css           # Styling and responsive design
├── ⚡ script.js           # Core functionality and interactions
├── 🖼️ assets/
│   ├── 🎵 songs/          # Audio files (.mp3)
│   ├── 🖼️ covers/         # Album artwork (.jpg)
│   ├── 🌟 logo.png        # Rhythmix logo
│   ├── 🎨 bg.jpg          # Background image
│   └── 📱 playing.gif     # Animation for playing status
└── 📖 README.md           # Project documentation
```

## 🎮 How to Use

### Basic Controls
- **▶️ Play/Pause**: Click the main play button or any track
- **⏭️ Next Track**: Skip to the next song in the playlist
- **⏮️ Previous Track**: Go back to the previous song
- **🎚️ Seek**: Drag the progress bar to jump to any point in the song

### Navigation
- Click any song in the playlist to start playing immediately
- Use keyboard shortcuts (if implemented) for quick control
- Visual indicators show the currently playing track

## 🔧 Customization

### Adding New Songs
1. Add your `.mp3` files to the `songs/` directory (name them 1.mp3, 2.mp3, etc.)
2. Add corresponding album art to `covers/` directory
3. Update the `songs` array in `script.js`:
   ```javascript
   let songs = [
       {songName: "Your Song Name", filePath: "songs/X.mp3", coverPath: "covers/X.jpg"},
       // Add more songs here
   ]
   ```

### Styling Changes
- Modify `style.css` to change colors, fonts, or layout
- Update the background image by replacing `bg.jpg`
- Customize the logo by replacing `logo.png`

### Functionality Extensions
- Add shuffle mode
- Implement repeat options
- Add volume control
- Create playlists feature

## 🌐 Browser Compatibility

| Browser | Version | Status |
|---------|---------|--------|
| Chrome  | 60+     | ✅ Full Support |
| Firefox | 55+     | ✅ Full Support |
| Safari  | 12+     | ✅ Full Support |
| Edge    | 79+     | ✅ Full Support |

## 📱 Responsive Design

Rhythmix adapts beautifully to different screen sizes:
- **Desktop**: Full-featured interface with sidebar and controls
- **Tablet**: Optimized layout for touch interaction
- **Mobile**: Streamlined design for small screens

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### Areas for Contribution
- 🎨 UI/UX improvements
- 🔧 New features (volume control, shuffle, repeat)
- 🐛 Bug fixes
- 📱 Mobile responsiveness enhancements
- 🎵 Audio format support expansion

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](License) file for details.

## 🙏 Acknowledgments

- **Font Awesome** for the beautiful icons
- **Google Fonts** for Ubuntu and Varela Round typography
- **NCS (NoCopyrightSounds)** for the amazing royalty-free music
- **Spotify** for design inspiration

## 🎯 Future Roadmap

- [ ] User authentication and profiles
- [ ] Cloud storage integration
- [ ] Social features (sharing, following)
- [ ] Advanced audio controls (equalizer, crossfade)
- [ ] Offline playback capability
- [ ] Mobile app development
- [ ] AI-powered recommendations

## 📞 Support

Having issues? We're here to help!

- 📧 Email: yashaswiaryan07588@gmail.com

---

<div align="center">
  <p>Made with ❤️ by music lovers, for music lovers</p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
