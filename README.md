# 🌟 Personal Portfolio Website

A modern, responsive portfolio website built with HTML5, CSS3, and Bootstrap 5. This project showcases my journey as a Year 2 Software Engineering student at Southern University College.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Pages](#pages)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Customization](#customization)
- [Contact](#contact)

## 🎯 About

This portfolio website serves as a digital representation of my academic journey, projects, and skills as a software engineering student. It features a sleek dark theme with electric blue and neon pink accents, creating a modern and professional appearance.

## ✨ Features

- **Fully Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, intuitive interface with smooth animations and transitions
- **Dark Theme** - Eye-friendly dark color scheme with vibrant accent colors
- **Interactive Gallery** - Auto-scrolling photo gallery showcasing recent experiences
- **Project Showcase** - Dedicated section highlighting key learning projects
- **Contact Form** - Functional contact form with validation
- **Smooth Animations** - Gradient effects, hover states, and transitions throughout
- **SEO Optimized** - Proper meta tags and semantic HTML structure

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling with modern features
  - CSS Grid & Flexbox for layouts
  - CSS Variables for theming
  - Keyframe animations
  - Gradient backgrounds
- **Bootstrap 5.3** - Responsive framework
- **Google Fonts** - Outfit font family
- **Unsplash** - High-quality placeholder images

## 📄 Pages

### 1. Home (`index.html`)
- Hero section with introduction
- Auto-scrolling photo gallery from Singapore Fintech Festival 2025
- Quick overview of current learning areas
- Call-to-action buttons

### 2. About (`about.html`)
- Personal introduction
- Educational timeline (Year 1 & Year 2 coursework)
- Skills & technologies
- Leadership experience
- Interests & hobbies

### 3. Projects (`projects.html`)
- **Library Management System** - Java/JavaFX application with SQL database
- **Personal Portfolio Website** - This current website project
- Each project includes description, technologies used, and learning outcomes

### 4. Contact (`contact.html`)
- Contact information (email, phone, location)
- Social media links (GitHub, Instagram, Facebook)
- Interactive contact form with validation
- Message character counter

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari)
- Text editor (VS Code recommended)
- Live Server extension (optional, for development)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone https://github.com/Ching040917/portfolio_website.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd portfolio_website
   ```

3. **Open in browser**
   - Double-click `index.html` to open in your default browser
   - Or use Live Server in VS Code for live reload functionality

### Using Live Server in VS Code

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. The website will open in your default browser with live reload enabled

## 📁 Project Structure

```
HTML ASS/
│
├── index.html          # Home page
├── about.html          # About page
├── projects.html       # Projects showcase
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── README.md           # Project documentation
│
└── images/             # Image assets
    ├── image1.jpeg     # Gallery images
    ├── image2.jpeg
    ├── ...
    ├── image9.jpg      # Hero image
    └── image12.jpg     # About page photo
```

## 🎨 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #00f2ff;      /* Main accent color */
    --secondary-color: #4361ee;     /* Secondary accent */
    --accent-color: #f72585;        /* Highlight color */
    --bg-dark: #1a1a2e;            /* Main background */
    --bg-white: #16213e;           /* Card background */
}
```

### Adding New Projects

In `projects.html`, copy and modify the project card template:

```html
<article class="project-card">
    <div class="project-image">
        <img src="your-image.jpg" alt="Project description">
    </div>
    <div class="project-content">
        <!-- Add your project details here -->
    </div>
</article>
```

### Updating Personal Information

- **Contact details**: Edit `contact.html` (email, phone, location)
- **Social links**: Update URLs in footer sections across all pages
- **About text**: Modify content in `about.html`
- **Gallery images**: Replace image files and update `src` attributes in `index.html`

## 🎓 Learning Outcomes

This project helped me learn:
- Responsive web design principles
- CSS Grid and Flexbox layouts
- CSS animations and transitions
- Working with CSS custom properties
- Bootstrap framework integration
- Semantic HTML5 structure
- Form validation and user input handling

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📧 Contact

**Ching Qing Yang**
- 📧 Email: [B240035A@sc.edu.my](mailto:B240035A@sc.edu.my)
- 📱 Phone: 6017-7059048
- 🐙 GitHub: [@Ching040917](https://github.com/Ching040917)
- 📸 Instagram: [@qyching_0417](https://www.instagram.com/qyching_0417/)
- 📍 Location: Johor Bahru, Johor, Malaysia

## 📝 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

- Southern University College for education and support
- Singapore Fintech Festival 2025 for the memorable experience
- Unsplash for placeholder images
- Bootstrap team for the excellent framework
- Google Fonts for the Outfit font family

---

**Note**: This is a student portfolio project created as part of web development coursework. All rights reserved © 2025.
