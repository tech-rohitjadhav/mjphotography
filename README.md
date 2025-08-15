# MJ Photography Studio Website

A beautiful, modern, and responsive photography website designed for wedding and celebration photography services.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Portfolio Gallery**: Filterable portfolio section with hover effects
- **Contact Form**: Functional contact form with validation
- **Smooth Scrolling**: Enhanced navigation experience
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Animations**: Scroll-triggered animations and hover effects
- **SEO Optimized**: Proper meta tags and semantic HTML

## 📁 File Structure

```
mjphotography/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # CSS styles and responsive design
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Folder for portfolio and other images
└── README.md           # This file
```

## 🚀 Getting Started

1. **Download/Clone** the files to your web server or local machine
2. **Open** `index.html` in a web browser to view the website
3. **Customize** the content, images, and styling as needed

## 🎨 Customization Guide

### 1. Branding & Content

#### Update Studio Information
- **Studio Name**: Change "MJ Photography" in the navigation and footer
- **Contact Details**: Update phone, email, and address in the contact section
- **About Section**: Modify the description and statistics
- **Services**: Customize service descriptions and pricing

#### Location in HTML:
```html
<!-- Navigation Logo -->
<div class="nav-logo">
    <h2>YOUR STUDIO NAME</h2>
</div>

<!-- Contact Information -->
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <div>
        <h4>Phone</h4>
        <p>+1 (555) YOUR-PHONE</p>
    </div>
</div>
```

### 2. Images & Portfolio

#### Replace Placeholder Images
The website currently uses placeholder elements with icons. To add real images:

1. **Add your photos** to the `images` folder
2. **Replace placeholder divs** with actual `<img>` tags

Example:
```html
<!-- Replace this placeholder -->
<div class="image-placeholder">
    <i class="fas fa-heart"></i>
    <p>Wedding Ceremony</p>
</div>

<!-- With actual image -->
<img src="images/wedding-ceremony.jpg" alt="Wedding Ceremony" class="portfolio-image">
```

#### Portfolio Categories
- **Weddings**: Wedding ceremonies, receptions, engagement sessions
- **Celebrations**: Birthdays, anniversaries, graduations
- **Portraits**: Family portraits, individual sessions

### 3. Color Scheme

#### Primary Colors
The website uses a purple gradient theme. To change colors, update these CSS variables:

```css
/* Main gradient colors */
.btn-primary {
    background: linear-gradient(135deg, #YOUR-COLOR-1 0%, #YOUR-COLOR-2 100%);
}

/* Service icons and accents */
.service-icon {
    background: linear-gradient(135deg, #YOUR-COLOR-1 0%, #YOUR-COLOR-2 100%);
}
```

### 4. Typography

#### Fonts Used
- **Headings**: Playfair Display (elegant serif)
- **Body Text**: Poppins (clean sans-serif)

To change fonts, update the Google Fonts link in the HTML head:
```html
<link href="https://fonts.googleapis.com/css2?family=YOUR-FONT:wght@400;700&display=swap" rel="stylesheet">
```

### 5. Services & Pricing

#### Update Service Cards
Modify the services section to match your offerings:

```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-heart"></i>
    </div>
    <h3>Your Service Name</h3>
    <p>Service description...</p>
    <ul>
        <li>Feature 1</li>
        <li>Feature 2</li>
        <li>Feature 3</li>
    </ul>
</div>
```

### 6. Testimonials

#### Add Real Client Reviews
Replace the sample testimonials with actual client feedback:

```html
<div class="testimonial-card">
    <div class="testimonial-content">
        <p>"Client's actual testimonial here..."</p>
    </div>
    <div class="testimonial-author">
        <div class="author-avatar">
            <i class="fas fa-user"></i>
        </div>
        <div class="author-info">
            <h4>Client Name</h4>
            <p>Service Type</p>
        </div>
    </div>
</div>
```

## 📱 Mobile Optimization

The website is fully responsive and includes:
- **Mobile navigation** with hamburger menu
- **Touch-friendly** buttons and interactions
- **Optimized layouts** for different screen sizes
- **Fast loading** on mobile networks

## 🔧 Technical Features

### JavaScript Functionality
- **Portfolio filtering** by category
- **Smooth scrolling** navigation
- **Form validation** and submission
- **Scroll animations** and effects
- **Mobile menu** toggle
- **Counter animations** for statistics
- **Back to top** button
- **Scroll progress** indicator

### CSS Features
- **CSS Grid** and **Flexbox** layouts
- **CSS animations** and transitions
- **Custom scrollbar** styling
- **Hover effects** and micro-interactions
- **Gradient backgrounds** and overlays

## 📧 Contact Form

The contact form includes:
- **Name, email, phone** fields
- **Service selection** dropdown
- **Event date** picker
- **Message** textarea
- **Form validation** (client-side)
- **Success message** on submission

**Note**: The form currently shows an alert message. For production use, you'll need to:
1. Set up a server-side form handler
2. Configure email delivery
3. Add spam protection (reCAPTCHA)

## 🌐 Deployment

### Local Testing
1. Open `index.html` in a web browser
2. All features work locally without a server

### Web Hosting
1. **Upload** all files to your web hosting provider
2. **Ensure** the file structure is maintained
3. **Test** all functionality on the live site

### Recommended Hosting
- **Netlify**: Free hosting with easy deployment
- **Vercel**: Fast static site hosting
- **GitHub Pages**: Free hosting for public repositories
- **Traditional hosting**: Any web hosting service

## 🎯 SEO Optimization

The website includes:
- **Semantic HTML** structure
- **Meta tags** for social sharing
- **Alt text** for images (add when replacing placeholders)
- **Structured content** with proper headings
- **Fast loading** optimized code

## 🔄 Updates & Maintenance

### Regular Updates
- **Portfolio**: Add new work regularly
- **Testimonials**: Update with recent client feedback
- **Services**: Modify offerings as needed
- **Contact info**: Keep details current

### Performance Tips
- **Optimize images** before uploading (compress, resize)
- **Use WebP format** for better compression
- **Minimize CSS/JS** for production
- **Enable caching** on your web server

## 📞 Support

For customization help or questions:
1. **Review** this README thoroughly
2. **Check** the code comments for guidance
3. **Test** changes in a local environment first
4. **Backup** files before making major changes

## 🎨 Design Credits

- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Playfair Display, Poppins)
- **Design**: Modern, clean photography studio aesthetic
- **Colors**: Purple gradient theme (easily customizable)

---

**Created with ❤️ for professional photography studios**

*This website is ready to use and can be easily customized to match your brand and style.*
