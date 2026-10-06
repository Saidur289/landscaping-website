<div align="center">
  <img src="assets/logo.jpg" alt="Summit Ridge Landscaping Logo" width="120" />

  # Summit Ridge Landscaping

  **A Premium, High-Conversion Landing Page for Landscaping Services**

  [![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
  [![Vanilla JS](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)](#)
  [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](#)
</div>

---

## 📖 Overview

The **Summit Ridge Landscaping** landing page is a masterclass in modern web aesthetics designed specifically for the landscaping and outdoor architecture industry. Built natively without heavy frameworks, it focuses on delivering a highly performant, visually stunning, and highly engaging user experience. 

From its interactive video-scrubbing hero section to its polished glassmorphism UI components, every pixel is engineered to build trust and drive client conversions.

<img src="assets/hero.jpg" alt="Hero Section Preview" width="100%" style="border-radius: 8px;" />

## ✨ Key Features

- **🎬 Scroll-Scrubbed Video Hero**: Creates a dynamic, premium feel where the background video plays frame-by-frame smoothly tied to the user's scroll position.
- **📱 Fully Responsive Design**: Flawlessly adapts to any screen size—mobile, tablet, or 4K desktop displays.
- **🧊 Glassmorphism UI Elements**: Employs frosted glass effects (`backdrop-filter`) on statistics and navigation components for a modern, layered depth.
- **⚡ Performant Scroll Animations**: Uses the lightweight `IntersectionObserver` API to orchestrate buttery-smooth reveal animations as the user scrolls down the page.
- **🎨 Premium Typography & Color System**: Thoughtfully crafted design system using *Abril Fatface* for bold, high-contrast headings and a rich palette of Deep Forest Greens, Warm Golds, and Creams.
- **🖼️ Masonry CSS Grid Layout**: An elegant, responsive masonry gallery showcasing project portfolios without the need for bloated JS libraries.

## 🛠️ Built With

This project avoids heavy dependencies in favor of pure, performant native web technologies:

- **HTML5**: Semantic, accessible structure.
- **Vanilla CSS3**: Custom CSS variables (Custom Properties), Flexbox, CSS Grid, and modern viewport units (`dvh`).
- **Vanilla JavaScript (ES6)**: Lightweight DOM manipulation, intersection observers, and scroll event listeners.

## 🚀 Getting Started

### Prerequisites

You don't need any complex build tools like Webpack or Node.js to run this project. A simple local static server is all you need.

- Node.js (Optional, if using `npx serve`)
- Python (Optional, if using `http.server`)
- VS Code Live Server Extension (Optional)

### Installation & Running Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Saidur289/landscaping-website.git
   cd landscaping-website
   ```

2. **Serve the project locally**

   *Using Node.js (npx):*
   ```bash
   npx serve .
   ```
   *Using Python 3:*
   ```bash
   python -m http.server 8000
   ```

3. **View in browser**
   Open `http://localhost:3000` (or the port specified by your server) to view the live site.

## 📂 Project Structure

```text
landscaping-website/
├── assets/
│   ├── gemini_generated_video_3f82a46f.mp4   # Hero scrubbing video
│   ├── hero.jpg                              # Fallback hero image
│   ├── logo.jpg                              # Brand logo
│   └── service-*.jpg                         # Various project/service photography
├── index.html                                # Main markup and embedded JS logic
├── index.css                                 # Global styles, variables, and animations
└── README.md                                 # Project documentation
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! 
Feel free to check [issues page](https://github.com/Saidur289/landscaping-website/issues).

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
<div align="center">
  <i>Designed and engineered with care for Summit Ridge Landscaping.</i>
</div>
