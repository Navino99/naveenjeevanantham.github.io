# Naveen Jeevanantham - Professional Portfolio

A modern, cybersecurity-themed portfolio website showcasing GRC expertise and technical capabilities.

## 🚀 Quick Start - Deploy to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `naveenjeevanantham.github.io` (exactly this format)
4. Set to **Public**
5. **DO NOT** initialize with README, .gitignore, or license
6. Click **"Create repository"**

### Step 2: Upload Files

#### Option A: Using Git (Recommended)

```bash
# Navigate to your project directory
cd /path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio website"

# Add remote repository
git remote add origin https://github.com/naveenjeevanantham/naveenjeevanantham.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Option B: Using GitHub Web Interface

1. Open your repository on GitHub
2. Click **"uploading an existing file"** link
3. Drag and drop `index.html` and `README.md`
4. Click **"Commit changes"**

### Step 3: Enable GitHub Pages

1. Go to repository **Settings**
2. Scroll to **Pages** section (left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Website

Your portfolio will be live at: **https://naveenjeevanantham.github.io**

## 🎨 Features

- **Modern Cybersecurity Theme**: Dark mode design with cyber-inspired aesthetics
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Scroll-triggered reveals and hover effects
- **Professional Sections**:
  - Hero with status badge
  - Achievement statistics
  - Professional experience
  - Technical skills categorized
  - Certifications
  - Contact information
- **Performance Optimized**: Single HTML file, no external dependencies beyond fonts
- **SEO Ready**: Proper meta tags and semantic HTML

## 🛠️ Customization

### Update Your Information

Edit the `index.html` file to customize:

1. **Personal Info**: Update name, title, location, contact details
2. **Professional Summary**: Modify hero section description
3. **Statistics**: Change achievement numbers in stats grid
4. **Experience**: Add/remove job positions and achievements
5. **Skills**: Update skill categories and tags
6. **Certifications**: Add new certifications
7. **Contact Links**: Update email, phone, LinkedIn

### Color Theme

Colors are defined in CSS variables at the top of the file:

```css
:root {
    --cyber-primary: #00ff88;     /* Main accent color */
    --cyber-secondary: #0a84ff;   /* Secondary accent */
    --cyber-accent: #ff0055;      /* Highlight color */
    --bg-dark: #0a0e27;           /* Background */
    --text-primary: #e8ecf4;      /* Main text */
}
```

### Fonts

Current fonts:
- **Headings**: Manrope (modern sans-serif)
- **Code/Mono**: IBM Plex Mono

To change fonts, modify the Google Fonts link in the `<head>` section.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, Animations
- **JavaScript**: Vanilla JS for scroll animations and interactions
- **Fonts**: Google Fonts (Manrope, IBM Plex Mono)
- **Hosting**: GitHub Pages (free)

## 📄 File Structure

```
naveenjeevanantham.github.io/
├── index.html          # Main portfolio page (all-in-one)
└── README.md           # This file
```

## 🚀 Future Enhancements

Consider adding:
- [ ] Blog section for cybersecurity articles
- [ ] Project showcase section
- [ ] Download resume button (PDF)
- [ ] Dark/light theme toggle
- [ ] Contact form integration
- [ ] Analytics (Google Analytics)
- [ ] Custom domain (optional)

## 📞 Support

For issues or questions about deployment:
- [GitHub Pages Documentation](https://docs.github.com/pages)
- [GitHub Pages Troubleshooting](https://docs.github.com/pages/getting-started-with-github-pages/troubleshooting-404-errors-for-github-pages-sites)

## 📝 License

This portfolio is open source and available for personal use and modification.

---

**Built by Naveen Jeevanantham** | Cybersecurity Engineer & GRC Specialist
