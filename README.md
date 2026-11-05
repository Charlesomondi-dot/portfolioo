# Charles Omondi - Professional Portfolio Website

A modern, responsive portfolio website showcasing projects, skills, CV, and testimonials.

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript interactivity
├── README.md           # This file
└── Assets/
    ├── Documents/
    │   ├── Charles_CV.pdf
    │   ├── Introduction to AI.pdf
    │   └── Testimonial STJTTID.pdf
    ├── HarnS/
    │   ├── Harns Company Profile (Updated).docx
    │   └── Harns Corporate Presentation Deck.pptx
    └── Images/
        ├── pic.png
        ├── pic2.jpg
        ├── pic3.jpg
        ├── pic4.jpg
        └── pic5.jpg
```

## ✨ Features

- **Modern Design**: Clean, professional layout optimized for top-tier companies
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Project Showcase**: Display your built projects with direct links
- **CV, Certificate & Testimonials**: Embedded PDF viewers for the updated CV, AI certificate, and testimonial
- **HarnS Company Profile**: Dedicated company overview with downloadable profile and presentation deck
- **Social Media Integration**: Direct links to all your social profiles
- **Contact Section**: Email and WhatsApp contact options
- **Smooth Animations**: Scroll animations and interactive elements
- **Fast Loading**: Optimized for performance

## 🎨 Sections

1. **Hero Section**: Eye-catching introduction with your profile image
2. **About Me**: Brief professional bio
3. **Featured Projects**: Showcase your built applications
4. **Skills & Technologies**: Display your technical expertise
5. **CV & Testimonials**: View your CV and professional recommendations
6. **Contact**: Multiple ways for recruiters to reach you

## 🚀 Deployment Options

### Option 4: Self-Hosted
1. Upload files to your hosting provider via FTP
2. Ensure all files are in the correct directory
3. Visit your domain in a browser

## 📝 Customization Guide

### Update Contact Information
In `index.html`, find and update:
- Email: harns.expertsolutions@gmail.com
- WhatsApp: Change `https://wa.me/254719501832` to your WhatsApp number
  - Format: `https://wa.me/[country_code][phone_number]` (no + or spaces)

### Add More Projects
Add new project cards in the Projects section:
```html
<div class="project-card">
    <div class="project-image" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
        <i class="fas fa-[icon-name]"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span class="tag">Technology</span>
        </div>
        <a href="project-url" target="_blank" class="btn btn-small">Visit Site</a>
    </div>
</div>
```

### Change Color Scheme
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #07578d;      /* HarnS technology blue */
    --secondary-color: #0b8fc4;    /* Action cyan */
    --accent-color: #f2b84b;       /* Premium gold accent */
    /* ... other variables ... */
}
```

### Add More Skills
Add skills in the Skills section:
```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skill-list">
        <span class="skill">Skill 1</span>
        <span class="skill">Skill 2</span>
    </div>
</div>
```

### Update Profile Image
Replace `Assets/Images/pic.png` with your preferred image, or change the src in hero section.

## 🔧 Technical Details

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for interactivity (no dependencies)
- **Icons**: Font Awesome 6.4.0 CDN
- **Responsive**: Mobile-first design approach
- **Accessibility**: Semantic HTML and proper contrast ratios

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🎯 SEO Optimization Tips

1. **Add Meta Tags** (optional):
   - Add in `<head>`:
   ```html
   <meta name="description" content="Charles Omondi - Full Stack Developer and Software Engineer">
   <meta name="keywords" content="developer, portfolio, full-stack, software engineer">
   ```

2. **Update Title**: Change `<title>` tag in `index.html`

3. **Add Sitemap** (if using GitHub Pages):
   - Create `sitemap.xml` for better SEO

## 📧 Contact & Support

- **Email**: harns.expertsolutions@gmail.com
- **WhatsApp**: Available in portfolio
- **Social Media**: Links in footer

## 📄 License

This portfolio template is personal and customized for Charles Omondi. 
Feel free to adapt and customize as needed.

---

**Last Updated**: October 2026
**Version**: 2.0
