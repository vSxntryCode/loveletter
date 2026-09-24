# Love Letter ❤️

A mobile-first interactive appreciation page for Alicia, inspired by a scrapbook / sealed-letter style.

## Current version

- Animated envelope opening
- Personal appreciation letter
- Polaroid-style photo placeholders
- "Lines I'd underline" section
- Promise / reassurance cards
- Interactive tap-to-leave-a-kiss section
- Fully responsive, single-file static website
- No external dependencies

## Adding photos later

The photo spaces currently say **our photo goes here**.

When the final photos are ready, add them to an `assets/` folder and replace each placeholder such as:

```html
<div class="photo">our photo<br>goes here</div>
```

with:

```html
<div class="photo"><img src="assets/photo-1.jpg" alt="Alicia and Enzo"></div>
```

The captions can be changed independently underneath each photo.

## Hosting

The site is static and can be published directly with GitHub Pages from the repository root on the `main` branch.
