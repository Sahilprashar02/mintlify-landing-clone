> A pixel-perfect, responsive clone of the Mintlify landing page, built with modern HTML & CSS.

---

## 📸 Preview

![Mintlify Clone Hero Section](images/hero-image-dark.svg)

---

## 📑 Table of Contents

- [Features](#-features)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Customization](#-customization)
- [Contributing](#-contributing)
- [License](#-license)

---

## ✨ Features

- **Responsive Design**: Fluid layout that adapts seamlessly to desktop, tablet, and mobile screens.
- **Modern Interactions**:
  - Glassmorphism effects in navigation and cards.
  - Subtle hover animations and transitions.
  - Smooth scrolling.
- **Semantic HTML**: Clean, accessible, and SEO-friendly structure.
- **Modern CSS**:
  - Uses CSS Variables (`:root`) for easy theming.
  - Flexbox and Grid layouts.
  - `lab()` color space for high-fidelity dark mode colors.

---

## 📂 Project Structure

```bash
mintify-project/
├── index.html          # Main landing page structure
├── style.css           # Global styles and variables
├── README.md           # Project documentation
└── images/             # Asset directory
    ├── mintlify-logo.ico
    ├── mintlify-wordmark.svg
    ├── bg-dark.svg
    ├── hero-image-dark.svg
    └── ... (icons and illustrations)
```

---

## 🚀 Getting Started

1.  **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/mintlify-clone.git
    cd mintlify-clone
    ```

2.  **Run the project**
    Simply open `index.html` in your preferred web browser.

    _OR use a live server (VS Code Extension):_
    - Right-click `index.html` -> "Open with Live Server"

---

## 🎨 Customization

You can easily customize the look and feel by editing the CSS variables in `style.css`.

### Colors

Navigate to the `:root` selector in `style.css`:

```css
:root {
  --color-primary: #16a34a; /* Main brand color */
  --color-bg-light: #020303; /* Background color */
  /* ... and more */
}
```

### Images

Replace assets in the `images/` folder. Ensure you update the filenames in `index.html` if they differ.

---

## 🤝 Contributing

Contributions are welcome!

1.  Fork the project.
2.  Create your feature branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
