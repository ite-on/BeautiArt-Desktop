# Store Web Pages

These static files form the complete BeautiArt Desktop website:

- `index.html`
- `privacy-policy.html`
- `support.html`
- `store-pages.css`
- `404.html`
- `favicon.png` and `social-card.png`
- `staticwebapp.config.json` for Azure Static Web Apps headers and 404 handling

Before publishing:

1. Reserve the final product name in Partner Center.
2. Confirm the same public support email appears in `PRIVACY.md`, `SUPPORT.md`, `privacy-policy.html`, `support.html`, and `store/store-submission.json`.
3. If the reserved name is not BeautiArt Desktop, update the same four files before hosting.
4. Deploy the complete `store/web/` directory so styles, images, and links resolve.
5. Confirm the home, privacy, and support pages return HTTP `200` over HTTPS without authentication.
6. Put the website URL, policy URLs, and support email in `store/store-submission.json`.
7. Run `scripts/validate-website.ps1 -BaseUrl <public-base-url>`.
8. Run `scripts/validate-store-readiness.ps1`.

The files contain no scripts, cookies, analytics, remote fonts, or third-party page resources.

See `docs/operations/website-deployment.md` for the Azure deployment and URL procedure.
