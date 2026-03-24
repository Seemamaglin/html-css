# Pure CSS Image Slider

This project implements a **Pure CSS Image Slider/Carousel** with both **automatic** and **manual** slide navigation.

## Features

1. Auto Slider:
   -> Uses CSS `@keyframes` to animate the `slide-wrapper` automatically.
   -> Slides move horizontally
   -> Provides a smooth transition between slides.

2. Manual Slider
   - Uses hidden radio buttons and `:target` pseudo-class for navigation.
   - Each slide is wrapped in a `.slide div` inside .slide-wrapper
   - Navigation dots allow users to select a specific slide.
   - Only one slide is visible at a time.
   - Dots remain visible and respond to hover.

## How It Works

### Auto Slider
- The `.slide-wrapper` moves using CSS `animation` and `transform: translateX()`.
- Each slide is assigned an equal portion(25%) of the wrapper width(100%).

### Manual Slider
- Each slide has a unique ID (`slide1`, `slide2`, etc.).
- Clicking a navigation dot updates the URL hash (e.g., `#slide2`).
- The `:target` pseudo-class detects the active slide.
- CSS `transform: translateX()` moves the `.slide-wrapper` to display the selected slide.

