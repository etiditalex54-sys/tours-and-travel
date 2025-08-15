# Tours & Travel Website

A simple static website for a tours and travel company. The site includes pages for Home, About, Tours, and Contact, along with basic styling.

## Structure
- `index.html` - Home page.
- `about.html` - Company information.
- `tours.html` - List of available tours.
- `contact.html` - Contact form for inquiries.
- `styles.css` - Common styles for all pages.

## Usage
Open any of the HTML files in a web browser to view the site. No additional setup is required.

## Deployment

This project includes a GitHub Actions workflow that publishes the site to
GitHub Pages whenever changes are pushed to the `main` branch.

1. Create a repository on GitHub and push this code:

   ```bash
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. In GitHub, ensure Pages is enabled (Settings → Pages) and points to the
   GitHub Actions workflow. The action will deploy and provide a link to the
   live site once it completes.
