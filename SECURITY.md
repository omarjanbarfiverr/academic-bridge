# Security Notes

This project is a lightweight static/Node website with a lead-capture endpoint for Render hosting.

## Production Checklist

- Set a strong `ACADEMIC_ADMIN_KEY` environment variable.
- Set a strong `ACADEMIC_ADMIN_PASSWORD` environment variable.
- Set a random `ACADEMIC_SESSION_SECRET` environment variable.
- Set the real `FIVERR_URL` environment variable.
- Use HTTPS on the production domain.
- Do not publish the admin key.
- Export and clear old leads regularly.
- Add spam protection before high-traffic campaigns.
- Use a persistent database or trusted form provider for serious production lead storage.
- Add cookie consent before enabling analytics, retargeting, or AdSense.

## Lead Data

The built-in backend stores inquiries in `data/leads.json`. This is useful for demos and small Render deployments, but a production business should use persistent storage such as Supabase, Airtable, Google Sheets, or a CRM.

## No Payments

This website must not collect payment details. All paid communication, payment, delivery, and revisions should happen through Fiverr.
