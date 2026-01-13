# Portfolio Website

A modern, responsive portfolio website for an AI and Computer Vision Software Engineer. Built with HTML, CSS, and JavaScript, featuring a beautiful design with dark/light mode toggle.

## Features

- 🎨 **Modern Design**: Clean, professional, and visually appealing interface
- 🌓 **Dark/Light Mode**: Toggle between themes with preference persistence
- 📱 **Responsive**: Fully responsive design that works on all devices
- ⚡ **Smooth Animations**: Elegant transitions and scroll animations
- 🎯 **Interactive Elements**: Typing animation, smooth scrolling, and form validation
- 🚀 **Performance**: Lightweight and fast-loading
- ♿ **Accessible**: Built with accessibility in mind

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- Vanilla JavaScript
- Google Fonts (Inter & JetBrains Mono)

## Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles and theme definitions
├── script.js           # JavaScript functionality
├── assets/             # Images and other assets
└── README.md           # This file
```

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. Customize the content, links, and information to match your profile

## Customization

### Personal Information

Update the following in `index.html`:
- Your name in the hero section
- Email, LinkedIn, and GitHub links
- Project descriptions and links
- Skills and technologies
- Social media links

### Theme Colors

Modify the CSS variables in `styles.css`:
- Light theme colors are in `:root`
- Dark theme colors are in `[data-theme="dark"]`
- Adjust gradients, accent colors, and backgrounds as needed

### Typing Animation

Update the phrases array in `script.js`:
```javascript
const phrases = [
    'AI Engineer',
    'Computer Vision Specialist',
    // Add your own phrases
];
```

## Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub (name it `portfolio` or your preferred name)
2. Upload all files to the repository
3. Go to repository Settings
4. Scroll down to Pages section
5. Under "Source", select the branch (usually `main` or `master`)
6. Select the root folder (`/`)
7. Click Save
8. Your site will be available at `https://yourusername.github.io/portfolio/`

### Method 2: Using Git Command Line

1. Initialize git repository:
```bash
git init
```

2. Add all files:
```bash
git add .
```

3. Commit files:
```bash
git commit -m "Initial commit"
```

4. Add remote repository:
```bash
git remote add origin https://github.com/yourusername/portfolio.git
```

5. Push to GitHub:
```bash
git branch -M main
git push -u origin main
```

6. Enable GitHub Pages in repository settings (as described in Method 1)

## Contact Form

The contact form is currently set up for client-side validation only. To make it functional, you have several options:

1. **Formspree**: Sign up at [formspree.io](https://formspree.io) and add your form endpoint
2. **EmailJS**: Use [EmailJS](https://www.emailjs.com/) for email functionality
3. **Backend Integration**: Integrate with your own backend API
4. **Netlify Forms**: If deploying to Netlify, use their form handling

Update the form submission handler in `script.js` to use your preferred method.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Fonts: [Google Fonts](https://fonts.google.com/)
- Design inspiration: Modern portfolio websites
- Icons: Emoji (can be replaced with icon libraries if desired)

## Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements that could benefit others, consider submitting a pull request!

## Support

If you have any questions or need help with deployment, please open an issue on GitHub.

---

Built with ❤️ using HTML, CSS, and JavaScript