# 📱 Developer Portfolio - Full Stack Project

A modern, responsive portfolio project showcasing full-stack development skills across web and mobile platforms.

## 🎯 Project Overview

This is a comprehensive portfolio project that demonstrates:
- **Web Development**: HTML5, CSS3, JavaScript with modern animations and responsive design
- **Mobile Development**: React Native with navigation and multiple screens
- **Full-Stack Architecture**: Complete project structure for both web and mobile platforms

## 📁 Project Structure

```
portfolio/
├── web/                    # Web portfolio (HTML/CSS/JavaScript)
│   ├── index.html         # Main portfolio page
│   ├── css/
│   │   └── styles.css     # Responsive styling with animations
│   └── js/
│       └── script.js      # Interactive functionality
├── mobile/                # React Native mobile app
│   ├── src/
│   │   ├── App.js         # Main app component with navigation
│   │   ├── screens/       # Screen components
│   │   │   ├── HomeScreen.js
│   │   │   ├── ProjectsScreen.js
│   │   │   └── SkillsScreen.js
│   │   └── index.js
│   ├── package.json
│   ├── .babelrc
│   └── metro.config.js
├── package.json           # Root package configuration
└── README.md             # This file
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- For React Native: Android Studio/Xcode (optional for development)

### Web Portfolio Setup

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Start the web server**:
   ```bash
   npm start
   ```

3. **Open in browser**:
   - Navigate to `http://localhost:8000`
   - The portfolio will be fully functional with animations and smooth scrolling

### React Native Mobile Setup

1. **Navigate to mobile directory**:
   ```bash
   cd mobile
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **For Android**:
   ```bash
   npm run android
   ```

4. **For iOS** (macOS only):
   ```bash
   npm run ios
   ```

5. **Start development server**:
   ```bash
   npm start
   ```

## ✨ Features

### Web Portfolio
- ✅ Modern responsive design (mobile-first)
- ✅ Smooth scroll navigation with anchor links
- ✅ Animated hero section with gradient background
- ✅ Interactive project cards with hover effects
- ✅ Skills showcase with progress indicators
- ✅ Contact form with validation
- ✅ Ripple button effects
- ✅ Footer with social links placeholder

### React Native Mobile App
- ✅ Bottom tab navigation
- ✅ Home screen with introduction and stats
- ✅ Projects listing with technology tags
- ✅ Skills display with progress bars
- ✅ Native styling and responsive layout
- ✅ Header customization per screen

## 🎨 Design Highlights

- **Color Scheme**:
  - Primary: Blue (#2563eb)
  - Accent: Amber (#fbbf24)
  - Neutral: Gray scale

- **Typography**: Clean, modern sans-serif (Segoe UI)
- **Animations**: CSS3 animations, transitions, and JavaScript-driven effects
- **Mobile First**: Fully responsive across all screen sizes

## 💻 Technologies Used

### Web
- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- No external dependencies (pure vanilla)

### Mobile
- React Native 0.74.1
- React Navigation (Bottom Tabs)
- JavaScript (Modern ES6+)

### Build & Development
- Node.js / npm
- Metro (React Native bundler)
- Babel for transpilation

## 📋 Customization Guide

### Update Personal Info
Edit `web/index.html` and `mobile/src/screens/HomeScreen.js`:
- Replace "John Developer" with your name
- Update email and contact information
- Modify project descriptions and technologies

### Customize Colors
Edit CSS variables in `web/css/styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #fbbf24;
}
```

### Add More Projects
1. **Web**: Add new `.project-card` divs in `web/index.html`
2. **Mobile**: Add items to the `projects` array in `ProjectsScreen.js`

## 🧪 Testing

```bash
# Test web portfolio (visual testing in browser)
npm start

# Build for production
npm run build

# Mobile development testing
cd mobile
npm start
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Android)

## 📦 Deployment

### Web Portfolio
- Host on: Netlify, Vercel, GitHub Pages, or any static hosting
- Build: Simple HTTP server or any static server

### React Native
- Package APK for Android using Android Studio
- Build IPA for iOS using Xcode or EAS Build

## 🔧 Development Workflow

1. **Web Development**:
   ```bash
   npm start
   # Edit web/index.html, web/css/styles.css, web/js/script.js
   # Changes reflect immediately in browser
   ```

2. **Mobile Development**:
   ```bash
   cd mobile
   npm start
   # Keep running in one terminal, use another for rebuilds
   npm run android  # or npm run ios
   ```

## 📝 Code Quality

- Clean, well-commented code
- Consistent naming conventions
- Responsive design practices
- Performance optimized
- Accessibility considerations

## 🎓 Learning Resources

This project demonstrates:
- Semantic HTML structure
- CSS Grid and Flexbox layouts
- Modern JavaScript patterns (arrow functions, async/await, DOM manipulation)
- React Native navigation and component lifecycle
- Responsive design principles
- Animation and transition techniques

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio!

## 📄 License

MIT License - feel free to use this template for your portfolio

## 🎉 Ready to Use

Your portfolio is now set up and ready to customize! 

**Next Steps**:
1. Update personal information
2. Add your own projects and descriptions
3. Customize colors and styling
4. Deploy to your preferred hosting platform

---

**Last Updated**: February 2026
**Version**: 1.0.0
