# Wishing Well Animation

This repository contains a simple web page that displays a heart animation as a wishing well. The animation is triggered when the user hovers over certain elements.

## Features

- **Heart Animation**: When the user hovers over the designated area, hearts appear and animate upwards and downwards, simulating a wish being sent.
- **Responsive Design**: The design adapts to different screen sizes to ensure a consistent experience across devices.
- **Customizable Text**: The text content within the wishing well can be easily modified to suit your needs.

## Setup

To view the animation, simply clone the repository and open the `index.html` file in your preferred web browser.

## Customization

- To change the text content, modify the `.upper-text`, `.lower-text`, and `.inside-text` elements within the `index.html` file.
- To adjust the animation speed or timing, modify the `@keyframes heartAnim` and the `.delay-*` classes in the `styles.css` file.

## Preview

Here's a snippet of the code to give you a preview of the structure:

```html
<div class="wish-container">
    <div class="upper-text">TOP SECRET, Только Счастью</div>
    ...
</div>
```

And the corresponding styles:

```css
.wish-container:hover .upper-text {
    top: -34px;
}
...
```

## Contributions

Contributions are welcome! If you'd like to suggest improvements or report bugs, please open an issue.
