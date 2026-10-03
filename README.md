# Alexandrite Chung’s Portfolio

A responsive Rutgers Business School portfolio, hosted on GitHub Pages.

**Website:** https://ajc591.github.io/Alex_chung.github/

## Files

- `index.html` — page content, responsive styles, and project dialogs. No build step or external libraries required.
- `Headshot.png` — profile photo.

## Personalize

Update the biography and project cards in `index.html` with your own information. Current projects are clearly labeled sample concepts, not completed work.

Near the bottom of `index.html`, add your public contact details and resume filename to:

```js
const profile = { email: '', linkedin: '', resume: '' };
```

For the resume, upload your PDF to this repository and set `resume` to its exact filename, such as `resume.pdf`. Set `linkedin` to your complete profile URL. Until these values are supplied, the corresponding buttons display an availability message and a GitHub profile link.

## Publishing

GitHub Pages publishes from the `main` branch. Commit changes to update the live site. The project outlines can be opened and downloaded directly from each card.
