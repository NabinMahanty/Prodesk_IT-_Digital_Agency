# ProDesk IT - Week 1 Project

A modern, responsive IT services website built with HTML, CSS, and vanilla JavaScript. This project showcases digital services with a clean, professional design and includes a dark/light theme toggle feature.

## Features

- **Responsive Design**: Fully responsive layout that works on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Theme toggle functionality for better user experience
- **Smooth Animations**: Scroll-based animations and smooth transitions
- **Modern UI/UX**: Clean and professional interface with intuitive navigation
- **Mobile Menu**: Hamburger menu for mobile navigation
- **Services Section**: Showcase of IT services offerings
- **Interactive Elements**: Dynamic navbar and overlay interactions

## Project Structure

```
Week_1/
│
├── index.html              # Main HTML file
├── README.md               # Project documentation
├── assets/
│   ├── css/
│   │   └── style.css      # Main stylesheet with theme support
│   └── images/            # Image assets
└── js/
    └── script.js          # JavaScript for interactivity
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties (CSS variables), Flexbox, Grid
- **JavaScript (ES6+)**: Vanilla JS for all interactions
- **Google Fonts**: Jost font family
- **Ionicons**: Icon library for UI elements

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.) - optional

### Installation

1. Clone or download this repository
2. Navigate to the project directory
3. Open `index.html` in your web browser

Then navigate to `http://localhost:8000` in your browser.

## Features Implementation

### Theme Toggle

- Click the moon/sun icon to switch between dark and light modes
- Theme preference can be toggled from both desktop and mobile views
- Smooth transition effects between themes

### Navigation

- Responsive navbar that collapses into a hamburger menu on mobile
- Smooth scrolling to page sections
- Active header styling on scroll
- Overlay effect when mobile menu is open

### Responsive Breakpoints

The design adapts to different screen sizes:

- Mobile: < 575px
- Tablet: 575px - 768px
- Desktop: > 768px

## Customization

### Changing Colors

Edit the CSS custom properties in `style.css`:

```css
:root {
  --sefety-orange: hsl(24, 100%, 50%);
  --davys-gray: hsl(220, 2%, 31%);
  --gunmetal: hsl(217, 21%, 16%);
}
```

### Adding Content

- Update sections in `index.html`
- Add new styles in `assets/css/style.css`
- Extend functionality in `js/script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
