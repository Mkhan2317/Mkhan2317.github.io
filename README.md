# MD Amir Khan - Portfolio Website

A modern, responsive portfolio website showcasing expertise in Quantitative Finance, Data Science, and Machine Learning.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling with active section highlighting
- **Mobile-Friendly**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: Intersection Observer API for scroll-triggered animations
- **Performance Optimized**: Fast loading with optimized assets

## 🚀 Sections

1. **Hero Section**: Introduction with key highlights and call-to-action buttons
2. **About**: Personal introduction, expertise, and key statistics
3. **Education**: Timeline view of educational background
4. **Experience**: Professional experience with detailed descriptions
5. **Projects**: Showcase of key projects with technologies used
6. **Skills**: Technical skills with visual progress bars and tags
7. **Contact**: Contact information and functional contact form

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality and animations
- **Font Awesome**: Icons for social links and contact information
- **Google Fonts**: Inter font family for clean typography

## 📁 File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # Documentation
```

## 🎨 Customization Guide

### Colors
The website uses a blue color scheme. To change the primary color, update these CSS variables:

```css
/* Main brand color */
#2563eb -> your-color

/* Gradient backgrounds */
linear-gradient(135deg, #667eea 0%, #764ba2 100%)
```

### Content Updates

#### Personal Information
Update the following in `index.html`:

1. **Name and Title**: Lines 25-26, 45-46
2. **Contact Information**: Lines 380-395
3. **Social Links**: Lines 60-62, update href attributes
4. **About Section**: Lines 80-95
5. **Education**: Lines 105-140
6. **Experience**: Lines 150-200
7. **Projects**: Lines 210-260

#### Adding New Sections
To add a new section:

1. Add navigation link in the navbar
2. Create section HTML structure
3. Add corresponding CSS styling
4. Update JavaScript for smooth scrolling

### Images
To add a profile picture:

1. Replace the `.profile-placeholder` div with an `<img>` tag
2. Update the CSS accordingly
3. Add company logos by replacing `.company-logo` divs with images

### Contact Form
The contact form currently shows an alert on submission. To connect to a backend:

1. Update the form action attribute
2. Modify the JavaScript submit handler
3. Add proper form validation
4. Connect to your preferred email service (EmailJS, Netlify Forms, etc.)

## 🚀 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Or connect your GitHub repository
3. Site will be automatically deployed

### Vercel
1. Import your GitHub repository
2. Deploy with default settings
3. Site will be live on Vercel domain

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Performance Optimization

- Minify CSS and JavaScript for production
- Optimize images (WebP format recommended)
- Enable compression on your hosting server
- Use a CDN for external libraries

## 📈 Analytics

To add Google Analytics:

1. Get your GA tracking ID
2. Add the tracking script to the `<head>` section
3. Configure goals and events as needed

## 🎯 SEO Optimization

The website includes:
- Semantic HTML structure
- Meta descriptions (add to `<head>`)
- Open Graph tags (add for social sharing)
- Structured data markup (recommended)

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, pull requests are welcome!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

If you have questions about customizing this portfolio, feel free to reach out:

- Email: mdamirkhan7@stevens.edu
- LinkedIn: [linkedin.com/in/amirkhan2317](https://linkedin.com/in/amirkhan2317/)
- GitHub: [github.com/Mkhan2317](https://github.com/Mkhan2317)
- Portfolio: [datascienceportfol.io/mkhan37](https://www.datascienceportfol.io/mkhan37)

---

**Note**: Remember to update all placeholder content with your actual information before deploying! 