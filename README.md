# Constellate Proteomics Website

A modern, responsive website for Constellate Proteomics featuring a black-and-white molecular biology aesthetic. Built with HTML, CSS, and JavaScript, optimized for Netlify deployment.

## 🧬 Features

- **Molecular Biology Aesthetic**: Black-and-white design with animated molecular elements
- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Meta tags and semantic HTML structure
- **Performance Focused**: Optimized assets and smooth scrolling

## 🚀 Quick Deploy to Netlify

### Option 1: Deploy with Netlify UI (Recommended)

1. **Fork/Clone this repository** to your GitHub account
2. **Go to [Netlify](https://www.netlify.com/)** and sign in
3. **Click "New site from Git"**
4. **Choose your repository** from the list
5. **Configure build settings**:
   - Build command: Leave empty (not needed for static sites)
   - Publish directory: Leave as default (root directory)
6. **Click "Deploy site"**

### Option 2: Drag & Drop

1. **Download this repository** as a ZIP file
2. **Extract the ZIP file**
3. **Go to [Netlify](https://www.netlify.com/)**
4. **Drag the extracted folder** to the Netlify dashboard
5. **Your site will deploy automatically**

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy the site
netlify deploy --prod --dir=.
```

## 📁 Project Structure

```
Constellate_site/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── favicon.svg         # SVG favicon
└── README.md           # This file
```

## 🎨 Design Features

### Color Scheme
- **Primary Black**: #000000
- **Secondary Black**: #1a1a1a
- **Primary White**: #ffffff
- **Secondary White**: #f8f8f8
- **Accent Gray**: #666666

### Typography
- **Font Family**: Inter (Google Fonts)
- **Weights**: 300, 400, 500, 600, 700

### Animations
- Floating molecule backgrounds
- Pulsing logo atoms
- Rotating DNA helix icons
- Smooth scroll-triggered animations
- Parallax scrolling effects

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px

## 🔧 Customization

### Colors
Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-black: #000000;
    --secondary-black: #1a1a1a;
    --primary-white: #ffffff;
    /* ... more colors */
}
```

### Content
Update the content in `index.html` to match your company information:

- Company name and description
- Services offered
- Contact information
- About section content

### Animations
Modify animation speeds and effects in `styles.css` and `script.js`.

## 📧 Contact Form

The contact form includes:
- Name, email, company, and message fields
- Client-side validation
- Success/error notifications
- Form reset after submission

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
1. Set up a form handling service (Netlify Forms, Formspree, etc.)
2. Update the form action and method attributes
3. Configure the backend service

## 🌐 SEO & Meta Tags

The site includes:
- Proper meta description
- Open Graph tags
- Semantic HTML structure
- Alt text for images
- Proper heading hierarchy

## 📊 Performance

- Optimized CSS with CSS custom properties
- Minimal JavaScript bundle
- Efficient animations using CSS transforms
- Responsive images and icons
- Fast loading times

## 🚀 Deployment Checklist

Before deploying to Netlify:

- [ ] Update company information in `index.html`
- [ ] Customize colors in `styles.css` if needed
- [ ] Test the contact form functionality
- [ ] Verify all links work correctly
- [ ] Test responsive design on multiple devices
- [ ] Optimize images if adding custom ones

## 🔍 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

This project is created for Constellate Proteomics. Feel free to modify and use for your own projects.

## 🤝 Support

For questions about this website template or deployment issues:
1. Check the [Netlify documentation](https://docs.netlify.com/)
2. Review the code comments for implementation details
3. Test locally before deploying

---

**Built with ❤️ for Constellate Proteomics**
