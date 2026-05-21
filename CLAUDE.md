# Project Memory — Baljeet Singh Saini Resume & Portfolio

## STANDING RULES — Always Follow
- **Push after every task** — every edit, no matter how small, must end with `git add → git commit → git push origin HEAD:main`
- **Branch mismatch** — local branch is `master`, remote is `main` — always push with `git push origin HEAD:main`
- **Update CLAUDE.md** whenever something significant changes (URLs, files, status, open items)

## Repository
- **Local path:** `E:\resume\html resume\`
- **GitHub:** `https://github.com/Baljeet-68/baljeet-68.github.io`
- **Live site:** `https://baljeet-68.github.io/` (user page — repo renamed from baljeet-68.portfolio.io)

## File Map — URL SWAP 2026-05-21
**Files were swapped: portfolio is now the homepage; resume is at `/resume.html`.**

| File | URL | Purpose |
|------|-----|---------|
| `index.html` | `baljeet-68.github.io/` | **Portfolio site (homepage)** — Three.js hero, full marketing page |
| `resume.html` | `baljeet-68.github.io/resume.html` | **Print-ready HTML resume** (A4, two-column orange/cream) |
| `Baljeet_Singh_Saini_Resume.pdf` | `/Baljeet_Singh_Saini_Resume.pdf` | Downloadable PDF resume — must be regenerated from `resume.html` after every resume edit (see PDF Regeneration below) |
| `sitemap.xml` | `/sitemap.xml` | XML sitemap (currently: `/` + `/resume.html`) |
| `robots.txt` | `/robots.txt` | Allows all crawlers, references sitemap |
| `googlec868ea36d97c9bbc.html` | `/googlec868ea36d97c9bbc.html` | Google Search Console HTML verification file |

Legacy files (`baljeet_resume_v1.html`, `baljeet_resume_v2.html`, `baljeet-portfolio.html`, `baljeet-portfolio-old.html`) were DELETED on 2026-05-21 per user request.

## PDF Regeneration — IMPORTANT
After any edit to `resume.html`, regenerate the PDF so the portfolio's Download Resume button serves the latest content. PowerShell (Windows, Chrome):
```powershell
& "C:\Program Files\Google\Chrome\Application\chrome.exe" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf="E:\resume\html resume\Baljeet_Singh_Saini_Resume.pdf" --virtual-time-budget=5000 "file:///E:/resume/html resume/resume.html"
```
Commit the regenerated PDF alongside the resume edit.

## Resume (resume.html) — Key Design Decisions
- **Fonts:** body → Times New Roman, headings → Cambria (system fonts, no Google Fonts import)
- **Line-height:** 1.15 across all content classes (minimum spacing)
- **Professional Summary:** `text-align: justify`
- **Target role:** Technical Project Manager, ₹12–14 LPA, India
- **Identity:** PM-first, not QA-first

### Resume CSS Variables
```css
:root {
  --font-h: 'Cambria', Georgia, serif;
  --font-b: 'Times New Roman', Times, serif;
}
```

### Sections in resume.html (in order)
1. Header / Contact
2. Professional Summary
3. Core Competencies
4. Technical Exposure (Tools / Cloud & Platforms / Tech Stack / QA & Testing / AI & Automation)
5. Professional Experience — MMF Infotech (TPM Mar 2023–Present + QA Sep 2022–Feb 2023) + Infograins (QA Intern)
6. Key Projects Managed (Affirmare, ZUMI, Zenful-Note, Nithasab, Project Tracker Tool)
7. Certifications — Google PM Certificate (Coursera, Sep 2025, ID: W8S5SN68E9DB)
8. Awards & Recognition
9. Earlier Career (Mechanical Engineering) — Mittal Coin / Signet / Kach Motors
10. Education — B.E. Mechanical, Vindhya Institute, 2013–2018
11. Languages

## Portfolio (index.html) — Key Design Decisions
- **Stack:** Three.js hero canvas, Fraunces (display), Outfit (sans), JetBrains Mono
- **Colors:** accent `#C85A00` (warm orange), bg white/cream, ink near-black
- **Features:** Custom cursor, magnetic buttons, scroll reveals, testimonials carousel, preloader

### Skills Categories (current)
1. Core Competencies — Agile/Scrum, SDLC, RAID Management, Vendor Management, Risk Governance, Stakeholder Governance, Shift-Left QA, OKR & KPI
2. Tools — JIRA, Confluence, ClickUp, GitHub Actions, Figma
3. Cloud & Platforms — AWS EC2/S3, Firebase, Shopify
4. Tech Stack (Hands-on) — React.js, Node.js, Flutter, FlutterFlow, MySQL, HTML5, CSS3, JavaScript
5. QA & Testing — Manual, Regression, Smoke/Sanity, UAT, API Testing, Selenium, Cypress
6. AI & Automation — Claude Code, ChatGPT, Gemini, Notion AI

### Nav structure
- Logo | About · Skills · Experience · Projects · Contact | Resume PDF ↓ | Let's Talk
- `Resume PDF ↓` links to `Baljeet_Singh_Saini_Resume.pdf` (download attribute)

### Meta / SEO in index.html (portfolio)
- Title: `Baljeet Singh Saini | Technical Project Manager Portfolio`
- Meta description: "Baljeet Singh Saini — Technical Project Manager with 3+ years in IT delivery..."
- OG tags: og:url → `https://baljeet-68.github.io/`, og:image → `https://baljeet-68.github.io/og-preview.png`
- Google verification tag: `8Qie4N7quKhg61n52eUF1viOC6CJx1Wb21AiYbmhswI`
- Favicon: SVG inline (BS initials, navy `#001f5b` background)

## Personal Details (for resume edits)
- **Name:** Baljeet Singh Saini
- **Email:** Baljeetsaini.68@gmail.com
- **Phone:** +91-7566148768
- **Location:** Indore, MP, India (Open to Remote & Relocation)
- **LinkedIn:** linkedin.com/in/baljeet-singh-saini
- **GitHub:** github.com/Baljeet-68
- **Portfolio:** https://baljeet-68.github.io/
- **Google PM Cert ID:** W8S5SN68E9DB (Sep 2025, Coursera)

## Current Employment
- **MMF Infotech Technologies Pvt. Ltd., Indore** — Sep 2022 – Present
  - TPM & QA Lead: Mar 2023 – Present
  - QA Engineer: Sep 2022 – Feb 2023
  - Key metrics: 40+ products, 10–15 concurrent programs, 95% on-time, teams of 20+, clients US/UK/Canada/Europe/APAC, +20% client satisfaction

## Promotion Timeline — IMPORTANT
- Promoted QA → TPM **within the first year** (not "6 months" — corrected across ALL files)
- Do NOT revert to "within 6 months" in any future edit

## SEO & Discoverability Status
- ✅ Google Search Console verified (HTML tag method)
- ✅ Verification meta tag in index.html + resume.html: `8Qie4N7quKhg61n52eUF1viOC6CJx1Wb21AiYbmhswI`
- ✅ HTML verification file: `googlec868ea36d97c9bbc.html`
- ✅ robots.txt: allows all, sitemap referenced
- ✅ sitemap.xml: 2 URLs (root → portfolio, /resume.html → resume) — resubmit to Google Search Console after URL swap
- ✅ Indexing requested via URL Inspection
- ⏳ Sitemap submission in Search Console — resubmit as `sitemap.xml` after repo rename

## Open Items / Future Work
- `og-preview.png` — OG image not yet created; screenshot portfolio hero, save as `og-preview.png`, commit to repo root
- Point 55 (resume checklist) — no e-commerce client project added; user to provide real project name/details
- PSM-1 certification — optional, add to Certifications when completed
- Sitemap resubmission — delete old `/sitemap.xml` in Search Console, resubmit as `sitemap.xml`

## Resume (resume.html) — Current Font Sizes
| Element | Size |
|---------|------|
| Name heading | 23pt |
| Job title | 10.5pt |
| Section heading | 9.5pt |
| Summary / body text | 9.3pt |
| Bullet list items | 9pt |
| Company / role title | 10pt / 9.5pt |
| Sidebar contact row | 8.8pt |
| Skill tags | 8.5pt |
| Project name | 9.3pt |
| Education inst | 9pt |

## Resume Rebuild — 2026-05-21
Major content overhaul triggered by recruiter-audit. Visual design (orange / two-column / A4) preserved; content surgery applied per `~/.claude/plans/i-want-you-to-floating-twilight.md`:
- New positioning: "Technical Program Manager · International Delivery (US · UK · EU · APAC)" + metric strip (40+ products · 10–15 programs · 95% on-time · +20% CSAT)
- Summary rewritten — leads with metrics, RAID/governance/vendor vocabulary, "within first year" promotion
- All 7 TPM bullets rewritten — every bullet now carries scope + metric/outcome
- Projects (Affirmare / ZUMI / Zenful-Note / Nithasab) rewritten in CAR format with credible scope/timeline metrics (no fabricated user counts)
- Sidebar skills restructured: Program & Delivery Mgmt → PM Tools → Engineering Context (renamed from "Tech Familiarity") → Cloud/DevOps/Release → AI/Automation → QA & Release Governance
- Removed: Personal Projects section, CSM-in-progress line, Languages section, Page 2 Portfolio block with tracker link
- Manufacturing section compressed; Silver Coin / Kaizen / 6-mo increments folded into mfg intro, removed from top Awards
- Page 2 sidebar replaced with Delivery Snapshot metrics block + Online links

## URL Swap + Legacy Cleanup — 2026-05-21
- `portfolio.html` renamed to `index.html` — portfolio is now the homepage at `baljeet-68.github.io/`
- Old `index.html` (resume) renamed to `resume.html` — resume now lives at `baljeet-68.github.io/resume.html`
- Portfolio hero CTA row now has 3 buttons: Download Resume (PDF) · View Resume (HTML) · Let's Talk
- PDF regenerated from updated `resume.html` via headless Chrome
- Legacy files deleted: `baljeet_resume_v1.html`, `baljeet_resume_v2.html`, `baljeet-portfolio.html`, `baljeet-portfolio-old.html`
- sitemap.xml updated; OG urls updated; all internal cross-links updated

## Commit History (recent)
- `<pending>` — Swap URLs (portfolio → /, resume → /resume.html) + regenerate PDF + delete legacy files
- `a20da8a` — Fix portfolio links — root URL serves resume, not portfolio
- `c0c347e` — Portfolio: sync positioning to new resume + prominent Download Resume CTA
- `d51f0a5` — CLAUDE.md: record commit hash for resume rebuild
- `958f1dd` — Resume: brutal-audit rebuild — metric-loaded positioning + CAR projects
- `a51b360` — Resume: increase all font sizes by 1pt
- `991d5e4` — CLAUDE.md: add standing rule — push after every task
- `6b4896a` — Update all URLs after repo rename to baljeet-68.github.io
- `84780e0` — Add sitemap.xml
- `b68ed84` — Add Google Search Console HTML verification file
- `4b8f2c4` — Update Google Search Console verification meta tag
- `160c4e5` — Add resume PDF for portfolio download button
- `06794a8` — Portfolio 22-point overhaul + resume content sync from PDF
