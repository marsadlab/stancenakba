# StanceNakba 2026 - Shared Task Website

A professional website for the StanceNakba 2026 Shared Task on Actor and Topic-Aware Stance Detection in Public Discourse.

## Features

- **Modern, Editorial Design**: Clean, professional aesthetic with distinctive typography
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: Engaging scroll animations and hover effects
- **Single Page Application**: All content on one page with smooth scroll navigation
- **GitHub Pages Ready**: Static HTML that works perfectly with GitHub Pages

## File Structure

```
stancenakba-2026/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
└── README.md           # Documentation
```

## Quick Start

### Option 1: Deploy to GitHub Pages

1. **Create a new GitHub repository** for your shared task website
   
2. **Upload the files**:
   - Upload `index.html` and `styles.css` to your repository

3. **Enable GitHub Pages**:
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click "Save"

4. **Access your website**:
   - Your site will be available at: `https://[your-username].github.io/[repository-name]/`
   - GitHub will provide the exact URL in the Pages settings

### Option 2: Local Development

1. Simply open `index.html` in your web browser
2. No build process or dependencies required!

## Customization

### Update Content

The website consists of two files:
- **index.html**: Contains all the content and structure
- **styles.css**: Contains all the styling

To update content:
- Edit text, dates, and examples in `index.html`
- Modify colors, fonts, and visual styling in `styles.css`

- **Task Details**: Edit the content in each section
- **Dates**: Update the timeline section with your specific dates
- **Contact Information**: Add organizer details in the footer
- **Call-to-Action Buttons**: Update the links in the "Ready to Participate?" section

### Color Scheme

The color scheme is defined in CSS variables at the top of `styles.css`:

```css
:root {
    --primary: #1a1a2e;      /* Main dark color */
    --secondary: #16213e;     /* Secondary dark */
    --accent: #e94560;        /* Accent color (pink/red) */
    --accent-light: #ff6b88;  /* Light accent */
    --text: #2d3436;          /* Main text color */
    --text-light: #636e72;    /* Secondary text */
    --bg: #ffffff;            /* Background */
    --bg-soft: #f8f9fa;       /* Soft background */
}
```

### Typography

The website uses two Google Fonts:
- **Crimson Pro**: Serif font for headings (elegant, editorial feel)
- **Work Sans**: Sans-serif for body text (clean, readable)

To change fonts:
1. Update the Google Fonts link in the `<head>` section of `index.html`
2. Update the `font-family` declarations in `styles.css`

## Sections Included

1. **Navigation**: Fixed top navigation with smooth scroll
2. **Hero Section**: Eye-catching introduction with key statistics
3. **Overview**: Research background and objectives
4. **Tasks**: Detailed descriptions of Subtask A and B
5. **Evaluation**: Metrics and assessment criteria
6. **Important Dates**: Visual timeline of key milestones
7. **Community**: Target audience and engagement
8. **Organizing Team**: Committee members and their affiliations
9. **Call-to-Action**: Registration and participation links
10. **Footer**: Contact and copyright information

## Technical Details

- **Separated Structure**: HTML for content, CSS for styling, JavaScript for interactions
- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript
- **Mobile-First**: Responsive design that works on all devices
- **Performance**: Optimized with CSS animations and minimal JavaScript
- **Accessibility**: Semantic HTML and proper heading hierarchy
- **SEO-Friendly**: Proper meta tags and structure

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Adding Additional Features

### Adding a Logo

Replace the text logo in the navigation:
```html
<a href="#" class="logo">
    <img src="path/to/logo.png" alt="StanceNakba 2026">
</a>
```

### Adding Contact Form

Add a form in the footer or create a new section:
```html
<form action="your-form-handler" method="POST">
    <input type="email" name="email" placeholder="Email" required>
    <textarea name="message" placeholder="Message" required></textarea>
    <button type="submit" class="btn btn-primary">Send</button>
</form>
```

### Adding Social Media Links

Add icons in the footer:
```html
<div class="social-links">
    <a href="https://twitter.com/yourhandle">Twitter</a>
    <a href="mailto:contact@example.com">Email</a>
</div>
```

## License

Feel free to modify and customize this website for your shared task.

## Support

If you encounter any issues or need help with customization, please refer to the GitHub Pages documentation or open an issue in your repository.

---

**Note**: Remember to update all placeholder links (registration, data download, contact) with actual URLs once they're available!
