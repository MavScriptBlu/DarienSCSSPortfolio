# Darien Johnas - Portfolio Website

A responsive portfolio website showcasing my software development projects and skills, built with modern web technologies and a cyberpunk-inspired design aesthetic.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with seamless desktop and mobile experiences
- **Custom Logo Integration**: DevLogo.gif serves as both branding and skip-to-main functionality
- **Modern SCSS Architecture**: Organized with BEM methodology and component-based structure
- **Interactive Elements**: Shrinking header on scroll, hover effects, smooth navigation
- **Mobile-Optimized Layout**: Full-width buttons, larger profile photos, right-aligned hamburger menu
- **Accessibility Focused**: WCAG compliant with proper ARIA labels and keyboard navigation
- **Real Projects**: Showcasing actual development work including WTWR, Spots Platform, and more
- **Modern Web Standards**: Uses `pagehide`/`pageshow` events and forced colors mode support
- **State Persistence**: Maintains scroll position and navigation context across page visits
- **Professional Content**: Authentic resume with real work experience and PDF viewer integration

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

- **Colors**: Cyberpunk-inspired palette with light blue (#89CFF0) and pink (#f7c5cc) accents
- **Typography**: VT323 monospace font for retro-tech aesthetic
- **Effects**: Dashed borders, box shadows, and smooth transitions
- **Accessibility**: Forced colors mode support, high contrast compatibility

## ✨ Recent Improvements

- **Custom Logo Integration**: Replaced text-based logo with animated DevLogo.gif that serves dual purpose as skip-to-main link
- **Mobile UX Enhancements**:
  - Hamburger menu repositioned to right side
  - Profile photo enlarged for better mobile visibility (200px vs 150px)
  - All buttons now match project card width for consistent design
- **Typography Improvements**: Enhanced font sizes across sections for better readability
- **Modern Page Lifecycle**: Implemented `pagehide`/`pageshow` events for reliable state management
- **Beacon API Integration**: Non-blocking analytics and session cleanup using `navigator.sendBeacon()`
- **Accessibility Enhancements**: Logo skip link with enhanced focus states (now simplified for cleaner design)
- **Resume Integration**: PDF now opens in new window instead of forcing download
- **State Persistence**: Automatically saves and restores scroll position and navigation context
- **Visual Consistency**: Uniform project card heights with flexbox layout and consistent mobile button widths

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
