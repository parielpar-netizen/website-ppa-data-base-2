PPA Development — Static version for GitHub + Vercel

DEPLOY:
1. Upload the contents of this folder to a GitHub repository.
2. In Vercel, import that repository.
3. Framework Preset: Other. Build Command: leave empty. Output Directory: leave empty (or ./).
4. Deploy.

IMPORTANT:
- index.html is the static landing page.
- login.html is only a visual demo; it does NOT authenticate users.
- Real login, client/admin dashboards, database, dynamic invoices, and Midtrans payments cannot run as static HTML alone. They need a backend or a hosted backend/database service.
