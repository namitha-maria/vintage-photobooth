# Vintage Photobooth

A retro-styled web photobooth that captures 3 photos and combines them into a classic photo strip with vintage filters. Built with pure HTML, CSS, and JavaScript - no dependencies required!

## Features

- **3-Shot Countdown Timer** - Classic photobooth countdown before each shot
- **Live Filter Preview** - See filters applied to your camera feed in real-time
- **Vintage Filter Options**:
  - Sepia
  - Black & White
  - High-Contrast Vintage
  - Film Grain
- **Customizable Text** - Add your own text and automatic date stamp
- **Instant Download** - Save your photo strip as a JPEG
- **Retro Design** - Beautiful vintage aesthetic with warm colors and classic fonts

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A working webcam
- HTTPS or localhost (required for camera access)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/namitha-maria/vintage-photobooth.git
```

2. Open the HTML file:
```bash
cd vintage-photobooth
open vintagebooth.html
```

Or simply double-click `vintagebooth.html` to open in your default browser.

### Usage

1. **Allow Camera Access** - Grant permission when your browser asks
2. **Choose a Filter** - Select your preferred vintage filter (optional)
3. **Customize Text** - Edit the text field (default: "LOVE")
4. **Start Shooting** - Click "Start 3-shot" button
5. **Strike a Pose** - You'll get a 3-second countdown before each photo
6. **Preview & Download** - Click "Preview Strip" to see your creation, then "Download Strip" to save

### Controls

- **Start 3-shot** - Begin the photo session
- **Retake** - Discard current photos and start over
- **Pause/Resume** - Temporarily pause the camera feed
- **Preview Strip** - Generate and view your photo strip
- **Download Strip** - Save your photo strip as an image

## Filters

- **None** - Original, unfiltered photos
- **Sepia** - Warm, vintage brown tone
- **Black & White** - Classic monochrome
- **High-Contrast Vintage** - Enhanced contrast with subtle sepia
- **Film Grain** - Black & white with authentic film grain texture

## Technical Details

- **Pure Vanilla JavaScript** - No frameworks or libraries
- **WebRTC** - Uses `getUserMedia()` API for camera access
- **Canvas API** - For image processing and filter effects
- **Responsive Design** - Works on desktop and tablet devices
- **CSS Filters** - Real-time live preview on video feed

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings > Pages
3. Select your branch (usually `main`) and root directory
4. Your site will be live at `https://namitha-maria.github.io/vintage-photobooth/`

**Note:** GitHub Pages uses HTTPS by default, so camera access will work perfectly!

### Local Testing

For local testing, use a local server instead of opening the file directly:

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve

# VS Code
# Use "Live Server" extension
```

Then visit `http://localhost:8000/vintagebooth.html`

## Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Fonts: [Google Fonts](https://fonts.google.com/) - Special Elite & Playfair Display
- Inspired by classic photobooth strips from the golden age of photography

## Contact

Have questions or suggestions? Feel free to open an issue or reach out!

---

Made with love and a passion for vintage aesthetics
