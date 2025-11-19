# Portfolio Website - CI/CD Project

A modern, fully responsive portfolio website built with HTML, CSS, and JavaScript, featuring a complete CI/CD pipeline with GitHub Actions.

## 🚀 Features

### Frontend Features
- **Modern Hero Section** with animated typing effect and gradient background
- **About Section** with professional introduction and highlights
- **Skills Section** with categorized technical skills and interactive cards
- **Experience Section** with timeline layout
- **Projects Section** showcasing 6 featured projects with GitHub links
- **Education Section** with academic achievements
- **Contact Section** with contact form and social links
- **Dark/Light Theme Toggle** with persistent theme storage
- **Smooth Scrolling** navigation
- **Responsive Design** for all devices (mobile, tablet, desktop)
- **Scroll Animations** using Intersection Observer
- **Active Section Highlighting** in navigation
- **Scroll to Top Button**
- **Mobile-Friendly Navigation** with hamburger menu

### CI/CD Features
- **Automated Linting** for HTML, CSS, and JavaScript
- **Build & Test Pipeline** with artifact generation
- **Automated Deployment** to GitHub Pages
- **Security Scanning** capabilities
- **Workflow Automation** on push and pull requests

## 🎨 Color Scheme

### Primary Colors
- **Primary**: `#6366F1` (Indigo)
- **Secondary**: `#8B5CF6` (Purple)
- **Accent**: `#EC4899` (Pink)
- **Success**: `#10B981` (Green)
- **Warning**: `#F59E0B` (Amber)

### Dark Theme (Default)
- **Background Dark**: `#0F172A` (Slate 900)
- **Background Light**: `#1E293B` (Slate 800)
- **Surface**: `#334155` (Slate 700)
- **Text Primary**: `#F1F5F9` (Slate 100)
- **Text Secondary**: `#CBD5E1` (Slate 300)

## 📁 Project Structure

```
CI-CD Project/
│
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
│
├── .github/
│   └── workflows/
│       ├── ci-cd.yml   # Main CI/CD pipeline
│       └── deploy.yml  # Deployment workflow
│
└── assets/             # Images and other assets (optional)
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Variables, Grid, Flexbox
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icons
- **GitHub Actions** - CI/CD pipeline
- **GitHub Pages** - Hosting

## 📋 Prerequisites

- A GitHub account
- Git installed on your local machine
- A modern web browser

## 🚀 Getting Started

### Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd "CI-CD Project"
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve
     ```

3. **Make changes**
   - Edit `index.html` for structure
   - Edit `styles.css` for styling
   - Edit `script.js` for functionality

### CI/CD Setup

1. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select source: "GitHub Actions"

2. **Push to main branch**
   - The CI/CD pipeline will automatically:
     - Lint your code
     - Build the project
     - Deploy to GitHub Pages

3. **View your site**
   - Your portfolio will be available at:
     `https://<username>.github.io/<repository-name>/`

## 📝 Customization

### Update Personal Information

1. **Edit `index.html`**:
   - Update name, title, and description in hero section
   - Modify about section with your information
   - Update skills, experience, projects, and education
   - Change contact information

2. **Update Social Links**:
   - Replace GitHub and LinkedIn URLs
   - Update email and phone number

3. **Modify Projects**:
   - Update project cards with your projects
   - Add or remove projects as needed
   - Update GitHub repository links

### Customize Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary: #6366F1;
    --secondary: #8B5CF6;
    --accent: #EC4899;
    /* ... more colors */
}
```

### Add Your Photo

Replace the placeholder in the About section:
```html
<div class="image-placeholder">
    <img src="assets/your-photo.jpg" alt="Your Name">
</div>
```

## 🔧 CI/CD Pipeline Details

### Workflow Jobs

1. **Lint & Validate**
   - Validates HTML structure
   - Checks CSS syntax
   - Lints JavaScript code

2. **Build & Test**
   - Creates build directory
   - Copies and minifies files
   - Generates build artifacts

3. **Deploy**
   - Automatically deploys to GitHub Pages
   - Only runs on main/master branch
   - Provides deployment URL

### Manual Deployment

You can also trigger deployment manually:
1. Go to "Actions" tab in GitHub
2. Select "Deploy Portfolio" workflow
3. Click "Run workflow"

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Features Breakdown

### Navigation
- Sticky navbar with scroll effect
- Active section highlighting
- Smooth scroll to sections
- Mobile hamburger menu
- Theme toggle button

### Animations
- Typing effect for name
- Fade-in animations on scroll
- Hover effects on cards
- Parallax background
- Smooth transitions

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px and 480px
- Flexible grid layouts
- Touch-friendly interactions

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Sonu Yadav**
- GitHub: [@Raos0nu](https://github.com/Raos0nu)
- LinkedIn: [Sonu Yadav](https://linkedin.com/in/sonu-yadav-577878268)
- Email: sonuyadav97297@gmail.com

## 🙏 Acknowledgments

- Font Awesome for icons
- GitHub Actions for CI/CD
- All the open-source tools and libraries used

## 📈 Future Enhancements

- [ ] Add blog section
- [ ] Integrate contact form with backend
- [ ] Add more animations
- [ ] Implement PWA features
- [ ] Add analytics
- [ ] Multi-language support
- [ ] Add testimonials section

---

**Built with ❤️ using HTML, CSS, and JavaScript**

