# Nexora - Digital Product Studio

A modern, responsive website for **Nexora**, a digital product studio that designs, builds, and scales web and mobile software solutions.

## 🔗 Live Website

**View the project online:** [https://varadashvili.github.io/fr-fin-hw](https://varadashvili.github.io/fr-fin-hw)

## 📋 Project Overview

Nexora is a professional, fully responsive website showcasing a digital product studio's services, team, and expertise. The site features a modern design with smooth animations, interactive components, and comprehensive information about the studio's offerings and team.

### Key Features

- **Responsive Design** - Fully responsive layout that works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional interface with smooth interactions and animations
- **Multi-Page Structure** - Organized navigation across multiple pages (Home, About, Services, News, Contact)
- **Hero Section** - Engaging hero section with call-to-action buttons and promotional cards
- **Services Showcase** - Detailed presentation of core services:
  - Web Development
  - UI/UX Design
  - Cloud & DevOps
- **Team Information** - Leadership section featuring the three co-founders and their expertise
- **Mission & Values** - Clear articulation of company values: Craft, People First, Momentum, and Integrity
- **Performance Metrics** - Showcase of key business metrics and quality indicators
- **Mobile Navigation** - Responsive hamburger menu for mobile devices
- **Social Links** - Integrated social media links in header and footer

## 🏗️ Project Structure

```
Part1-Final/
├── index.html                 # Home page
├── pages/
│   ├── About.html            # About the company
│   ├── Services.html         # Services offered
│   ├── News.html             # News/Blog section
│   └── Contact.html          # Contact form
├── scss/
│   ├── styles.scss           # Main SCSS file
│   ├── styles.css            # Compiled CSS
│   ├── styles.css.map        # CSS source map
│   ├── _global.scss          # Global styles
│   ├── _reset.scss           # CSS reset
│   ├── _variables.scss       # SCSS variables (colors, fonts, spacing)
│   ├── _mixins.scss          # SCSS mixins for reusable styles
│   ├── _main.scss            # Main page styles
│   ├── _about.scss           # About page styles
│   ├── _services.scss        # Services page styles
│   ├── _contact.scss         # Contact page styles
│   ├── _News.scss            # News page styles
│   ├── _placeholders.scss    # Placeholder animations and effects
│   └── _contact.scss         # Contact-specific styles
├── img/                       # Images and assets
└── README.md                 # This file
```

## 🎨 Design & Technology

### Technologies Used

- **HTML5** - Semantic markup for content structure
- **SCSS** - Professional CSS preprocessing with variables, mixins, and nesting
- **CSS3** - Modern styling with animations and transitions
- **Font Awesome 7.0.1** - Icon library for visual elements
- **Google Fonts** - Inter font family (weights: 400, 500, 600, 700, 800)
- **Responsive Design** - Mobile-first approach with flexible layout

### Color Scheme & Typography

The project uses a coordinated color palette and typography system defined in `_variables.scss`:

- **Typography:** Inter font family with multiple weight variants
- **Responsive Layout:** Container-based grid system for consistent spacing
- **Color System:** Professional palette suitable for a tech/design studio
- **Spacing:** Consistent use of spacing utilities for visual hierarchy

### SCSS Architecture

The SCSS is organized into logical modules:

- **_variables.scss** - Global variables for colors, fonts, sizes, and breakpoints
- **_mixins.scss** - Reusable style mixins for common patterns
- **_reset.scss** - CSS reset for browser consistency
- **_global.scss** - Global styles applied across all pages
- **_main.scss** - Home page specific styles
- **_about.scss** - About page specific styles
- **_services.scss** - Services page specific styles
- **_contact.scss** - Contact page specific styles
- **_News.scss** - News/Blog page specific styles
- **_placeholders.scss** - Animation and reveal effect styles

## 📄 Pages Overview

### Home Page (index.html)

The landing page featuring:
- Navigation header with logo and main menu
- Hero section with company tagline and CTA buttons
- Partners section showcasing client logos
- Services overview with three main service offerings
- Statistics section (8+ years experience, 200+ projects, 40+ team members, 98% retention)
- Call-to-action section encouraging visitor engagement
- Comprehensive footer with links and social media

### About Page (pages/About.html)

Detailed company information including:
- Company overview and mission statement
- Company origin story and growth trajectory
- Mission & Values section with four core values
- Leadership team with founder profiles
- Quality metrics (99.9% uptime, 24h support response, 100% code review)

### Services Page (pages/Services.html)

Detailed information about offered services:
- Web Development services
- UI/UX Design expertise
- Cloud & DevOps capabilities

### News Page (pages/News.html)

Blog or news section for company updates and insights

### Contact Page (pages/Contact.html)

Contact form and information for getting in touch with the studio

## 🚀 Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, WebStorm, etc.)
- Local server (optional, for development)

### Installation

1. Clone or download the project
   ```bash
   git clone https://github.com/varadashvili/fr-fin-hw.git
   ```

2. Navigate to the project directory
   ```bash
   cd Part1-Final
   ```

3. Open `index.html` in your web browser or use a local server
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   ```

4. Visit `http://localhost:8000` in your browser

## 🎯 Development

### SCSS Compilation

If you modify SCSS files, you'll need to compile them to CSS:

```bash
# Using a SCSS compiler or build tool
sass scss/styles.scss scss/styles.css --watch
```

### Code Structure

Each page follows a consistent structure:
- Semantic HTML5 markup
- BEM naming convention for CSS classes
- Responsive breakpoints for mobile, tablet, and desktop
- Accessibility considerations

## 📱 Responsive Breakpoints

The design is optimized for:
- Mobile (< 768px)
- Tablet (768px - 1024px)
- Desktop (> 1024px)

## ✨ Features & Functionality

### Navigation
- Responsive navigation menu
- Mobile hamburger menu toggle
- Active link indicators
- Smooth page transitions

### Interactive Elements
- Hover effects on buttons and links
- Reveal animations on scroll
- Smooth transitions and animations
- Icon integration with Font Awesome

### Performance
- Optimized asset loading
- CSS source maps for debugging
- Compiled and minified CSS

## 🤝 Company Information

**Nexora - Digital Product Studio**

- **Founded:** 2018
- **Team Size:** 40 members
- **Experience:** 8+ years
- **Projects Completed:** 200+
- **Client Retention:** 98%

### Leadership

1. **Polikarpe Ghobeglejiashvili** - Co-founder & CEO
   - Leads strategy and partnerships
   - Former product lead with 12 years in tech

2. **Kalistrate Samchkuashvili** - Co-founder & CTO
   - Heads engineering and architecture
   - Specializes in clean code and fast systems

3. **Agrafina Samadalashvili** - Head of Design
   - Shapes the look and feel of every product
   - Sharp eye for detail and user experience

## 📝 License

This project is provided as-is for educational and demonstration purposes.

## 🔗 Links

- **Live Website:** [https://varadashvili.github.io/fr-fin-hw](https://varadashvili.github.io/fr-fin-hw)
- **GitHub Repository:** [github.com/varadashvili/fr-fin-hw](https://github.com/varadashvili/fr-fin-hw)

---

**Last Updated:** 2026

*This is a professional portfolio/showcase website for Nexora digital product studio, demonstrating modern web design and development practices.*

