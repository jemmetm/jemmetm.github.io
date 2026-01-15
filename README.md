# EMCEV Website

A modern, responsive website built with HTML5, CSS3, and vanilla JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with breakpoints for all screen sizes
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Mobile navigation, form handling, and scroll effects
- **Performance Optimized**: Lightweight code with optimized assets
- **Accessibility**: Semantic HTML and keyboard navigation support
- **Cross-browser Compatible**: Works on all modern browsers

## 📁 Project Structure

```
EMCEV Website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── package.json        # Project dependencies and scripts
└── README.md           # Project documentation
```

## 🛠️ Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone or download the project**
   ```bash
   # If using git
   git clone <repository-url>
   cd emcev-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm start
   ```
   This will open the website in your browser at `http://localhost:3000`

### Alternative Setup (Without Node.js)

If you don't have Node.js installed, you can simply:

1. Open `index.html` directly in your web browser
2. Or use any local web server of your choice

## 📜 Available Scripts

- `npm start` - Start development server with live reload
- `npm run dev` - Start development server with file watching
- `npm run serve` - Start simple HTTP server
- `npm run build` - Build command (no build process needed for static site)
- `npm run lint:css` - Lint CSS files
- `npm run lint:js` - Lint JavaScript files
- `npm run format` - Format code with Prettier

## 🎨 Customization

### Colors
The website uses a modern color palette defined in CSS custom properties. Main colors:
- Primary: `#3b82f6` (Blue)
- Secondary: `#64748b` (Slate)
- Background: `#ffffff` (White)
- Text: `#1e293b` (Dark slate)

### Typography
- Font Family: Inter (Google Fonts)
- Fallbacks: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif

### Sections
The website includes the following main sections:
- **Header**: Navigation with mobile menu
- **Hero**: Landing section with call-to-action
- **About**: Feature cards with icons
- **Services**: Service offerings with descriptions
- **Contact**: Contact form and information
- **Footer**: Links and company information

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Content Updates

To update the website content:

1. **Text Content**: Edit the HTML file directly
2. **Styling**: Modify `styles.css`
3. **Functionality**: Update `script.js`
4. **Images**: Replace placeholder SVGs with actual images

### Adding Images
Replace the placeholder SVG in the hero section with your actual images:
```html
<!-- Replace this -->
<div class="hero__placeholder">
  <svg>...</svg>
</div>

<!-- With this -->
<img src="your-image.jpg" alt="Description" class="hero__image">
```

## 🚀 Deployment

### Static Hosting
This is a static website that can be deployed to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Connect your repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload files to an S3 bucket
- **Any web server**: Upload files via FTP/SFTP

### Build Process
No build process is required. Simply upload all files to your web server.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

If you have any questions or need help with customization, please:
- Open an issue on GitHub
- Contact us at hello@emcev.com

## 🔄 Version History

- **v1.0.0** - Initial release with basic website structure
  - Responsive design
  - Mobile navigation
  - Contact form
  - Modern UI/UX

---

Made with ❤️ by the EMCEV Team
