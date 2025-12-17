# Joshua Andafu Portfolio

A modern, responsive personal portfolio website showcasing my skills and experience as a Software Engineer. Built with HTML, CSS, and JavaScript, featuring dark/light mode toggle, multiple color themes, and smooth animations.

## 🚀 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Dark/Light Mode**: Toggle between dark and light themes
- **Color Themes**: 5 different color schemes to choose from
- **Smooth Animations**: CSS transitions and JavaScript-powered interactions
- **Typing Animation**: Dynamic text animation on the homepage
- **Single Page Application**: Navigation between sections without page reloads
- **Mobile Menu**: Collapsible navigation for mobile devices
- **CV Download**: Direct download link to my resume
- **Contact Form**: Ready-to-use contact form structure

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Custom properties (variables), Flexbox, Grid, animations
- **JavaScript (ES6+)**: DOM manipulation, event handling, Typed.js integration
- **Font Awesome**: Icons for visual elements
- **Google Fonts**: Poppins and Clicker Script font families

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── app.js             # JavaScript functionality
├── color-1.css        # Red theme
├── color-2.css        # Orange theme
├── color-3.css        # Green theme
├── color-4.css        # Blue theme (default)
├── color-5.css        # Pink theme
├── Andafu_CV.pdf      # Resume/CV file
├── joelo.jpg          # Profile image
└── backend/           # Backend directory (currently empty)
```

## 🖥️ Sections

1. **Home**: Introduction with typing animation and hero image
2. **About**: Personal information, skills progress bars, education, and experience timeline
3. **Services**: Offered services including web design, graphic design, and software solutions
4. **Portfolio**: Showcase of projects with links to live demos and source code
5. **Contact**: Contact information and contact form

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - this is a static website

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. **Open in browser**:
   - Open `index.html` directly in your web browser
   - Or serve locally using any static server

### Local Development Server (Optional)

You can use any static server to serve the files locally:

**Using Python:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## 🎨 Customization

### Changing Colors

The website supports 5 color themes. To modify or add new themes:

1. Create a new CSS file (e.g., `color-6.css`)
2. Define the `--skin-color` variable:
   ```css
   :root {
       --skin-color: #your-color;
   }
   ```
3. Link the new stylesheet in `index.html` with `class="alternate-style"`
4. Add a color picker in the style switcher

### Personal Information

Update the following sections in `index.html`:

- **Personal details**: Name, profession, contact info in the About section
- **Skills**: Modify percentages and skill names
- **Education/Experience**: Update timeline items
- **Services**: Change service descriptions
- **Portfolio**: Add new projects with images and links

### Images

Replace the following files with your own:
- `joelo.jpg`: Profile/hero image
- Portfolio images in the Portfolio section

## 📱 Responsive Breakpoints

- **Desktop**: > 1199px
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px

## 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Modern mobile browsers

## 📞 Contact

**Joshua Andafu**
- Email: joshuaandafu2@gmail.com
- Phone: +254 793 381 989
- Website: www.vildexprosol.com
- Location: Nairobi, Kenya

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this repository and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

---

**Built with ❤️ by Joshua Andafu**
