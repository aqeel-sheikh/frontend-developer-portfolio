# Frontend Developer Portfolio

A modern, responsive portfolio website for frontend developers featuring smooth scrolling animations, dark/light theme toggle, and an elegant design. Built with vanilla HTML, CSS, and JavaScript, enhanced with GSAP animations and Lenis smooth scrolling.

[![Live Demo]](https://aqeelsheikh.netlify.app) <br/>
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Preview
<img width="1275" height="593" alt="image" src="https://github.com/user-attachments/assets/37a0308d-6968-436b-963a-edf8433b6be1" />


## ✨ Features

- **Smooth Scrolling**: Buttery smooth scrolling experience powered by Lenis
- **Scroll Animations**: Eye-catching animations using GSAP ScrollTrigger
- **Dark/Light Theme**: Toggle between dark and light modes with smooth transitions
- **Fully Responsive**: Optimized for all devices - desktop, tablet, and mobile
- **Modern UI/UX**: Clean, professional design with attention to detail
- **Contact Form**: Functional contact form with Web3Forms integration
- **Performance Optimized**: Fast loading times and optimized assets
- **SEO Friendly**: Proper semantic HTML and meta tags

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6+)** - Vanilla JS for interactions
- **GSAP** - Professional-grade animations
- **Lenis** - Smooth scrolling library
- **Web3Forms** - Contact form functionality

## 🚀 Quick Start

### Prerequisites

- A modern web browser
- A code editor (VS Code recommended)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/aqeel-sheikh/frontend-developer-portfolio
   cd frontend-developer-portfolio
   ```

2. **Open the project**
   - Simply open `index.html` in your browser
   - Or use a local development server (recommended):
   
   **Using VS Code Live Server:**
   - Install the Live Server extension
   - Right-click on `index.html` and select "Open with Live Server"

3. **Customize the content**
   - Edit `index.html` to add your personal information
   - Update images in the `assets/images/` folder
   - Modify colors and styles in `assets/css/style.css`
   - Configure Web3Forms code for the contact form (see below)

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   ├── js/
│   │   └── script.js      # Main JavaScript file
│   └── images/
│       ├── icons/         # SVG icons
│       ├── skills/        # Technology logos
│       └── pfp.jpg        # Profile picture
├── blogs/                 # Blog section (if applicable)
└── README.md             # This file
```

## ⚙️ Configuration

### Setting Up Web3Forms

1. Sign up at [Web3Forms](https://www.web3forms.com/)
2. Create a new access key
3. Replace the access key in your HTML form:

```html
html<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
    <input type="text" name="name" required>
    <input type="email" name="email" required>
    <textarea name="message" required></textarea>
    <button type="submit">Send Message</button>
</form>
```

### Customizing Theme Colors

Edit the CSS custom properties in `assets/css/style.css`:

```css
:root {
    --primary-color: #your-color;
    --background-color: #your-color;
    --text-color: #your-color;
    /* Add more custom colors */
}
```

## 🎨 Customization Guide

### Adding Your Information

1. **Profile Section**: Update name, title, bio, and contact information
2. **Skills Section**: Add/remove skills in the Skills section
3. **Projects Section**: Showcase your projects with images and descriptions
4. **Social Links**: Update your social media URLs

### Modifying Animations

GSAP animations are configured in `script.js`. You can adjust:

- Animation duration
- Easing functions
- Trigger points
- Animation effects

Example:
```javascript
gsap.from(".element", {
    scrollTrigger: {
        trigger: ".element",
        start: "top 80%",
    },
    y: 100,
    opacity: 0,
    duration: 1,
});
```

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints for:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🌐 Deployment

### Netlify (Recommended)

1. Push your code to GitHub
2. Go to [Netlify](https://www.netlify.com/)
3. Click "Add new site" → "Import an existing project"
4. Connect your GitHub repository
5. Deploy!

### GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages"
3. Select your branch and folder
4. Save and your site will be live

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [GSAP](https://greensock.com/gsap/) - Animation library
- [Lenis](https://github.com/studio-freight/lenis) - Smooth scrolling
- [Web3Forms](https://www.web3forms.com/) - Contact form service

## 👤 Author

**Aqeel Sheikh**

- Website: [aqeelsheikh.vercel.app](https://aqeelsheikh.vercel.app)
- GitHub: [@aqeel-sheikh](https://github.com/aqeel-sheikh)
- Twitter: [@aqeell_sheikh](https://x.com/aqeell_sheikh)
- Email: [sheikhakeelw01@gmail.com](sheikhakeelw01@gmail.com)

## 💬 Support

If you found this project helpful, please give it a ⭐️!

For questions, business or support, reach out via:
- Email: sheikhakeelw01@gmail.com
- Discord: @akeell

---

**Happy Coding! 🚀**
