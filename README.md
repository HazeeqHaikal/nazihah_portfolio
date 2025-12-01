# Nazihah Portfolio

A minimalist portfolio website featuring a clean, modern design with smooth animations and a beige aesthetic. Built with Tailwind CSS and AOS (Animate On Scroll) library.

## ✨ Features

- **Minimalist Design**: Clean beige color palette with elegant typography
- **Responsive Layout**: Fully responsive grid system that works on all devices
- **Smooth Animations**: Scroll-based animations using AOS library
- **Modern UI Components**: 
  - Fixed floating navigation bar
  - Bento-style grid layout
  - Interactive hover effects
  - Custom scrollbar styling
- **Typography**: Combination of Inter and Playfair Display fonts
- **Sections**:
  - Hero section with introduction
  - Featured project showcase
  - Expertise highlights
  - Availability status
  - Project portfolio
  - About section
  - Contact information

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools required - this is a static HTML site

### Installation

1. Clone the repository:
```bash
git clone https://github.com/HazeeqHaikal/nazihah_portfolio.git
```

2. Navigate to the project directory:
```bash
cd nazihah_portfolio
```

3. Open `index.html` in your browser:
   - Double-click the file, or
   - Use a local server (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

## 🎨 Customization

### Colors

The color scheme is defined in the Tailwind config within `index.html`. Modify the beige palette to match your preferences:

```javascript
colors: {
    beige: {
        50: '#FDFBF7',  // Main background
        100: '#F5F2EB', // Secondary background
        200: '#EBE5DA', // Borders/Accents
        // ... more shades
    }
}
```

### Content

Update the following sections in `index.html`:
- **Name**: Search for "Alex Morgan" and replace with your name
- **Bio**: Update the introduction text
- **Projects**: Replace project descriptions and images
- **Expertise**: Modify the skills list
- **Contact**: Update email and social links

### Fonts

Currently using:
- **Sans-serif**: Inter (body text)
- **Serif**: Playfair Display (headings)

Change fonts by modifying the Google Fonts link and Tailwind font configuration.

## 📦 Dependencies

All dependencies are loaded via CDN:
- [Tailwind CSS](https://tailwindcss.com/) - Utility-first CSS framework
- [AOS](https://michalsnik.github.io/aos/) - Animate On Scroll library
- [Google Fonts](https://fonts.google.com/) - Inter & Playfair Display

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Nazihah**

- GitHub: [@HazeeqHaikal](https://github.com/HazeeqHaikal)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📸 Screenshots

_Add screenshots of your portfolio here_

## 🙏 Acknowledgments

- Design inspiration from minimalist portfolio trends
- Icons from SVG libraries
- Tailwind CSS for rapid styling
- AOS library for smooth animations

---

Made with ❤️ and minimal design principles
