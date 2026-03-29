---
name: pain-point-mapper
description: Generate ranked pain points, emotional hooks, and an objection map from ICP data. USE WHEN user says "pain points" OR "what are their problems" OR "objection handling" OR "why would they buy" OR provides ICP data and wants to go deeper on pain. Takes ICP output and produces daily frustrations, strategic problems, and a complete objection map.
---

# Pain Point Mapper

Takes ICP data and turns it into ammunition. Daily frustrations ranked by intensity. Strategic problems ranked by business impact. An objection map that pre-handles every reason they won't reply. This is the bridge between knowing WHO to target and knowing WHAT to say.

## How to Use

User provides one of:
- Output from the ICP Extractor skill
- A target persona description (job title + company type + what they're trying to do)
- A product URL + "give me pain points" (run ICP Extractor first, then this)

No follow-up questions. Work with what you have.

## What to Generate

### TOP 5 DAILY PAIN POINTS

Ranked by emotional intensity — #1 is the thing that makes them vent in Slack at 3pm on a Tuesday.

For each pain point:

**Pain Point: {NAME IT IN 3-5 WORDS}**
- **The frustration** — one sentence, written exactly as the prospect would say it to a colleague. Not formal. Not clean. The way real people actually complain.
- **The workaround** — what are they currently doing instead? Every pain point has a workaround — usually ugly, manual, and fragile. Describe it specifically.
- **The cost** — quantify it. Time wasted per week. Revenue left on the table. Deals lost per quarter. Reputation damage. Be specific, use realistic numbers.
- **The feeling** — name the emotion. Not "frustrated." More like: "That sinking feeling when you open the CRM on Monday and realize half the follow-ups from last week never went out." Paint the moment.
- **Cold email hook** — one sentence that would make this person stop scrolling. This is the "I see you" moment.

### TOP 3 STRATEGIC PAIN POINTS

These are the problems their boss cares about. The ones that show up in board decks and quarterly reviews.

For each:

**Strategic Pain: {NAME IT}**
- **The business problem** — frame it in terms leadership uses. Revenue impact. Market position. Competitive gap. Efficiency loss at scale.
- **Why nothing has fixed it** — what's been tried? What tools did they buy that didn't work? What process did they implement that nobody followed? Why is this still unsolved?
- **The win state** — what does the world look like if this pain disappears? Paint the picture. "The VP of Sales opens the dashboard Monday morning and sees every prospect from last week has been contacted, personalized, and sequenced — without anyone on the team doing manual research."
- **Who cares internally** — which stakeholders feel this pain? (Often multiple: the VP wants the metric, the manager wants the process, the rep wants fewer tabs open)

### OBJECTION MAP

The top 7 reasons this prospect would NOT reply to a cold email about this product. These are the mental reflexes that happen in the 3 seconds between reading your email and hitting delete.

For each objection:

**Objection: "{EXACT WORDS THEY'D THINK}"**
- **Why they think this** — what past experience or assumption drives this objection?
- **The reframe** — one sentence that neutralizes it. Not a sales pitch. A perspective shift.
- **Where to deploy** — should this reframe go in the email body, the follow-up, or the subject line?

Common objection categories to cover:
1. "We already have a tool for this" (incumbent objection)
2. "We're not doing outbound / that's not how we sell" (channel objection)
3. "I don't have time to evaluate something new" (bandwidth objection)
4. "This sounds like every other tool" (differentiation objection)
5. "I don't trust cold emails selling cold email tools" (meta objection)
6. "My team won't adopt another tool" (change management objection)
7. "We tried something like this and it didn't work" (burned-before objection)

Adapt these to the specific ICP. Not every category applies to every prospect.

### EMOTIONAL INTENSITY RANKING

After all pain points and objections, provide a ranked summary:

```
HIGHEST IMPACT FOR COLD EMAIL COPY:
1. {Daily Pain #X} — why this one wins for email
2. {Daily Pain #X} — backup angle
3. {Strategic Pain #X} — works for senior titles

HARDEST OBJECTIONS TO OVERCOME:
1. {Objection} — why it's sticky
2. {Objection} — common but addressable

QUICK WIN HOOKS (ready to paste into email openers):
1. "{hook from pain point 1}"
2. "{hook from pain point 2}"
3. "{hook from pain point 3}"
```

## Output Rules

- Write in the prospect's language. If they say "leads" don't write "demand generation pipeline opportunities."
- Pain points should sound like things said over coffee, not in a strategy doc.
- Every workaround should be specific enough that the prospect reads it and thinks "...that's literally what I do."
- Quantified costs should be realistic. Don't inflate. A believable "$2,400/month in wasted SDR time" hits harder than a made-up "$500K in lost revenue."
- The objection map should feel like you've sat through their sales calls. Not theoretical objections — real ones.
- If you don't have enough context for a specific pain point, make it clear what assumption you're making so the user can correct it.

## Example

Input: RevOps lead at B2B SaaS, 200 employees, evaluating data enrichment tools

**Daily Pain #1: "The Franken-Stack"**
- Frustration: "We're paying for ZoomInfo, Clearbit, AND Apollo and I still can't get a clean phone number for half our target accounts."
- Workaround: SDRs manually check LinkedIn, then Lusha, then RocketReach, then give up and send email-only. Takes 8-12 minutes per prospect.
- Cost: 3 SDRs x 40 prospects/day x 10 min wasted = 20 hours/week of manual enrichment. That's half an SDR's entire job — just looking up data.
- Feeling: The dread of logging into the enrichment tool dashboard and seeing the hit rate drop another 3% this quarter. Knowing you're paying $40K/year for data that's wrong 30% of the time.
- Cold email hook: "Your team is probably running 3+ enrichment tools and still manually checking LinkedIn for half their prospects."
