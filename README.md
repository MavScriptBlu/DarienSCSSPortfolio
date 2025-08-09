# Darien Johnas - Portfolio Website

A responsive, accessible portfolio website showcasing software development projects and skills, built with modern web technologies and a cyberpunk-inspired design aesthetic. Features comprehensive keyboard navigation, WCAG AA compliance, and enhanced mobile UX.

## 🚀 Features

- **Full Keyboard Accessibility**: Complete keyboard navigation with proper focus management and no keyboard traps
- **WCAG AA Compliant**: High contrast text, accessible color schemes, and proper ARIA labeling
- **Touch-Friendly**: 44px+ minimum touch targets exceeding accessibility standards (48px on mobile)
- **Responsive Design**: Mobile-first approach with seamless desktop and mobile experiences
- **Custom Logo Integration**: DevLogo.gif serves as both branding and skip-to-main functionality
- **Modern SCSS Architecture**: Organized with BEM methodology and component-based structure
- **Interactive Elements**: Shrinking header on scroll, hover effects, smooth navigation
- **Enhanced Mobile UX**: Click-outside-to-close menu, consistent button sizing, optimized layouts
- **Real Projects**: Showcasing actual development work including WTWR, Spots Platform, and more
- **Modern Web Standards**: Uses `pagehide`/`pageshow` events and forced colors mode support
- **State Persistence**: Maintains scroll position and navigation context across page visits
- **Professional Content**: Authentic resume with real work experience and PDF viewer integration

## 🌟 Accessibility Features

- **Keyboard Navigation**: Full keyboard access with Tab, Enter, Space, and Escape key support
- **Focus Management**: Visible focus indicators and proper focus trapping in mobile menu
- **Screen Reader Support**: Comprehensive ARIA labels, roles, and semantic HTML structure
- **Touch Accessibility**: 44px minimum touch targets (48px on mobile) for all interactive elements
- **Color Contrast**: WCAG AA compliant color contrast with dark backgrounds for light blue text
- **Mobile Menu UX**: Click outside to close, Escape key support, proper focus management
- **Skip Links**: Direct navigation to main content via custom logo integration
- **Forced Colors Mode**: Full support for Windows High Contrast and forced colors accessibility features

## 🛠️ Technologies Used

- **HTML5**: Semantic markup with accessibility features
- **SCSS/Sass**: Advanced CSS preprocessing with organized file structure
- **JavaScript**: Vanilla JS for interactive functionality and modern page lifecycle management
- **BEM Methodology**: Consistent CSS naming convention
- **Git**: Version control and project management
- **Modern CSS**: Forced colors mode, high contrast support, CSS Grid/Flexbox

## 📱 Sections

- **Header**: Fixed navigation with custom logo, mobile hamburger menu positioned on right
- **Intro Banner**: Personal introduction with enlarged mobile profile image and centered content
- **Latest Projects**: Grid showcase of development projects with uniform card sizing and full-width mobile buttons
- **Skills**: Technical competencies organized by category with enhanced typography
- **Resume**: Real education and work experience with PDF viewer (opens in new window)
- **Contact**: Professional links with full-width mobile layout matching project cards

## 🏗️ Project Structure

```bash
├── index.html              # Main HTML file with integrated DevLogo
├── dist/                   # Compiled CSS output
│   └── main.css           # Production-ready styles
├── src/                    # Source files
│   ├── assets/             # Resume PDF (other files gitignored for privacy)
│   ├── img/                # Images including custom DevLogo.gif
│   └── scss/               # SCSS source files
│       ├── base/           # Base styles and resets
│       ├── blocks/         # Component styles (BEM methodology)
│       └── utils/          # Variables, mixins, and accessibility features
└── package.json            # Dependencies and build scripts
```

## 🔧 Development

```bash
# Install dependencies
npm install

# Build CSS
npm run build

# Watch for changes
npm run watch

# Format code
npm run format
```

## 🎨 Design System

- **Colors**: Cyberpunk-inspired palette with accessible light blue (#89CFF0) and pink (#f7c5cc) accents
- **Contrast Solution**: Dark background badges (#2c2c2c) for light blue text ensuring WCAG AA compliance
- **Typography**: VT323 monospace font for retro-tech aesthetic with enhanced readability
- **Touch Targets**: 44px+ minimum size with 48px mobile optimization for accessibility compliance
- **Effects**: Dashed borders, box shadows, smooth transitions, and consistent button styling
- **Accessibility**: Forced colors mode support, high contrast compatibility, focus-visible indicators

## ✨ Recent Improvements

### Accessibility Enhancements

- **Comprehensive Keyboard Navigation**: All functionality accessible via keyboard with no traps
- **Enhanced Focus Management**: Visible focus indicators and proper focus trapping in mobile navigation
- **Touch Target Compliance**: 44px minimum (48px mobile) exceeding WCAG AA standards
- **Color Contrast Solution**: Dark background badges for blue text ensuring excellent readability
- **Mobile Menu UX**: Click outside to close functionality with proper accessibility support

### Button & Layout Consistency

- **Unified Button Styling**: Projects and resume buttons now identical in size and behavior
- **Centralized CSS Architecture**: All button styling inherited from base.scss for consistency
- **Mobile Optimization**: Full-width buttons matching section layouts with proper spacing
- **Visual Consistency**: Uniform project card heights and consistent mobile button presentation

### Modern Web Standards

- **Enhanced Mobile Navigation**: Click outside to close with proper event handling
- **Improved State Management**: Better scroll position and navigation context persistence
- **Performance Optimizations**: Debounced event handling and efficient DOM manipulation
- **Cross-browser Compatibility**: Enhanced support for various accessibility features

## 🚀 Performance Features

- **BFCache Optimization**: Properly handles browser Back/Forward Cache for smooth navigation
- **Modern Event Handling**: Uses current web standards instead of deprecated APIs
- **Debounced State Saving**: Efficient localStorage usage for scroll position and navigation context
- **Responsive Images**: Optimized loading and display across all devices
- **Visibility API**: Lightweight state management when users switch tabs or minimize browser
- **Page Lifecycle Management**: Proper handling of page show/hide events for better user experience
- **Analytics Structure**: Code framework ready for future analytics implementation (currently development-only logging)

## 📧 Contact

- **GitHub**: [iiBamBlue](https://github.com/iiBamBlue)
- **LinkedIn**: [darien-blue](https://www.linkedin.com/in/darien-blue)
