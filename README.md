# AdaptiveInteractive.com

Single-page business card website for AdaptiveInteractive.

## Purpose

This site is the initial public web presence for AdaptiveInteractive.com.

It is intentionally minimal:

- No contact information yet
- No blog
- No client portal
- No backend
- No build system
- No framework dependency

## Hosting target

Azure Static Web Apps, free tier.

## Deployment target

GitHub Actions CI/CD to Azure Static Web Apps.

## Local preview in Codespaces

From the Codespaces terminal, run:

```bash
python3 -m http.server 8080
```

Then open the forwarded port when Codespaces prompts you.

Alternatively, open the **Ports** tab, find port `8080`, and click the globe/browser icon.

## Project structure

```text
.
├── index.html
├── styles.css
├── staticwebapp.config.json
└── README.md
```

## To-do later

- Add an Open Graph image for Adaptive Interactive link previews once the visual branding direction is more settled.
- Recommended og:image size should be verified with Copilot when ready to implement.
- Add automated social metadata validation to GitHub Actions after the custom domain is stable.

## Social preview testing

After metadata changes are deployed, test the public site URL with social preview/debugging tools.

Current public Azure Static Web Apps URL:

```text
https://green-island-079b5a81e.7.azurestaticapps.net/
```

Future custom domain URL:

```text
https://adaptiveinteractive.com/
```