# Nexus/Arch - Computer System Design Website

![Website Preview](https://via.placeholder.com/800x400/2563eb/ffffff?text=Nexus%2FArch+System+Design+Website)

A modern, responsive landing page for computer system design and architecture. This website showcases the system design lifecycle, core principles, and provides a visual blueprint for computer architects, hardware designers, and students.

🔗 **Live Demo**: [Coming Soon]

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## 🔍 Overview

Nexus/Arch is a static HTML/CSS website designed to present computer system design concepts in a clean, professional format. It targets:

- Computer architects and hardware designers
- Students learning system design
- Engineering teams documenting architecture
- Educators teaching computer organization

The page walks visitors through the four main phases of system design, presents a concrete 8-core mesh system example, and outlines core design principles.

## ✨ Features

- **Responsive Design** - Works on desktop, tablet, and mobile devices
- **Modern UI** - Clean gradients, cards, and professional color scheme (blue/neutral palette)
- **System Design Lifecycle** - Four interactive cards explaining design phases
- **Architecture Blueprint** - Example 8-core mesh system with component list and ASCII diagram
- **Design Principles** - Four core principles with visual emphasis
- **Tool Ecosystem** - Quick reference to popular system design tools (gem5, Verilator, etc.)
- **Font Awesome Icons** - Over 40 icons for visual enhancement
- **Smooth Hover Effects** - Interactive card animations

## 🛠 Technologies Used

- **HTML5** - Semantic structure
- **CSS3** - Flexbox, Grid, custom properties, animations
- **Font Awesome 6** - Icon library (free version)
- **Google Fonts (Inter)** - Primary typeface (system fallback included)

No JavaScript frameworks or build tools required - pure HTML/CSS!

## 📁 Project Structure

```
nexus-arch-website/
│
├── index.html          # Main landing page
├── README.md           # Documentation
└── assets/             # (Optional) For images/custom assets
    └── preview.png     # Screenshot for GitHub
```

## 💻 Installation

### Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/nexus-arch-website.git
   cd nexus-arch-website
   ```

2. **Open in browser**
   - Simply open `index.html` in any modern browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with live-server)
     npx live-server
     ```

3. **View the site**
   - Navigate to `http://localhost:8000` (or your server's URL)

### Deployment Options

- **GitHub Pages**: Push to a repository and enable Pages
- **Netlify/Vercel**: Drag and drop the folder
- **Any static hosting**: Upload the HTML file

## 🎨 Usage

### As a Template

Feel free to customize this website for your own projects:

1. **Change colors** - Modify the CSS variables (search for `#2563eb` for primary blue)
2. **Update content** - Replace text in the hero section, cards, and blueprint
3. **Add real images** - Replace the ASCII diagram with actual architecture diagrams
4. **Add pages** - Link to additional documentation or tools

### Example Customizations

```css
/* Change primary color to purple */
:root {
  --primary: #9333ea;  /* Replace all #2563eb occurrences */
}

/* Modify card hover effect */
.phase-card:hover {
  transform: translateY(-10px);
  box-shadow: 0 30px 40px -16px var(--primary);
}
```

## 🖌 Customization Guide

### Sections You Can Modify

| Section | HTML ID/Class | What to Change |
|---------|---------------|----------------|
| Hero text | `.hero-text h1` | Main headline |
| Design phases | `.phase-card` | Phase titles, descriptions |
| Blueprint | `.blueprint` | System example, specs |
| Principles | `.principle-item` | Principle titles, descriptions |
| Footer | `footer` | Links, copyright |

### Adding Real Diagrams

Replace the ASCII art in `.mock-schematic` with:
- SVG diagrams
- PNG screenshots
- Actual system design tool outputs

```html
<!-- Replace this -->
<div class="mock-schematic">...</div>

<!-- With an image -->
<img src="assets/mesh-diagram.svg" alt="8-core mesh architecture">
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Report bugs** - Open an issue
2. **Suggest features** - New sections, improved visuals
3. **Submit PRs** - Code improvements, translations

### Development Guidelines

- Keep the design consistent (blue/neutral theme)
- Maintain responsiveness
- Test across browsers (Chrome, Firefox, Safari)
- No JavaScript dependencies unless necessary

## 📄 License

MIT License - feel free to use this for personal or commercial projects. Attribution appreciated but not required.

```
Copyright (c) 2025 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files...
```

## 🙏 Acknowledgments

- Font Awesome for the icon set
- Inter font family (default system fallback)
- UI inspiration from modern hardware design tools

---

**Built with ❤️ for computer architects and hardware enthusiasts**

[Report Bug](https://github.com/yourusername/nexus-arch-website/issues) · [Request Feature](https://github.com/yourusername/nexus-arch-website/issues)
