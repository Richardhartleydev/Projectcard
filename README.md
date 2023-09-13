## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](<./images/Screenshot%20(2679).png>)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

Using 'srcset' within a img-tag to swap from a mobile image to desktop image at a specific width

```html
<source srcset="images/image-product-desktop.jpg" media="(min-width: 600px)" />
```

My first usage of custom properties in css, made applying colors, fonts + font weights much easier across a project

```css
:root {
  --ff-accent: "Fraunces", serif;
  --ff-base: "Montserrat", sans-serif;

  --fw-regular: 500;
  --fw-bold: 700;

  --clr-primary-400: hsl(158, 36%, 37%);
  --clr-primary-700: hsl(158, 36%, 25%);
  --clr-primary-200: hsl(30, 38%, 92%);

  --clr-secondary-900: hsl(212, 21%, 14%);
  --clr-secondary-500: hsl(228, 12%, 48%);
  --clr-secondary-100: hsl(0, 0%, 100%);
}
```
