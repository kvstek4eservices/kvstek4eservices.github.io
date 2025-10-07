# kvsTek eServices - Personal Website

A beautiful, modern personal website for a technology trainer specializing in App Development, Web Development, and Hardware & Networking Support.

## 🎨 Features

- **Modern UI Design**: Clean, professional design with gradient accents and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Smooth scrolling, hover effects, and dynamic animations
- **Sections Include**:
  - Hero section with animated floating cards
  - About section with professional introduction
  - Services showcase with detailed offerings
  - Featured courses grid
  - Student testimonials
  - Contact form with validation
  - Social media links

## 🚀 Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icon library for visual elements
- **Google Fonts**: Inter font family for clean typography

## 📁 Project Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Setup Instructions

### Option 1: Direct File Opening

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website is ready to use

### Option 2: Using a Local Server (Recommended)

Using a local server provides a better development experience:

#### Using Python:
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

#### Using Node.js (http-server):
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 8000
```

#### Using PHP:
```bash
php -S localhost:8000
```

Then open your browser and navigate to `http://localhost:8000`

### Option 3: Using VS Code Live Server

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🎯 Customization Guide

### Update Personal Information

1. **Name and Branding**: Search for "kvsTek eServices" in `index.html` and replace with your name
2. **Contact Information**: Update email, phone, and location in the contact section
3. **Social Media Links**: Replace `#` in social links with your actual profile URLs

### Modify Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #ec4899;     /* Accent color */
    --accent-color: #14b8a6;        /* Additional accent */
}
```

### Add Your Own Content

- **Courses**: Add or modify course cards in the courses section
- **Testimonials**: Update testimonial cards with real student feedback
- **Services**: Customize service offerings and features
- **Stats**: Update the hero statistics (students trained, courses offered, etc.)

### Add Images

To add a profile picture or other images:

1. Create an `images` folder in the project directory
2. Add your images to this folder
3. Update the relevant sections in `index.html`:

```html
<!-- Example: Replace icon with image -->
<img src="images/profile.jpg" alt="kvsTek eServices" class="about-image">
```

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

## 🎨 Color Scheme

- **Primary**: Indigo (#6366f1)
- **Secondary**: Pink (#ec4899)
- **Accent**: Teal (#14b8a6)
- **Background**: Dark Navy (#0f172a)
- **Surface**: Slate (#1e293b)

## ✨ Features Breakdown

### Navigation
- Fixed navigation bar with scroll effect
- Active link highlighting based on scroll position
- Mobile-responsive hamburger menu

### Hero Section
- Animated gradient background shapes
- Floating technology cards with animations
- Call-to-action buttons
- Statistics counter animation

### Services Section
- Three main service categories
- Featured service highlighting
- Detailed feature lists
- Hover effects with 3D tilt

### Contact Form
- Form validation
- Success notification system
- Responsive layout
- Social media integration

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Future Enhancements

Consider adding these features:

- [ ] Blog section for tech articles
- [ ] Course enrollment system
- [ ] Student portal/dashboard
- [ ] Video testimonials
- [ ] Live chat integration
- [ ] Newsletter subscription
- [ ] Backend integration for contact form
- [ ] CMS integration for easy content updates
- [ ] Multi-language support
- [ ] Dark/Light theme toggle

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you have suggestions for improvements, please create an issue or submit a pull request.

## 📄 License

This project is open source and available for personal and commercial use.

## 📧 Contact

For questions or support, reach out through the contact form on the website or via:
- Email: kvstek4eservices@gmail.com
- Phone: +91 9400251470

---

**Built with ❤️ by kvsTek eServices**

*Empowering the next generation of tech professionals*
