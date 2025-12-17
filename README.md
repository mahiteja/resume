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
└── README.md           # This file
```

## Deploying to GitHub Pages

### Automatic Deployment with GitHub Actions (Recommended)

This repository includes a GitHub Actions workflow that automatically deploys your resume to GitHub Pages on every push to the `main` branch.

**Setup Steps:**

1. **Push your code to GitHub:**
   ```bash
   git add .
   git commit -m "Add resume with GitHub Actions workflow"
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on **Settings** → **Pages** (in the left sidebar)
   - Under **Source**, select **GitHub Actions**
   - Save the settings

3. **Automatic Deployment:**
   - The workflow will automatically run on every push to `main`
   - Your resume will be available at: `https://yourusername.github.io/repository-name/`
   - Check the **Actions** tab to monitor deployment progress

### Manual Deployment (Alternative)

If you prefer manual deployment without GitHub Actions:

1. Go to repository **Settings** → **Pages**
2. Under **Source**, select **Deploy from a branch**
3. Choose `main` branch and `/ (root)` folder
4. Click **Save**

### GitHub Actions Workflow

The included workflow (`.github/workflows/deploy.yml`) provides:
- ✅ Automatic deployment on every push to `main`
- ✅ Manual deployment trigger via Actions tab
- ✅ Proper permissions configuration
- ✅ Concurrent deployment handling
- ✅ Built-in artifact upload and deployment

**Workflow Features:**
- Triggers on push to `main` branch
- Can be manually triggered from Actions tab
- Uses official GitHub Pages actions
- Deploys entire repository content
- Shows deployment status and URL

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
