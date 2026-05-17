# Academic Bridge Fiverr Funnel Website

Premium static/Node website for an academic assistance brand focused on PFE, TFE, research guidance, formatting, citations, proofreading, and presentation support.

The website is built to redirect all paid communication, ordering, payment, delivery, and revisions to Fiverr. It does not include checkout, cart, user accounts, or direct payment.

## Pages

- `index.html` - high-conversion landing page with lead form
- `services.html` - ethical service descriptions
- `portfolio.html` - anonymized sample portfolio
- `blog.html` - SEO blog hub
- `pfe-report-structure.html` - sample SEO article
- `apa-citation-guide.html` - sample SEO article
- `research-methodology-guide.html` - sample SEO article
- `about.html`
- `contact.html`
- `faq.html`
- `privacy.html`
- `terms.html`
- `disclaimer.html`
- `admin.html` - private dashboard for leads and blog CMS
- `article.html` - dynamic public article page for posts created in admin
- `/blog/article-slug` - server-rendered SEO article URLs on Render
- `cookie-policy.html`, `editorial-policy.html`, `advertising-policy.html`, `accessibility.html` - AdSense trust pages

## Local Run

```bash
npm start
```

Open:

```txt
http://localhost:4173
```

## Configure Fiverr Link

Set your real Fiverr URL in Render:

```txt
FIVERR_URL=https://www.fiverr.com/your-real-username
SITE_URL=https://your-real-domain.com
```

For GitHub Pages, edit `DEFAULT_FIVERR_URL` in `js/main.js`.

## Admin Dashboard

Open:

```txt
http://localhost:4173/admin.html
```

Local default login password:

```txt
local-admin-key
```

On Render, set:

```txt
ACADEMIC_ADMIN_PASSWORD=your-private-password
ACADEMIC_SESSION_SECRET=your-random-secret
ACADEMIC_ADMIN_KEY=your-api-export-key
```

The admin dashboard can:

- View leads
- Update lead status
- Add private lead notes
- Delete leads
- Export leads as CSV
- Create blog articles
- Edit blog articles
- Publish or draft articles
- Delete articles

## Lead Capture And Blog CMS

Render hosting supports the lead form and CMS:

- `POST /api/leads`
- Data is stored in `data/leads.json`
- Admin view: `/admin.html`
- CSV export: `/api/admin/leads.csv`
- Articles are stored in `data/articles.json`
- Public articles appear on `blog.html` and `article.html?slug=...`

Set:

```txt
ACADEMIC_ADMIN_PASSWORD=your-login-password
```

Important: Render free instances may have ephemeral storage. For serious production lead storage, connect a database or form service such as Supabase, Airtable, Google Sheets, or a CRM endpoint.

## GitHub Pages

GitHub Pages can host the static pages, but it cannot save lead data or run the admin CMS because there is no backend. The Fiverr buttons still work. For lead storage on GitHub Pages, connect a third-party form service.

## Policy Positioning

Use ethical language only:

- Formatting support
- Proofreading
- Citation guidance
- Research planning
- Methodology guidance
- Literature review organization
- Structure improvement

Avoid:

- Grade guarantees
- Completing work students must submit as their own
- Exam or assignment completion
- Fake reviews or fake university partnerships
