# Overview

This is a personal portfolio website for Harisaikumar Bathula, a Computer Science Engineer specializing in AI & ML. The website showcases his professional background, skills, projects, experience, and education in a modern, responsive single-page application format. The portfolio is built as a static website with smooth scrolling navigation and interactive animations to provide an engaging user experience.

# User Preferences

Preferred communication style: Simple, everyday language.

# System Architecture

## Frontend Architecture
- **Single-Page Application (SPA)**: Built as a static HTML website with JavaScript for interactivity
- **Responsive Design**: Mobile-first approach with responsive navigation and layouts
- **Component-Based Structure**: Organized into distinct sections (Home, About, Skills, Projects, Experience, Education, Contact)
- **Smooth Scrolling Navigation**: JavaScript-powered navigation with active section highlighting
- **Progressive Enhancement**: Core content accessible without JavaScript, enhanced with interactive features

## Styling Architecture
- **CSS Custom Properties**: Likely uses CSS variables for consistent theming
- **External Font Integration**: Google Fonts (Inter) for typography
- **Icon System**: Font Awesome for scalable vector icons
- **Modular CSS**: Organized styling with component-based classes
- **Animation Framework**: Custom scroll-triggered animations and transitions

## JavaScript Architecture
- **Vanilla JavaScript**: No framework dependencies for maximum performance
- **Event-Driven Design**: DOM event listeners for user interactions
- **Modular Functions**: Separated concerns with dedicated initialization functions
- **Scroll Management**: Custom scroll detection for navigation and animations
- **Form Handling**: Contact form with likely validation and submission logic

## Performance Optimizations
- **Static Deployment**: No server-side processing required
- **CDN Resources**: External libraries loaded from CDNs
- **Minimal Dependencies**: Lightweight approach with only essential external resources

# External Dependencies

## CDN Resources
- **Font Awesome 6.4.0**: Icon library for UI elements and social media icons
- **Google Fonts (Inter)**: Primary typography with multiple font weights (300-700)

## Potential Integrations
- **Contact Form Service**: Likely integrates with a form handling service (Formspree, Netlify Forms, or similar)
- **Analytics**: May include Google Analytics or similar tracking
- **Hosting Platform**: Designed for static hosting (Netlify, Vercel, GitHub Pages)

## Browser APIs
- **Intersection Observer**: Likely used for scroll animations and section detection
- **Local Storage**: Potentially for user preferences or form data persistence
- **Fetch API**: For contact form submissions to external services