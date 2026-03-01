# Tech Context - Kaos599 README

## Technology Stack
- **Structure**: GitHub Flavored Markdown (GFM).
- **Styling/Animation**: SVG 1.1 / CSS3 (embedded in `<foreignObject>`).
- **Deployment**: GitHub Pages/Profile (Self-hosted via repository).
- **Theme**: Dark Mode optimized (Chartreuse Green: #39d353, Background: #0d1117).

## Technical Constraints
1.  **No External Scripts**: Animations must be pure SVG/CSS as GitHub strips `<script>` tags.
2.  **File Size**: Keep individual SVGs under 100KB to ensure fast loading on mobile/desktop.
3.  **Cross-Browser**: Must render correctly in Chrome, Firefox, and Safari (Safari can be picky with `foreignObject`).
4.  **No Iframes**: All visual logic MUST be contained within the SVG itself.

## Key CSS Techniques
- `@keyframes` for continuous animations (typing, glitch, rotation).
- CSS `filter` for glows and blurs.
- `animation-delay` for sequencing staggered effects.
- Hover-based triggers using `:hover` within the SVG.
