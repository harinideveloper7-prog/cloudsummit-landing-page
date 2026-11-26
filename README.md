# CloudSummit 2027 - Responsive Tech Conference Landing Page

A beginner-friendly HTML5 and CSS3 landing page project built for Visual Studio Code.

## Project Files
- `index.html` — Semantic HTML5 structure (Header, Hero, Highlights, Speakers, Agenda, Registration Form, Footer)
- `style.css` — External stylesheet demonstrating:
  - **Box Model & Selectors**: Element, class, ID (`#speakers`, `#schedule`, `#register`), attribute (`input[type="email"]`), child (`>`), and pseudo-class (`:hover`, `:focus`) selectors
  - **Flexbox**: Navigation bar, hero buttons, feature cards, registration form, and footer layout
  - **CSS Grid**: Responsive speaker cards (`repeat(auto-fit, minmax(230px, 1fr))`) and conference agenda (`repeat(auto-fill, minmax(280px, 1fr))`)
  - **Transitions & Transforms**: Spring hover states on feature cards (`scale(1.04)`, `rotate(-10deg)`), leftward slide on agenda cards (`translateX(-6px)`), and `translateY()` / `scale()` across buttons and cards
  - **CSS Animations**: `@keyframes slideZoomIn` and `@keyframes pulseGlow`
  - **Media Queries**: Breakpoints at `768px` (tablet) and `480px` (mobile)

## How to Run in VS Code
1. Open the `cloudsummit-landing-page` folder in Visual Studio Code.
2. Install or open the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.
