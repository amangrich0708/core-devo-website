# CORE Devo website

Official CORE Devo site built with React, Vite and React Router.

## Pages
- `/` Home
- `/about` About
- `/program` Program
- `/schedule` Schedule
- `/sponsors` Sponsors
- `/contact` Contact

## Deploy on Vercel
1. Upload the **contents of this folder** to your GitHub repository `core-devo-website` (do not upload this ZIP itself).
2. In Vercel select Add New > Project and import the GitHub repository.
3. Choose the **Vite** framework preset if prompted. Build command: `npm run build`; output directory: `dist`. Click Deploy.
4. Under Project > Settings > Domains, add `www.coredevo.org` and `coredevo.org`. Copy the exact DNS entries provided by Vercel into GoDaddy.
5. Configure `www.coredevo.org` as the primary domain and redirect `coredevo.org` to `www`.

## Important before publicly sharing
- Contact information is intentionally a placeholder until you provide a real team email.
- The Schedule page is a placeholder rather than an invented calendar.
- Add actual sponsor logos only after sponsors have confirmed participation.
- Review team text and images and confirm permission before posting photos of minors.

## To run locally (optional)
`npm install` then `npm run dev`.
