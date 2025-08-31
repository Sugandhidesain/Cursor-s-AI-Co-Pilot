# The Malaka - Ebook Landing Page

A production-ready, pixel-perfect landing page for "The Malaka" Tailwind CSS ebook, built with modern web technologies and responsive design principles.

## 🎯 Design Rationale

This landing page was created to match the Figma design specifications exactly while maintaining production-ready code quality. The design follows these key principles:

### **Layout & Grid System**
- **8px Grid System**: All spacing, padding, and margins follow an 8px baseline grid for consistent visual rhythm
- **Auto Layout**: Components use flexbox and CSS Grid for responsive, maintainable layouts
- **Pixel-Perfect Implementation**: Exact measurements from Figma design (1440px × 10384px) with responsive breakpoints

### **Component Architecture**
- **Reusable Components**: Consistent button styles, section headers, and card layouts
- **Modular CSS**: Organized by section with clear naming conventions
- **Responsive Variants**: Mobile-first approach with breakpoints at 1200px, 768px, and 480px

### **Typography & Colors**
- **Font Hierarchy**: DM Sans (primary), Source Sans Pro (secondary), Inter (accent)
- **Color Palette**: Primary teal (#00BAC7), dark navy (#272D3E), with proper contrast ratios
- **Consistent Spacing**: 8px increments for margins, padding, and gaps

## 🚀 Features

- **Responsive Design**: Mobile-first approach with breakpoint optimization
- **Interactive Elements**: Hover effects, smooth scrolling, and animated counters
- **Performance Optimized**: Efficient CSS and JavaScript with minimal dependencies
- **Accessibility**: Proper semantic HTML, ARIA labels, and keyboard navigation
- **Cross-Browser Compatible**: Modern CSS with fallbacks for older browsers

## 📁 Project Structure

```
├── index.html          # Main HTML structure
├── styles.css          # Complete CSS styling
├── script.js           # Interactive functionality
├── README.md           # This file
└── assets/             # Image assets (to be added)
    ├── hero-book.png
    ├── feature-1.png
    ├── feature-2.png
    ├── feature-3.png
    ├── author-avatar.png
    ├── benefits-book.png
    ├── preview-book.png
    ├── testimonial-1.png
    ├── testimonial-2.png
    └── testimonial-3.png
```

## 🛠️ Setup Instructions

### 1. Clone or Download
Download all files to your local development environment.

### 2. Add Assets
Create an `assets` folder and add the required images:
- **hero-book.png**: Main book image (641×935px)
- **feature-1.png**: Utility-First Framework image (372×221px)
- **feature-2.png**: Tailwind JIT Engine image (372×221px)
- **feature-3.png**: Unopinionated-Framework image (372×221px)
- **author-avatar.png**: Author profile image (60×60px)
- **benefits-book.png**: Benefits section book image (445×571px)
- **preview-book.png**: Preview section book image (367×579px)
- **testimonial-1.png**: Ahmad Saugi avatar (50×50px)
- **testimonial-2.png**: Dedik Sugiharto avatar (50×50px)
- **testimonial-3.png**: Lutfi Hanafiah Ramadhan avatar (50×50px)

### 3. Open in Browser
Simply open `index.html` in a modern web browser to view the landing page.

### 4. Development Server (Optional)
For development with live reload:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

## 🎨 Design Specifications

### **Layout Dimensions**
- **Desktop**: 1440px × 10384px
- **Tablet**: 768px breakpoint
- **Mobile**: 480px breakpoint

### **Color Scheme**
- **Primary**: #00BAC7 (Teal)
- **Secondary**: #272D3E (Dark Navy)
- **Accent**: #F4F7FF (Light Blue)
- **Success**: #20D27D (Green)
- **Error**: #F52E52 (Red)
- **Text**: #272D3E (Dark), rgba(39, 45, 62, 0.8) (Medium), rgba(255, 255, 255, 0.8) (Light)

### **Typography Scale**
- **Hero Title**: 48px (DM Sans, 500)
- **Section Headers**: 32px (DM Sans, 500)
- **Body Text**: 16px-18px (DM Sans, 400)
- **Labels**: 14px (DM Sans, 700, 10% letter-spacing)

### **Spacing System**
- **Base Unit**: 8px
- **Small Gaps**: 10px, 15px, 20px
- **Medium Gaps**: 30px, 40px, 50px
- **Large Gaps**: 80px, 100px, 200px

## 🔧 Customization

### **Colors**
Update CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #00BAC7;
    --secondary-color: #272D3E;
    --accent-color: #F4F7FF;
}
```

### **Typography**
Modify font imports in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Your+Font:wght@400;500;700&display=swap" rel="stylesheet">
```

### **Layout**
Adjust container max-width and padding in `styles.css`:
```css
.container {
    max-width: 1440px;
    padding: 0 130px;
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (Full layout)
- **Tablet**: 768px - 1199px (2-column grids)
- **Mobile**: 480px - 767px (Single column, stacked)
- **Small Mobile**: <480px (Optimized spacing)

## 🚀 Performance Features

- **CSS Optimization**: Minimal unused styles, efficient selectors
- **JavaScript**: Event delegation, intersection observers
- **Images**: Responsive sizing, lazy loading ready
- **Fonts**: Google Fonts with display=swap

## 🌐 Browser Support

- **Modern Browsers**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+
- **CSS Features**: Flexbox, CSS Grid, CSS Variables, Transitions
- **JavaScript**: ES6+, Intersection Observer, Event Listeners

## 📝 License

This project is created for educational and portfolio purposes. The design concept belongs to the original Figma creator.

## 🤝 Contributing

Feel free to submit issues, feature requests, or pull requests to improve the landing page.

## 📞 Support

For questions or support, please refer to the project documentation or create an issue in the repository.

---

**Built with ❤️ using modern web technologies**
