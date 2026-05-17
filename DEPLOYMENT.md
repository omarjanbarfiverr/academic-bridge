# Deployment Guide

## Render Deployment

1. Push this folder to GitHub.
2. Create a new Render Web Service.
3. Select the repository.
4. Use these settings:
   - Runtime: Node
   - Build command: leave empty
   - Start command: `node server.js`
5. Add environment variables:
   - `FIVERR_URL` = your Fiverr profile or gig URL
   - `SITE_URL` = your public website URL, without trailing slash
   - `ACADEMIC_ADMIN_PASSWORD` = your dashboard login password
   - `ACADEMIC_SESSION_SECRET` = random secret for admin session cookies
   - `ACADEMIC_ADMIN_KEY` = private API/export key
6. Deploy.

Your lead form, admin dashboard, and blog CMS will run through the Node backend.

## GitHub Pages Deployment

1. Push the project to GitHub.
2. Go to repository Settings.
3. Open Pages.
4. Deploy from branch.
5. Select the main branch and root folder.

GitHub Pages serves only static files. Forms will not save to `data/leads.json`, and the admin CMS will not work. Use Render for built-in lead capture and article management, or connect the form to a third-party form provider.

## Replace Placeholders

Before launch:

- Replace `https://www.fiverr.com/your-fiverr-username`
- Replace `https://example.com` in `sitemap.xml`, `robots.txt`, and structured data
- Add your real brand name
- Add real Fiverr review snippets only if accurate and permitted
- Add cookie consent if you add analytics or advertising scripts
- Add your real Google AdSense publisher ID to `ads.txt` after AdSense gives you the line
- Publish more original educational articles before applying to AdSense
