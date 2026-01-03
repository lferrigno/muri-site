# Muri Website

Static website for [muri.lat](https://www.muri.lat)

## Local Development

### Prerequisites
- Any local HTTP server (Python, Node, etc.)

### Running Locally

**Using Python:**
```bash
python3 -m http.server 8080
```

**Using Node (npx):**
```bash
npx serve .
```

**Using PHP:**
```bash
php -S localhost:8080
```

Then open http://localhost:8080 in your browser.

### Project Structure

```
├── index.html      # Main HTML file
├── css/
│   └── styles.css  # All styles
├── js/
│   └── main.js     # Navigation, scroll behavior
└── CNAME           # Custom domain config for GitHub Pages
```

## Deployment

The site is automatically deployed to GitHub Pages when pushing to `main` branch.

- **Production URL:** https://www.muri.lat
- **GitHub Pages URL:** https://lferrigno.github.io/muri-site/
