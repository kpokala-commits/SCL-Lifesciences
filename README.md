# SCL Lifesciences × Salesforce — The Art of Possible

A single-file, customer-facing interactive executive perspective built for the SCL Lifesciences leadership team.

## Contents
- `index.html` — the full website, HTML/CSS/JS in one file; no JavaScript frameworks, external fonts or image dependencies.

## Content design
- Salesforce-inspired palette: Cloud Blue `#0176d3`, Navy `#032d60`, generous white space, rounded sections, concise editorial headings and pill buttons.
- Uses the locally available Salesforce Sans or an Arial fallback; it does **not** distribute proprietary Salesforce fonts or official logo assets. If the Salesforce account team has approved brand-kit assets, substitute them before external circulation.
- Brand motif in the header is a simple non-official SVG cloud symbol, not the Salesforce trademark artwork. Replace only with a properly approved logo from Salesforce Brand Central.
- Focused story: SCL operating context; three hypothetical opportunities; one editable illustrative reporting scenario; a viewpoint for managing director, business and people leaders; a simple Salesforce technical possibility.
- The site is a static business concept: no data uploaded, no cookies, no API calls or analytics pixels.

## Evidence and caveats
SCL public figures, from SCL's own site: 350 KL manufacturing capacity; 2 manufacturing sites; over 30 years of manufacturing experience. Links are embedded in the website.

Paraphrased themes are based on the Salesforce team's user-provided approved operations conversations, not verbatim customer quotes.

The calculator uses explicit example inputs (12 people × 2 hours/week × 25% less reporting time = 6 team-hours/week, 312 team-hours/52 weeks). These are **not SCL baselines, actual savings, EBITDA effects, ROI or Salesforce performance benchmarks**.

Use case examples are hypotheses, not diagnosed workflow deficiencies. The current ERP is treated as a system of record, not a replacement target. Tableau features, available data, access rights and implementation details remain subject to customer and product validation.

## Deploy
1. Review `index.html` with the Salesforce account team and company brand/legal guidance, especially logo use and any customer references.
2. Use a company-approved commercial static host (for example, your organization's Vercel setup). Do not assume a personal free hosting tier is approved for business use.
3. Upload `index.html` as the entry point, without an extra parent folder; for platforms with repository deployment, put `index.html` at the repository root.
4. Deploy and verify HTTPS, all responsive layouts, working use-case/persona tabs and calculator sliders, and source hyperlinks.
5. The page includes `noindex,nofollow` but that is **not authentication**. Configure access controls if required by company policy.
6. Replace or add any meeting booking URL only after the account team approves it.

## Checks performed
- HTML links, interactive IDs, use-case changes, persona changes, calculator values, source availability and mobile overflow were tested locally with a Chromium headless browser.
