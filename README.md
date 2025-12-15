# YFN Home Page - Refactored

A modern, responsive website for the YFN Home Page project. This refactor improves maintainability, performance, and user experience.

## Features

- **Responsive Design**: Works on mobile, tablet, and desktop devices
- **Modern HTML5**: Semantic markup with proper accessibility
- **CSS Grid & Flexbox**: Modern layout techniques
- **Mobile-First Approach**: Optimized for mobile devices first
- **Reusable Components**: Consistent navigation and styling across pages

## Project Structure

```
src/
├── index.html          # Main landing page
├── about.html          # About us page
├── products.html       # Products page
├── css/
│   ├── main.css        # Main styles
│   └── menu.css        # Navigation menu styles
├── js/
│   └── menu.js         # Mobile menu functionality
├── images/
│   ├── yfn_logo_.svg   # Main logo
│   └── hero-background.svg # Hero section background
└── downloads/
    └── vtuploader2_2.exe # Downloadable application
```

## Improvements Made

1. **Code Organization**:
   - Created a logical folder structure
   - Separated concerns (HTML, CSS, JS, images)
   - Used consistent naming conventions

2. **Semantic HTML**:
   - Added proper HTML5 semantic elements (`<header>`, `<nav>`, `<main>`, `<footer>`)
   - Improved accessibility with proper ARIA attributes

3. **Responsive Design**:
   - Implemented mobile-first CSS
   - Added hamburger menu for mobile devices
   - Used CSS Grid for flexible layouts

4. **Performance**:
   - Optimized CSS with modular approach
   - Used SVG images for better scalability
   - Reduced HTTP requests where possible

5. **Maintainability**:
   - Modular CSS architecture
   - Reusable components
   - Clear documentation

## Usage

To run the site locally:

```bash
npm install
npm start
```

Or use a local server of your choice pointing to the `src/` directory.

## Browser Support

- Chrome, Firefox, Safari, Edge (latest versions)
- Mobile browsers (iOS Safari, Chrome for Android)

## License

This project is licensed under the ISC License.
