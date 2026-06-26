# Firm Brief — Plan Simple

*Source of truth for the website build. Claude reads this at the start of every session.*

---

## The Firm

**Name:** Plan Simple
**Tagline:** Estate planning for busy people who don't want to think about death.
**Location:** Bethesda, Maryland
**Practice Areas:** Wills, Revocable Living Trusts, Powers of Attorney (financial + healthcare), Advance Directives, Guardianship Designations
**Out of scope (referred out):** Complex tax planning, Medicaid planning, business succession, high-net-worth estate tax work
**Bar admissions:** Maryland (primary focus), DC, New York

---

## The Attorney

**Carolyn Elefant** — Founder
- Cornell Law School graduate
- Former FERC attorney-advisor
- Associate at two national law firms
- Founded Law Offices of Carolyn Elefant in 1993 (energy/regulatory practice)
- Founder of MyShingle.com (2002) — longest-running blog on solo/small firm practice
- Author: "Solo by Choice" (ABA)
- SuperLawyer, Energy & Natural Resources (DC), since 2012
- 2023 American Legal Technology Lifetime Achievement Award
- Guest lecturer: Harvard Law, GWU Law, University of Maryland Law
- Argued before the United States Supreme Court
- Known for: plain-English writing, practical advice, early tech adoption, making law accessible

**What to use from her background on the site:**
- Credentialed enough to charge $10K. Chooses not to.
- 30+ years building a solo firm = she IS the busy professional this firm serves
- Known writer and communicator — her voice is warm, direct, no-jargon
- Do NOT lead with energy law credentials. Use the narrative: "I've spent decades helping lawyers build efficient practices. Now I'm applying that to estate planning — so you get attorney-quality work without the big-firm price."

---

## The Clients

**Ideal client:** 35–55 years old, $80K–$300K income, married with 1–2 kids, owns a home in Maryland. College-educated professional (healthcare, tech, government, small business owner). Has been meaning to do this for years. Keeps putting it off.

**Primary trigger events:**
1. New baby / becoming a parent (highest conversion)
2. Death of a parent or close call
3. Turning 40
4. Buying a home
5. Getting married / remarried (blended family)

**What they're afraid of:**
- Thinking about death (the biggest barrier — reframe everything as "protecting your family")
- Paying $5,000+ for something they don't understand
- Getting talked into complexity they don't need
- Wasting a Saturday on a lawyer who bills by the hour
- Forms that won't hold up

**Why they choose an attorney over DIY (LegalZoom, Trust & Will):**
- State-specific compliance (Maryland has specific execution requirements)
- Personalized guidance on guardianship, blended families, beneficiary designations
- Peace of mind that it's done right
- Someone to call when life changes

**How clients find the firm:** Local search ("estate planning attorney Bethesda"), referrals from financial advisors / real estate agents / OB-GYNs, word of mouth

---

## Service Packages (Flat Fees)

| Package | What's Included | Price |
|---------|----------------|-------|
| **The Essentials** | Will (individual or mirror wills for couples) + Financial POA + Healthcare POA + Advance Directive | $800 individual / $1,200 couple |
| **The Family Plan** | Everything in Essentials (couple) + Guardianship designations for minor children + Personal property memorandum | $1,800 |
| **The Trust Package** | Revocable living trust + Pour-over wills (x2) + Financial POA (x2) + Healthcare POA + Advance Directive (x2) + Trust funding checklist | $2,800 |
| **Document Update** | Review + redraft one existing document | $300–$500 |

**Positioning:** The gap between $200 DIY (risky) and $5,000 traditional attorney (overkill). Attorney-quality, flat-fee, fast.

---

## Positioning & Differentiators

1. **Flat fees always** — no hourly surprises, no meter running
2. **Straightforward estates only** — no upselling into complexity you don't need
3. **Fast** — done in 48 hours
4. **Credentialed but accessible** — Cornell/FERC/Supreme Court background means overqualified for cookie-cutter work; she does it anyway because it matters
5. **Founder who gets it** — 30 years as a solo attorney = she knows exactly what busy professionals need and don't need

**Tone:** Warm, direct, plain-English. Slightly irreverent about the death-avoidance thing. Not preachy. Not fear-based. More like a knowledgeable friend than a formal law firm.

---

## Design Direction

**Feel:** Modern, colorful, credible. Not the navy-and-gold stuffy law firm. Not the sterile white clinical look. Think: confident, approachable, a little bold.
**Colors:** To be developed — avoid traditional law firm navy/gold. Consider warm but professional palette (deep teal, warm coral, clean off-white, or similar).
**Headshots:** TBD — Carolyn has existing professional photos from other contexts
**References:** TBD

---

## SEO & AEO Requirements

**Must-have schema:** LegalService, Attorney (Person), FAQPage, LocalBusiness
**Local SEO:** Target Bethesda, Montgomery County, greater Maryland
**Content pillars:**
- "What happens if you die without a will in Maryland"
- "Do I need a living trust or just a will?"
- "How much does estate planning cost in Maryland?"
- "Estate planning for new parents"
- "Simple estate plan checklist"

**AI engine optimization:** Structured FAQ content, cite authoritative sources, E-E-A-T signals (bar admissions, credentials, years in practice), clean schema on every page

**Keywords to own:** "affordable estate planning Maryland," "estate planning attorney Bethesda," "simple will and trust Maryland," "flat fee estate planning Maryland"

---

## Copy Principles (StoryBrand)

- The CLIENT is the hero — not the firm
- Lead with their problem: "You've been meaning to do this for years."
- Position Plan Simple as the guide with a clear, simple plan
- Every section moves the visitor toward booking a call
- Reframe death as protection: "This isn't about dying. It's about making sure the people you love are taken care of."
- Counter the procrastination directly — name it, normalize it, remove the excuse

---

## Security & Compliance

- HTTP security headers in vercel.json
- All API keys in Vercel environment variables only
- .env files in .gitignore
- Server-side form validation
- Honeypot spam protection on contact form
- ABA Formal Opinion 477R: attorney-client confidentiality applies to pre-engagement contact form submissions
- Attorney-client disclaimer on contact form, footer, every blog post, every practice area page

---

## Pages to Build

1. **Home** — hero, problem, packages, social proof, CTA
2. **Services** — overview page linking to each package
3. **/services/wills** — wills practice area
4. **/services/trusts** — revocable living trusts
5. **/services/powers-of-attorney** — financial + healthcare POA
6. **/services/advance-directives** — living will / advance directive
7. **/services/family-plan** — the Family Plan package page
8. **About** — Carolyn's bio, reframed for this practice
9. **Blog** — SEO/AEO content hub
10. **Contact** — booking / inquiry form
11. **FAQ** — schema-optimized answers to common objections
