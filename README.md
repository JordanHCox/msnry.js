# msnry.js

A lightweight, responsive jQuery plugin that creates masonry-style layouts for you.

## Features

- Supports 2 masonry layout types
- Auto column balancing based on container width
- Fade, scale, and slide animations
- Responsive design
- Optional random image fill for testing

## Usage

```html
<div id="gallery">
  <img src="..." />
  <img src="..." />
</div>

<script>
  $('#gallery').masonry({
    type: 'masonry',
    minColumns: 2,
    maxColumns: 5,
    gap: '20px',
    scrollAnimation: {
      type: 'fade',
      speed: 300
    }
  });
</script>
```

## Installation

```
npm install msnry.js
```

Or include directly:

```html
<script src="https://cdn.jsdelivr.net/npm/msnry.js/dist/msnry.min.js"></script>
```

## License

MIT
