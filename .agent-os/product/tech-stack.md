# Technical Stack

> Last Updated: 2025-07-26
> Version: 1.0.0

## Core Technologies

### Application Framework
- **Framework:** Vanilla JavaScript
- **Version:** ES6+
- **Language:** JavaScript

### Database
- **Primary:** None (Client-side only)
- **Version:** N/A
- **ORM:** N/A

## Frontend Stack

### JavaScript Framework
- **Framework:** None (Vanilla JS)
- **Version:** ES6+
- **Build Tool:** None (Direct browser execution)

### Import Strategy
- **Strategy:** Inline scripts
- **Package Manager:** None
- **Node Version:** N/A

### CSS Framework
- **Framework:** Custom CSS with CSS Variables
- **Version:** CSS3
- **PostCSS:** No

### UI Components
- **Library:** Custom components
- **Version:** N/A
- **Installation:** N/A

## Assets & Media

### Fonts
- **Provider:** System fonts
- **Loading Strategy:** Font stack with system fallbacks

### Icons
- **Library:** Emoji icons
- **Implementation:** Direct Unicode characters

## Infrastructure

### Application Hosting
- **Platform:** Static hosting
- **Service:** GitHub Pages / Netlify / Vercel (any static host)
- **Region:** Global CDN

### Database Hosting
- **Provider:** N/A
- **Service:** N/A
- **Backups:** N/A

### Asset Storage
- **Provider:** Same as application host
- **CDN:** Provided by hosting platform
- **Access:** Public

## Deployment

### CI/CD Pipeline
- **Platform:** GitHub Actions (optional)
- **Trigger:** Push to main branch
- **Tests:** None currently

### Environments
- **Production:** Single environment
- **Staging:** N/A
- **Review Apps:** N/A

## Code Repository
- **URL:** To be determined

## Architecture Decisions

### Single-File Application
The entire application is contained in a single `index.html` file with inline CSS and JavaScript. This approach was chosen for:
- Maximum portability
- Zero build complexity
- Instant deployment
- Offline capability

### Client-Side Only
No backend or database requirements. All game logic runs in the browser for:
- Complete privacy (no data collection)
- No server costs
- Instant response times
- Works offline after initial load

### Modern CSS with Variables
Using CSS custom properties for theming enables:
- Easy dark/light mode switching
- Consistent color management
- Future customization options

### SVG Graphics
The hangman drawing uses inline SVG for:
- Crisp graphics at any size
- Small file size
- Easy animation control
- No external image dependencies