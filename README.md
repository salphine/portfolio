# Salphine Chemos - Portfolio Website

## 🚀 Live Demo
[View Portfolio](https://salphine.github.io/portfolio/)

## 📋 Overview
This is a modern, interactive portfolio website for Salphine Chemos, a Full-Stack Developer and Fintech Specialist. The portfolio showcases professional experience, technical skills, projects, certifications, and provides a CV download feature.

## ✨ Features

### 🎨 Design & UI
- Modern, responsive design with gradient animations
- Interactive color-changing dashboard cards
- Smooth hover effects and transitions
- Mobile-first responsive layout
- Professional black & white CV generation

### 📊 Dashboard Metrics
- **7+ Projects** - Total deployed applications
- **12 Certifications** - Cisco certifications including CyberOps, Ethical Hacking
- **50+ GitHub Stars** - Community engagement metrics
- **50+ Community Members** - Leadership experience
- **5+ Mentees** - Mentorship contributions

### 📄 CV Generation
- **Canva-style CV** - Professional black & white design
- **Download Options** - Export as PDF or PNG
- **Live Preview** - See CV before downloading
- **Auto-generated** - Pulls data from portfolio content

### 🔗 Key Sections
1. **Professional Summary** - Overview of skills and experience
2. **Key Expertise** - Core competencies and specializations
3. **Technical Skills** - Organized by category (Development, Security, Data, Design)
4. **Projects** - Interactive project cards with live demos and GitHub links
5. **Experience** - Timeline view of professional work history
6. **Certifications** - 12 Cisco certifications with icons
7. **Leadership** - Community involvement and mentorship
8. **References** - Professional references with contact information

### 🛠️ Technical Projects Featured
- **Chemosmart WMS** - Medical inventory system with WebRTC
- **Health Patient Management** - Patient records and analytics
- **Enterprise Sales Management** - Sales forecasting with ML
- **Smart Attendance** - Facial recognition attendance system
- **Telco Churn Analysis** - Power BI data analysis

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom styling with animations
- **JavaScript** - Interactive features and CV generation
- **Font Awesome** - Icon library

### Libraries
- **html2canvas** - CV to image conversion
- **jsPDF** - PDF generation for CV download

### Design
- **Google Fonts (Inter)** - Typography
- **CSS Gradients** - Dynamic backgrounds
- **CSS Animations** - Interactive elements

## 📁 Project Structure
```
portfolio-website/
├── index.html              # Main portfolio page
├── README.md              # Documentation
└── assets/                # (Optional) Images and assets
```

## 🚀 Getting Started

### Prerequisites
- Any modern web browser
- Code editor (VS Code recommended)

### Installation
1. **Clone the repository**
```bash
git clone https://github.com/salphine/portfolio-site.git
cd portfolio-site
```

2. **Open the portfolio**
```bash
# Open index.html in your browser
open index.html
# Or use Live Server in VS Code
```

3. **Customize content**
   - Update the `summary` section in the HTML
   - Modify project cards with your own projects
   - Update certification and experience sections
   - Change contact information in the header and footer

## 🔧 Customization Guide

### Updating Personal Information
Find and replace in `index.html`:
```html
<!-- Name and Title -->
<h1>SALPHINE CHEMOS</h1>
<div class="subtitle">Full‑Stack Developer · Fintech Specialist</div>

<!-- Contact Information -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <a href="mailto:salphinechemos@gmail.com">salphinechemos@gmail.com</a>
</div>
```

### Adding Projects
```html
<!-- Project Card Template -->
<div class="project-card">
    <div class="project-header">
        <h3>🏥 Project Name</h3>
        <div class="project-tech">
            <span class="tech-badge">Tech1</span>
            <span class="tech-badge">Tech2</span>
        </div>
    </div>
    <div class="project-content">
        <p>Project description goes here.</p>
        <ul class="project-features">
            <li><i class="fas fa-check-circle"></i> Feature 1</li>
            <li><i class="fas fa-check-circle"></i> Feature 2</li>
        </ul>
        <div class="project-links">
            <a href="#" target="_blank" class="project-link demo">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="#" target="_blank" class="project-link github">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

### Updating CV Generation
The CV is automatically generated from portfolio content. To customize the CV format:
```javascript
// Located in the <script> section
function generateCVPreview() {
    // Modify the CV structure here
    cv.innerHTML = `...`;
}
```

## 📱 Responsive Design
- **Desktop** - Full layout with side-by-side sections
- **Tablet** - Adjusted grid layouts
- **Mobile** - Stacked layout with optimized touch targets

## 🌐 Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License
© 2026 Salphine Chemos. All rights reserved.

## 🤝 Connect with Me
- **GitHub**: [github.com/salphine](https://github.com/salphine)
- **LinkedIn**: [linkedin.com/in/salphine-chemos](https://linkedin.com/in/salphine-chemos)
- **Email**: salphinechemos@gmail.com
- **Portfolio**: [salphine.github.io/portfolio](https://salphine.github.io/portfolio/)

## 📝 Notes
- All project links are configured with correct Streamlit URLs
- GitHub repositories are linked with correct repository names
- CV generation uses html2canvas for PNG and jsPDF for PDF export
- Legal policies (Privacy, Terms, Cookies) are accessible in the footer

## 🚨 Troubleshooting

### CV Download Not Working
- Ensure html2canvas and jsPDF are loaded from CDN
- Check browser console for errors
- Try refreshing the page

### Links Not Opening
- Verify URLs are correct in the HTML
- Check if `target="_blank"` is set for external links
- Ensure no ad-blockers are interfering

### Layout Issues
- Clear browser cache
- Check browser zoom level
- Ensure CSS is not being overridden

---

**Built with ❤️ by Salphine Chemos**
