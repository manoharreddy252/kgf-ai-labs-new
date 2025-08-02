# KGF AI Labs

A simple, modern website for KGF AI Labs built for GitHub Pages deployment.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly layout
- ⚡ Fast loading with optimized CSS
- 🌈 Beautiful gradient background
- 🎯 Call-to-action buttons
- 📧 Contact information

## Deployment to GitHub Pages

### Method 1: Direct Upload (Recommended for simple sites)

1. Create a new repository on GitHub named `kgf-ai-labs-new`
2. Upload the `index.html` file to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Method 2: Using GitHub CLI

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit"

# Create repository on GitHub
gh repo create kgf-ai-labs-new --public

# Push to GitHub
git push -u origin main
```

### Method 3: Using GitHub Desktop

1. Open GitHub Desktop
2. Add the `kgf-ai-labs-new` folder as a repository
3. Publish to GitHub
4. Enable GitHub Pages in repository settings

## Customization

### Colors
The website uses a purple gradient theme. To change colors, modify the CSS variables in the `<style>` section:

```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Content
Edit the HTML content in `index.html` to customize:
- Company name and tagline
- Feature descriptions
- Contact information
- Social media links

### Adding Pages
To add more pages:
1. Create additional HTML files (e.g., `about.html`, `services.html`)
2. Update navigation links in `index.html`
3. Upload all files to the repository

## File Structure

```
kgf-ai-labs-new/
├── index.html          # Main homepage
└── README.md          # This file
```

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- Responsive Design
- Modern CSS Gradients

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

For questions or support, please open an issue on GitHub or contact the development team.

---

**Note**: This is a static website designed for GitHub Pages. For dynamic features, consider using a framework like React, Vue, or Angular. 