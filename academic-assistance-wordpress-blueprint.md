# Premium Academic Assistance WordPress Website Blueprint

## 1. Strategic Positioning

### Brand Role

This website is a professional portfolio, SEO content hub, and lead-generation funnel for an academic assistance brand specializing in PFE, TFE, academic reports, research structure, formatting, methodology guidance, literature review support, APA citations, proofreading, and French/English academic guidance.

The site must not sell services directly, collect payments, create a checkout flow, or encourage academic misconduct. The only commercial conversion path is Fiverr.

### Core Compliance Statement

Use this wording across the homepage, services page, footer, FAQ, contact page, popup, and disclaimer:

> I provide educational guidance, formatting support, research planning, proofreading, citation support, and structure improvement. I do not complete academic work that must be submitted as your own. All orders, payments, and project communication are handled securely through Fiverr.

### Brand Promise

Clear, structured academic support for students who need help organizing, improving, formatting, proofreading, and understanding their academic projects while respecting university rules and academic integrity.

### Main CTA System

Primary CTA:

- Contact Me on Fiverr
- Order Safely via Fiverr
- Discuss Your Project on Fiverr

Secondary CTA:

- View Academic Support Options
- Read Student Guides
- See Portfolio Examples

Avoid:

- Buy now
- Pay here
- Order now outside Fiverr
- We write your thesis
- Guaranteed grade
- Submit-ready assignment
- Plagiarism-free essay writing service

## 2. Policy Guardrails

### Fiverr-Safe Positioning

Fiverr prohibits academic and workplace dishonesty, including services that complete assignments expected to be done independently, such as homework, exams, dissertations, theses, research papers, research proposals, and academic assignments. Therefore, the website must describe services as educational support, guidance, editing, formatting, research planning, citation support, and coaching.

Safe wording:

- Academic assistance
- Research guidance
- Structure support
- Formatting help
- APA citation support
- Methodology coaching
- Literature review guidance
- Proofreading and clarity improvement
- Presentation design support
- French and English academic support

Unsafe wording:

- We write your thesis for you
- We complete your PFE/TFE
- Submit this as your own work
- Guaranteed passing grade
- We do your homework
- Exam completion
- Dissertation writing service
- Research paper writing service

### AdSense-Safe Positioning

Google Publisher Policies prohibit content that enables dishonest behavior, including sale or distribution of term papers, paper-writing, or exam-taking services. To stay AdSense-safe, the blog should be educational, tutorial-based, and integrity-focused.

Safe content themes:

- How to structure a PFE report
- How to cite in APA style
- How to organize a literature review
- How to choose a research methodology
- Common formatting mistakes
- How to prepare for supervisor feedback
- How to improve clarity in academic writing

Unsafe content themes:

- Buy a completed thesis
- Download ready-to-submit PFE
- Hire someone to write your assignment
- How to pass without studying
- Prewritten research paper for submission

### GDPR Basics

The website should collect only necessary lead data, explain why the data is collected, show a GDPR notice near each form, and allow users to request access, correction, or deletion of their data.

Form notice:

> By submitting this form, you agree that your information may be used to respond to your inquiry. Your project details are never sold. For orders, payment, and project communication, you will be redirected to Fiverr.

Recommended retention:

- Contact form leads: 6 to 12 months
- Analytics data: configured according to Google Analytics retention settings
- Newsletter data: only if email marketing is later added, with explicit opt-in

## 3. WordPress Build Architecture

### CMS Stack

- WordPress
- Hello Elementor child theme
- Elementor Pro
- Rank Math SEO
- Fluent Forms Pro or WPForms Pro
- Elementor Popup Builder or Convert Pro
- LiteSpeed Cache if the server supports LiteSpeed, otherwise WP Rocket or FlyingPress
- ShortPixel, Imagify, or EWWW Image Optimizer
- Complianz or CookieYes for cookie consent
- Wordfence Security or Solid Security
- UpdraftPlus or BlogVault for backups
- Site Kit by Google or manual Google Analytics/Search Console integration
- Redirection plugin for 301 management
- Table of Contents plugin or Rank Math TOC block

### Do Not Install

- WooCommerce
- Membership plugins
- LMS checkout plugins
- Cart plugins
- User account plugins
- Direct payment gateways

### Admin Control Areas

The admin should be able to edit:

- Pages
- Blog posts
- Categories
- Tags
- Menus
- Header and footer
- CTA button links
- Elementor global colors
- Elementor global fonts
- Popup form content
- Form submissions
- Portfolio examples
- Testimonial snippets from verified Fiverr reviews
- SEO titles and meta descriptions
- Open Graph images
- Sitemap settings
- Robots.txt
- Cookie notice text

### Recommended Custom Post Types

Optional but useful:

- Portfolio Examples
- Review Highlights
- FAQs

If the owner wants a simpler build, keep everything as normal pages, posts, and Elementor sections.

## 4. Website Map

### Core Pages

- `/` - Home
- `/services/` - Services
- `/portfolio/` - Portfolio
- `/about/` - About
- `/blog/` - Blog
- `/faq/` - FAQ
- `/contact/` - Contact
- `/privacy-policy/` - Privacy Policy
- `/terms-of-use/` - Terms of Use
- `/disclaimer/` - Disclaimer

### Optional SEO Support Pages

- `/services/pfe-assistance/`
- `/services/tfe-assistance/`
- `/services/academic-formatting/`
- `/services/literature-review-guidance/`
- `/services/research-methodology-guidance/`
- `/services/apa-citation-support/`
- `/services/french-academic-support/`
- `/services/english-academic-support/`

These should be guidance-focused landing pages and must still redirect to Fiverr for discussion.

## 5. Navigation Structure

### Header

Left:

- Logo

Center:

- Home
- Services
- Portfolio
- Blog
- FAQ
- About

Right:

- Contact Me on Fiverr

Mobile:

- Hamburger menu
- Sticky bottom CTA: Discuss on Fiverr

### Footer

Columns:

- Brand summary
- Services
- Blog categories
- Policies
- Fiverr CTA

Footer disclaimer:

> This website provides academic support information and portfolio examples only. All paid work, communication, and payment are handled through Fiverr. Services are limited to ethical educational support, formatting, proofreading, citation guidance, research planning, and structure improvement.

## 6. Visual System

### Colors

- White: `#FFFFFF`
- Near black: `#111111`
- Rich black text: `#1A1A1A`
- Soft gray background: `#F7F7F5`
- Border gray: `#E6E2D8`
- Gold accent: `#B8944D`
- Muted gold: `#D8C48A`
- Deep charcoal: `#242424`

### Typography

Recommended Google Fonts:

- Headings: Manrope, Inter, or Plus Jakarta Sans
- Body: Inter, Source Sans 3, or Lato

Suggested sizes:

- Desktop H1: 56 to 68px
- Mobile H1: 34 to 42px
- Section headings: 36 to 44px desktop, 28 to 34px mobile
- Body: 17 to 18px
- Buttons: 15 to 16px, semibold

### UI Style

- White backgrounds
- Soft gray content bands
- Gold accent lines
- Minimal shadows
- 6 to 8px card radius
- Thin borders instead of heavy effects
- Large readable spacing
- Premium editorial academic aesthetic

### Image Direction

Hero image:

- Premium academic workspace
- Laptop
- Research notes
- Neutral desk
- Books or paper documents
- No fake university logos
- No diploma imagery implying credential sales

Blog images:

- Desk research scenes
- Notebooks
- Citation guides
- Study planning
- Abstract academic visuals
- Avoid photos implying exams are being completed for students

## 7. Homepage Architecture And Copy

### Section 1: Hero

Headline:

Professional Academic Assistance for PFE, TFE and Research Projects

Subheadline:

Structured, ethical academic support for students worldwide in French and English, including formatting, research planning, methodology guidance, literature review support, proofreading, and APA citations.

Primary CTA:

Contact Me on Fiverr

Secondary CTA:

Discuss Your Project Safely

Tertiary CTA:

View Support Options

Trust strip:

- Fiverr-managed orders
- Secure Fiverr payment
- French and English support
- APA and academic formatting
- Research structure guidance

Compliance microcopy:

All project discussions, payments, and deliveries are handled through Fiverr. Support is provided for educational guidance, formatting, proofreading, citations, and structure improvement.

### Section 2: Trust And Social Proof

Headline:

Academic Support Built Around Clarity, Structure and Trust

Intro:

Students need more than quick edits. They need organized guidance, clear communication, and a process that helps them understand and improve their work responsibly.

Cards:

- Professional communication
- Clear report structure
- Formatting and citation support
- Revisions handled through Fiverr
- International student experience

Review display rule:

Use only real, verified Fiverr reviews with permission or show anonymized review themes without presenting them as direct testimonials.

Safe testimonial format:

> Review theme from verified Fiverr feedback: clear communication, structured delivery, and helpful formatting support.

Do not fabricate reviewer names, star ratings, universities, countries, or order counts.

### Section 3: Why Choose This Academic Support

Headline:

A Structured Process for Serious Academic Projects

Cards:

Structured academic work:

I help organize reports, sections, headings, tables, citations, and presentation flow so your work becomes easier to review and improve.

Research-based methodology:

Support with research questions, methodology structure, data collection planning, and academic logic.

Professional formatting:

Formatting support for reports, theses, references, page layout, tables of contents, figures, captions, and appendices.

International standards:

Guidance aligned with common academic expectations while respecting your university instructions.

French and English support:

Academic assistance for students working in English, French, or bilingual project contexts.

Secure Fiverr process:

All project communication, order management, revisions, and payment are handled safely through Fiverr.

Timely delivery:

Clear timeline discussion before work begins, with realistic delivery planning through Fiverr.

Revision clarity:

Revision requests are managed through Fiverr according to the agreed scope.

### Section 4: Services Preview

Headline:

Academic Assistance Services

Intro:

Choose the type of support you need, then discuss the project scope directly on Fiverr before placing any order.

Service cards:

PFE Assistance:

Structure planning, formatting guidance, section organization, proofreading, citation support, and presentation preparation for final-year projects.

CTA: Discuss PFE Support on Fiverr

TFE Assistance:

Guidance for organizing your TFE report, improving academic clarity, preparing references, and aligning your structure with supervisor expectations.

CTA: Discuss TFE Support on Fiverr

Research Formatting:

Professional formatting for headings, page layout, table of contents, figures, captions, references, appendices, and academic consistency.

CTA: Discuss Formatting on Fiverr

Literature Review Guidance:

Support organizing sources, themes, research gaps, synthesis structure, and citation logic.

CTA: Discuss Literature Review Support

APA Citation Support:

Help with in-text citations, reference list consistency, APA formatting, source organization, and citation cleanup.

CTA: Discuss APA Support on Fiverr

Academic Proofreading:

Clarity, grammar, readability, academic tone, paragraph flow, and formatting consistency.

CTA: Discuss Proofreading on Fiverr

Methodology Guidance:

Support with methodology structure, research design explanation, sampling logic, tools, and limitations.

CTA: Discuss Methodology on Fiverr

Presentation Support:

Academic slide structure, speaker flow, defense preparation visuals, and clean presentation formatting.

CTA: Discuss Presentation Support

### Section 5: Ethical Academic Support Statement

Headline:

Support That Respects Academic Integrity

Copy:

This service is designed to help students improve organization, formatting, clarity, citations, and research structure. It is not a shortcut for academic misconduct and does not replace your own research, analysis, or responsibility. Every project must follow your institution's academic rules.

CTA:

Ask About Ethical Support on Fiverr

### Section 6: How It Works

Headline:

How the Fiverr Process Works

Steps:

1. Send your project details

Share your academic level, topic, deadline, language, university instructions, and the type of support you need.

2. Discuss requirements on Fiverr

We clarify scope, timeline, deliverables, and revision expectations through Fiverr before any order begins.

3. Receive structured assistance

You receive guidance, formatting, proofreading, citations, or structure support based on the agreed scope.

4. Request revisions if included

Revision requests are handled according to the Fiverr order terms and agreed project scope.

5. Final delivery through Fiverr

All delivery, communication, and payment stay inside Fiverr for a secure and transparent process.

Microcopy:

Payments and communication are handled securely via Fiverr.

### Section 7: Portfolio Preview

Headline:

Portfolio Examples and Academic Support Samples

Copy:

Explore anonymized examples of formatting improvements, structure outlines, citation cleanup, presentation layouts, and report organization. No confidential student work is displayed.

Portfolio card types:

- PFE report structure sample
- TFE formatting before/after sample
- APA citation cleanup sample
- Literature review matrix sample
- Methodology framework sample
- Academic presentation sample

CTA:

View Portfolio

### Section 8: Blog Preview

Headline:

Academic Guides for PFE, TFE and Research Projects

Copy:

Read practical guides on academic writing, report structure, methodology, APA citations, literature review organization, and productivity.

Featured blog blocks:

- How to Structure a PFE Report Step by Step
- TFE Report Formatting Checklist
- APA Citation Mistakes Students Should Avoid

CTA:

Read the Blog

### Section 9: FAQ Preview

Questions:

Is payment secure?

Yes. Paid orders, communication, delivery, and payment are handled through Fiverr.

Do you work internationally?

Yes. Support is available for students in different countries, depending on the project scope, language, and deadline.

What languages do you support?

English and French.

What academic levels do you assist with?

Support may be available for undergraduate, final-year, master's, and professional academic reports, depending on scope and ethical requirements.

Can I request revisions?

Yes, revisions are handled through Fiverr according to the agreed order terms.

What formatting styles are supported?

Common academic formatting styles can be supported, including APA-style citations, university templates, report formatting, tables, figures, and references.

How fast is delivery?

Delivery depends on the scope, number of pages, complexity, and deadline. Timelines are discussed before ordering on Fiverr.

### Section 10: Final CTA

Headline:

Ready to Improve Your Academic Project Structure?

Copy:

Send your project details on Fiverr and receive a clear, professional discussion about the support available for your report, research project, PFE, TFE, or academic formatting needs.

Button:

Discuss Your Project on Fiverr

Microcopy:

No direct checkout on this website. Orders are handled safely through Fiverr.

## 8. Services Page

### Page Title

Academic Assistance Services

### Meta Description

Ethical academic support for PFE, TFE, research formatting, methodology guidance, literature review organization, APA citations, proofreading, and French/English academic projects through Fiverr.

### Hero Copy

Get structured support for academic projects without bypassing your own responsibility as a student. Services focus on formatting, proofreading, citations, research structure, methodology guidance, literature review organization, and presentation support.

CTA:

Contact Me on Fiverr

### Service Sections

PFE Assistance:

- Report structure review
- Section organization
- Formatting support
- Academic tone improvement
- Citation cleanup
- Defense presentation support

TFE Assistance:

- Project structure guidance
- Report formatting
- Clarity and proofreading
- Reference organization
- Methodology section support
- Supervisor feedback organization

Academic Report Formatting:

- Headings
- Table of contents
- Page numbering
- Tables and figures
- Captions
- References
- Appendices
- University template alignment

Literature Review Guidance:

- Source organization
- Theme mapping
- Gap identification
- Synthesis structure
- Citation consistency
- Research matrix creation

Research Methodology Guidance:

- Research design explanation
- Qualitative/quantitative structure
- Sampling logic
- Data collection tool explanation
- Limitations
- Ethical considerations

APA Citation Support:

- In-text citations
- Reference list cleanup
- Formatting consistency
- Missing citation checks
- Source organization

Proofreading:

- Grammar
- Clarity
- Academic tone
- Flow
- Paragraph transitions
- Formatting consistency

Presentation Support:

- Slide structure
- Defense story flow
- Visual hierarchy
- Academic slide cleanup
- Speaker note organization

### Services Page Compliance Box

This website does not accept direct payments or orders. To protect both clients and the seller, all project discussions, scope agreements, payments, delivery, and revisions are completed through Fiverr.

## 9. Portfolio Page

### Page Goal

Show capability without exposing confidential student work or implying completed assignments for submission.

### Portfolio Categories

- Formatting samples
- Structure outlines
- Citation cleanup
- Literature review frameworks
- Methodology frameworks
- Presentation samples

### Portfolio Rules

- Use anonymized mockups
- Remove names, schools, university logos, supervisors, IDs, and private data
- Do not publish complete student assignments
- Do not claim partnerships with universities
- Do not show fake grades or results

### Portfolio Card Template

Title:

PFE Report Formatting Structure

Problem:

The document needed clearer academic hierarchy, consistent headings, organized figures, and clean reference formatting.

Support provided:

Formatting guidance, table of contents cleanup, APA reference organization, and section structure recommendations.

Result:

A clearer, easier-to-review academic document structure.

CTA:

Discuss Similar Support on Fiverr

## 10. About Page

### Page Title

About This Academic Support Brand

### Copy

I help students organize, format, proofread, and improve the structure of academic projects in English and French. My work focuses on clarity, academic presentation, research organization, citation consistency, and responsible educational support.

Academic projects can feel overwhelming when instructions, deadlines, sources, formatting rules, and supervisor feedback all arrive at the same time. This brand exists to make the process more structured and easier to manage.

All paid work is discussed, ordered, delivered, and revised through Fiverr. This keeps the process transparent, secure, and aligned with Fiverr's communication and payment system.

### Values

- Academic integrity
- Clear communication
- Ethical student support
- Professional formatting
- International standards
- Confidentiality
- Practical guidance

CTA:

Contact Me on Fiverr

## 11. Contact Page

### Page Title

Contact Me Through Fiverr

### Copy

For project inquiries, please contact me on Fiverr. Share your project topic, academic level, language, deadline, instructions, and the type of support you need.

No payments are accepted on this website. Fiverr is used for secure communication, payment protection, delivery, and revisions.

### Contact Form Purpose

The onsite form should be used only for initial inquiries or newsletter-style lead capture. The form confirmation should redirect users to Fiverr or show a Fiverr CTA.

### Contact Form Fields

- Full name
- Email
- Educational level
- School or university
- Project topic
- Deadline
- Language
- Type of support needed
- Additional notes
- Consent checkbox

### Post-Submit Message

Thank you. Your inquiry has been received. For faster discussion, secure payment, and order protection, please continue the conversation on Fiverr.

Button:

Continue to Fiverr

## 12. FAQ Page

### Main FAQ Copy

Is payment secure?

Yes. Payments are handled through Fiverr, not this website. Fiverr manages order payment, delivery, and revision workflows.

Do you complete academic work for students?

No. Support is limited to ethical academic assistance such as formatting, proofreading, research planning, methodology guidance, citation cleanup, structure improvement, and educational guidance. Students remain responsible for their own academic work.

Do you support PFE and TFE projects?

Yes. Support may include structure planning, formatting, proofreading, citation organization, methodology guidance, literature review organization, and presentation support.

Do you support French and English?

Yes. Support is available in French and English.

Can I request revisions?

Yes. Revision details depend on the Fiverr order scope and package selected.

Do you guarantee grades?

No. No ethical academic support service can guarantee grades, supervisor approval, or academic outcomes.

Can you follow my university template?

Yes, if you provide the template and instructions through Fiverr.

Can you help with APA citations?

Yes. APA citation support may include in-text citation cleanup, reference list formatting, and citation consistency checks.

How do I start?

Click the Fiverr CTA, send your project details, and discuss the ethical support options available for your project.

## 13. Popup Lead Strategy

### Popup Trigger Rules

- After 8 seconds
- Exit intent
- Scroll depth 50 percent
- Show maximum once every 7 days per user
- Do not show instantly on mobile
- Do not block legal pages

### Popup Design

- White background
- Gold accent border
- Black typography
- Compact two-column desktop layout
- Single-column mobile layout
- Clear X close button
- No aggressive countdown timers

### Popup Title

Need Help With Your PFE or Research Project?

### Popup Subtitle

Share your project details, then continue to Fiverr for secure discussion, payment, delivery, and revisions.

### Fields

- Full name
- Email
- Educational level
- School/University
- Project topic
- Deadline
- Language
- Additional notes
- Consent checkbox

### Buttons

Primary:

Continue to Fiverr

Secondary:

Discuss Project on Fiverr

### GDPR Notice

By submitting this form, you agree that your information may be used to respond to your inquiry. Your details are not sold. Paid orders, communication, and delivery are handled on Fiverr.

### Admin Lead Handling

Use Fluent Forms or WPForms entries:

- Store leads in WordPress dashboard
- Export CSV
- Add spam protection
- Send admin email notification
- Send user confirmation email
- Add reCAPTCHA or Turnstile

## 14. Blog Architecture

### Blog Page Layout

Top:

- Blog hero
- Search bar
- Category filter
- Featured guide

Main:

- 3-column desktop post grid
- 1-column mobile post grid
- Category chips
- Featured image
- Reading time
- Excerpt

Sidebar desktop:

- Fiverr CTA
- Popular guides
- Categories
- Newsletter only if later approved

Single Post Template:

- Breadcrumbs
- Title
- Last updated date
- Author box
- Table of contents
- Article body
- Ethical note
- Related articles
- Fiverr CTA
- FAQ block where relevant

### Categories

- PFE Guide
- TFE Guide
- Research Methodology
- APA Citation
- Academic Writing
- Student Productivity
- Formatting Tutorials
- Literature Review
- Research Tools
- Thesis Structure

### Tags

- PFE structure
- TFE report
- APA 7
- research question
- methodology
- literature review
- report formatting
- academic proofreading
- defense presentation
- French academic writing
- English academic writing

## 15. Article Ideas

### PFE Guide

1. How to Structure a PFE Report Step by Step
2. PFE Introduction: What to Include and What to Avoid
3. PFE Methodology Section: Simple Structure for Students
4. How to Prepare a PFE Defense Presentation
5. Common PFE Formatting Mistakes and How to Fix Them
6. How to Turn Supervisor Feedback Into a Clear Revision Plan

### TFE Guide

1. How to Organize a TFE Report From Introduction to Conclusion
2. TFE Formatting Checklist for Students
3. How to Write a Clear TFE Problem Statement
4. TFE Literature Review Structure Explained
5. How to Prepare Your TFE Before Final Submission Review

### Research Methodology

1. Qualitative vs Quantitative Methodology: Student-Friendly Guide
2. How to Choose the Right Research Methodology
3. How to Explain Sampling in an Academic Report
4. How to Write Research Limitations Clearly
5. How to Align Research Questions With Methodology

### APA Citation

1. APA 7 Citation Basics for Students
2. In-Text Citations vs Reference List: What's the Difference?
3. Common APA Citation Mistakes in Academic Reports
4. How to Format Online Sources in APA Style
5. APA Checklist Before Submitting Your Report

### Academic Writing

1. How to Improve Academic Tone Without Overcomplicating Your Text
2. How to Write Strong Academic Paragraphs
3. How to Make Your Report More Structured and Readable
4. How to Write a Better Conclusion for a Research Project
5. How to Use Transitions in Academic Writing

### Student Productivity

1. How to Plan a Research Project Deadline
2. How to Break a Thesis Into Weekly Tasks
3. How to Organize Sources Without Losing Time
4. How to Prepare for a Meeting With Your Supervisor
5. How to Reduce Stress During Final-Year Projects

### Formatting Tutorials

1. How to Create a Clean Table of Contents
2. How to Format Tables and Figures in an Academic Report
3. How to Organize Appendices
4. How to Format Headings Consistently
5. How to Prepare a Professional Academic Document Layout

### Literature Review

1. What Is a Literature Review?
2. How to Organize Sources by Theme
3. How to Find Research Gaps
4. Literature Review Matrix: How Students Can Use It
5. How to Synthesize Sources Instead of Listing Them

### Research Tools

1. Best Tools for Organizing Academic Sources
2. How to Use Zotero for Citations
3. How to Use Mendeley for Research Organization
4. How to Track Supervisor Feedback
5. How to Create a Research Planning Template

### Thesis Structure

1. Standard Thesis Structure Explained
2. How to Write a Clear Abstract
3. How to Structure Chapter One
4. How to Connect Findings With Research Questions
5. How to Prepare a Thesis Formatting Checklist

## 16. SEO Strategy

### Primary Keyword Clusters

English:

- academic assistance
- PFE assistance
- TFE assistance
- academic report formatting
- research methodology help
- literature review guidance
- APA citation support
- academic proofreading
- thesis formatting support
- research project guidance

French:

- aide PFE
- assistance PFE
- aide TFE
- rapport de stage PFE
- mise en page mémoire
- aide méthodologie recherche
- revue de littérature
- citation APA
- correction académique
- présentation soutenance PFE

### Search Intent Mapping

Informational:

- How to structure a PFE report
- APA citation examples
- Literature review guide
- Methodology section explained

Commercial but policy-safe:

- PFE formatting assistance
- Academic proofreading Fiverr
- APA citation support Fiverr
- Research methodology guidance Fiverr

Navigational:

- Brand name + Fiverr
- Brand name academic support

### Content Rules

Each post should include:

- Clear educational purpose
- Original explanations
- No promises of grades
- No invitation to submit someone else's work
- Internal links to related guides
- CTA to Fiverr for ethical support
- FAQ section when helpful
- Author note with academic integrity statement
- Last updated date

### Suggested URL Structure

Pages:

- `/services/`
- `/portfolio/`
- `/about/`
- `/contact/`

Blog posts:

- `/blog/how-to-structure-pfe-report/`
- `/blog/apa-citation-mistakes/`
- `/blog/research-methodology-guide/`

Categories:

- `/category/pfe-guide/`
- `/category/tfe-guide/`
- `/category/research-methodology/`

Avoid dates in URLs.

## 17. Metadata Examples

### Homepage

SEO title:

Professional Academic Assistance for PFE, TFE and Research Projects

Meta description:

Ethical academic assistance for PFE, TFE, research formatting, methodology guidance, literature review organization, APA citations, proofreading, and French/English support through Fiverr.

### Services Page

SEO title:

Academic Assistance Services for PFE, TFE, Formatting and Research Guidance

Meta description:

Explore ethical academic support services including PFE and TFE guidance, academic formatting, APA citation support, methodology guidance, proofreading, and literature review organization.

### Blog Page

SEO title:

Academic Writing Blog for PFE, TFE, APA and Research Methodology

Meta description:

Student-friendly guides for PFE, TFE, academic writing, APA citations, literature review structure, research methodology, formatting, and productivity.

### Article Example

Title:

How to Structure a PFE Report Step by Step

Meta description:

Learn how to structure a PFE report with clear sections, methodology, literature review, findings, conclusion, formatting tips, and an ethical academic support checklist.

## 18. Internal Linking Strategy

### Homepage Links To

- Services
- Portfolio
- Blog
- FAQ
- Contact/Fiverr

### Services Links To

- Specific service sections
- Blog guides
- Portfolio examples
- Fiverr CTA

### Blog Links To

Every article should include:

- 2 to 4 internal links to related guides
- 1 link to services page
- 1 contextual Fiverr CTA
- 1 link to disclaimer or academic integrity statement when relevant

### Example Internal Links

From "How to Structure a PFE Report":

- Link to Research Methodology Guide
- Link to APA Citation Mistakes
- Link to PFE Formatting Checklist
- Link to Services page
- CTA to Discuss PFE Support on Fiverr

## 19. Technical SEO

### Rank Math Configuration

Enable:

- Titles and meta
- XML sitemap
- Breadcrumbs
- Schema module
- Redirections
- 404 monitor
- Open Graph metadata
- Twitter cards
- Image SEO

Schema:

- Organization schema
- Website schema
- BreadcrumbList schema
- Article schema for blog posts
- FAQPage schema where appropriate

Important note:

FAQPage structured data can still help describe page content, but Google has limited FAQ rich-result visibility mainly to authoritative government and health sites. Do not rely on FAQ schema as a major traffic lever.

Review schema:

Do not add self-serving review or aggregate rating schema for the business homepage or services pages. Display verified Fiverr reviews visually only if accurate and permitted, but avoid marking them up in a way that violates Google's review snippet guidance.

### Sitemap

Include:

- Pages
- Posts
- Categories
- Portfolio if used as public CPT

Exclude:

- Tag archives if thin
- Search results
- Admin pages
- Form confirmation pages
- Thank-you pages if thin

### Robots.txt

Suggested:

```txt
User-agent: *
Disallow: /wp-admin/
Allow: /wp-admin/admin-ajax.php

Sitemap: https://example.com/sitemap_index.xml
```

### Search Console

Setup:

- Verify domain property
- Submit sitemap
- Monitor indexing
- Check Core Web Vitals
- Check enhancements
- Inspect important service pages

### Analytics

Track:

- Fiverr CTA clicks
- Popup submissions
- Contact form submissions
- Scroll depth
- Blog category traffic
- Top converting articles
- Mobile CTA clicks

Use consent-compliant analytics configuration for users where required.

## 20. Structured Data Plan

Homepage:

- Organization
- WebSite

Pages:

- WebPage
- BreadcrumbList

Blog posts:

- Article or BlogPosting
- BreadcrumbList
- FAQPage if a real FAQ exists on the page

FAQ page:

- FAQPage

Do not use:

- Product schema
- Offer schema
- AggregateRating schema unless the implementation fully satisfies Google's review snippet rules and is not self-serving
- Course schema unless there is an actual course

## 21. CTA Strategy

### Global CTA Texts

- Contact Me on Fiverr
- Discuss Your Project on Fiverr
- Order Safely via Fiverr
- Continue on Fiverr
- Ask About Ethical Academic Support
- Discuss Formatting Support
- Discuss PFE Support
- Discuss TFE Support
- Start a Safe Fiverr Conversation

### CTA Placement

Header:

- Contact Me on Fiverr

Hero:

- Contact Me on Fiverr
- View Services

After services:

- Discuss Your Project on Fiverr

Blog sidebar:

- Need help organizing your academic project? Discuss ethical support on Fiverr.

Mobile sticky:

- Fiverr Contact

Exit popup:

- Continue to Fiverr

Footer:

- Order Safely via Fiverr

### CTA Tracking

Use UTM tags:

```txt
https://www.fiverr.com/your-profile?utm_source=website&utm_medium=cta&utm_campaign=homepage_hero
```

Create different UTMs for:

- Header CTA
- Hero CTA
- Blog CTA
- Popup CTA
- Mobile sticky CTA
- Footer CTA

## 22. Conversion Funnel

### Funnel Path

1. Visitor arrives from Google search, social, or direct link
2. Visitor reads homepage, service page, or blog post
3. Trust blocks reassure them about process, ethics, Fiverr protection, and language support
4. Visitor clicks Fiverr CTA or submits popup/contact form
5. Visitor continues to Fiverr for discussion
6. Scope, payment, order, revision, and delivery happen on Fiverr

### Conversion Psychology

Trust:

- Fiverr-managed payment
- Clear process
- Ethical positioning
- No direct checkout
- Transparent revision flow

Clarity:

- Service categories
- How it works
- FAQ
- Portfolio examples

Risk reduction:

- No grade guarantee claims
- No fake partnerships
- No pressure
- No hidden payment system
- Privacy notice

Authority:

- Educational blog
- Formatting examples
- APA tutorials
- Methodology explainers

## 23. Mobile UX Structure

### Mobile Header

- Logo
- Hamburger menu
- Compact Fiverr CTA icon/button

### Mobile Sticky CTA

Bottom sticky bar:

- Discuss on Fiverr

Rules:

- Height under 64px
- Does not cover cookie banner
- Not shown on legal pages if intrusive

### Mobile Homepage Order

1. Hero
2. Trust badges
3. Fiverr CTA
4. Services
5. How it works
6. Ethical support statement
7. Reviews/themes
8. Blog guides
9. FAQ
10. Final CTA

### Mobile Performance

- Use compressed WebP images
- Avoid autoplay video
- Limit animation
- Lazy load below-fold images
- Use system fallback fonts
- Keep Elementor sections lean

## 24. Speed Optimization

### Hosting

Use managed WordPress hosting with:

- PHP 8.2 or newer
- HTTP/2 or HTTP/3
- Server-level caching
- CDN support
- Daily backups
- SSL

### Performance Settings

Enable:

- Page caching
- Browser caching
- CSS minification
- JS deferral where safe
- Critical CSS
- Lazy loading
- WebP conversion
- Database cleanup
- Heartbeat control

Avoid:

- Too many Elementor addons
- Heavy sliders
- Large background videos
- Unoptimized images
- Multiple analytics scripts

### Core Web Vitals Targets

- LCP under 2.5s
- INP under 200ms
- CLS under 0.1
- Mobile PageSpeed target: 80+

## 25. Security Recommendations

### WordPress Security

- Use strong admin password
- Enable 2FA
- Limit login attempts
- Disable XML-RPC if not needed
- Keep plugins updated
- Use reputable plugins only
- Schedule backups
- Use malware scanning
- Use SSL
- Change default admin username
- Restrict file editing from dashboard

### Backup Strategy

- Daily database backup
- Weekly full-site backup
- Offsite storage
- Test restore once after launch

### Form Security

- reCAPTCHA or Cloudflare Turnstile
- Honeypot
- Rate limiting
- Spam keyword filtering
- No file uploads unless necessary

## 26. Legal Pages

### Privacy Policy Must Include

- Who owns the website
- What data is collected
- Why data is collected
- Contact form data
- Analytics/cookies
- Fiverr redirect disclosure
- Data retention
- User rights
- How to request deletion
- Third-party tools
- Cookie policy

### Terms Of Use Must Include

- Website informational purpose
- No direct orders/payments
- Fiverr handles paid work
- No guarantee of academic results
- No misuse of support
- Intellectual property terms
- Limitation of liability
- External links

### Disclaimer Must Include

- Educational support only
- No academic cheating support
- No guarantee of grades
- No university affiliation unless true
- No professional legal/academic institutional advice
- Users remain responsible for following their school policies

## 27. Fiverr-Safe Legal Wording

Use:

> All paid services are provided through Fiverr. This website does not process orders, payments, or deliveries directly.

Use:

> Support is limited to ethical academic assistance such as formatting, proofreading, citation guidance, research planning, and structure improvement.

Use:

> Students are responsible for ensuring that any support they request complies with their institution's academic integrity rules.

Avoid:

> We complete your thesis.

Avoid:

> Guaranteed grade improvement.

Avoid:

> Submit our work as your final project.

## 28. AdSense-Safe Wording

Use:

> Learn how to organize your research report with a clear academic structure.

Use:

> This guide explains citation formatting and source organization for educational purposes.

Use:

> If you need help understanding formatting, citations, or structure, you can discuss ethical support through Fiverr.

Avoid:

> Buy a research paper.

Avoid:

> We write your assignment.

Avoid:

> Ready-made thesis for submission.

Avoid:

> Pass your exam with our service.

## 29. Trust-Building Sections

### Trust Strip

- Secure Fiverr payment
- Ethical academic support
- French and English
- Formatting and citations
- Clear revision process

### Trust Explanation

Every project begins with a clear discussion of scope, deadline, language, instructions, and ethical boundaries. If a request does not fit academic integrity standards, it should be refused or redirected toward guidance-only support.

### Review Section

Use:

- Verified Fiverr review excerpts
- Screenshots only if allowed by Fiverr and privacy-safe
- Anonymized themes
- No fabricated names or ratings

### Confidentiality Section

Copy:

Your project details are treated confidentially. Portfolio examples are anonymized or recreated as sample templates, and no private student work is published without permission.

## 30. Elementor Implementation Plan

### Global Theme Builder

Create:

- Header template
- Footer template
- Blog archive template
- Single post template
- Page template
- 404 template
- Popup template

### Elementor Global Widgets

Create reusable widgets:

- Fiverr CTA button
- Compliance notice
- Trust badges
- Service card
- Testimonial card
- FAQ accordion
- Blog CTA box
- Portfolio card

### Page Settings

Use:

- Full-width canvas only where appropriate
- Standard page width: 1200px
- Section padding desktop: 80 to 120px
- Section padding mobile: 48 to 72px
- Card padding: 28 to 36px

### Motion

Use minimal animation:

- Fade up 10 to 20px
- No excessive parallax
- No heavy sliders

## 31. Launch Checklist

### Before Launch

- Replace all placeholder Fiverr URLs
- Add real logo
- Add real brand name
- Add real contact email for privacy requests
- Add real verified Fiverr review snippets only if allowed
- Configure Rank Math
- Create sitemap
- Submit to Search Console
- Configure analytics events
- Configure cookie banner
- Test forms
- Test mobile sticky CTA
- Test popup triggers
- Compress images
- Check PageSpeed
- Check all legal pages
- Check all Fiverr policy wording

### After Launch

- Publish 10 cornerstone articles
- Interlink all service pages and blog posts
- Track Fiverr CTA clicks
- Review top search queries monthly
- Update articles every 6 months
- Add new portfolio samples quarterly
- Audit plugin updates monthly

## 32. First 10 Cornerstone Articles

1. How to Structure a PFE Report Step by Step
2. How to Structure a TFE Report: Complete Student Guide
3. APA Citation Guide for Academic Reports
4. How to Write a Literature Review Without Losing Structure
5. Research Methodology Guide for Students
6. PFE Formatting Checklist Before Submission Review
7. How to Prepare a PFE Defense Presentation
8. How to Improve Academic Writing Clarity
9. How to Organize Research Sources With Zotero or Mendeley
10. Common Academic Report Formatting Mistakes

## 33. Source Notes For Policy And SEO

Official sources used for guardrails:

- Fiverr Help Center: Academic and workplace dishonesty on Fiverr  
  https://help.fiverr.com/hc/en-us/articles/360020869658-Academic-and-workplace-dishonesty-on-Fiverr
- Google Publisher Policies: dishonest behavior restrictions  
  https://support.google.com/adsense/answer/4533378
- Google AdSense Program policies  
  https://support.google.com/adsense/answer/48182
- Google Search Central SEO Starter Guide  
  https://developers.google.com/search/docs/fundamentals/seo-starter-guide
- Google Search Central structured data gallery  
  https://developers.google.com/search/docs/guides/search-gallery
- Google Search Central Breadcrumb structured data  
  https://developers.google.com/search/docs/appearance/structured-data/breadcrumb
- Google Search Central FAQ rich result changes  
  https://developers.google.com/search/blog/2023/08/howto-faq-changes
- Google Search Central Review snippet structured data guidelines  
  https://developers.google.com/search/docs/appearance/structured-data/review-snippet
- European Commission GDPR principles  
  https://commission.europa.eu/law/law-topic/data-protection/rules-business-and-organisations/principles-gdpr_en
- European Commission GDPR individual rights  
  https://commission.europa.eu/law/law-topic/data-protection/information-individuals_en

Implementation reminder:

These notes are a strategic and technical blueprint, not legal advice. Before launch, the owner should review Fiverr's current rules, Google Publisher Policies, and local privacy requirements.
