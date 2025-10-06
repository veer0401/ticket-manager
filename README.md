# Updated README.md with Screenshots Section

# 🎟️ Ticket Manager

A modern, mobile-responsive QR-based ticket management system with real-time scanning capabilities. Built with pure HTML, CSS, and JavaScript.

![Ticket Manager](https://img.shields.io/badge/Version-1.0.0-purple)
![License](https://img.shields.io/badge/License-MIT-green)
![Mobile](https://img.shields.io/badge/Mobile-Responsive-blue)

## 📸 Screenshots

### 🎯 Scanner Interface
<img width="600" alt="QR Scanner Interface" src="https://github.com/user-attachments/assets/297c0e66-bbd9-4423-89c3-fa58398d550e" />
*Real-time QR code scanning with custom animated overlay and camera controls*

### 🎟️ Ticket Generator
<img width="600" alt="Ticket Generator" src="https://github.com/user-attachments/assets/929f18d3-ab3b-4535-9ad4-21319a9f75dc" />
*Bulk ticket generation with QR code preview and multiple export options*

### 📤 CSV Upload
<img width="600" alt="CSV Upload Page" src="https://github.com/user-attachments/assets/43dafc6f-607d-4e2d-8e54-ca7b42514ec5" />
*Drag & drop CSV upload with template download and data validation*

### 📊 Analytics Dashboard
<img width="600" alt="Analytics Dashboard" src="https://github.com/user-attachments/assets/69ec1a25-2598-4324-8045-5ad4c5559311" />
*Comprehensive dashboard with real-time statistics and advanced filtering*


## ✨ Features
### 🎯 Core Functionality
- **QR Code Scanner** - Real-time ticket validation with custom scanner UI
- **Bulk Ticket Generation** - Create thousands of tickets with unique QR codes
- **CSV Import/Export** - Easy data management with template support
- **Entry Dashboard** - Comprehensive analytics and filtering
- **Local Storage** - No backend required, works entirely in browser

### 📱 Mobile-Optimized
- **Touch-Friendly Interface** - Optimized for mobile devices
- **Responsive Design** - Works seamlessly on all screen sizes
- **Mobile-Specific Features** - Camera controls, haptic feedback, gesture support
- **PWA Ready** - Can be installed as a mobile app

### 🎨 Modern Tech Design
- **Dark Theme** - Easy on the eyes with purple/teal accents
- **Smooth Animations** - Engaging user experience
- **Custom Scanner** - Animated laser and scanning frame
- **Card-Based Layout** - Clean and organized interface

## 🚀 Quick Start

### Prerequisites
- Modern web browser with camera access
- No installation or dependencies required!

### Installation
1. Clone the repository:
```bash
git clone https://github.com/veer0401/ticket-manager.git
```

2. Open `index.html` in your browser:
```bash
cd ticket-manager
open index.html
```

**Live Demo**: [GitHub Pages](https://veer0401.github.io/ticket-manager/)

That's it! The application runs entirely in the browser.

## 📁 File Structure

```
ticket-manager/
├── index.html              # Main scanner interface
├── ticket_generator.html   # Bulk ticket generation
├── upload_tickets.html     # CSV upload functionality
├── entries.html           # Analytics dashboard
└── README.md
```

## 🎮 Usage

### 1. Scanning Tickets (`index.html`)
- Open the scanner page
- Allow camera permissions
- Point camera at QR codes
- Real-time validation with audio/visual feedback

### 2. Generating Tickets (`ticket_generator.html`)
- Set ticket prefix and event name
- Choose number of tickets (1-5000)
- Generate QR codes in batches
- Export as CSV or ZIP with QR images

### 3. Uploading Tickets (`upload_tickets.html`)
- Download CSV template
- Upload existing ticket data
- Drag & drop support
- Preview before import

### 4. Analytics Dashboard (`entries.html`)
- View all tickets with filtering
- Real-time statistics
- Export filtered data
- Clear data management

## 📊 Features Breakdown

### Scanner Page
- Custom scanner overlay with animated laser
- Camera switching support
- Real-time validation feedback
- Mobile-optimized touch controls
- Statistics dashboard

### Generator Page
- Batch processing for large volumes
- QR code preview (first 20 tickets)
- Multiple export formats
- Progress indicators
- Mobile-friendly form inputs

### Upload Page
- Drag & drop CSV upload
- Data validation
- Template download
- Preview functionality
- Error handling

### Dashboard Page
- Advanced filtering (event, status, search)
- Real-time statistics
- Multiple export options
- Responsive data tables
- Bulk operations

## 📱 Mobile Features

- **Touch-Optimized** - Larger buttons and touch targets
- **Gesture Support** - Swipe-friendly interfaces
- **Haptic Feedback** - Vibration on scan success
- **Orientation Handling** - Landscape/portrait optimization
- **Safe Area Support** - Notch and home indicator aware

## 🛠️ Technical Details

### Technologies Used
- **HTML5** - Semantic structure
- **CSS3** - Modern styling with CSS Grid/Flexbox
- **JavaScript ES6+** - Vanilla JS with modern features
- **Local Storage** - Client-side data persistence

### External Libraries
- `html5-qrcode` - QR code scanning
- `qrcode.js` - QR code generation
- `jszip` - ZIP file creation
- `file-saver` - Client-side file downloads

### Browser Support
- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Customization

### Styling
Modify CSS variables in `:root` to customize colors:
```css
:root {
  --primary: #6a1b9a;
  --secondary: #00bcd4;
  --dark-bg: #121212;
  /* ... */
}
```

### Ticket Format
Customize ticket ID generation in `ticket_generator.html`:
```javascript
const id = `${prefix}-${Date.now()}-${i+1}`;
```

## 📈 Performance

- **Optimized Scanning** - 10 FPS for smooth performance
- **Batch Processing** - Handles 5000+ tickets efficiently
- **Lazy Loading** - QR codes generated on demand
- **Memory Management** - Automatic cleanup of large operations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Troubleshooting

### Common Issues

**Camera not working:**
- Ensure HTTPS in production
- Check browser permissions
- Try different camera

**QR codes not scanning:**
- Ensure good lighting
- Hold device steady
- Check QR code quality

**Export not working:**
- Check browser download settings
- Ensure sufficient storage
- Try different browser

### Browser Compatibility
For best experience, use:
- Chrome/Edge for desktop
- Safari for iOS
- Chrome for Android

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- QR scanning powered by [html5-qrcode](https://github.com/mebjas/html5-qrcode)
- QR generation by [davidshimjs/qrcodejs](https://github.com/davidshimjs/qrcodejs)
- Icons from Twemoji and system emoji
- Inspired by modern event management systems

## 📞 Support

For support and questions:
- Open an [issue](https://github.com/veer0401/ticket-manager/issues)
- Check [troubleshooting](#troubleshooting) section
- Review existing issues for solutions

---

**⭐ Star this repo if you find it helpful!**

**Repository**: [https://github.com/veer0401/ticket-manager](https://github.com/veer0401/ticket-manager)
```

## Additional GitHub Repository Setup

### Creating GitHub Pages (Optional)
To deploy your ticket manager as a live demo:

1. Go to your repository settings on GitHub
2. Navigate to "Pages" in the sidebar
3. Select "Deploy from a branch" 
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"

Your live demo will be available at: `https://veer0401.github.io/ticket-manager/`

### Adding Actual Screenshots
To replace the placeholder images with actual screenshots:

1. Take screenshots of your application
2. Save them in a `/screenshots` folder in your repository
3. Update the image URLs in the README to point to your actual screenshots

Example:
```markdown
![Scanner Page](./screenshots/scanner-desktop.png)
![Mobile View](./screenshots/scanner-mobile.png)
```

### Repository Topics
Add these topics to your GitHub repository for better discoverability:
- `qr-scanner`
- `ticket-management`
- `event-management`
- `javascript`
- `html5`
- `mobile-responsive`
- `progressive-web-app`
