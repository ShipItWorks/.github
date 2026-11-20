# ShipItWorks

**Software, shown as it really is.**

ShipItWorks is one person, Robert Sweetman. The product I am working on is patchowner. Ten more are paused, each with its score and its list of what is not done.

I score each product in public. Every product gets a score out of 100 on [one published rubric](https://shipitworks.com/how-we-score/). Every product page lists what works today and what is not done yet. Every number names the file it came from.

Site: [shipitworks.com](https://shipitworks.com) · Contact: support@shipitworks.com

## The products

Scores are from each product's scorecard on [shipitworks.com](https://shipitworks.com), each on my own rubric; the Scored column gives the date of each one. Same rubric, same 0-to-100 scale, highest first. Most are not finished; each page says where it stops.

Paused since 18 November 2026, while I finish patchowner. patchowner is the only product I am working on.

| # | Product | Score | Stage | Scored | Status | What it does | Demo |
|---|---------|------:|-------|--------|--------|--------------|------|
| 1 | [patchowner](https://shipitworks.com/patchowner/) | 87 | Release candidate | 2026-11-20 | Working on it | Finds the exploited vulnerabilities from CISA's catalog that match what you run and writes each one up for the person who owns the fix, in plain sentences. Proven 10 of 13 features; 9 items not done; shown with sample data. | [Watch it work](https://shipitworks.com/patchowner/) |
| 2 | [Graphsmith](https://shipitworks.com/graphsmith/) | 82 | Beta | 2026-11-12 | Paused | A design-time environment for graph-based AI and automation workflows. | [transcript](https://shipitworks.com/graphsmith/transcript/) |
| 3 | [AI Consumer Rights](https://shipitworks.com/aiconsumerrights/) | 78 | Beta | 2026-11-12 | Paused | Plain-language help with your rights when AI makes decisions about you. | [video + transcript](https://shipitworks.com/aiconsumerrights/) |
| 4 | [Yield](https://shipitworks.com/yield/) | 70 | Beta | 2026-11-17 | Paused | An agent orchestration platform: its agents do tasks, ask before saving anything, and are designed to stop at the spending cap you set. | [video + transcript](https://shipitworks.com/yield/) |
| 5 | [AI Value](https://shipitworks.com/aivalue/) | 68 | Beta | 2026-11-11 | Paused | Model AI ROI, P&L margins, Balance Sheet cash flow & 30-day adoption pilots. | [transcript](https://shipitworks.com/aivalue/transcript/) |
| 6 | [Plainspoken](https://shipitworks.com/plainspoken/) | 67 | Beta | 2026-11-12 | Paused | You type what you want; it rewrites a prompt an AI understands, then explains changes. | [transcript](https://shipitworks.com/plainspoken/transcript/) |
| 7 | [HomeIoT Guardian](https://shipitworks.com/homeiotguardian/) | 66 | Beta | 2026-11-12 | Paused | Guided checks of your home Wi-Fi settings, a scan for devices that announce themselves, and a checklist to harden each one. | [transcript](https://shipitworks.com/homeiotguardian/transcript/) |
| 8 | [Helmline](https://shipitworks.com/helmline/) | 65 | Beta | 2026-11-16 | Paused | Unified RMM and PSA platform for managed service providers, one multi-tenant schema | [video + transcript](https://shipitworks.com/helmline/) |
| 9 | [ScamShield Companion](https://shipitworks.com/scamshield-companion/) | 65 | Beta | 2026-11-12 | Paused | Offline-first scam-safety app built around Prevent, Protect, Recover; built so analysis runs on the device (offline use not yet tested). | [transcript](https://shipitworks.com/scamshield-companion/transcript/) |
| 10 | [Onegin](https://shipitworks.com/onegin/) | 64 | Beta | 2026-11-12 | Paused | Give your AI coding assistant a map of your code. | [transcript](https://shipitworks.com/onegin/transcript/) |
| 11 | [PocketSec](https://shipitworks.com/pocketsec/) | 56 | Alpha | 2026-11-12 | Paused | Find out how hackable you are. The scan runs in your browser; what leaves the device is not yet traced (the password check sends a 5-character hash prefix to Have I Been Pwned). | [transcript](https://shipitworks.com/pocketsec/transcript/) |

Onegin's repository is still named graph-app.

None of the Android apps is on Google Play yet. Google asks new developer accounts to run a closed test with 12 testers for 14 days first; I have not done that test.

## How the score works

Up to 100 points per product. A point counts only when there is proof: a test run, a build, a screenshot or a video.

| Area | Points |
|------|-------:|
| Core features work end to end | 25 |
| Tests exist and pass | 15 |
| Reproducible build or artifact | 15 |
| Security and privacy | 10 |
| Docs | 10 |
| Accessibility and UX | 10 |
| Distribution readiness | 10 |
| Ops hygiene | 5 |

0-24 pre-alpha · 25-59 alpha · 60-84 beta · 85-99 release candidate · 100 with a stable interface is 1.0. The full rubric and FAQ: [shipitworks.com/how-we-score](https://shipitworks.com/how-we-score/). Every claim and its source: [shipitworks.com/claims](https://shipitworks.com/claims/).

## Who I build for

I build for two kinds of people.

Professionals who already have good tools and will judge mine by the same bar: managed service providers (Helmline), IT and security teams (patchowner), and developers (Yield, Onegin, Graphsmith). I am not aiming for "good for a one-person shop." I am aiming for the standard the category leaders set, and I publish the score so you can see how far I am from it.

And people the industry tends to skip: older users, people on cheap phones, people who read slowly, people who have been scammed before (AI Consumer Rights, Plainspoken, ScamShield Companion, HomeIoT Guardian, PocketSec). Same bar. Accessibility is a scored line on every product, not a promise.

## How I work

- I say only what I can back. Every number names its source.
- I say what is not finished before anyone asks.
- I name people, companies and tools to give credit. If I cannot name them to credit them, I leave the name out.
- I collect as little data as possible. No accounts and no newsletter. Each product page has a waitlist form, and one email reaches me.
- Built with Claude, by Anthropic. Directed, tested and owned by Robert Sweetman in Stoughton, Massachusetts. Demo videos are narrated by an AI voice (ElevenLabs, "Bella") over made-up demo data, and each video says so at the end.

## Repositories

Each product has a public repository here with a README and a CHANGELOG: its score, what works, what is not done yet, what changed, and a demo link. Source code is private for now; a LICENSE will be added when a repository's code opens. Until then the product's page on the site is the source of truth.

## Elsewhere

[shipitworks.com](https://shipitworks.com) · [X @ShipItWorks](https://x.com/ShipItWorks) · Founder: [Robert Sweetman](https://github.com/e-allora)

---

This README was drafted with Claude (Anthropic) from the site's own pages on 2026-11-02 and reviewed by Robert Sweetman. The 2026-11-07 update was made by Claude from the site's pages and has not been reviewed.