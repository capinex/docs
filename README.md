# Capinex Finance — User Guide

Step-by-step documentation for the Capinex Finance app, written for the sales team. No technical jargon, just how-tos.

Built with [Mintlify](https://mintlify.com). Live site: **docs.capinex.in**.

## Editing the docs

```bash
npm i -g mint    # install the CLI (one-off)
mint dev         # local preview at http://localhost:3000
mint validate    # check the build
mint broken-links
```

Pages live as `.mdx` files. Add a new page to `docs.json` so it shows up in the sidebar.

## Structure

```
.
├── docs.json                     # site configuration (theme, navigation)
├── introduction.mdx              # landing page
├── getting-started/              # sign-in, menu tour
├── features/                     # one page per main feature
├── admin/                        # super-admin-only features
└── help/                         # sign-out, troubleshooting
```

## Deploy

Mintlify auto-deploys on push to `main`. Custom domain `docs.capinex.in` is configured in the Mintlify dashboard.
