# FUNDSWEB - Educational Website

A modern, responsive educational website showcasing courses, events, and instructor information.

## Author
**Ananyaa Gupta**

## Project Overview

This project represents a complete restructuring and standardization of the VALE educational website. The website has been optimized from a complex multi-page structure to a streamlined, user-friendly interface with five main pages.

## Website Structure

### Main Pages (5)
1. **Home** (`index.html`) - Landing page with overview
2. **About** (`about.html`) - Information about the website
3. **Services** - Comprehensive services section including:
   - **Courses** (`course.html`) - Course listings
   - **Instructors** (`team.html`) - Team and instructor profiles
   - **Events** (`event.html`) - Upcoming events and workshops
4. **Blog** (`blog.html`) - Articles and updates
5. **Contact** (`contact.html`) - Contact form and information

### Supporting Pages
- `single_course.html` - Detailed individual course information (accessed from course listings)
- `event_single.html` - Detailed individual event information (accessed from event listings)

## Features

### Analytics & Tracking
- Google Analytics (gtag) script integrated across all pages
- Custom contact form tracking script on `contact.html`

### Contact Form
- Fully functional contact form with validation
- Successfully sends messages
- Enhanced with custom tracking script

### Social Media Integration
All social media links have been updated with company profiles:
- Facebook
- Twitter
- YouTube
- Instagram
- LinkedIn

### Branding
- Custom company logo implemented across all pages
- Consistent branding throughout the website

## Technical Details

### File Structure Optimization
**Before:** 27+ HTML files with redundant pages
**After:** 11 streamlined HTML files

### Scripts Implementation
1. **Google Analytics (gtag)**
   - Location: All HTML pages
   - Purpose: Website traffic tracking and analytics
   - Note: No modifications made to the script

2. **Contact Form Script**
   - Location: `contact.html` only
   - Position: After gtag script
   - Purpose: Form submission handling and tracking

## Directory Structure

```
yale/
├── assets/
│   └── (css, js, images, fonts)
├── index.html
├── about.html
├── course.html
├── single_course.html
├── team.html
├── event.html
├── event_single.html
├── blog.html
├── blog_single.html
├── contact.html
└── README.md
```

## Project Requirements Met

✅ Reduced website to 5 main pages as specified
✅ Implemented gtag script on all pages
✅ Added contact tracking script on contact page
✅ Updated all social media links with company profiles
✅ Changed logo to company branding
✅ Maintained functional contact form
✅ Preserved detailed course and event pages for user navigation

## Navigation Flow

- **Courses Page** → Click on course → `single_course.html` (detailed view)
- **Events Page** → Click on event → `event_single.html` (detailed view)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- Backend integration for dynamic content
- User authentication system
- Course enrollment functionality
- Event registration system
- Newsletter subscription

## License

This project is part of an educational assignment.

## Contact

For any queries regarding this project, please reach out through the contact form on the website.

---

**Note:** This website was restructured and standardized as part of a course requirement, transforming a complex multi-page structure into a clean, maintainable five-page architecture while preserving essential functionality.