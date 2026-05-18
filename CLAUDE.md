# Project Memory — Baljeet Singh Saini Resume & Portfolio

## Repository
- **Local path:** `E:\resume\html resume\`
- **GitHub:** `https://github.com/Baljeet-68/baljeet-68.portfolio.io`
- **Live site:** `https://baljeet-68.github.io/baljeet-68.portfolio.io/`
- **Branch mismatch:** local branch is `master`, remote is `main` — always push with `git push origin HEAD:main`

## File Map
| File | Purpose |
|------|---------|
| `index.html` | Main resume (print-ready, A4, formerly baljeet_resume_v2.html) |
| `portfolio.html` | Portfolio site (formerly baljeet-portfolio.html) |
| `Baljeet_Singh_Saini_Resume.pdf` | Downloadable PDF resume (linked from nav) |
| `baljeet_resume_v1.html` | Old resume — preserved, do NOT delete |
| `baljeet-portfolio-old.html` | Old portfolio — preserved, do NOT delete |
| `baljeet_resume_v2.html` | Source v2 resume — preserved |
| `baljeet-portfolio.html` | Source portfolio — preserved |

## Resume (index.html) — Key Design Decisions
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

### Sections in index.html (in order)
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

## Portfolio (portfolio.html) — Key Design Decisions
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

## Personal Details (for resume edits)
- **Name:** Baljeet Singh Saini
- **Email:** Baljeetsaini.68@gmail.com
- **Phone:** +91-7566148768
- **Location:** Indore, MP, India (Open to Remote & Relocation)
- **LinkedIn:** linkedin.com/in/baljeet-singh-saini
- **GitHub:** github.com/Baljeet-68
- **Portfolio:** baljeet-68.github.io
- **Google PM Cert ID:** W8S5SN68E9DB (Sep 2025, Coursera)

## Current Employment
- **MMF Infotech Technologies Pvt. Ltd., Indore** — Sep 2022 – Present
  - TPM & QA Lead: Mar 2023 – Present
  - QA Engineer: Sep 2022 – Feb 2023
  - Key metrics: 40+ products, 10–15 concurrent programs, 95% on-time, teams of 20+, clients US/UK/Canada/Europe/APAC, +20% client satisfaction

## Promotion Timeline — IMPORTANT
- Promoted QA → TPM **within the first year** (not "6 months" — this was corrected across all files)
- Do NOT revert to "within 6 months" in any future edit

## Open Items / Future Work
- `og-preview.png` — OG image for LinkedIn/WhatsApp preview not yet created; add a screenshot of portfolio and commit as `og-preview.png` to repo root
- `robots.txt` — ✅ created at repo root (allows all, references sitemap)
- Google Search Console — ✅ verified & indexing requested; meta tag: `8Qie4N7quKhg61n52eUF1viOC6CJx1Wb21AiYbmhswI`
- Point 55 (resume checklist) — no e-commerce client project added yet (user to provide real project name)
- PSM-1 certification — optional, add to Certifications when completed

## Commit History (recent)
- `160c4e5` — Add resume PDF for portfolio download button
- `06794a8` — Portfolio 22-point overhaul + resume content sync from PDF
- `b04a04d` — Promote v2 resume and new portfolio as main pages
