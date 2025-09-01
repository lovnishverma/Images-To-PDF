# 🖼️ → 📄 Images to PDF Converter

A powerful, client-side web application that converts multiple images into a single PDF document. Built with modern web technologies and designed with privacy in mind - all processing happens in your browser!

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://lovnishverma.github.io/Images-To-PDF/)
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## ✨ Features

### 🚀 Core Functionality
- **Drag & Drop Interface**: Simply drag images into the browser or click to browse
- **Multiple Format Support**: JPG, PNG, GIF, WebP, and more image formats
- **Batch Processing**: Convert multiple images at once
- **Real-time Preview**: See your images before conversion
- **Drag to Reorder**: Easily rearrange image order with drag & drop

### ⚙️ Customization Options
- **Page Sizes**: A4, Letter, A3, A5, Legal formats
- **Orientation**: Auto-detect, Portrait, or Landscape
- **Image Quality**: High, Medium, or Low compression
- **Layout Options**: 1, 2, or 4 images per page
- **Margins**: Adjustable page margins (0-50mm)
- **Aspect Ratio**: Preserve original ratios or fit to page
- **Custom Filename**: Name your PDF output

### 🔒 Privacy & Security
- **100% Client-Side**: No server uploads - your images never leave your device
- **No Registration**: Use immediately without accounts or sign-ups
- **Offline Capable**: Works without internet once loaded
- **Secure Processing**: All operations happen in your browser's sandbox

### 📊 Smart Analytics
- **Image Counter**: Track how many images you've added
- **File Size Monitoring**: See total size of your images
- **Dimension Analysis**: Average image dimensions display
- **Progress Tracking**: Real-time conversion progress

## 🎯 Use Cases

- **Document Scanning**: Convert phone photos of documents to PDF
- **Photo Albums**: Create PDF albums from digital photos
- **Presentations**: Combine screenshots and images into PDFs
- **Archives**: Digitize and organize image collections
- **Reports**: Add images to create visual PDF reports
- **Portfolios**: Showcase artwork or photography in PDF format

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|---------|
| Chrome | 80+ | ✅ Full Support |
| Firefox | 75+ | ✅ Full Support |
| Safari | 13+ | ✅ Full Support |
| Edge | 80+ | ✅ Full Support |
| Opera | 67+ | ✅ Full Support |

## 🛠️ Technology Stack

- **Frontend**: Vanilla HTML5, CSS3, JavaScript (ES6+)
- **PDF Generation**: [jsPDF](https://github.com/parallax/jsPDF) library
- **Styling**: Custom CSS with modern design principles
- **File Handling**: HTML5 File API and Canvas API
- **Drag & Drop**: HTML5 Drag and Drop API

## 🚀 Getting Started

### Option 1: Use Online
Visit the live demo: [https://lovnishverma.github.io/Images-To-PDF/](https://lovnishverma.github.io/Images-To-PDF/)

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/lovnishverma/Images-To-PDF.git

# Navigate to the project directory
cd Images-To-PDF

# Open in your preferred web server
# For Python 3:
python -m http.server 8000

# For Node.js (with http-server):
npx http-server

# Or simply open index.html in your browser
```

## 📖 How to Use

1. **Add Images**: 
   - Drag and drop images onto the dropzone, or
   - Click "Browse Files" to select images from your device

2. **Arrange Images**: 
   - Drag images to reorder them
   - Remove unwanted images using the × button

3. **Customize Settings**:
   - Choose page size (A4, Letter, etc.)
   - Set orientation (Auto, Portrait, Landscape)
   - Adjust image quality and margins
   - Select images per page layout

4. **Generate PDF**:
   - Click "Generate PDF" button
   - Your PDF will automatically download

## 🎨 Design Features

- **Modern Dark Theme**: Easy on the eyes with gradient accents
- **Responsive Design**: Works on desktop, tablet, and mobile
- **Smooth Animations**: Hover effects and transitions
- **Intuitive UX**: Clear visual feedback and status updates
- **Accessibility**: Keyboard navigation and screen reader friendly

## 🔧 Configuration

The application supports various customization options through the settings panel:

```javascript
// Default settings
const defaultSettings = {
  pageSize: 'a4',           // a4, letter, a3, a5, legal
  orientation: 'auto',      // auto, portrait, landscape
  imageQuality: 'medium',   // high, medium, low
  margin: 10,               // 0-50 (mm)
  imagesPerPage: 1,         // 1, 2, 4
  fitToPage: true,          // boolean
  preserveAspectRatio: true // boolean
};
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the Repository**
2. **Create a Feature Branch**: `git checkout -b feature/amazing-feature`
3. **Commit Changes**: `git commit -m 'Add amazing feature'`
4. **Push to Branch**: `git push origin feature/amazing-feature`
5. **Open a Pull Request**

### Development Guidelines
- Use modern ES6+ JavaScript
- Follow existing code style and formatting
- Test across multiple browsers
- Ensure responsive design works
- Add comments for complex functionality

## 📝 Changelog

### v1.0.0 (Current)
- ✅ Initial release
- ✅ Drag & drop image upload
- ✅ Multiple page size options
- ✅ Configurable image quality
- ✅ Real-time preview and stats
- ✅ Mobile responsive design
- ✅ Progress tracking
- ✅ Client-side processing

### Planned Features
- 🔄 Image rotation and cropping
- 🔄 Watermark support
- 🔄 Batch image compression
- 🔄 OCR text extraction
- 🔄 Template-based layouts
- 🔄 Cloud storage integration options

## 🐛 Known Issues

- Very large images (>10MB) may cause memory issues on low-end devices
- Safari on iOS may have limitations with very large PDFs
- Some older mobile browsers may not support all features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Lovnish Verma**
- GitHub: [@lovnishverma](https://github.com/lovnishverma)
- Website: [lovnishverma.github.io](https://lovnishverma.github.io)

## 🙏 Acknowledgments

- [jsPDF](https://github.com/parallax/jsPDF) - PDF generation library
- [MDN Web Docs](https://developer.mozilla.org/) - Web development documentation
- Modern web browser APIs for file handling and canvas operations
- The open-source community for inspiration and best practices

## 📞 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/lovnishverma/Images-To-PDF/issues) page
2. Create a new issue if your problem isn't listed
3. Provide detailed information about your browser and the steps to reproduce

## ⭐ Show Your Support

If you found this project helpful, please consider:
- Giving it a ⭐ on GitHub
- Sharing it with others who might find it useful
- Contributing improvements or bug fixes

---

<div align="center">

**[🚀 Try it Live](https://lovnishverma.github.io/Images-To-PDF/) | [📝 Report Bug](https://github.com/lovnishverma/Images-To-PDF/issues) | [💡 Request Feature](https://github.com/lovnishverma/Images-To-PDF/issues)**

Made with ❤️ for the web development community

</div>
