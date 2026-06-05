# Banked LinkedIn posts

Five posts ready to publish. Cadence: 2/week, Tuesday and Friday. Use these for the first 2.5 weeks. Then we write more based on what gets traction.

Voice rules:
- First person
- No buzzwords (no "leverage," "unlock," "transform," "revolutionize")
- One concrete number or example per post
- End with a question or a stake-in-the-ground statement (not a hashtag soup)
- No emoji unless intentional
- 150–250 words

Post on Damian's personal profile, not a company page. Personal posts get 2-5× the reach of company pages on LinkedIn.

---

## Post 1 — "What AI for PE actually looks like"

The pitch deck version of AI in PE is "your portfolio companies will be 30% more efficient."

The actual version is: a Claude agent reads the sponsor PDF when it lands in Drive, confirms all four inputs are present, flags what's missing, and pings the analyst. That happens before the workbook is opened. It saves about an hour per portfolio company per quarter.

Multiplied across 20 portcos, that's a working day saved every quarter from one tiny agent.

Then there are six more like it — one for comps refresh, one for the commentary drafting, one for the red-flag cross-check at the end. None of them are sexy. All of them are real.

The mistake most firms make is starting with the big swing. The right move is to ship the boring one first, watch it run for a month, and let the deal team feel the difference. Then the next agent gets approved without a debate.

If you're running a quarterly cycle for 10+ portcos, the first agent worth building is the verifier. It's the cheapest one and the one that catches the most mistakes.

---

## Post 2 — "The single highest-error step in a PE quarterly cycle"

Phase 5 of a typical PE quarterly cycle is updating the investor report. It includes about a dozen mechanical steps. One of them is rolling every column reference forward — every cell that pointed at column AU now points at AV.

This is done for every cell of every company every quarter. It is the highest-error step in the entire process. A single missed cell distorts the LP report.

It is also the cleanest AI win imaginable.

No judgment required. The model just has to identify that we're at quarter-end and increment one column. There's nothing to debate, no firm-specific style. The rule is the rule.

I see PE firms talking about AI for sourcing, for IC memo drafting, for portfolio scoring. All interesting. None of those are the first thing to ship.

The first thing to ship is the boring one with the most error risk and the least judgment. That's the test case. Once it runs clean for a quarter, you know the team trusts it. Then you ship the next.

---

## Post 3 — "Six patterns from Anthropic's financial-services repo PE firms should know"

Anthropic published a financial-services agent reference repo this spring. It's open source. Most PE firms haven't read it.

The patterns I see used most:

1. **Statement auditor** — reads any financial statement, flags inconsistencies. Use it for sponsor PDFs and audit prep.
2. **Market researcher** — searches the web for sector developments, M&A, comparable transactions. Use it for quarterly comps refresh.
3. **Valuation reviewer** — compares a proposed multiple against comp data and precedent transactions. Use it to pressure-test the sponsor mark.
4. **IC memo drafter** — writes investment committee memos in the firm's voice. Use it for first drafts of LP commentary.
5. **Portfolio monitoring** — continuous sweeps of public records for portcos. Use it between quarters to surface material events.
6. **Comps analysis** — public-comp screening. Use it as the precursor to the workbook refresh.

These are not "ideas." They are working agent patterns shipped with code. If your firm has an analyst building Excel macros, you have someone who can deploy these in a week.

(Bridgeworks adapted six of these for a 20-portco diligence pilot. Linking the case in the comments.)

---

## Post 4 — "What AI consultants get wrong about PE-backed companies"

Most AI consultants pitching PE-backed portcos make the same three mistakes:

1. **They pitch the sponsor instead of the portco.** The CEO of the portco is the buyer. The sponsor is the influencer. The pitch deck always opens with sponsor logos. Reverse this.

2. **They sell horizontal AI tools.** "Our platform integrates with everything." The portco doesn't want a platform. They want one workflow improved by Friday. Build that workflow. Skip the platform.

3. **They underprice the ongoing work.** Diagnostic gets sold cheap. The build is overpriced. Then nothing happens between the build and the next request. Retainers handle this — retainers price the relationship, not the project.

Real version: a CFO of a PE-backed company in the $30M–$100M range buys for two reasons. Quarterly reporting to the sponsor that's currently painful. Or a value-creation initiative on the operating side that needs automation faster than the team can hire for.

If you can map AI to either of those two, you have a sale. If you can't, you don't.

---

## Post 5 — "Why we redact client names from our case studies (and still publish them)"

We just published two long-form case studies on our site. One is a 7-agent diligence system for a PE asset manager. One is a connected lead funnel for a regional services chain.

Both clients are real. Neither is named.

Why redact:
- The 7-agent system is in pilot. Public attribution before production is a setup for being wrong publicly.
- Naming a client signals we'd do it again. Some clients want it. Some don't. Default: ask.
- The work is the proof, not the logo. Specific numbers ($14.77M mark, 1.5× multiple, 20 portcos, six phases) carry more weight than a brand badge.

Why publish anyway:
- Other firms with the same shape recognize themselves. They reach out. That's the point.
- AI consulting is over-pitched and under-shown. A real architecture is worth more than ten testimonials.
- Once the work is public (anonymized), pattern travel begins. The next client benefits from what we already shipped.

The third principle of how we work: we publish what we build, anonymized, so the next client benefits. Comments open.

(Linking the cases in the first comment.)
