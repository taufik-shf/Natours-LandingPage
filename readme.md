## 🌿 Natours - Advanced CSS Implementation

_Professional Web Development Showcase_

### 🚀 Developed a responsive landing page

Developed a landing page for adventure tourism company "Natours", focusing on:

- Semantic HTML5 structure with ARIA landmarks
- CSS architecture following 7-1 pattern
- Performance-focused asset delivery
- Cross-browser compatible animations
- Desktop-first responsive strategy
- Custom build workflow with npm scripts
  <br>

### 🛠️ Technical Merit:

- Implemented complex UI patterns without JavaScript:
  - Hamburger navigation system
  - Modal presentation layer
  - Interactive card flips
- Achieved 95+ Lighthouse accessibility score
- Visual Effects:
  - flip-able cards with perspective transforms
  - Custom clip-path polygon shapes
  - Background with gradient color overlays
- Performance:
  - Critical CSS inlining
  - Image-set for modern formats and response to differen screen resolution
  - Lazy-loading implementation
- Sass: Project Architecture
  ```bash
  sass/
  ├── abstracts/
  ├── base/
  ├── components/
  ├── layout/
  ├── pages/
  └── main.scss
  ```
- Automated build process
  ```bash
  # Development
  npm run startdev   # Parallel Sass compilation + Live server
  # Production Build
  npm run build:css  # Full processing pipeline:
                   # 1. SCSS Compilation → 2. Concatenation →
                   # 3. Auto-prefixing → 4. Minification →
                   # 5. Cleanup
  ```
  <br>

### 📜 Credits

- Design Concept: [Jonas Schmedtmann](https://www.udemy.com/user/jonasschmedtmann/) (Udemy Instructor)
- Icon System: [Linea-Basic Icon](https://linea.io/)
- Nature Photos: [Unsplash](https://unsplash.com/)
  <br>

### 🚦 Disclaimer:

- Developed for educational purposes as part of advanced CSS training.
- Commercial images used under fair use for portfolio demonstration.
