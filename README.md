# Gerald Albacite - Portfolio Website

A modern, responsive portfolio website showcasing my experience as a Full-Stack Developer, Technical Specialist, and Graphic Designer with comprehensive project showcases.

## About

This portfolio highlights my professional journey, including my current role at Davao del Sur State College where I develop and maintain e-FIMS (Electronic Financial Information Management System) and e-HRIS (Electronic Human Resource Information System) using Laravel PHP. The portfolio features detailed project screenshots, interactive elements, and a professional design that demonstrates my technical expertise and design capabilities.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations and dark/light mode toggle
- **Interactive Elements**: Animated skill bars, floating icons, scroll effects, and hover animations
- **Project Showcases**: Detailed project screenshots with comprehensive descriptions
- **Contact Form**: Functional contact form with validation
- **Smooth Navigation**: Smooth scrolling and active section highlighting
- **SEO Optimized**: Meta tags, sitemap, and structured data for better search visibility

## Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with Flexbox and Grid
- **Icons**: Font Awesome 6
- **Fonts**: Google Fonts (Inter)
- **Animations**: CSS animations and JavaScript Intersection Observer API

## Sections

1. **Hero Section**: Introduction with animated floating icons and call-to-action buttons
2. **About**: Professional background and statistics with detailed experience overview
3. **Experience**: Timeline of work experience with detailed descriptions and achievements
4. **Skills**: Interactive skill bars organized by category (Frontend, Backend, Database, Tools)
5. **Projects**: Featured projects with detailed screenshots and technical information
   - **e-FIMS System**: Procurement dashboard, admin panel, and attendance management
   - **e-HRIS System**: Employee dashboard, account management, and travel order tracking
6. **Contact**: Contact form and professional contact information
7. **Project Screenshots Page**: Dedicated page with comprehensive project showcases

## Setup Instructions

1. **Clone or Download**: Get the portfolio files
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **Local Server** (Optional): For best experience, serve files through a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Updating Personal Information

1. **Contact Details**: Update email, phone, and location in the contact section
2. **Social Links**: Replace `#` placeholders with your actual social media profiles
3. **Project Links**: Update project links to point to your actual projects or repositories

### Adding Your Photo

Replace the profile icon in the hero section:
1. Add your profile image to the project folder
2. Update the `.profile-avatar` section in `styles.css` to use your image:
   ```css
   .profile-avatar {
       background-image: url('path-to-your-image.jpg');
       background-size: cover;
       background-position: center;
   }
   ```

### Modifying Content

- **Experience**: Update the timeline section with your actual work experience
- **Skills**: Adjust skill percentages and add/remove skills as needed
- **Projects**: Replace with your actual projects and their descriptions

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Modern mobile browsers

## Performance Features

- **Optimized Images**: Uses CSS gradients and Font Awesome icons for fast loading
- **Efficient Animations**: Hardware-accelerated CSS animations and smooth transitions
- **Lazy Loading**: Intersection Observer API for smooth scroll animations
- **Responsive Images**: Scalable vector icons and CSS-based graphics
- **Project Screenshots**: High-quality screenshots with optimized loading
- **Dark/Light Mode**: Theme toggle with persistent user preference

## File Structure

```
portfolio/
├── index.html              # Main portfolio page
├── projects.html           # Detailed project screenshots page
├── styles.css              # CSS styles and animations
├── script.js               # JavaScript functionality
├── favicon.svg             # Website favicon
├── robots.txt              # SEO robots file
├── sitemap.xml             # XML sitemap for SEO
├── screenshots/            # Project screenshot directory
│   ├── efims/             # e-FIMS system screenshots
│   └── e-hris/            # e-HRIS system screenshots
└── README.md               # This file
```

## Recent Updates

### Latest Portfolio Enhancements (August 2024)

- **Comprehensive Project Showcases**: Added detailed screenshots for both e-FIMS and e-HRIS systems
- **Enhanced Project Descriptions**: Updated all project descriptions to accurately reflect functionality
- **Improved Layout**: Better responsive design with consistent card heights and spacing
- **Dark/Light Mode**: Added theme toggle functionality with persistent user preferences
- **SEO Optimization**: Added meta tags, sitemap, and robots.txt for better search visibility
- **Professional Screenshots**: High-quality screenshots showcasing:
  - **e-FIMS System**: Procurement dashboard, admin panel, user management, and attendance modules
  - **e-HRIS System**: Employee dashboard, account management, and travel order tracking
- **Removed Placeholder Content**: Replaced all placeholder content with actual project showcases

## Deployment

Your portfolio is now deployed and available at:
- **GitHub Repository**: https://github.com/rockshot3313/geraldalbacite-portfolio

### Deployment Options

#### 1. **Netlify (Recommended)**
1. Go to [netlify.com](https://netlify.com) and sign up
2. Click "New site from Git"
3. Connect your GitHub account and select this repository
4. Deploy settings: Build command: (leave empty), Publish directory: (leave empty)
5. Click "Deploy site" - Your site will be live in minutes!

#### 2. **GitHub Pages**
1. Go to your repository: https://github.com/rockshot3313/geraldalbacite-portfolio
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Select "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be available at: `https://rockshot3313.github.io/geraldalbacite-portfolio/`

#### 3. **Vercel**
1. Go to [vercel.com](https://vercel.com) and sign up
2. Click "New Project"
3. Import your GitHub repository
4. Deploy with default settings
5. Your site will be live instantly!

### Custom Domain
After deployment, you can add a custom domain like `geraldalbacite.com` through your hosting provider's settings.

## Contact

- **Personal Email**: geraldalbacite.org@gmail.com
- **Work Email**: gerald.albacite@dssc.edu.ph
- **Phone**: +63 967 419 1024
- **Location**: Sta. Cruz Zone 3, Davao del Sur, Philippines
- **Current Position**: Full-Stack Developer at Davao del Sur State College

### Connect with Gerald

- **GitHub**: [github.com/rockshot3313](https://github.com/rockshot3313)
- **Facebook**: [facebook.com/00endlesslove](https://www.facebook.com/00endlesslove)
- **X (Twitter)**: [x.com/geraldgotdz](https://x.com/geraldgotdz)

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ by Gerald Albacite**
