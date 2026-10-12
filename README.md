# 🌍 Non-Profit & Charity Foundation Website Template

A modern, accessible, and fully responsive website template designed for non-profit organizations, NGOs, charities, and social welfare foundations. Built with **HTML5**, **CSS3**, and **Vanilla JavaScript**, featuring a seamless **Dark/Light Mode** toggle, interactive forms, and tabbed navigation.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](#)

---

## 🌟 Key Features

- 🌓 **Dynamic Dark / Light Mode**: Instant theme switching with `localStorage` persistence and automatic system preference detection (`prefers-color-scheme`).
- 📱 **Fully Responsive Layout**: Mobile-friendly navigation with an animated hamburger drawer menu and flexible CSS Grid/Flexbox layouts.
- 📑 **Multi-Page Architecture**:
  - **Home (`index.html`)**: Hero showcase, mission summary, focus areas, impact statistics, and call-to-actions.
  - **About Us (`about.html`)**: Organization journey, story, guiding principles, mission, and vision.
  - **Our Work (`work.html`)**: Community programs, quantifiable impact numbers, and beneficiary success stories.
  - **Get Involved (`involve.html`)**: Interactive tab-based interface containing:
    - Volunteer Application form
    - Custom Donation tier selector & form
    - Corporate & Community Partnership details
  - **Contact Us (`contact.html`)**: Contact details, interactive Google Maps embed, and direct message form.
- ⚡ **Zero Heavy Dependencies**: Pure semantic HTML5, custom modern CSS variables, FontAwesome icons, and Vanilla JS for ultra-fast loading speed.
- 🎨 **Modern Design System**: Reusable CSS custom properties (color variables, smooth transitions, and modular card components).

---

## 📁 Project Structure

```text
├── index.html          # Main landing page
├── about.html          # Organization mission, vision & story
├── work.html           # Programs and community impact stories
├── involve.html        # Volunteer, donation & partnership page
├── contact.html        # Contact details & Google Maps embed
├── css/
│   └── style.css       # Complete stylesheet with theme variables
├── js/
│   └── main.js         # Theme toggle, tabs, mobile menu & form handlers
├── LICENSE             # Open-source MIT License
└── README.md           # Documentation
```

---

## 🚀 Getting Started

No build tools or server setup required! This is a 100% static project.

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/ngo-charity-website.git
cd ngo-charity-website
```

### 2. Run locally
- Simply double-click `index.html` to open it in any web browser.
- Or use VS Code's **Live Server** extension for real-time reload.
- Or run a quick local Python server:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🌐 Deploy to GitHub Pages (Free Live Demo)

1. Push this project to your GitHub repository.
2. In your GitHub repository, go to **Settings** > **Pages**.
3. Under **Build and deployment** > **Branch**, select `main` (or `master`) and folder `/ (root)`.
4. Click **Save**. Within 1–2 minutes, your live demo will be published at:
   `https://<your-username>.github.io/<repo-name>/`

---

## 🛠️ Customization

- **Branding & Logo**: Update the text inside `<a href="index.html" class="logo">` across HTML files.
- **Color Theme**: Modify the primary and secondary colors in [`css/style.css`](css/style.css):
  ```css
  :root {
      --primary-color: #4a6fdc;
      --secondary-color: #ff6b6b;
      --dark-color: #1a1a2e;
      --light-color: #f8f9fa;
  }
  ```
- **Contact Info & Social Links**: Update the placeholder emails (`info@example.org`) and social URLs in the footer of each HTML file.

---

## 📄 License

This project is licensed under the **MIT License** — you are free to use, modify, and distribute this template for personal or commercial projects. See the [LICENSE](LICENSE) file for details.
