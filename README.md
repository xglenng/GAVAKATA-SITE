# Gavakata Software Website

A responsive, single-page marketing website for Gavakata Software LLC.

## Project structure

- `index.html` — complete website, styles, content, and favicon
- `.gitignore` — excludes common local and operating-system files

No framework, package manager, build step, or environment variables are required.

## Preview locally

You can open `index.html` directly in a browser, or run a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Upload to GitHub

1. Create a new empty GitHub repository.
2. Extract this ZIP.
3. Upload `index.html`, `README.md`, and `.gitignore` to the repository root.
4. Commit the files to the `main` branch.

## Publish with GitHub Pages

1. Open the repository's **Settings**.
2. Select **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait for GitHub to provide the public URL.

## Before public launch

- Purchase and connect the final business domain.
- Activate `garrett@gavakatasoftware.com` or replace it in `index.html`.
- Replace the email-based call-to-action with the final booking link.
- Review pricing, service descriptions, and legal footer text.


## Support and policy pages

- `/support/` — customer support, billing questions, and studio transaction guidance
- `/privacy/` — privacy policy for the website and Maia
- `/terms/` — software and website terms, including monthly subscriptions

All pages use directory `index.html` files for GitHub Pages compatibility and share footer navigation. Preview with the static server above. No dependencies or build step are required.

Before publishing, the business owner should review the policy text against actual operations, confirm the existing public support mailbox is monitored, confirm cancellation/refund handling and provider/data-retention practices, and obtain legal review as appropriate. The policy date is October 26, 2026; update it when adopting revisions. No subscription prices, guaranteed support response times, or new support mailboxes are invented. Publishing these pages does not configure Stripe or activate subscriptions.

The Pages workflow deploys automatically on pushes to `main`. Review locally before committing/pushing. After deployment, verify all three URLs publicly before entering them in Stripe.
