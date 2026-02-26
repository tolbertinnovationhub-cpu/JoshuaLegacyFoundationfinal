# Joshua Legacy Foundation Website

A professional, responsive website for The Joshua Legacy Foundation (TJLF) - an innovative youth and leadership development organization committed to empowering vulnerable children across Liberia.

## Overview

This website represents Joshua Legacy Foundation's mission: "Crafting Leaders. Celebrating Culture. Creating Change."

The site showcases:

- **Mission & Vision** - Foundation's commitment to youth empowerment and national restoration
- **STEMACH Program** - Science, Technology, Engineering, Mathematics, Arts, Culture, and Heritage integrated education
- **Strategic Goals** - Five-year plan to reach 100,000+ youth across all 15 counties of Liberia
- **Leadership** - Meet the founding team led by Winston A. Tolbert and partners
- **Partnership Network** - Educational, development, and investment partners worldwide
- **Impact Stories** - Real transformation stories from youth participants
- **Core Values** - Faith, Cultural Pride, Youth Empowerment, Innovation, Community Collaboration

## File Structure

```
├── index.html        # Main website with all sections
├── styles.css        # Complete responsive styling
├── script.js         # Interactive features and forms
├── README.md         # This documentation
└── images/          # Folder for website images (to be added)
```

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE
- Images for website sections

### Installation

1. Clone or download this project
2. Create an `images` folder in the project root
3. Add the following images to the `images` folder:
   - `hero-bg.jpg` - Hero section background
   - `issue.jpg` - Youth empowerment imagery
   - `work.jpg` - STEMACH Education program
   - `story1.jpg`, `story2.jpg`, `story3.jpg` - Transformation stories

### Running Locally

**Option 1: Python HTTP Server**
```bash
# Python 3
python -m http.server 8000
# Visit http://localhost:8000
```

**Option 2: VS Code Live Server**
1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

**Option 3: Direct Browser**
Open `index.html` directly (some features limited)

## Key Sections

### Hero Banner
Eye-catching introduction with mission statement and call-to-action buttons for supporters and volunteers

### Welcome
Overview of Joshua Legacy Foundation's vision and commitment to youth empowerment

### The Challenge
Describes poverty and vulnerability issues affecting Liberian youth, with organization's response

### STEMACH Program
Explains the integrated educational approach combining modern innovation with cultural heritage

### Vision for Impact
Goals showing commitment to training 100,000+ youth annually across 15 counties

### Transformation Stories
Real stories of youth leadership development and community impact

### Core Approach
Three pillars: Spiritual Foundation, STEMACH Education, Community Partnership

### Partners & Supporters
Network of educational, humanitarian, and investment partners

### Engagement Areas
- Volunteer opportunities
- Partnership collaboration
- Donor information
- Contact and newsletter signup

## Customization Guide

### Organization Information
Update in `index.html`:
- Executive Director: Winston A. Tolbert
- Location: Monrovia, Liberia
- Service areas: All 15 counties of Liberia + Mano River Union
- Contact email: info@joshualegacy.org

### Color Scheme
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2c5f7f;      /* Main blue */
    --secondary-color: #ff6b35;    /* Orange accent */
    --accent-color: #ffd60a;       /* Yellow highlight */
}
```

### Content Updates
- **Mission Statement**: Update hero section tagline
- **Program Details**: Edit STEMACH section
- **Impact Goals**: Modify statistics in "Vision for Impact" section
- **Partner Organizations**: Update partners list
- **Contact Information**: Modify footer and contact form

### Form Integration

**Contact Form**: Connect to backend service:
```html
<form action="https://formspree.io/f/YOUR_ID" method="POST">
```

**Newsletter**: Integrate email service:
```html
<form action="YOUR_MAILCHIMP_URL" method="POST">
```

## Design Features

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 600px
- Flexible grid layouts
- Touch-friendly buttons

### Interactive Elements
- Smooth scrolling navigation
- Form validation
- Scroll animations
- Active navigation highlighting
- Hover effects

### Accessibility
- Semantic HTML5 structure
- Proper heading hierarchy
- Image alt text
- Keyboard navigation
- Focus states on inputs

## Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Grid and Flexbox
- **Vanilla JavaScript** - No dependencies

## Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## About Joshua Legacy Foundation

Founded in 2020 as a registered NGO in Liberia, TJLF is committed to:

- **Youth Empowerment**: Training at-risk, orphaned, and vulnerable youth
- **Leadership Development**: Building future leaders for national restoration
- **Cultural Preservation**: Celebrating African heritage and traditions
- **Educational Innovation**: Implementing STEMACH system across Liberia
- **Community Transformation**: Creating lasting positive change through partnerships

### Leadership Team

- **Winston A. Tolbert** - Founder & Executive Director
- **John Okech Magero** - Administration & Finance Coordinator
- **Samuel Asa Chenekan** - Director for Human Rights & Child Advocacy
- **Board of Directors** - 9 members overseeing strategic direction
- **Strategic Advisors** - International experts in various domains

## Deployment Options

### Netlify
1. Connect GitHub repository
2. Deploy (no build command needed)

### GitHub Pages
1. Push to GitHub
2. Enable in repository settings
3. Select main branch

### Traditional Hosting
1. Upload files via FTP
2. Ensure proper permissions
3. Visit your domain

## Future Enhancements

Consider adding:
- Blog/news section
- Volunteer management system
- Donation portal
- Program registration
- Success stories carousel
- Multi-language support
- Online courses platform
- Impact dashboard

## Support & Questions

For customization help or feature requests, refer to inline comments in:
- `styles.css` - CSS structure
- `script.js` - JavaScript functionality
- `index.html` - HTML semantic structure

## License

This website template is provided for Joshua Legacy Foundation. For use outside this organization, contact foundation leadership.

## Contact

**Joshua Legacy Foundation**
- Location: Monrovia, Liberia
- Email: info@joshualegacy.org
- Service Area: All 15 Counties of Liberia + Mano River Union
- Registered NGO since 2020

---

**Last Updated**: January 2026
**Version**: 1.0
**Mission**: "Crafting Leaders. Celebrating Culture. Creating Change."
