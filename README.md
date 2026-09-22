# Domainly — domain & hosting marketplace

A polished frontend MVP for buying domains and hosting plans.

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static server:

```bash
python3 -m http.server 8080
```

Then visit http://localhost:8080.

## Included in this MVP

- Responsive marketing website and domain search with mock availability results
- Hosting plans with monthly/yearly pricing
- Cart with localStorage persistence
- Sign-up and login experience at `auth.html`
- Customer dashboard at `dashboard.html` with domains, hosting, billing, and activity views
- Demo account flow that stores profile information in localStorage
- Mobile responsive layouts

## Production next steps

Connect the search and checkout actions to a real registrar API, Stripe Checkout, authentication, and hosting provisioning service. Never put provider credentials in browser code.
