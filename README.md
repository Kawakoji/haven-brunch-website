# Haven Brunch Website

A refined, elegant website for Haven Brunch - creating bubbles of sweetness during precious events through carefully crafted, gourmet brunch experiences.

## 🌿 Brand Identity

**Haven Brunch** represents a safe haven for experiencing soft, calm, and warm moments around refined brunches. The brand focuses on:

- **Softness** → A soothing atmosphere, never flashy
- **Generosity** → Delicious recipes, heartfelt plates  
- **Attention to Detail** → Presentation, flavor, hospitality
- **Accessible Elegance** → Beauty without pretension

## 🎨 Design Features

### Color Palette
- **Soft Cream** (#FAF4EF) - Background, softness
- **Golden Beige** (#E8D8C3) - Elegance, warmth
- **Golden Caramel** (#B98565) - Gourmet accent
- **Cocoa Brown** (#4E342E) - Contrast, text
- **Off-white** (#FDFBF9) - Purity, balance

### Typography
- **Headings**: TAN-NEW-YORK (elegant serif) with Playfair Display fallback
- **Body Text**: Adumu Font (clean, modern sans-serif) with Inter fallback

### Interactions
- Subtle fade-in animations
- Smooth scrolling navigation
- Elegant hover effects
- Responsive mobile navigation
- Interactive gallery with lightbox
- Form validation and notifications

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Local web server (optional, for development)

### Installation

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **For development**: Use a local server like Live Server in VS Code

### File Structure
```
haven-brunch/
├── fonts/              # Custom font files directory
│   ├── fonts-info.md   # Font installation guide
│   └── (font files)    # TAN-NEW-YORK and Adumu font files
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 📱 Features

### Sections
- **Hero Section**: Welcoming introduction with brand promise
- **Story Section**: Brand mission, values, and personality
- **Menu Section**: Signature brunch items with elegant layout
- **Gallery Section**: Visual showcase with interactive lightbox
- **Contact Section**: Booking form with validation

### Functionality
- **Responsive Design**: Works on all devices
- **Smooth Navigation**: Animated scrolling between sections
- **Mobile Menu**: Hamburger navigation for mobile devices
- **Form Handling**: Contact form with validation
- **Interactive Gallery**: Clickable images with lightbox view
- **Scroll Effects**: Parallax and fade-in animations
- **Performance Optimized**: Throttled scroll events

## 🛠️ Customization

### Font Setup
**Important**: The website uses custom fonts that need to be installed:

1. **Download the fonts**:
   - **TAN-NEW-YORK**: Download from TanType or FontFreebie
   - **Adumu Font**: Download from appropriate font source

2. **Install the fonts**:
   - Place font files in the `/fonts/` directory
   - Required formats: `.woff2` and `.woff`
   - See `/fonts/fonts-info.md` for detailed instructions

3. **Current fallbacks**: Until custom fonts are installed, the site uses:
   - Headings: Playfair Display (Google Fonts)
   - Body text: Inter (Google Fonts)

### Adding Images
Replace the placeholder elements in the HTML with actual images:

1. **Hero Image**: Replace `.hero-image-placeholder` content
2. **Story Image**: Replace `.story-image-placeholder` content  
3. **Gallery Images**: Replace `.gallery-image-placeholder` content

### Updating Content
- **Menu Items**: Edit the menu sections in `index.html`
- **Contact Info**: Update contact details in the contact section
- **Brand Story**: Modify the story section content

### Styling Changes
All styles are contained in `styles.css` with clear section comments:
- Colors are defined using CSS custom properties
- Responsive breakpoints: 1024px, 768px, 480px
- Animation durations and easing can be adjusted

## 🎯 Brand Guidelines

### Voice & Tone
- Warm and welcoming
- Elegant but accessible  
- Professional yet personal
- Focus on emotional experiences

### Visual Style
- Clean, minimalist layouts
- Soft, warm color palette
- High-quality imagery
- Subtle animations
- Generous white space

## 📞 Contact Integration

The contact form is ready for backend integration. To make it functional:

1. **Replace** the form submission handler in `script.js`
2. **Add** your email service or backend endpoint
3. **Configure** form validation rules as needed

Current form fields:
- Name (required)
- Email (required)
- Event Type
- Preferred Date
- Number of Guests
- Message (required)

## 🌟 Performance

The website is optimized for performance:
- Minimal external dependencies
- Optimized CSS with efficient selectors
- Throttled scroll events
- Lazy loading ready
- Mobile-first responsive design

## 📄 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🤝 Contributing

To enhance the website:
1. Follow the established design patterns
2. Maintain the brand color palette
3. Ensure responsive design
4. Test across different devices
5. Keep accessibility in mind

---

*A refined brunch to elevate your precious moments* ✨
