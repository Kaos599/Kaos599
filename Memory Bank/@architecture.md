# @Architecture - Kaos599 Profile System

## System Overview
The Kaos599 profile is a decoupled set of animated SVG components integrated into a GFM (GitHub Flavored Markdown) host. Each component is a self-contained unit of logic and style.

## Component Map
- `hero-banner.svg`: Entry point animation (Top of page).
- `vitruvian-kaos.svg`: Central branding visual (Center).
- `about-agentic.svg`: Knowledge base/Introduction component (Interactive).
- `card-*.svg`: Project-specific highlight cards.

## Interaction Flow
1.  **Initial Load**: All SVGs start continuous animations (Scanlines, Rotations).
2.  **Hover (Hero)**: Subtle glow intensification.
3.  **Hover (Terminal)**: Triggers "System Override" glitch (Easter Egg).
4.  **Hover (Project Cards)**: Expands card and increases border glow brightness.

## Data Flow
- `README.md` -> References `*.svg` via `<img>` tags.
- `*.svg` -> Internal CSS drives visual state based on time and user interaction.
