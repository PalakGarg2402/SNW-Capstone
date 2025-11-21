# SNW-Capstone
# QuickMart - Food Delivery Website

A modern, responsive food and grocery delivery website built as a college capstone project. This project showcases fundamental web development skills using pure HTML5 and CSS3, without any JavaScript frameworks or libraries.

## 🎯 Project Overview

**QuickMart** is a static website inspired by popular food delivery platforms like Swiggy Instamart. It features a clean, professional design with warm orange colors and modern UI/UX patterns. The website allows users to browse product categories, view featured products, check special offers, and contact the business.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Modern UI**: Clean interface with warm orange color scheme and smooth transitions
- **Product Categories**: Browse through 6 main categories (Fruits, Vegetables, Snacks, Beverages, Cooking Essentials, Dairy)
- **Featured Products**: Showcase of popular products with pricing, images, and discount badges
- **Special Offers**: Promotional banners with colorful gradient backgrounds and promo codes
- **Contact Form**: Get in touch section with contact information and form
- **Sticky Navigation**: Fixed header for easy navigation throughout the site

## 🛠️ Technologies Used

- **HTML5**: Semantic markup, forms, meta tags
- **CSS3**: 
  - CSS Grid for product and category layouts
  - Flexbox for navigation and components
  - CSS Variables for consistent theming
  - Media queries for responsive design
  - Transitions and hover effects
  - Gradient backgrounds
- **Google Fonts**: Poppins font family
- **Unsplash**: Placeholder product images

## 📁 File Structure

```
foodmart/
├── index.html          # Main HTML file with all sections
├── style.css           # Complete stylesheet with responsive design
└── README.md           # Project documentation (this file)
```

## 🚀 How to Run

### Option 1: Direct Browser Open
Simply open the `index.html` file in your web browser:

**macOS:**
```bash
open index.html
```

**Linux:**
```bash
xdg-open index.html
```

**Windows:**
```bash
start index.html
```

### Option 2: Using a Local Server (Recommended)

Using a local development server helps with testing and avoids CORS issues:

**Using Python 3:**
```bash
python3 -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js:**
```bash
npx http-server -p 8000
```

Then visit `http://localhost:8000` in your browser.

## 📱 Responsive Breakpoints

The website adapts to different screen sizes:

- **Desktop**: > 768px (full multi-column layout)
- **Tablet**: 481px - 768px (adjusted columns, stacked navigation)
- **Mobile**: ≤ 480px (single column, vertical navigation)

## 🎨 Color Scheme

The design uses a warm, inviting color palette:

- **Primary Orange**: `#ff5200` (brand color, buttons, accents)
- **Orange Dark**: `#e64a00` (hover states)
- **White**: `#ffffff` (backgrounds, text on dark)
- **Light Gray**: `#f5f5f5` (section backgrounds)
- **Text Dark**: `#333333` (primary text)
- **Success Green**: `#60b246` (discount badges)

## 📋 Sections Included

1. **Header**: Sticky navigation with logo and menu links
2. **Hero Section**: Eye-catching banner with search functionality (UI only)
3. **Categories**: 6 product category cards with icons
4. **Featured Products**: 6 product cards with images, pricing, and CTA buttons
5. **Special Offers**: 3 promotional offer cards with gradient backgrounds
6. **Contact**: Contact information and form layout
7. **Footer**: Multi-column footer with links and social media

## 🎓 Educational Purpose

This project was created as a college capstone project to demonstrate:

- Understanding of HTML5 semantic elements
- Proficiency in CSS3 layout techniques (Grid, Flexbox)
- Responsive web design principles
- CSS organization and best practices
- Design system implementation with CSS variables
- Clean, maintainable code structure

## 🔧 Customization

### Changing Colors
All colors are defined as CSS variables in `style.css`:
```css
:root {
    --primary-orange: #ff5200;
    --success-green: #60b246;
    /* ... other colors */
}
```

### Adding Products
To add new products, copy an existing `.product-card` div in `index.html` and update:
- Product image URL
- Product name
- Weight/quantity
- Price
- Discount badge (if applicable)

### Modifying Categories
Edit the `.category-card` divs in the Categories section with new:
- Emoji icons
- Category names
- Descriptions

## 📝 Notes

- All prices are in Indian Rupees (₹)
- Product images are loaded from Unsplash (requires internet connection)
- Forms are UI-only and don't submit data (no backend)
- "Add to Cart" buttons are non-functional (no JavaScript)
- Navigation uses anchor links for smooth scrolling

## 🌐 Browser Compatibility

This website works on all modern browsers:
- Google Chrome (latest)
- Mozilla Firefox (latest)
- Safari (latest)
- Microsoft Edge (latest)

*Note: Internet Explorer is not supported due to modern CSS features.*

## 📧 Contact

For questions or feedback about this project, please use the contact form on the website or reach out via:

- **Email**: support@quickmart.com
- **Phone**: +91 98765 43210
- **Address**: 123 MG Road, Bengaluru, Karnataka 560001

## 📄 License

This project is created for educational purposes as part of a college capstone project.

---

**Developed by**: [Your Name]  
**Project Type**: College Capstone Project  
**Date**: November 2024  
**Status**: ✅ Complete
