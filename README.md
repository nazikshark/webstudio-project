# GoIT Markup Final Project — Responsive Web Design

This is the final homework assignment of the HTML/CSS course. It showcases a fully responsive landing page built with a Mobile First approach, featuring adaptive images and a functional mobile menu.

## 📋 Project Overview
The main goal was to transform a static layout into a professional, responsive website that works perfectly on all devices, from smartphones (320px) to desktops (1158px).

## 🚀 Key Features & Technical Implementation:

### 📱 Responsiveness (Mobile First):
- **Viewport**: Correct `<meta name="viewport">` settings for all pages.
- **Breakpoints**: The layout is fully optimized for three main breakpoints: `320px`, `768px`, and `1158px`.
- **Media Queries**: Used `@media (min-width: ...)` to progressively enhance the design from mobile to desktop, avoiding code duplication.
- **No Overflow**: Guaranteed zero horizontal scrolling on devices starting from `320px` width.

### 🖼 Adaptive Imagery (Retina Ready):
- **Responsive Images**: All content and background images support high-density screens (`1x` and `2x`).
- **High Resolution**: Implemented `min-resolution` media features to serve sharp images for Retina displays.
- **Optimization**: All assets are optimized for fast loading.

### 🍔 Mobile Menu:
- **Full Viewport**: The mobile menu occupies the entire screen height when active.
- **Toggle Logic**: Implemented via an `is-open` class to manage visibility.
- **Seamless Styling**: All interactive elements of the mobile menu are styled according to the layout.

### 🏗 Code Quality:
- **Normalization**: Integrated `modern-normalize.css` for cross-browser consistency.
- **Prettier**: Clean, well-formatted, and readable source code.
- **Architecture**: Strictly followed the provided style guides and best practices.

## 🛠 Technologies Used:
- HTML5 (Semantic Markup)
- CSS3 (Flexbox, Advanced Media Queries)
- BEM Methodology
- Adaptive Images (srcset / image-set)
- Basic JavaScript (for mobile menu toggling)

## 🔗 Live Demo:
[Link to your GitHub Pages here]
