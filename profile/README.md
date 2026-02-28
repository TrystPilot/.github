<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Trystpilot&fontSize=72&fontColor=fff&animation=twinkling&fontAlignY=38&desc=Anonymous+Relationship+Review+Directory&descAlignY=58&descSize=18" width="100%" />

<br/>

> **Think Trustpilot — for the people you've dated.**
>
> Anonymous. Structured. Moderated.

<br/>

</div>

---

## What We're Building

**Trystpilot** is a structured reputation index for past romantic partners — letting people share and research anonymous experiences across six relationship dimensions, identified only by first name, last initial, and city. Never a full name. Never contact info. Never exposed.

We believe accountability and privacy aren't opposites. Trystpilot is built to hold both.

---

## How It Works

Reviews are anonymous, structured, and moderated before publication. Every profile is identified by **first name + last initial + city** — a soft fingerprint that enables meaningful lookup without enabling targeted harassment.

**The six rating dimensions:**

| Dimension | Weight |
|---|---|
| Overall | 35% |
| Communication | 20% |
| Trustworthiness | 20% |
| Emotional Availability | 15% |
| Compatibility | 10% |
| Respect | — (display only, weight pending) |

Scores apply **recency decay** — fresh reviews carry more signal than old ones.

---

## Built With

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Upstash_Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

</div>

---

## Moderation & Safety

Trystpilot applies aggressive automatic filtering before anything reaches a human reviewer:

- Full names, addresses, phone numbers, and social handles are **blocked at submission**
- Explicit content, threats, harassment, and coercion language are **quarantined**
- Any person can request profile removal at any time via `/legal/removal`
- Zip codes are used only for internal deduplication — **never displayed**

High-risk content goes to a human moderation queue. Nothing gets published automatically without clearing the filter pipeline.

---

## Privacy Principles

```
No real names in full       →  Profiles show "Alex M., Chicago" — nothing more
No contact information      →  No phone, email, handles, or addresses. Ever.
Removal on request          →  Any individual can request removal, no hoops
Anonymous reviewers         →  Hash-based fingerprinting, no accounts required
```

---

## Current Status

Phase 1 is actively in development. Core infrastructure — database schema, text filtering, reputation scoring, review + profile APIs, and legal pages — is complete. Live search, real-time feeds, and self-serve profile creation are coming in Phase 2.

See the roadmap in our main repository for the full phased build-out and triage items.

---

## Legal

Trystpilot's legal framework covers Terms of Service, Community Guidelines, Content Policy, DMCA, Removal Requests, and Law Enforcement guidance. Public launch requires attorney sign-off on defamation and right-to-privacy exposure across target jurisdictions — this is a hard prerequisite, not an afterthought.

---

<div align="center">

**[Visit trystpilot.xyz](https://trystpilot.xyz)**

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer" width="100%" />

*© 2025 Trystpilot. All rights reserved.*

</div>
