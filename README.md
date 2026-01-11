# Zerolink - Premium Studio Gallery System

A stunning photography website with a premium Black & White theme, interactive animations, and unique cursor effects.

## ✨ Features

### 🎨 Visual Design
- **B/W Premium Theme** - Elegant monochrome color palette
- **Glassmorphism UI** - Frosted glass card effects
- **Smooth Scroll Animations** - Elements fade in as you scroll
- **Responsive Design** - Works on all devices

### 📷 Interactive Camera Cursor
- **Mini camera icon** follows your mouse
- **Flash effect** on click with screen flash
- **Shutter sound** plays when you click
- Works across all sections

### 🖼️ Hero Section
- **Floating photo gallery** in background
- **Animated photos** gently moving
- **Grayscale-to-color** hover effects

### 📸 Software Showcase
- Image gallery with 3 slots
- Hover effects with color reveal
- Stats bar with metrics

### 💬 Studio Testimonials
- 3 testimonial cards with star ratings
- Professional studio reviews
- Trust indicators

### 💰 Pricing Section
- Lifetime license offer
- Animated pricing card
- CTA buttons

## 🚀 Getting Started

1. Clone or download the repository
2. Open `index.html` in a web browser
3. No build steps required!

## 📁 Project Structure

```
website/
├── index.html          # Main website file
├── assets/
│   ├── how_it_works.png
│   ├── youtube_banner.png
│   └── privacy.svg
└── README.md
```

## 🎯 Customization

### Replace Software Screenshots
Update the `src` attributes in the Software Showcase section:
```html
<img src="assets/your-screenshot.png" alt="Description">
```

### Adjust Camera Cursor Size
In the CSS, modify `.cursor-spotlight`:
```css
width: 60px;   /* Camera width */
height: 45px;  /* Camera height */
```

### Change Flash Duration
In the JavaScript, adjust the timeout:
```javascript
setTimeout(() => { ... }, 150); // milliseconds
```

## 🛠️ Technologies Used

- HTML5
- CSS3 (Tailwind CSS CDN)
- Vanilla JavaScript
- Lucide Icons
- Google Fonts (Plus Jakarta Sans)

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## 📄 License

© 2024 Zerolink India. All Rights Reserved.

---

Made with ❤️ for professional photography studios
