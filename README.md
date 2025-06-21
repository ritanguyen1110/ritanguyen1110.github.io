# Tramori - Premium Japanese Green Tea

A beautiful, modern landing page for Tramori matcha business built with HTML, CSS, and JavaScript. This website showcases premium Japanese matcha products with an elegant design and smooth user experience, embodying the brand's slogan "A Sip of Heritage."

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Performance Optimized**: Fast loading with optimized code
- **Accessibility**: Keyboard navigation and screen reader friendly
- **SEO Ready**: Proper meta tags and semantic HTML structure

## 📁 File Structure

```
matcha/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Getting Started

### Prerequisites

- A GitHub account
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Setting up GitHub Pages

1. **Create a new repository** on GitHub:
   - Go to [GitHub](https://github.com)
   - Click "New repository"
   - Name it `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Make it public
   - Click "Create repository"

2. **Upload your files**:
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/yourusername/yourusername.github.io.git
     ```
   - Copy all the files from this project into the cloned repository
   - Add, commit, and push the files:
     ```bash
     git add .
     git commit -m "Initial commit: Tramori matcha business landing page"
     git push origin main
     ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch
   - Click "Save"

4. **Your website will be live** at `https://yourusername.github.io`

### Alternative: Using a custom repository name

If you want to use a different repository name (e.g., `tramori-matcha`):

1. Create a repository with your desired name
2. Upload the files as described above
3. In the GitHub Pages settings, select "Deploy from a branch" and choose "main"
4. Your site will be available at `https://yourusername.github.io/tramori-matcha`

## 🎨 Customization

### Colors
The website uses a green color scheme that can be easily customized. Main colors are defined in `styles.css`:

```css
:root {
    --primary-color: #4a7c59;
    --secondary-color: #2d5a27;
    --accent-color: #6b8e6b;
}
```

### Content
- **Business Information**: Update contact details, address, and social media links in `index.html`
- **Products**: Modify product names, descriptions, and prices in the products section
- **Images**: Replace placeholder elements with actual product images
- **Branding**: The website is already branded for "Tramori" with the slogan "A Sip of Heritage"

### Styling
- **Fonts**: The website uses Inter font from Google Fonts. You can change this in the `<head>` section of `index.html`
- **Layout**: Modify grid layouts and spacing in `styles.css`
- **Animations**: Adjust animation timing and effects in both CSS and JavaScript files

## 📱 Responsive Design

The website is fully responsive and includes:
- Mobile-first design approach
- Hamburger menu for mobile devices
- Flexible grid layouts
- Optimized typography for all screen sizes
- Touch-friendly buttons and interactions

## 🔧 Technical Features

### JavaScript Functionality
- Mobile navigation toggle
- Smooth scrolling navigation
- Form validation and submission
- Intersection Observer for scroll animations
- Loading animations
- Notification system
- Parallax effects
- Typing animation for hero title
- Scroll progress indicator

### CSS Features
- CSS Grid and Flexbox layouts
- CSS animations and transitions
- Custom properties (CSS variables)
- Backdrop filters
- Gradient backgrounds
- Box shadows and hover effects

### Performance Optimizations
- Debounced scroll events
- Optimized animations using `requestAnimationFrame`
- Efficient DOM queries
- Minimal external dependencies

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 Contact Forms

The website includes contact forms that are currently set up for demonstration. To make them functional:

1. **Backend Integration**: Connect to a backend service (e.g., Netlify Forms, Formspree, or your own server)
2. **Email Service**: Set up email notifications for form submissions
3. **Validation**: The forms include client-side validation, but you may want to add server-side validation

### Example: Using Formspree
Replace the form action in `index.html`:

```html
<form action="https://formspree.io/f/your-form-id" method="POST">
```

## 🔍 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Alt text for images
- Open Graph tags
- Structured data (can be added)
- Fast loading times
- Mobile-friendly design

## 📈 Analytics

To add analytics to your website:

1. **Google Analytics**: Add the tracking code to the `<head>` section of `index.html`
2. **Other Analytics**: Integrate with services like Hotjar, Mixpanel, etc.

## 🚀 Deployment Options

### GitHub Pages (Recommended)
- Free hosting
- Automatic deployment from Git
- Custom domain support
- SSL certificate included

### Other Options
- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **AWS S3**: Static website hosting
- **Traditional hosting**: Upload files to any web server

## 🤝 Contributing

Feel free to fork this project and customize it for your own matcha business. If you make improvements that could benefit others, consider submitting a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you need help setting up or customizing the website:

1. Check the GitHub Issues section
2. Review the code comments for guidance
3. Consult the browser's developer tools for debugging
4. Test on different devices and browsers

## 🎯 Next Steps

After setting up your website:

1. **Add Real Content**: Replace placeholder text with your actual business information
2. **Upload Images**: Add real product photos and branding images
3. **Connect Forms**: Set up functional contact forms
4. **Add Analytics**: Track visitor behavior
5. **SEO Optimization**: Add more specific meta tags and content
6. **Performance**: Optimize images and consider using a CDN
7. **Security**: Add security headers and HTTPS redirects

## 🍵 About Tramori

Tramori represents the essence of Japanese tea culture, bringing authentic matcha to tea enthusiasts worldwide. Our slogan "A Sip of Heritage" reflects our commitment to preserving traditional tea-making methods while sharing the rich cultural heritage of Japanese matcha with modern audiences.

---

**Happy coding! 🍵** 