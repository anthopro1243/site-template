# Mission: Turn a $98 cloud credit into more than $98 of real profit

## Situation (all true)
I'm Anthony, in Dallas, TX (75287). I have $98 of Claude Code cloud session credit that expires November 5, 2026. Every cloud session spends part of it, and it is the entire compute budget for this project. Treat compute as the scarcest resource: no padding, no re-doing work, check PLAN.md and LEDGER.md before starting anything.

Objective: at least $98 in net profit (revenue minus cash spent) by November 5, then keep going. Success is real dollars from real customers, not plans or drafts.

## The business (already decided — don't re-brainstorm it)
One-page websites for Dallas small businesses (restaurants, barbershops, salons, auto shops) that have no website or a bad one. I find prospects while driving for DoorDash, you build a demo site from public info, I pitch it in person. Offer: $199 flat + domain at cost, optional $15/month for hosting and updates.
- Cash available beyond the credit: [FILL IN]
- Hours per week: [FILL IN]

## How we work
- You build; I review, approve, pitch, and handle all money and accounts.
- You never send messages, create accounts, spend money, or publish anything publicly. Mark anything I need to do as "ACTION FOR ANTHONY" with exact steps.
- PLAN.md: current status, prospect pipeline, next 3 actions.
- LEDGER.md: every dollar spent/earned with dates, plus a one-line note per session of what was built.

## Rules
- Legal and honest only: no fake reviews, no misleading claims, no implying a demo is a business's official site.
- If unsure whether something is allowed, say so and stop.
- Be honest about quality and odds. Never report progress that didn't happen.

## Builder mode
This repo is a reusable one-page website template.
- All business-specific content lives in /data/business.json (name, category, address, phone, hours, services/menu with prices, photos, colors). The page renders entirely from that file, so a new client = new JSON, nothing else.
- Static site only (HTML/CSS/JS or Astro), no backend, no paid dependencies.
- Mobile-first: big click-to-call button, tap-to-open Google Maps directions, hours with an "open now" indicator.
- Target 90+ Lighthouse performance and accessibility.
- Demo builds show a footer banner "Demo prepared for [Business] — not their official site" and include <meta name="robots" content="noindex">. Both are removed only after a client pays.
- Include basic local SEO: title, meta description, LocalBusiness schema.org JSON-LD.
