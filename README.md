# BasementGhost Media — Website

Official website for **BasementGhost Media**, an AI automation & digital growth studio founded by Rafael Rosario.

🔗 **Live site:** [basementghost.com](https://basementghost.com)

## About BasementGhost Media

BasementGhost Media helps businesses uncover where AI can save time, cut busywork, and improve day-to-day operations. We build the automations, AI agents, and content systems that let teams work smarter — combining strategy, hands-on implementation, and ongoing support.

**What we offer:**
- **AI Audits & Strategy Sessions** — clarity on where AI can help your business
- **Automation Sprints** — building or improving one focused workflow (lead intake, CRM, reporting, content repurposing, etc.)
- **AI Content Systems** — repeatable systems for creating and publishing content with AI support
- **Custom AI Builds** — agents, internal tools, multi-step automations, integrations
- **Ongoing AI Ops Support** — continued optimization, maintenance, and team support
- **AI Workshops** — team training on ChatGPT, Claude, and practical AI adoption
- **Free Assessments** — no-cost Security and AI Readiness evaluations for businesses and organizations

Founded by **Rafael Rosario**, BasementGhost Media also publishes writing on AI, automation, and the future of work on [Substack](https://rrosariothethird.substack.com).

## Site structure

| File | Description |
|---|---|
| `index.html` | Homepage — hero, services, showcase, pricing, assessments, contact |
| `workshops.html` | AI Workshops menu (Intro to AI, OpenAI in Depth, Claude in Depth) |
| `insights.html` | Blog / Substack post roundup |
| `privacy.html` | Privacy Policy |
| `accessibility.html` | Accessibility Statement |

## Tech

Single self-contained static HTML files — no build step, no dependencies to install. Fonts (Space Grotesk, DM Serif Display) load from Google Fonts via CDN link. The contact form submits to a Google Sheet ("Website Contacts") via a Google Apps Script web app endpoint.

## Deployment

Hosted as a static site (GitHub Pages, currently mapped to a custom domain via GoDaddy DNS). To update: replace the relevant `.html` file(s) in this repo and commit — no build or deploy step required.

## Contact

📧 info@basementghost.com
