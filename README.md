# Domaine de Bargue - Website

A modern, responsive website for Domaine de Bargue showcasing French wine, hospitality, and countryside elegance.

## 🎨 Design System

### Color Palette
- **Dark Blue** (#01263f) - Primary text and accents
- **Navy** (#016793) - Secondary elements
- **Light Blue** (#51a3cf) - Accent backgrounds
- **Sky Blue** (#bfe0f3) - Light backgrounds
- **Purple** (#550356) - Accent highlights
- **Magenta** (#ee297a) - Call-to-action and highlights
- **Pink** (#fd86a6) - Complementary accent
- **Off-white** (#f7fcff) - Light backgrounds

### Typography
- **Font**: Fredoka (via Google Fonts) - A modern, friendly, bubbly typeface
- **Weights**: 400, 500, 600, 700

## 📁 Project Structure

```
DomaineDeBargue/
├── index.html                 # Main HTML file
├── styles/
│   ├── main.css              # Main stylesheet with design system
│   └── responsive.css        # Mobile and tablet responsive styles
├── scripts/
│   └── main.js               # JavaScript for interactivity
├── images/                   # Images folder (placeholder structure)
├── assets/                   # Additional assets
├── .github/
│   └── workflows/
│       └── deploy.yml        # GitHub Pages deployment workflow
├── .gitignore               # Git ignore file
└── README.md                # This file
```

## ✨ Features

- **Responsive Design**: Mobile-first approach with breakpoints for tablet and desktop
- **Smooth Navigation**: Smooth scrolling and active link highlighting
- **Mobile Menu**: Hamburger menu for mobile devices
- **Hero Section**: Eye-catching banner with call-to-action
- **Product Showcase**: Grid layout for wines and services
- **Image Gallery**: Hover effects and animations
- **Testimonials**: Client reviews and feedback
- **Contact Form**: Functional contact form with validation
- **Accessibility**: WCAG compliant with keyboard navigation
- **Performance**: Optimized for fast loading
- **SEO**: Meta tags and structured content

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/EdouardPradie/DomaineDeBargue.git
cd DomaineDeBargue
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (http-server)
npx http-server
```

3. Navigate to `http://localhost:8000` in your browser

### Customization

#### Update Content
- Edit the text in `index.html` to match your domain information
- Replace image placeholders with actual images in the `images/` folder
- Update contact information in the Contact section

#### Modify Colors
Edit the CSS variables in `styles/main.css`:
```css
:root {
    --color-dark-blue: #01263f;
    --color-navy: #016793;
    --color-light-blue: #51a3cf;
    --color-sky-blue: #bfe0f3;
    --color-purple: #550356;
    --color-magenta: #ee297a;
    --color-pink: #fd86a6;
    --color-off-white: #f7fcff;
}
```

#### Update Typography
Modify font sizes and weights in the `:root` section of `styles/main.css`

## 🌐 Deployment

### GitHub Pages

The project is automatically deployed to GitHub Pages via GitHub Actions.

1. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Set Source to "GitHub Actions"

2. **Automatic Deployment**:
   - The workflow automatically deploys on push to `main` or `master` branch
   - View deployment at: `https://yourusername.github.io/DomaineDeBargue/`

3. **Manual Deployment**:
   - Go to Actions tab
   - Select "Deploy to GitHub Pages" workflow
   - Click "Run workflow"

## 📱 Responsive Breakpoints

- **Mobile**: < 480px
- **Tablet**: 480px - 768px
- **Desktop**: > 768px
- **Large Desktop**: > 1400px

## ♿ Accessibility

- WCAG 2.1 AA compliant
- Keyboard navigation support
- High contrast mode support
- Reduced motion support
- Screen reader friendly
- Proper heading hierarchy
- Alt text for images

## 🔍 SEO

- Semantic HTML structure
- Meta tags for social sharing
- Open Graph tags
- Proper heading hierarchy
- Image alt text
- Fast loading performance
- Mobile responsive

## 🐛 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

Domaine de Bargues

## 🎯 Future Enhancements

- [ ] Blog section for wine stories
- [ ] Booking system for accommodation
- [ ] Wine shop integration
- [ ] Event calendar
- [ ] Multi-language support
- [ ] Newsletter subscription
- [ ] Virtual vineyard tour
- [ ] Wine pairing recommendations

---

**Last Updated**: 2024
