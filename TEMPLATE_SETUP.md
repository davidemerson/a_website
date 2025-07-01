# Personal Website Template Setup

This is a minimal, fast-loading personal website template. Here's how to customize it for your use:

## Quick Setup

1. **Replace placeholder content in `index.html`:**
   - `Your Name` → Your actual name
   - `Your professional description` → Your bio/description
   - `https://yoursite.com/` → Your domain
   - `you@yoursite.com` → Your email
   - `yourusername` → Your social media usernames
   - Company/organization links and descriptions

2. **Update assets:**
   - Replace `assets/resume.html` with your resume (PDF or HTML)
   - Replace `assets/favicon.ico` with your favicon  
   - Replace `assets/davidfont.woff2` with your preferred web font (or remove font-face declaration)
   - Optionally replace `assets/cursor.webp` with your custom cursor

3. **Update `404.html`:**
   - Replace `Your Name` and `yoursite.com` with your details

4. **Update metadata files:**
   - `sitemap.xml` - Update URLs to your domain
   - `robots.txt` - Update sitemap reference
   - `assets/site.webmanifest` - Update for your site

## Photo Options

The template uses a placeholder image. You can:
- Use a Gravatar URL: `https://s.gravatar.com/avatar/YOURHASH?s=300`
- Host your own image and update the `src` attribute
- Use any other image hosting service

## Optional Customizations

- **Remove custom cursor:** Delete cursor references in CSS to use default cursors
- **Change colors:** Update the `#f2f2f2` background and `#00008b` link colors in `style.css`
- **Remove webring:** Delete the webring paragraph if you're not part of XXIIVV
- **Add analytics:** Insert your tracking code before the closing `</head>` tag

## File Sizes
- Total HTML/CSS: ~4.3KB
- Assets: ~180KB (mostly fonts and favicons)
- Loads fast on any connection

## Browser Support
Works on all modern browsers and many legacy ones due to minimal dependencies.
