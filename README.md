# Personal Portfolio Website

## Overview
This project is a responsive personal portfolio website developed using **HTML5** and **CSS3**. The website showcases my profile, technical skills, projects, and contact information. It uses semantic HTML elements to improve accessibility and readability.

## Design Rationale
The website follows a clean and dark-themed design with blue accent colors to provide a professional appearance. The homepage introduces my profile, followed by dedicated sections for About, Projects, and Contact. Consistent spacing, typography, and reusable color variables create a visually balanced interface. Interactive hover and focus effects improve user experience.

## Layout Technique
The website uses both **Flexbox** and **CSS Grid** to create a responsive and well-structured layout. **Flexbox** is used for one-dimensional layouts such as the navigation bar, hero section, and aligning items within containers, making it easy to distribute space and maintain consistent alignment. **CSS Grid** is used for two-dimensional layouts, particularly for arranging project cards and other content sections where rows and columns are required. Combining Flexbox and Grid results in cleaner code, improved responsiveness, and easier maintenance. CSS custom properties (`:root` variables) are used to maintain a consistent color theme and simplify future updates.

The website includes two responsive breakpoints:
- **Tablet:** 768px and below
- **Mobile:** 480px and below

These breakpoints ensure that the content adapts smoothly across desktop, tablet, and mobile devices.

## Features
- Semantic HTML5 structure
- Responsive design using Flexbox and Grid
- CSS custom properties for theming
- Hover, focus, and animation effects
- Accessible forms with proper labels

## Known Limitations
- Contact form is static and does not submit data.
- Navigation menu is not collapsible since JavaScript is not used.