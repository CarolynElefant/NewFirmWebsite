# Plan Simple — Website Project

This project is building a law firm website for Plan Simple, an estate planning firm in Bethesda, Maryland. The attorney is Carolyn Elefant — Cornell Law, 30+ years solo practice, non-coder. Treat every technical concept as if explaining it for the first time.

---

## Always Read Before Starting Work

- `.planning/FIRM_BRIEF.md` — firm profile, clients, packages, copy principles, SEO requirements

---

## How to Communicate

- Explain what every command does before running it
- When errors occur, explain in plain English first
- One concept at a time
- Never assume coding knowledge

---

## Tech Stack

- **Astro** — builds the site
- **Tailwind CSS** — styles it
- **GitHub** — version control
- **Vercel** — hosting and deployment

Do not suggest alternatives.

---

## Copy Rules

- StoryBrand: client is the hero, Plan Simple is the guide
- Reframe death as protection: "make sure the people you love are taken care of"
- Name and normalize procrastination — then remove the excuse
- Flat fees always front-and-center
- Warm, direct, plain-English — slightly irreverent, never preachy

---

## Non-Negotiables

- Attorney-client disclaimer: contact form, footer, every blog post, every practice area page
- Each service on its own URL (/services/wills, /services/trusts, etc.)
- Every blog post attributed to Carolyn Elefant
- JSON-LD structured data on every page (LegalService, Attorney, FAQPage as appropriate)
- No image over 200KB committed to the repo
- Schema: LegalService + Attorney + FAQPage + LocalBusiness

## Security (dedicated phase required)

- HTTP security headers in vercel.json
- API keys in Vercel env vars only — never in source code
- .env in .gitignore
- Server-side form validation
- Honeypot on contact form
- ABA 477R compliance on contact form data handling
