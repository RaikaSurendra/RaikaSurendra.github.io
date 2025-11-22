# Minimalist Resume Page

A clean, minimalist personal website inspired by [mitchellh.com](https://mitchellh.com/).

## Quick Start

1. Open `index.html` in your browser to preview: `file:///Users/surendraraika/projects/githubio/index.html`
2. Customize the content (see below)
3. Deploy to GitHub Pages

## Customization Guide

### Update Your Bio (`index.html`)

Look for `<!-- TODO: ... -->` comments in the HTML and update:

1. **Current Role** (line ~26): Update your job title and company
2. **About You** (line ~30): Add your interests, expertise, and current projects
3. **Certifications/Languages** (line ~35): Add your certifications, languages, or hobbies

### Update Social Links (`index.html`)

In the footer section (around line 42), update:

- **Email**: Replace `your.email@example.com` with your actual email
- **GitHub**: Replace `yourusername` with your GitHub username
- **Twitter/X**: Replace `yourusername` with your handle (or remove this link)
- **Add more**: You can add more social links following the same pattern

### Customize Styling (`style.css`)

The design uses CSS variables for easy customization:

```css
:root {
    --color-text: #000000;           /* Main text color */
    --color-text-light: #666666;     /* Lighter text/hover color */
    --color-background: #ffffff;     /* Background color */
    --max-width: 650px;              /* Content max width */
}
```

## Deploy to GitHub Pages

1. Create a repository named `yourusername.github.io`
2. Push these files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://yourusername.github.io`

## Design Principles

- **Minimalist**: Clean typography, lots of whitespace
- **Responsive**: Works on all screen sizes
- **Fast**: No frameworks, just vanilla HTML/CSS
- **Accessible**: Semantic HTML, proper contrast

## File Structure

```
githubio/
├── index.html      # Main HTML file
├── style.css       # Styling
└── README.md       # This file
```

## Tips

- Keep your bio concise (2-3 paragraphs like Mitchell Hashimoto's)
- Use simple, clear language
- Focus on what you're currently doing
- Add personality (hobbies, interests)
- Keep the design minimal - resist the urge to add too much
