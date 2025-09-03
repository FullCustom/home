# Full Custom Music Repair Website

## Overview
This repository contains the source code for the Full Custom Music Repair website, a professional service specializing in guitar amplifier repair, vintage restoration, and custom builds. Located at 400 Market Street Rear, Lemoyne, PA 17043, the business has been operating full-time since 1997 and is an authorized warranty center for brands like Fender, Gibson, and Marshall. The website (`https://www.fullcustommusic.com`) provides information about services, contact details, and a repair tag system.

The project uses HTML, CSS, and Bootstrap 3.3.6 to create a responsive, user-friendly interface. Recent updates include accessibility fixes (e.g., navbar toggle `aria-label`), removal of inline styles, and SEO optimizations (e.g., meta tags, schema markup).

## Features
- Responsive design with Bootstrap 3.3.6
- SEO-optimized with meta descriptions, keywords, and LocalBusiness schema
- Accessible navigation with proper ARIA attributes
- Clean, professional layout with Montserrat font
- Links to related services (e.g., `repairtag.fullcustommusic.com`, Narwhal Industries)

## Installation
To set up the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/full-custom-music-repair.git
   cd full-custom-music-repair
   ```

2. **Ensure Dependencies**:
   - The project relies on external CDNs for:
     - Bootstrap 3.3.6 CSS: `https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css`
     - jQuery 1.12.0: `https://ajax.googleapis.com/ajax/libs/jquery/1.12.0/jquery.min.js`
     - Bootstrap 3.3.6 JS: `https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js`
     - Montserrat font: `https://fonts.googleapis.com/css?family=Montserrat`
   - No local installation of these dependencies is required unless you prefer hosting them.

3. **Verify Assets**:
   - Ensure the following files/folders are present:
     - `_img/logo.jpg`, `_img/front.jpg`, `_img/porto.jpg`, `_img/workin.jpg`
     - `_css/home.css`
     - `fav.ico` (in the root directory)
   - Replace placeholder images with actual files if needed.

4. **Serve the Website**:
   - Use a local server (e.g., Python’s `http.server`):
     ```bash
     python -m http.server 8000
     ```
   - Open `http://localhost:8000` in a browser.

## File Structure
```
full-custom-music-repair/
├── _css/
│   └── home.css           # Custom styles for the website
├── _img/
│   ├── logo.jpg           # Site logo (max-width: 375px)
│   ├── front.jpg          # Storefront image
│   ├── porto.jpg          # Amplifier repair image
│   └── workin.jpg         # Technician at work image
├── index.html             # Main webpage
├── fav.ico                # Favicon
└── README.md              # This file
```

## Usage
- **Development**: Edit `index.html` for content changes and `_css/home.css` for styling. Test changes locally before deploying.
- **SEO**: The site includes meta tags, LocalBusiness schema, and optimized headings. Update keywords in `index.html` as needed.
- **Accessibility**: Ensure all buttons and links have ARIA attributes or descriptive text. Run Lighthouse audits to verify.
- **Deployment**: Host on a server (e.g., Apache, Nginx) at `https://www.fullcustommusic.com`. Ensure `_img` and `_css` folders are accessible.

## Contributing
1. Fork the repository.
2. Create a branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit changes with clear messages:
   ```bash
   git commit -m "Add your description here"
   ```
4. Push to your fork and submit a pull request.

Please ensure:
- No inline styles in HTML (all styles in `home.css`).
- Accessibility compliance (e.g., ARIA labels, sufficient contrast).
- Image files are compressed (<100KB recommended).

## Known Issues
- Ensure all images (`_img/*.jpg`, `fav.ico`) exist to avoid 404 errors.
- Test external CDN links for reliability; consider local hosting if issues arise.
- Check `.bg-3` section for text contrast (currently `#333333` on white).

## License
&copy; 2025 Timothy Eisenacher. All rights reserved.

## Contact
For inquiries, contact Full Custom Music Repair:
- **Email**: info@fullcustommusic.com
- **Phone**: 717-761-0890
- **Address**: 400 Market Street Rear, Lemoyne, PA 17043

For technical issues, open a GitHub issue or contact the repository maintainer.