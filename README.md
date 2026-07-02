# KCD Kuala Lumpur 2026 Schedule Dashboard

This repository contains a static dashboard for the KCD Kuala Lumpur 2026 schedule.

## Deployment

The site is ready for Vercel static deployment.

### Option 1: Deploy via Vercel CLI

1. Install the Vercel CLI if you don't already have it:
   ```bash
   npm install -g vercel
   ```
2. Log in to Vercel:
   ```bash
   vercel login
   ```
3. Deploy the site from this repo folder:
   ```bash
   vercel
   ```
4. For a production deploy:
   ```bash
   vercel --prod
   ```

### Option 2: Deploy via Vercel dashboard

1. Push this repository to GitHub.
2. Create a new project in the Vercel dashboard.
3. Connect your GitHub repository.
4. Use the default settings — Vercel will detect `index.html` and deploy the static site.

## Files

- `index.html` — main site entrypoint for deployment
- `interactive_schedule_insights_dashboard.html` — original dashboard source file
- `vercel.json` — explicit static deployment configuration

## Local preview

Use Vercel Dev (optional):

```bash
vercel dev
```

## Notes

- The dashboard uses CDN-hosted Tailwind CSS and Material Icons.
- No build step is required for deployment.
