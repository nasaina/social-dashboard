A responsive social media dashboard with dark mode functionality, showcasing statistics from Facebook, Twitter, Instagram, and YouTube.

## About

This is my first frontend project while I didn't really master coding yet.
It was built for the **Techzara Weekly Coding Challenge** hackathon in 2020, and it won **3rd place** in the frontend challenge.

## Live Demo

🌐 [https://nasaina.surge.sh](https://nasaina.surge.sh)

## Features

- 📊 **Social Media Statistics Dashboard** - Display followers and engagement metrics
- 🌓 **Dark Mode Toggle** - Switch between light and dark themes with localStorage persistence
- 📱 **Fully Responsive Design** - Optimized for all screen sizes:
  - Mobile (portrait & landscape)
  - Tablets (portrait & landscape)
  - Desktop
- 🎨 **Brand Color Indicators** - Color-coded bars for each social media platform
- 📈 **Trend Indicators** - Visual display of positive/negative metric changes

## Tech Stack

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styles with media queries for responsive design
- **Bootstrap 3** - UI framework for layout and components
- **JavaScript** - Dark mode toggle functionality

## Project Structure

```
nasaina-anderson/
├── index.html           # Main HTML file (fully commented)
├── index.css            # Custom styles (documented with English comments)
├── bootstrap/
│   ├── dist/           # Bootstrap framework files
│   └── dm/             # Dark mode implementation
│       ├── dark-mode.css        # Dark theme styles
│       └── dark-mode-switch.js  # Dark mode toggle logic
├── icons/              # Social media icons and brand images
└── README.md           # Project documentation
```

## Code Documentation

The codebase has been thoroughly documented with:

- **HTML Comments**: Each section clearly labeled (header, social media cards, statistics grid)
- **CSS Comments**: 
  - Media queries labeled by device type and screen size
  - Component styles explained (cards, indicators, brand bars)
  - Light and dark mode styles documented
- **Responsive Breakpoints**:
  - `< 452px` - Very small phones
  - `299px - 588px` - Small phones (portrait)
  - `588px - 750px` - Large phones (landscape)
  - `750px - 770px` - Tablets (portrait)
  - `770px - 1100px` - Tablets (landscape)
  - `> 1100px` - Desktop

## Run Locally

1. Clone the repository
2. Open `index.html` in your browser
3. No build process or dependencies required!

## Dark Mode

The dark mode feature uses:
- JavaScript to toggle the `data-theme="dark"` attribute
- LocalStorage to persist user preference
- CSS custom styles for dark theme colors

Toggle dark mode using the switch in the top-right corner of the dashboard.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

This project is intentionally simple as a first frontend build and a hackathon submission. The code has been cleaned up and documented to help other developers understand the structure and implementation.

---

**Built with ❤️ by Nasaina Anderson** | Hackathon Project 2020
