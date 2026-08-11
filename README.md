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