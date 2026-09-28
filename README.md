# EditXMustafa 🎨✂️💻

A professional portfolio website showcasing graphic design, video editing, web development, and social media management services.

## 📋 Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Pages](#pages)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Accessibility](#accessibility)
- [Browser Support](#browser-support)
- [Contact](#contact)

## ✨ Features

### Portfolio Website (`index.html`)
- **Professional Design**: Modern, responsive portfolio with dark/light mode toggle
- **Services Showcase**: Interactive table displaying all services and skills
- **Portfolio Gallery**: Featured projects with modal details view
- **Contact Form**: Functional contact form with validation and localStorage storage
- **SEO Optimized**: Structured data (Schema.org), meta tags, and semantic HTML
- **Accessibility**: Full WCAG compliance with proper ARIA labels and keyboard navigation
- **Animations**: Smooth transitions and fade-in effects for enhanced UX
- **Mobile Responsive**: Fully responsive design for all device sizes

### Digital Clock (`clock.html`)
- **Multi-timezone Support**: Display current time across 36+ world timezones
- **Real-time Updates**: Updates every second for accurate time display
- **Add/Remove Timezones**: Dynamically add custom timezones or use presets
- **Local Storage**: Saves timezone preferences between sessions
- **Dark/Light Mode**: Theme toggle with persistence
- **Responsive Grid**: Adaptive layout for desktop and mobile devices

## 📁 Project Structure

```
EditXMustafa/
├── index.html          # Main portfolio website
├── clock.html          # Digital clock with timezone converter
├── README.md           # Project documentation
└── .gitignore          # Git ignore file
```

## 📄 Pages

### 1. **index.html** - Professional Portfolio
Main portfolio page featuring:
- Navigation with smooth scrolling
- Hero section with contact information
- Services table with action buttons
- Portfolio gallery with 3 featured projects
- Contact form for inquiries
- Dark/light mode toggle
- Accessible modals for project details

**Sections:**
- **Home**: Introduction and contact details
- **Services**: Professional services with tools used
- **Portfolio**: Featured work samples
- **Contact**: Contact form for project inquiries

### 2. **clock.html** - Digital Clock
Interactive timezone converter featuring:
- Main clock displaying local time
- Custom timezone selector
- Preset timezones (GMT, EST, PST, CET, JST)
- Real-time clock cards for each timezone
- Add/Remove/Clear all functionality
- Local storage for preferences

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup with accessibility features
- **CSS3**: Modern styling with CSS variables and flexbox/grid
- **JavaScript (ES6+)**: Interactive functionality and state management

### Features Implemented
- **Dark/Light Mode**: CSS variables and localStorage
- **LocalStorage API**: Form submissions and user preferences
- **Responsive Design**: CSS media queries and clamp()
- **Animations**: Keyframe animations with motion preferences support
- **Modal System**: Custom modal implementation with accessibility
- **Form Validation**: Email validation with regex and error handling

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.)
- Git (optional, for cloning)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/mustafaprofessional0-glitch/EditXMustafa.git
cd EditXMustafa
```

2. **Open in browser**
   - Double-click `index.html` for portfolio
   - Double-click `clock.html` for digital clock

3. **Or use a local server**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (with http-server)
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## 💻 Usage

### Portfolio Website

**Navigation**
- Click navigation links to jump to sections
- Use theme toggle button (🌙/☀️) to switch modes
- All links support keyboard navigation

**Contact Form**
- Fill in all required fields
- Form validates email format
- Successful submission shows confirmation message
- Data stored in localStorage

**Gallery**
- Click project cards to view details in modal
- Press Enter or Space on keyboard to open modal
- Use X button or press Escape to close modal

### Digital Clock

**Adding Timezones**
1. Select timezone from dropdown
2. Click "Add" button or press Enter
3. Clock card appears in grid

**Quick Setup**
- Click "Add Presets" to add common timezones (GMT, EST, PST, CET, JST)

**Managing Timezones**
- Click × button on card to remove timezone
- Click "Clear All" to remove all timezones
- Preferences auto-save to localStorage

## ♿ Accessibility

### Features Implemented
- ✅ **WCAG 2.1 Level AA** compliance
- ✅ **Semantic HTML5**: Proper heading hierarchy, form labels, landmarks
- ✅ **ARIA Attributes**: Proper role, aria-label, aria-labelledby, aria-live
- ✅ **Keyboard Navigation**: All interactive elements accessible via Tab
- ✅ **Focus Management**: Visible focus indicators and modal focus trapping
- ✅ **Color Contrast**: WCAG AA minimum contrast ratios
- ✅ **Motion Preferences**: Respects prefers-reduced-motion
- ✅ **Screen Readers**: Compatible with NVDA, JAWS, VoiceOver
- ✅ **Form Validation**: Clear error messages and success feedback

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `Tab` | Navigate between elements |
| `Shift + Tab` | Navigate backwards |
| `Enter` | Activate button/link or open modal |
| `Space` | Activate button or open modal |
| `Escape` | Close modal |
| `Arrow Keys` | Navigate in dropdowns |

## 🌐 Browser Support

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ Latest 2 versions | Full support |
| Firefox | ✅ Latest 2 versions | Full support |
| Safari | ✅ Latest 2 versions | Full support |
| Edge | ✅ Latest 2 versions | Full support |
| Opera | ✅ Latest 2 versions | Full support |
| IE 11 | ❌ Not supported | Use modern browser |

## 📱 Responsive Breakpoints

- **Mobile**: < 768px (single column layout)
- **Tablet**: 768px - 1024px (2 column layout)
- **Desktop**: > 1024px (full grid layout)

## 🎨 Color Scheme

### Dark Mode (Default)
- Background: `#0f172a`
- Card: `#1e293b`
- Accent: `#38bdf8` (Sky Blue)
- Text: `#f8fafc`
- Dim Text: `#94a3b8`

### Light Mode
- Background: `#ffffff`
- Card: `#f3f4f6`
- Accent: `#0ea5e9`
- Text: `#1f2937`
- Dim Text: `#6b7280`

## 📊 Projects Data

### Services
1. **Video Editing** - Adobe Premiere, CapCut
2. **Graphic Design** - Photoshop, Illustrator
3. **Web Development** - HTML, CSS, JavaScript
4. **Social Media Management** - Meta Business, TikTok, Instagram

### Featured Portfolio
1. **YouTube Intro** - Professional video editing
2. **Brand Identity** - Complete branding package
3. **E-commerce Site** - Responsive web platform

## 🔧 Customization

### Change Colors
Edit CSS variables in `:root` selector:
```css
:root {
    --accent-color: #your-color;
    --bg-color: #your-bg;
    /* ... other variables */
}
```

### Update Contact Information
Edit in `index.html`:
```html
<p>📞 Phone: <a href="tel:YOUR-NUMBER">Your Number</a></p>
<p>📧 Email: <a href="mailto:YOUR-EMAIL">Your Email</a></p>
```

### Add Timezones to Clock
Edit `TIMEZONES` array in `clock.html`:
```javascript
const TIMEZONES = [
    { offset: 0, name: 'UTC±00:00', city: 'London' },
    // Add more timezones
];
```

## 📧 Contact

- **Name**: Mustafa
- **Phone**: +92 322 5253517
- **Email**: mustafaprofessional0@gmail.com
- **Portfolio**: [EditXMustafa](https://editxmustafa.com)

## 📄 License

This project is open source and available under the MIT License.

## 🙏 Credits

- Icons and emoji for visual enhancement
- CSS Grid and Flexbox for responsive layouts
- LocalStorage API for data persistence
- Schema.org structured data for SEO

## 🚀 Future Enhancements

- [ ] Add image gallery with lightbox
- [ ] Backend API integration for contact form
- [ ] Blog section for portfolio stories
- [ ] Client testimonials section
- [ ] Project filtering by category
- [ ] Social media feed integration
- [ ] Animation preloader
- [ ] Multi-language support

## 📝 Notes

- All form data is stored locally using localStorage (client-side)
- For production, integrate with backend email service
- Customize project links and descriptions as needed
- Test on various devices for best experience

---

**Last Updated**: 2026
**Created by**: Mustafa (mustafaprofessional0-glitch)
