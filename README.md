# Silhouette

Film & TV reviews. Minimal static site for GitHub Pages.

## Setup

1. Create a new GitHub repository named `silhouette` (or `yourusername.github.io`)
2. Push all files in this folder to the repo
3. Go to **Settings → Pages**, set source to `main` branch, root `/`
4. Your site will be live at `https://yourusername.github.io/silhouette/`

## Adding a new post

1. Copy `posts/little-jaffna.html` as a template
2. Update the title, kicker, lede, and body content
3. Add a card for it in `index.html` (and `film.html` or `tv.html`)

## Structure

```
silhouette/
├── index.html          # Homepage
├── film.html           # Film filter
├── tv.html             # TV filter
├── css/style.css       # All styles
├── js/main.js          # Minimal JS
└── posts/
    ├── beef-s2.html
    ├── little-jaffna.html
    └── vettaiyan.html
```

No build step. No dependencies. Just HTML, CSS, and a Google Fonts import.
