# Resume - Mahiteja Bollojula

Professional single-page HTML resume with responsive layout, print support, and export utilities.

## Features

- Semantic HTML5 structure with accessible sectioning
- Responsive design for desktop and mobile
- Inline, self-contained styling and scripting in one file
- Timeline-based experience section
- Export toolbar for PDF, DOCX, JPG, and Markdown
- Print-optimized styling for clean hardcopy/PDF output
- SEO-friendly metadata and social-profile links
- GitHub Pages deployment workflow included

## Project Structure

```text
resume/
├── index.html
├── README.md
└── .github/
    └── workflows/
        └── deploy.yml
```

## Run Locally

Option 1:
- Open index.html directly in your browser.

Option 2:
- Start a local static server:

```bash
python -m http.server 8000
```

- Open http://localhost:8000

## GitHub Pages Deployment

This repository includes [.github/workflows/deploy.yml](.github/workflows/deploy.yml) for automatic Pages deployment.

1. Push changes to the main branch.
2. In GitHub repository settings, open Pages.
3. Set Source to GitHub Actions.
4. Verify deployment in the Actions tab.

Published URL format:
- https://yourusername.github.io/repository-name/

## Customization

Main file to edit:
- [index.html](index.html)

Sections you can update quickly:
- Header and contact information
- Summary and skills
- Experience timeline and date ranges
- Education and certifications

Styling and behavior:
- CSS variables and layout rules are in the style block inside index.html.
- Export and interaction logic are in the script block inside index.html.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari and Chrome for Android)

## License

Copyright (c) Mahiteja Bollojula. All rights reserved.
