# Resume - Mahiteja Bollojula

A professional, responsive HTML resume optimized for GitHub Pages with modern design and enhanced user experience.

## ✨ Features

- **Semantic HTML5**: Clean structure with header, main, and footer elements
- **Mobile Responsive**: Fully responsive design that works perfectly on all devices
- **Professional Styling**: Modern gradient design with sophisticated color scheme
- **Executive Summary**: Eye-catching summary section highlighting key achievements
- **Interactive Elements**: Smooth hover effects and transitions
- **Enhanced Typography**: Optimized fonts with anti-aliasing for crisp text
- **LinkedIn Integration**: Direct link to professional LinkedIn profile
- **Print Optimized**: Professional print styles for PDF generation
- **SEO Optimized**: Meta tags for better search engine visibility
- **GitHub Pages Ready**: Can be hosted directly on GitHub Pages with zero configuration

## File Structure

```
my-resume/
├── index.html          # Main HTML resume file
├── style.css           # Stylesheet with responsive design
├── Mahiteja_Bollojula.docx  # Original resume (DOCX format)
└── README.md           # This file
```

## Deploying to GitHub Pages

### Option 1: Using GitHub Web Interface

1. Create a new repository on GitHub (e.g., `my-resume`)
2. Go to the repository settings
3. Navigate to "Pages" section in the left sidebar
4. Under "Source", select the branch you want to deploy (usually `main` or `master`)
5. Select the root folder (`/`) as the source
6. Click "Save"
7. Your resume will be available at: `https://yourusername.github.io/my-resume/`

### Option 2: Using Git Command Line

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Add HTML resume"

# Add remote repository
git remote add origin https://github.com/yourusername/my-resume.git

# Push to GitHub
git push -u origin main
```

Then follow steps 2-7 from Option 1 to enable GitHub Pages.

## Local Development

To view the resume locally:

1. Simply open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then open http://localhost:8000 in your browser
   ```

## Customization

### Colors

Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #2c3e50;    /* Dark blue-gray */
    --secondary-color: #3498db;  /* Blue */
    --accent-color: #e74c3c;     /* Red */
    --text-color: #333;          /* Dark gray */
    --bg-color: #ffffff;         /* White */
    --light-bg: #f8f9fa;        /* Light gray */
}
```

### Content

Edit `index.html` to update:
- Contact information
- Profile summary
- Skills
- Work experience
- Any other sections

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

© 2025 Mahiteja Bollojula. All rights reserved.
