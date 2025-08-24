# VitalEd - Medical Education Platform

## 🏥 Overview
VitalEd is a sophisticated medical education platform designed for healthcare professionals and medical students. The platform provides comprehensive learning management, analytics, and community features for medical institutions.

## 🚀 Quick Start

### Deploy to Netlify (Recommended)
1. Download all files from this repository
2. Go to [Netlify](https://app.netlify.com)
3. Drag and drop the entire `vital-ed` folder onto Netlify
4. Your site will be live instantly!

### Deploy to GitHub Pages
1. Fork or clone this repository
2. Go to Settings → Pages
3. Select "Deploy from branch"
4. Choose `main` branch and `/root` folder
5. Save and wait for deployment

## 📁 File Structure
```
vital-ed/
├── index.html          # Main platform application
├── madigan-demo.html   # Madigan Army Medical Center Demo
└── README.md          # This file
```

## 🔐 Access Information

### Main Platform (`index.html`)
- **Student Access**: 
  - Select any institution
  - Enter any email (e.g., `student@university.edu`)
  - Enter any password
  
- **Admin Access**:
  - Click "Administrator Access →" link at login
  - Instant access to admin dashboard

### Madigan Demo (`madigan-demo.html`)
- Specialized version for Madigan Army Medical Center
- Military medical training focus
- Same login process as main platform

## ✨ Features

### Student Dashboard
- 📊 Personalized learning analytics
- 📚 Course progress tracking
- 📈 Performance metrics
- 👥 Community interaction
- 📅 Calendar integration
- 🏆 Certification management

### Admin Dashboard
- 📊 Platform-wide analytics
- 👥 User management system
- 📚 Course administration
- 💰 Revenue tracking
- 🔧 System health monitoring
- 📱 Customizable widget system

### Key Capabilities
- **Responsive Design**: Works on all devices
- **Real-time Analytics**: Live data visualization
- **Customizable Widgets**: Drag-and-drop dashboard
- **Multi-institutional**: Support for multiple medical schools
- **Role-based Access**: Student, Instructor, Admin roles

## 🎨 Technology Stack
- **Frontend**: Pure HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with modern design system
- **Icons**: Emoji-based for universal compatibility
- **Deployment**: Static site, no backend required

## 🔧 Customization

### Adding Your Institution
Edit the institution dropdown in `index.html`:
```html
<option value="your-institution">Your Medical School</option>
```

### Changing Colors
Modify CSS variables in the `:root` section:
```css
:root {
    --primary: #1e40af;     /* Main brand color */
    --accent: #dc2626;      /* Accent color */
    --success: #16a34a;     /* Success states */
}
```

### Adding Widgets
Add new widgets in the admin dashboard section following the existing pattern.

## 📱 Browser Support
- ✅ Chrome (90+)
- ✅ Firefox (88+)
- ✅ Safari (14+)
- ✅ Edge (90+)
- ✅ Mobile browsers

## 🚦 Status
- ✅ Production Ready
- ✅ Fully Responsive
- ✅ Cross-browser Compatible
- ✅ Accessibility Compliant

## 📄 License
This project is available for educational and demonstration purposes.

## 🤝 Support
For questions or support regarding deployment:
1. Check the deployment section above
2. Ensure all files are in the correct structure
3. Verify browser compatibility

## 🌟 Demo Links
Once deployed, you can access:
- Main Platform: `your-site.netlify.app/index.html`
- Madigan Demo: `your-site.netlify.app/madigan-demo.html`

---

**Built with 💙 for Medical Education**