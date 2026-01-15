# Croppy

A free, open-source, client-side web application for fixing perspective distortion in photos and videos. Correct images of screens, documents, whiteboards, and other subjects photographed from an angle.

## Features

- **Image Perspective Correction** - Fix skewed photos with an intuitive 4-corner selection tool
- **Video Perspective Correction** - Apply the same corrections to video content
- **Precision Zoom Lens** - Magnified view with crosshair for accurate corner placement
- **Real-time Preview** - See your correction area before applying
- **High-Quality Output** - Bilinear interpolation for smooth results
- **Multiple Input Methods** - File upload, drag-and-drop, or paste from clipboard
- **Keyboard Shortcuts** - Press Enter to crop, Escape to close

## Privacy First

All processing happens entirely in your browser. Your images and videos never leave your device.

## Tech Stack

- Pure HTML5, CSS3, and vanilla JavaScript
- No frameworks, no dependencies, no build process
- Canvas API for image/video rendering
- Homography transformation with Gaussian elimination
- Works offline once loaded

## Usage

### Online
Visit the hosted version at **[nicershot.netlify.app](https://nicershot.netlify.app/)**

### Local
Simply open `index.html` in any modern browser:
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/croppy.git

# Open in browser
open croppy/index.html
```

### How to Use

1. Load an image via upload, drag-and-drop, or paste (Ctrl/Cmd+V)
2. Drag the four corner points to match the edges of the area you want to straighten
3. Use the zoom lens for precise placement
4. Press Enter or click "Crop" to apply the correction
5. Download your corrected image

## Files

| File | Description |
|------|-------------|
| `index.html` | Image perspective correction tool |
| `video.html` | Video perspective correction tool |

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge) on Windows, Mac, and Linux.

## License

MIT License - feel free to use, modify, and distribute.

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.
