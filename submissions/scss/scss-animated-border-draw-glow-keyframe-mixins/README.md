# Animated Border Draw & Glow Keyframe Mixins

<<<<<<< HEAD
A reusable SCSS utility module for creating animated border drawing effects and glowing border highlights.

## Features

- Animated border drawing effect
- Custom glow effect
- Reusable SCSS mixins
- Adjustable animation duration
- Adjustable glow blur radius

---

## File Included

- _animated-border-draw-glow-keyframe-mixins.scss

---

## Mixins

### 1. animated-border-draw()

Creates animated border drawing effect.

Parameters:

- $color → Border color
- $width → Border thickness
- $duration → Animation duration

Example:

```scss
.card {
  @include animated-border-draw(#ff5733, 3px, 1s);
}
```

---

### 2. border-glow()

Creates glowing border effect.

Parameters:

- $glow-color → Glow color
- $blur → Blur radius

Example:

```scss
.card {
  @include border-glow(#00ffff, 15px);
}
```

---

## CSS Output Example

```css
.card {
  position: relative;
  border: 2px solid transparent;
  box-shadow: 0 0 12px #3498db;
}
```
=======
## Overview

This SCSS utility provides reusable mixins for animated border drawing and glowing border effects.

It allows developers using EaseMotion CSS to easily add animated border effects with customizable parameters.

---

## Included Mixins

### 1. animated-border-draw

Creates an animated border drawing effect.

Usage:

```scss
.card {
  @include animated-border-draw(#00ffff, 2px, 1.5s);
}
```

Parameters:

- `$color` → Border color
- `$border-width` → Border thickness
- `$duration` → Animation duration

---

### 2. animated-border-glow

Creates a glowing animated border.

Usage:

```scss
.card {
  @include animated-border-glow(#00ffff, 12px, 2s);
}
```

Parameters:

- `$color` → Glow color
- `$blur` → Glow blur intensity
- `$duration` → Animation duration

---

## Why useful?

This utility helps developers quickly add visually appealing border animations and reusable motion effects inside the EaseMotion CSS design system.
>>>>>>> main
