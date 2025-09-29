# TxPhotobooth - Professional Photo Studio

A modern, responsive photo booth application built with HTML5, CSS3, and JavaScript. Features camera capture, vintage filters, photo layout arrangement, and custom frame selection.

## 🌟 Features

- **Camera Capture**: High-quality photo capture with webcam
- **Vintage Filters**: Multiple LUT-based color filters
- **Photo Layout**: 4-photo grid arrangement with drag & drop
- **Frame Selection**: Built-in and custom frame options
- **Responsive Design**: Works on desktop and mobile
- **Modern UI**: Beautiful gradient design with glassmorphism effects

## 🚀 Quick Deploy to Vercel

### Method 1: Deploy via Vercel CLI

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm i -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy**:
   ```bash
   vercel --prod
   ```

### Method 2: Deploy via Vercel Dashboard

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Deploy automatically

## 📁 Project Structure

```
txphotobooth/
├── home.html              # Landing page
├── vintage.html           # Camera & filter selection
├── layout.html            # Photo arrangement
├── frame.html             # Frame selection
├── capture.html           # Photo capture
├── beauty.html            # Beauty mode (deprecated)
├── bua.html              # Additional feature
├── backupwebcam.html     # Backup camera
├── logo-test.html        # Logo testing
├── frames/               # Frame images
│   ├── goc.png
│   ├── nhieu.png
│   └── xuoc.png
├── filter/               # LUT filter files
├── images/               # Static images
├── fonts/                # Custom fonts
├── galleries/            # Photo galleries
├── output/               # Generated photos
├── vintage_output/       # Vintage filter output
├── print_out/            # Print-ready images
├── vercel.json           # Vercel configuration
├── package.json          # Project metadata
└── README.md             # This file
```

## 🛠️ Local Development

1. **Clone repository**:
   ```bash
   git clone <your-repo-url>
   cd txphotobooth
   ```

2. **Start local server**:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Or using Node.js
   npx http-server -p 8000
   ```

3. **Open browser**:
   Navigate to `http://localhost:8000`

## 🎨 Customization

### Adding New Filters
1. Add `.cube` files to `filter/` folder
2. Update filter list in `vintage.html`

### Adding New Frames
1. Add `.png` files to `frames/` folder
2. Update `loadBuiltInFrames()` in `frame.html`

### Styling
- Main styles are in each HTML file's `<style>` section
- Color scheme uses pink/purple gradients
- Responsive breakpoints at 768px

## 📱 Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## 🔧 Technical Details

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Camera**: getUserMedia API
- **Image Processing**: Canvas API
- **Storage**: localStorage, sessionStorage
- **Filters**: LUT (Look-Up Table) processing
- **Deployment**: Vercel Static Hosting

## 📞 Support

- **Contact**: Zalo 0395 458 706
- **Company**: Tiva Solutions
- **Website**: [Your Website URL]

## 📄 License

MIT License - see LICENSE file for details

---

**TxPhotobooth** - Professional Photo Studio by Tiva Solutions
