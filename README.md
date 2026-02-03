# Football Club Starter Kit

A complete starter kit for football club websites using MinimalDocs with the "club" theme.

## Getting Started

1. Copy this folder to your project directory
2. Run `minimaldocs dev` to start the development server
3. Customise the content for your club

## Structure

```
├── docs.json                  # Site configuration
├── index.mdx                  # Homepage
├── teams/
│   ├── first-team.mdx
│   ├── reserves.mdx
│   ├── under-18s.mdx
│   ├── under-16s.mdx
│   ├── academy.mdx
│   ├── womens-first-team.mdx
│   └── womens-reserves.mdx
├── news/
│   ├── index.mdx
│   ├── match-reports.mdx
│   ├── transfers.mdx
│   └── community.mdx
└── club/
    ├── about.mdx
    ├── history.mdx
    ├── stadium.mdx
    ├── contact.mdx
    ├── policies/
    │   ├── safeguarding.mdx
    │   ├── code-of-conduct.mdx
    │   ├── equality.mdx
    │   └── privacy.mdx
    └── documents/
        ├── constitution.mdx
        ├── agm-minutes.mdx
        └── financial-reports.mdx
```

## Customisation

### docs.json

Update the following in `docs.json`:

- `name` — Your club name
- `colors.primary` — Your club's primary colour
- `navbar.links` — Navigation links
- `footer.socials` — Social media links

### Content

Replace the placeholder content with your club's:

- Team information and squad lists
- News and match reports
- Club history and facilities
- Policies and documents

## Theme

This starter uses the "club" theme, designed for sports organisations. Features:

- Bold header with diagonal stripe accents
- Mega-menu dropdown navigation
- Full-width content layout (no sidebar)
- Strong uppercase typography
- Hero-style page headers
- Multi-column rich footer
