# System Patterns - Kaos599 README

## Design Patterns
1.  **The Terminal Mask**: Using dark overlaps and dashed borders to simulate a terminal CRT screen.
2.  **Scanline Effect**: A semi-transparent overlay with moving horizontal lines to give a "retro-future" look.
3.  **Typing Sequencing**: Using `step-end` keyframes to simulate character-by-character typing.
4.  **Glitch Intervals**: Using non-linear keyframe percentages to create sudden "glitches" in opacity or transform.

## Component Structure
1.  **SVG Wrapper**: Setting `viewBox="0 0 W H"` for responsiveness.
2.  **Style Block**: Embedded `<style>` for component-specific animations.
3.  **ForeignObject Container**: Hosting the HTML/CSS structure.
4.  **Fallback Path**: Simple text or basic SVG for browsers that don't support `foreignObject`.

## File Organization
- `README.md`: Root configuration and layout.
- `*.svg`: Standalone animated components.
- `Memory Bank/`: Documentation and project state.
