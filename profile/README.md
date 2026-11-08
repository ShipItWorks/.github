# ShipItWorks

**Software, shown as it really is.**

ShipItWorks builds desktop, web and Android apps and scores each one in public. Every product gets a score out of 100 on [one published rubric](https://shipitworks.com/how-we-score/). Every product page lists what works today and what is not done yet. Every number names the file it came from.

Site: [shipitworks.com](https://shipitworks.com) · Contact: support@shipitworks.com

## The products

Scores as on [shipitworks.com](https://shipitworks.com) on 2026-11-07, each on our own rubric; no score moved in this update, and each product page gives its scored date. Same rubric, same 0-to-100 scale, highest first. Most are not finished; each page says where it stops.

| # | Product | Score | Stage | What it does | Demo |
|---|---------|------:|-------|--------------|------|
| 1 | [patchowner](https://shipitworks.com/patchowner/) | 83 | Beta | Turns the CISA KEV catalog into vulnerability notices routed to the owner of an affected item. Built, tested with sample data on a sample inventory; relevance is not measured and it has not been tried on a real inventory. | [video + transcript](https://shipitworks.com/patchowner/) |
| 2 | [AI Consumer Rights](https://shipitworks.com/aiconsumerrights/) | 80 | Beta | Plain-language help with your rights when AI makes decisions about you. | [video + transcript](https://shipitworks.com/aiconsumerrights/) |
| 3 | [Helmline](https://shipitworks.com/helmline/) | 78 | Beta | Unified RMM and PSA platform for managed service providers, one multi-tenant schema. | [video + transcript](https://shipitworks.com/helmline/) |
| 4 | [Yield](https://shipitworks.com/yield/) | 76 | Beta | A helper that does tasks, asks before saving anything, and never overspends your cap. | [video + transcript](https://shipitworks.com/yield/) |
| 5 | [Plainspoken](https://shipitworks.com/apps/#plainspoken) | 75 | Beta | You type what you want; it rewrites a prompt an AI understands, then explains the changes. | [transcript](https://shipitworks.com/plainspoken/transcript/) |
| 6 | [HomeIoT Guardian](https://shipitworks.com/apps/#HomeIoTGuardian) | 73 | Beta | Audit home Wi-Fi security, discover smart devices, harden your connected home. | [transcript](https://shipitworks.com/homeiotguardian/transcript/) |
| 7 | [AI Value](https://shipitworks.com/apps/#aivalue) | 72 | Beta | Model AI ROI, P&L margins, balance-sheet cash flow and 30-day adoption pilots. | [transcript](https://shipitworks.com/aivalue/transcript/) |
| 8 | [ScamShield Companion](https://shipitworks.com/apps/#scamshield-companion) | 71 | Beta | Offline-first scam-safety app built around Prevent, Protect, Recover; built so analysis runs on the device (offline use not yet tested). | [transcript](https://shipitworks.com/scamshield-companion/transcript/) |
| 9 | [graph-app](https://shipitworks.com/apps/#graph-app) | 67 | Beta | Give your AI coding assistant a map of your code. | [transcript](https://shipitworks.com/graph-app/transcript/) |
| 10 | [Graphsmith](https://shipitworks.com/apps/#graphsmith) | 67 | Beta | A design-time environment for graph-based AI and automation workflows. | [transcript](https://shipitworks.com/graphsmith/transcript/) |
| 11 | [PocketSec](https://shipitworks.com/apps/#pocketsec) | 63 | Beta | Find out how hackable you are in 60 seconds. The scan runs in your browser. | [transcript](https://shipitworks.com/pocketsec/transcript/) |

None of the Android apps is on Google Play yet. Google asks new developer accounts to run a closed test with 12 testers for 14 days first; we have not done that test.

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

## Who we build for

We build for two kinds of people.

Professionals who already have good tools and will judge ours by the same bar: managed service providers (Helmline), IT and security teams (patchowner), and developers (Yield, graph-app, Graphsmith). We're not aiming for "good for a one-person shop." We're aiming for the standard the category leaders set, and we publish the score so you can see how far we are from it.

And people the industry tends to skip: older users, people on cheap phones, people who read slowly, people who have been scammed before (AI Consumer Rights, Plainspoken, ScamShield Companion, HomeIoT Guardian, PocketSec). Same bar. Accessibility is a scored line on every product, not a promise.

## How we work

- Say only what we can back. Every number names its source.
- Say what is not finished before anyone asks.
- Name people, companies and tools to give credit. If we cannot name them to credit them, we leave the name out.
- Collect as little data as possible. No forms, no accounts, no newsletter; one email reaches us.
- We use AI and say so. Claude (by Anthropic) helps write the code and wrote the site. Demo videos are narrated by an AI voice (ElevenLabs, "Alice") over made-up demo data, and each video says so at the end.

## Repositories

Each product has a public repository here with a README and a CHANGELOG: its score, what works, what is not done yet, what changed, and a demo link. Source code is private for now; a LICENSE will be added when a repository's code opens. Until then the product's page on the site is the source of truth.

## Latest changes (2026-11-07)

Dated lines for each product are on its page under "What changed" and in its repository's CHANGELOG. Merged to a default branch this round: Yield, Helmline, AI Consumer Rights, HomeIoT Guardian, ScamShield Companion, AI Value, PocketSec, graph-app and Graphsmith. patchowner and Plainspoken had nothing merged. Release tags now exist on each private repository's default branch.

## Elsewhere

[shipitworks.com](https://shipitworks.com) · [X @ShipItWorks](https://x.com/ShipItWorks) · Founder: [Robert Sweetman](https://github.com/e-allora)

---

This README was drafted with Claude (Anthropic) from the site's own pages on 2026-11-02 and reviewed by Robert Sweetman. The 2026-11-07 update was made by Claude from the site's pages and has not been reviewed.