# Salvador Consulting - Static Website

Professional fiscal, accounting, and labor consulting website built with HTML, CSS, and JavaScript.

## 📁 Project Structure

```
fiscal-web/
├── index.html          # Main HTML file
├── assets/
│   ├── style.css       # Styling
│   └── script.js       # JavaScript functionality
├── img/
│   └── logo.png        # Your logo
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser

### GitHub Pages Deployment

1. **Create a GitHub Repository**
   - Go to GitHub and create a new repository named: `username.github.io`
   - Replace `username` with your GitHub username

2. **Push Code to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
   - Save

4. **Your site will be live at:** `https://username.github.io`

## 📝 Customization

### Update Logo
Replace `img/logo.png` with your Salvador Consulting logo.

### Update Email
- Contact form sends to: `sedaaykutlu@gmail.com`
- Edit in `index.html` line: `<a href="mailto:sedaaykutlu@gmail.com">`
- Also update in `assets/script.js` in the form handler

### Update Phone Number
- Edit line in `index.html`: `<a href="tel:+34600000000">`

### Colors
- Edit CSS variables in `assets/style.css`:
  - `--primary-color`: Main brand color (currently #003d82)
  - `--secondary-color`: Secondary color (currently #0066cc)
  - `--accent-color`: Accent color for buttons (currently #f39200)

### Content
Edit text in `index.html` to match your services and information.

## 🎨 Features

- Responsive design (mobile, tablet, desktop)
- Smooth scrolling navigation
- Contact form with email integration
- Service cards with hover effects
- Team section
- About/Story section with stats
- Professional animations
- Mobile-friendly hamburger menu

## 📧 Contact Form

The contact form currently uses `mailto:` links, which opens the user's default email client. 

For automatic email delivery without user intervention, you would need:
- A backend service (Node.js, Python, etc.)
- A service like Formspree, Basin, or Netlify Forms
- Currently works for: Manual email client opening

## ⚙️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid & Flexbox
- **JavaScript** - Vanilla JS for interactivity
- **GitHub Pages** - Free static hosting

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Copyright © 2026 Salvador Consulting. All rights reserved.

## 📞 Support

For customization help, refer to the comments in the HTML, CSS, and JS files.

---

**Ready to deploy?** Follow the GitHub Pages deployment steps above and your site will be live! 🎉
