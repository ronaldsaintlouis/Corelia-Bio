# Corelia Bio — Netlify-ready website

This package contains a single-file static website for Corelia Bio.

## Files
- `index.html` — main landing page

## Fastest publish path on Netlify
1. Log into Netlify.
2. Open **Netlify Drop** or create a new project.
3. Drag the whole folder or the `index.html` file into Netlify.
4. Your site will be published instantly on a Netlify subdomain.

## Git-based deployment later
If you want continuous deployment:
1. Put this folder into a GitHub repository.
2. In Netlify, choose **Add new project** > import from Git.
3. Since this is a static site, you typically do not need a build command.
4. Publish directory can remain the project root.

## Contact form
The contact form is set up for Netlify Forms using static HTML attributes.
After the first deploy, verify form detection in the Netlify dashboard.

## Custom domain
When connecting a custom domain, make sure your DNS records point correctly to Netlify before SSL can be issued.
