# The 27th Plate - Cloud Kitchen Website

A fully responsive, mobile-first website for "The 27th Plate" homemade cloud kitchen. Built with clean HTML5, CSS3, and Bootstrap 5 for maximum responsiveness and accessibility.

## 🏗️ Website Structure

```
27th plate/
├── index.html                          # Home page
├── about.html                          # About the cloud kitchen
├── menu.html                           # Menu overview with all products
├── contact.html                        # Contact form and information
├── order.html                          # Order options and testimonials
├── css/
│   └── style.css                       # Main stylesheet (responsive, mobile-first)
├── products/                           # Individual product detail pages
│   ├── fresh-juice-watermelon.html     # Water Melon Chill Splash
│   ├── fresh-juice-passion.html        # Passion Bliss
│   ├── fresh-juice-woodapple.html      # Creamy Wood Apple
│   ├── beverage-coffee-cloud.html      # Coffee Cloud
│   ├── lunch-grandma-yellow-rice.html  # Grandma's Chicken Yellow Rice
│   └── lunch-chicken-rice-curry.html   # Homemade Chicken Rice & Curry
├── images/
│   ├── products/                       # Product images
│   ├── origin/                         # Origin story images
│   └── story/                          # Product story images
└── Images/
    └── Official logo.png               # Navbar logo (existing)
```

## 📄 Page Descriptions

### Home Page (`index.html`)
- Hero section with welcome message and CTA button
- About section describing the cloud kitchen concept
- Quick navigation to menu and other pages
- Responsive layout that adapts to all screen sizes

### About Page (`about.html`)
- Detailed story of the brand
- Values and mission statement
- Multiple sections highlighting why to choose The 27th Plate
- Organized with images and descriptive text

### Menu Page (`menu.html`)
- All products organized by category:
  - **Fresh Juices**: Watermelon, Passion Fruit, Wood Apple
  - **Beverages**: Coffee Cloud
  - **Lunch Specials**: Grandma's Yellow Rice, Chicken Rice & Curry
- Each product shown as a card with image, description, and link to detail page
- Responsive grid layout (3 columns on desktop, 1 on mobile)

### Product Detail Pages
Each product has its own page (`products/` folder) featuring:
- Product image
- Full description
- Origin story section with image
- Product story section with image
- "Order Now" button linking to order page
- Back to menu link for easy navigation

### Contact Page (`contact.html`)
- **Contact Information**:
  - Phone: 0771 466 419
  - Email: the27plate@gmail.com
  - Hours of operation
- Contact form with fields for:
  - Name (required)
  - Email (required)
  - Phone number (optional)
  - Message (required)

### Order Page (`order.html`)
- Four order options:
  - PickMe Food (https://pickme-app-sl.onelink.me/...)
  - Uber Eats (https://www.ubereats.com/...)
  - Instagram (@the27thplatesl)
  - Direct call (0771 466 419)
- Why order from us section with benefits
- Customer testimonials section with 5-star reviews
- All buttons are mobile-friendly and prominently displayed

## 🎨 Design Features

### Color Scheme
- **Primary Color**: #ffd6d6 (Light Pink)
- **Secondary Color**: #7a0000 (Deep Red)
- **Accent Color**: #ff6b6b (Vibrant Red)
- **Light Background**: #fff5f5 (Very Light Pink)

### Typography
- Font Family: Poppins (from Google Fonts)
- Font Weights: 400, 500, 600
- Responsive font sizes that scale on mobile devices

### Responsive Design
- **Mobile First**: Designed and optimized for mobile first, then enhanced for larger screens
- **Breakpoints**:
  - Desktop: 1200px max-width container
  - Tablet: Adjustments from 768px
  - Mobile: Optimizations for screens under 576px
- **Features**:
  - Flexbox and CSS Grid layouts
  - Responsive images with max-width: 100%
  - Mobile navigation with Bootstrap collapsible menu
  - Touch-friendly buttons and links

### Components
1. **Navigation Bar**: Fixed/sticky, responsive, Bootstrap-based
2. **Hero Section**: Full-width gradient background with CTA
3. **Cards**: Product cards with hover effects and shadows
4. **Grid Layout**: Responsive product grid (auto-fit, minmax)
5. **Forms**: Styled input fields with focus states
6. **Buttons**: Multiple button styles (primary, secondary, large)
7. **Testimonials**: Review cards with star ratings
8. **Footer**: Simple copyright notice

## 🚀 Getting Started

### 1. Setup
- All files are ready to use
- No build process required
- Works with any local or remote server

### 2. Local Testing
Use a simple HTTP server to test locally:

```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open: `http://localhost:8000`

### 3. Adding Images
Place placeholder or actual images in these folders:
- `images/products/` - Product photos
- `images/origin/` - Origin story photos
- `images/story/` - Product story photos

File naming convention:
- `watermelon-juice.jpg`
- `passion-juice.jpg`
- `woodapple-juice.jpg`
- `coffee-cloud.jpg`
- `yellow-rice.jpg`
- `chicken-rice-curry.jpg`

And corresponding images in `origin/` and `story/` folders with similar names.

## 📱 Responsive Behavior

### Desktop (1200px+)
- 3-column product grid
- Full navigation menu displayed
- Large hero section
- Optimized padding and margins

### Tablet (768px - 1199px)
- 2-column product grid
- Full menu with possible wrapping
- Adjusted font sizes
- Medium padding

### Mobile (< 576px)
- 1-column product grid
- Collapsed navigation menu (hamburger)
- Optimized touch targets (44px minimum)
- Reduced padding/margins for screen space
- Larger, easier-to-tap buttons
- Single-column order buttons

## 🔗 Internal Linking Structure

- All internal links use relative paths for portability
- Product pages in `/products/` folder use `../` to reference root files
- Consistent navbar on all pages for easy navigation
- Back links on product detail pages return to menu

## 📧 Contact & Order Information

- **Phone**: 0771 466 419
- **Email**: the27plate@gmail.com
- **Instagram**: @the27thplatesl
- **PickMe**: [Link in order page]
- **Uber Eats**: [Link in order page]

## ✨ Key Features

✅ Fully responsive design (mobile-first)
✅ No JavaScript dependencies (pure HTML/CSS)
✅ Bootstrap 5 for grid and utilities
✅ Accessible HTML5 structure
✅ SEO-friendly markup
✅ Fast loading (optimized CSS)
✅ Easy to maintain and update
✅ Product showcase with detailed pages
✅ Multiple order options
✅ Customer testimonials
✅ Contact form
✅ Consistent branding throughout

## 📝 Customization Guide

### Change Colors
Edit the CSS variables in `css/style.css` at the top:
```css
:root {
  --primary-color: #ffd6d6;     /* Change navbar background */
  --secondary-color: #7a0000;   /* Change headings and text */
  --accent-color: #ff6b6b;      /* Change hover states */
}
```

### Update Content
- Edit any `.html` file to update content
- Product descriptions: Edit in both menu.html and individual product pages
- Contact info: Update in contact.html and order.html
- Social links: Update in order.html

### Add New Products
1. Create new `products/product-name.html` file (use existing product pages as template)
2. Add product card in `menu.html`
3. Add product images to `images/` folders
4. Update nav links if needed

## 🔒 Best Practices

- Keep the navbar HTML structure unchanged across all pages
- Use consistent relative paths for images
- Test on multiple devices before deployment
- Use semantic HTML5 elements
- Maintain consistent spacing and styling
- Always provide alt text for images

## 📦 Dependencies

- **Bootstrap 5.3.2** (CDN) - Grid system and utilities
- **Poppins Font** (Google Fonts, CDN) - Typography
- **No JavaScript frameworks required** - Vanilla CSS and HTML only

## 🎯 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

---

**Created for The 27th Plate - Homemade Cloud Kitchen**  
**Designed and Developed by Abishek**  
**© 2025 All Rights Reserved**
