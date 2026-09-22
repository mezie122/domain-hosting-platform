# Domainly — domain & hosting marketplace

A polished frontend MVP for buying domains and hosting plans. This version runs as a static site with mock availability, cart state, and dashboard data stored in localStorage.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Included in this MVP

- Responsive landing page
- Domain search with mock availability results
- Hosting plans and billing toggle
- Cart drawer with domain and hosting items
- Simulated checkout flow
- Customer dashboard preview
- Mobile navigation
- LocalStorage cart persistence

## Production next steps

Connect the search and checkout actions to a real registrar API, Stripe Checkout, authentication, and hosting provisioning service. Never put provider credentials in browser code.
