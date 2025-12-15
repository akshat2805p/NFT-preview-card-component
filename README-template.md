# NFT Preview Card Component

This project is a responsive preview card component for an NFT, displaying the artwork, description, price, and creator information.

## Overview

### Features

- Optimal layout for different screen sizes
- Hover effects for the NFT image (displaying an overlay icon), the title, and the creator name.

### Screenshot

![Design Preview](./design/desktop-preview.jpg)

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Absolute/Relative positioning for overlays

### Technical Highlights

This project focuses on CSS positioning techniques, specifically using `::after` pseudo-elements for creating overlay effects.

```css
.photu {
  position: relative;
}

.photu::after {
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: hsl(192, 63%, 55%, 50%);
  display: none; /* Shown on hover */
}
```
