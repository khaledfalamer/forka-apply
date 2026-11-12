# Forka careers page (apply.forka.com): notes for Claude

Owner: Khaled Alamer, CEO of Forka Collective. Read this before any change.

## Standing rules (Khaled)
- Never change the live page, and never push to main, unless Khaled says "add it" / "go live" for that change.
- No emojis. Forka brand: charcoal / paper / bronze, EB Garamond headings, Inter Tight text, IBM Plex Sans Arabic. Every screen fully in English and Arabic (RTL).
- Plain, warm language. Every candidate gets a reply. Never show salaries or internal names in job ads.
- Before any change or go-live: look at the live design first (header, logo, colours, fonts). If it differs from what the work was built on, change nothing and show Khaled side-by-side screenshots; he decides. Every change keeps the current colours and logo design (Khaled, 12 Nov 2026).

## How it works
- index.html is the public careers page and the booking page (candidates pick their interview or HR-call time). config.js points to the Hiring server (the Apps Script web app in the forka-erp repo, server/Hiring.gs). CNAME is apply.forka.com, served by GitHub Pages.
- Jobs, applications and CVs live in the Hiring Google Sheet and Drive, never in this repo. Anti-spam: a hidden field and one application per person per job per hour.
- A copy of this page also exists at erp.forka.com/apply (forka-erp repo, apply/). Keep the two in step, or tell Khaled when they differ.
- Hiring packs: the JD and job ad are drafted from department scorecards and approved by Khaled in chat before any ad is posted. Applications go to hr@forka.com with the job title in the subject.
