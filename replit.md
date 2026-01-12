# FlexiGrowth

## Overview

FlexiGrowth is a static marketing/landing page website for a company branded as "Catalyst for Progress." The project is a single-page HTML site with embedded CSS styling, featuring a modern, professional design with custom brand colors and typography.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture

**Technology Stack:**
- Pure HTML5 with embedded CSS
- No JavaScript framework or build tools
- Single-file architecture (`index.html`)

**Design Approach:**
- Custom CSS with CSS variables for theming
- Responsive design using CSS clamp() for fluid spacing
- Smooth scrolling enabled via `scroll-smooth` class
- Google Fonts integration (DM Sans typeface)

**Styling Strategy:**
- CSS custom properties (variables) for brand consistency
- Mobile-first responsive approach implied by viewport meta tag
- Reset/normalize styles embedded directly
- Font smoothing for better text rendering

**Brand System:**
- Primary colors: FlexiGreen (#22d669), Innovative Blue (#150089)
- Neutral colors: Leadership Black (#231f20), Visionary White (#ffffff)
- Surface and muted colors for UI hierarchy

### Backend Architecture

This is a static site with no backend infrastructure. All content is rendered client-side from a single HTML file.

### Data Storage

No database or data persistence layer. Content is hardcoded in HTML.

## External Dependencies

### Third-Party Services

| Service | Purpose | Integration Method |
|---------|---------|-------------------|
| Google Fonts | Typography (DM Sans) | CDN link in HTML head |

### CDN Resources
- fonts.googleapis.com - Font stylesheet delivery
- fonts.gstatic.com - Font file delivery

No APIs, databases, or authentication systems are currently integrated.