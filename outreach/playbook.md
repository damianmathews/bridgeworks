# Bridgeworks outbound playbook

Master document. Read first. Everything else (templates, posts) flows from this.

## Goal

First paid Bridgeworks engagement signed in 30–60 days. Minimum bar: one paid diagnostic ($7.5k+). Stretch: one paid diagnostic + one started build.

## ICP (Ideal Customer Profile)

We are pitching **finance-first** for the next 90 days. Three concentric circles, prioritized:

**Inner circle — fastest convert:**
- Private-equity firms, $500M–$5B AUM
- 10–30 portfolio companies
- US-based, ideally East Coast or Texas (Damian's geography for in-person)
- Mid-market focus (not mega-funds, not micro-funds)
- Already running quarterly valuation cycles manually or with light tooling

**Middle circle — strong fit:**
- Family offices ($100M–$1B AUM) with direct private investments
- Boutique asset managers with private credit, real estate, or specialty positions
- Independent valuation firms wanting to deliver more for less

**Outer circle — opportunistic only:**
- PE-backed portfolio companies themselves (CFO, COO buyers)
- Professional services firms (accounting, advisory) with finance practice arms

### The right person at each account

In priority order:
1. **Head of portfolio operations / VP value creation** — owns process efficiency, has budget, feels the pain weekly
2. **Chief operating officer** — same as above for smaller firms
3. **CFO** — owns the close cycle, audit, LP reporting
4. **Partner / Principal** with operations focus — for firms where there's no dedicated ops head
5. **Director of investor relations** — owns LP reporting and tech buying around it

Avoid: junior analysts, generic associates. They forward but don't decide. Their forward usually dies.

### Disqualifiers

- Funds under $250M AUM (often too small to budget $7.5k+ engagements)
- Funds with internal data-science teams of 3+ (they build it themselves)
- Sovereign wealth or institutional pension allocators (procurement nightmare)
- Anything outside the US for now (sales-cycle complexity)

## The 50-account target list

Build a Notion table or Airtable base with these columns:

| Column | Type | Notes |
|---|---|---|
| Firm | text | Company name |
| AUM | number | Approximate, in $M |
| HQ | text | City |
| Portcos | number | Number of portfolio companies (if PE) |
| Target person | text | Full name + title |
| LinkedIn URL | url | Their LinkedIn |
| Email | text | Found via Apollo, Clay, or guessed |
| Sponsor of | text | One signature company in their portfolio you'll reference |
| Hook | text | One sentence: why now, why them |
| Status | select | Researching / Sent / Replied / Booked / Closed / Passed |
| Last touch | date | Most recent action |
| Next action | text | What to do next |
| Notes | long text | Anything from conversations |

**How to source 50 names:**
1. PitchBook / Crunchbase / Preqin (free tier) — filter PE firms by AUM range and US HQ
2. LinkedIn Sales Navigator (1-week free trial if you don't already pay) — search "Head of Portfolio Operations" + "Private Equity" + AUM filters
3. PEHub / PEI News — read recent quarterly fund-raising stories; firms with new vehicles are spending
4. Your network — ask 5 contacts "who do you know at PE firms running 10+ portcos?"

Target: 50 accounts built by end of week 1. Doesn't need to be perfect. 30 is fine to start.

## The multi-touch sequence

Per the 2026 outbound research, multi-channel sequences boost engagement 287%. Single-channel cold email gets 3% reply. Multi-channel personalized hits 8–18%. We run multi-channel.

**Day 0: LinkedIn connect**
Personalized connect note. <300 chars. No pitch. Curiosity-led.

**Day 2 (or when connect accepts): LinkedIn DM**
Reference something specific they posted or their firm announced. Soft intro to what Bridgeworks does.

**Day 5: Email #1**
Direct, short, references a public signal (recent fund close, portfolio expansion, recent hire). Soft ask: 15-min call to compare notes on AI for quarterly cycle.

**Day 12: Email #2 — value add**
Send something useful. The Bridgeworks Farol case study URL. No ask. "Thought this might be relevant given [their context]."

**Day 21: Breakup email**
Short. "Going to stop reaching out. If timing changes, here's where to find me." This often gets replies because the urgency is removed.

**Stop the sequence** the moment they reply. Move to human conversation.

## Volume targets

| Week | New accounts contacted | Total in sequence | Expected replies | Expected calls |
|---|---|---|---|---|
| 1 | 0 (build list) | 0 | — | — |
| 2 | 25 | 25 | 1–2 | 0–1 |
| 3 | 25 | 50 | 2–4 | 1–2 |
| 4 | 25 | 50 (some dropped) | 3–5 | 2–3 |
| 5–8 | 25/wk | 50–75 active | 4–6/wk | 2–3/wk |

By end of week 4: realistically 1–2 diagnostic conversations should be live. Goal: 1 signed by week 6.

## Tools (cheapest viable stack)

- **Gmail** for sending (don't use a third-party warm-up tool for this volume; you'll be at <50 sends/day, under any spam threshold)
- **Notion or Airtable** for tracking — free tier
- **Apollo.io** free tier for finding emails (50 credits/month)
- **Clay** if Apollo runs out — 100 free credits
- **LinkedIn Premium / Sales Navigator** — $99/mo for the Navigator search filters and InMail allowance, worth it during this window
- **Mixmax** or **Right Inbox** for email templates and tracking — free tier

**Don't use:**
- Mass email tools (Instantly, Lemlist) at this stage — they encourage high-volume low-quality sending, which is the opposite of what works for $7.5k+ engagements
- Calendly auto-booking links in cold emails — feels transactional, reduces reply rate. Manual scheduling for the first call is fine.

## Conversation playbook

When someone replies positively:

1. **Don't pitch on the first call.** Listen. Ask about their current cycle, their pain, what they've tried. 30 minutes.
2. **Map their process** to one of the three pillars (probably Finance for this ICP). If it doesn't map, say so honestly.
3. **Propose the diagnostic.** Two weeks, fixed fee, written deliverable. Send a follow-up email within 24 hours with a scope and quote.
4. **If they say yes**, send a Bridgeworks engagement letter (template lives in /outreach/contracts/ — TODO).
5. **If they say no or not now**, ask if you can stay in touch quarterly. Add to nurture sequence.

## What to do daily (when running)

15-minute morning:
- Check replies. Respond to any.
- Send 3–5 LinkedIn connect requests for the day's batch.

30-minute midday:
- Research 3–5 new accounts. Add to tracker.
- Send 3–5 personalized cold emails (today's batch).

15-minute end-of-day:
- Update tracker. Anything to follow up tomorrow?
- Note any signal that moves an account from cold → warm.

Total: ~60 minutes/day on outbound. Leaves 2–3 hours/day for diagnostic work, content, and build engagements.

## What to do weekly

- Monday: plan the week. Decide which 25 accounts to add.
- Wednesday: LinkedIn post #1 of the week
- Friday: LinkedIn post #2 of the week
- Friday afternoon: review reply rates. If <5% reply rate on the week's batch, the messages aren't personalized enough. Re-cut.

## Warm intros (parallel track)

You said 1–3 warm intros in finance. These run on their own track. They're worth more than any 25 cold accounts.

**For each warm intro:**
1. Ask the introducer to send a one-line intro email. Do NOT draft it for them — that reads as canned.
2. Within 1 day of intro landing, reply with a short note: "Great to connect. Brief context on what I do: [2 sentences]. Open to a quick call next week to compare notes?"
3. Calendar within 7 days.
4. Same first-call structure as cold replies.

## Operations case study (long-term)

By week 8, document everything in this folder + actual results into a public case study at `/work/operations-outbound.html`. This becomes the Bridgeworks flagship Operations engagement: "How we built an AI-powered outbound system that landed [N] clients in 60 days."

Pipeline + proof, same artifact.
