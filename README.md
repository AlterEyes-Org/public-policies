# public-policies

Public privacy policies and legal notices for AlterEyes NV apps, served by GitHub Pages at
**https://legal.altereyes.site/**.

## Layout

| Path | URL |
|---|---|
| `index.md` | `/` — overview of all policies |
| `zen_garden/privacy/index.md` | `/zen_garden/privacy/` |

## Adding or changing a policy

1. Create `<app>/privacy/index.md` (or `<app>/terms/index.md`, …) starting with front matter:

   ```markdown
   ---
   title: Privacy Policy — <App name>
   ---
   ```

2. Add a link to it in `index.md`.
3. Update the **Last updated** date in the policy itself.
4. Commit and push to `main`. GitHub Pages rebuilds within about a minute.

Never change or remove a published URL: app-store listings link to them.

## Hosting

- GitHub Pages (Jekyll, deploy from `main` / root), repo `AlterEyes-Org/public-policies`.
- Custom domain from `CNAME`; DNS record `CNAME legal → altereyes-org.github.io` in DigitalOcean (altereyes.site).
- Page template: `_layouts/default.html`; logo: `_includes/logo.svg`.
