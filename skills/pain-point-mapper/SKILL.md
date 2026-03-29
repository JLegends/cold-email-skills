---
name: pain-point-mapper
description: Generate multi-layer pain points, gap quantification, objection pre-handling, and copy-ready hooks from ICP data. USE WHEN user says "pain points" OR "what are their problems" OR "objection handling" OR "why would they buy" OR provides ICP data and wants to go deeper on pain. Uses Sandler Pain Funnel (3-layer depth), Gap Selling (quantified gaps), MEDDIC (pain scoring), Challenger Sale (reframes), Gong data (67K calls), and Chris Voss tactical empathy.
---

# Pain Point Mapper

Takes ICP data and turns it into ammunition for cold email. Every pain point is structured in three layers (Sandler), quantified as a gap (Keenan), scored for urgency (MEDDIC), and paired with a Challenger reframe and pre-handled objections (Gong + Voss).

This is the bridge between knowing WHO to target and knowing WHAT to say.

## How to Use

User provides one of:
- Output from the ICP Extractor skill
- A target persona description (job title + company type + what they're trying to do)
- A product URL + "give me pain points" (run ICP Extractor first, then this)

No follow-up questions. Work with what you have.

## What to Generate

### SECTION 1: PAIN POINTS (Top 5)

Ranked by emotional intensity. #1 is the thing that makes them vent in Slack at 3pm on a Tuesday.

For each pain point, generate ALL of the following:

#### {PAIN POINT NAME} (3-5 words)

**Three-Layer Depth** (Sandler Pain Funnel)

Most cold emails only hit layer 1. Top performers hit all three. Reps must go past comfortable surface questions to reach the personal layer.

- **Layer 1 — Surface/Technical Pain:** The operational problem they'd mention casually. What's broken, slow, or annoying. Written as the prospect would say it to a colleague.
  - Example: "Our CRM data is a mess."

- **Layer 2 — Business Impact Pain:** What it costs the company. Revenue, pipeline, efficiency, competitive position. Frame in terms leadership uses. Quantify it.
  - Example: "We're losing 15% of leads because follow-up timing is based on stale data. That's roughly $180K/quarter in pipeline we never touch."

- **Layer 3 — Personal/Career Pain:** How it affects the individual. Their reputation, their stress, their performance review, their career trajectory. This is the layer that drives action.
  - Example: "The VP of Sales asked me last Thursday why our outbound conversion dropped 20% this quarter. I didn't have a good answer. That's the third time in six months I've been in that seat."

**Gap Quantification** (Gap Selling — Keenan)

The sale exists because there's a gap between current state and desired state. The bigger the gap, the more urgent the purchase.

- **Current State:** What's happening now. Be specific and concrete.
- **Future State:** What should be happening. Paint the picture.
- **The Gap:** The quantified difference. Time, money, risk, or opportunity cost. Use realistic numbers.
- **Gap Owner:** Who in the org is responsible for closing this gap? Name the role.

**MEDDIC Pain Score** (0-3)
- 0 = No pain identified
- 1 = Vague awareness ("things could be better")
- 2 = Can articulate but not quantify ("we lose deals because of this")
- 3 = Named, quantified, owner identified ("we lose $180K/quarter in pipeline because of stale data, and I'm the one who has to explain it to the VP")

Rate the pain point's score based on how most prospects in this ICP would experience it. Score 3 means the pain is ready for a direct cold email. Score 1-2 means the email needs to do the awareness work first.

**Pain Intensity Level**
- Latent — they don't know they have it yet. Email must create awareness.
- Acknowledged — they know but aren't prioritizing. Email must amplify consequences.
- Active — they're looking for solutions. Email must differentiate.
- Urgent — they need to solve this NOW. Email must reduce friction to action.

**Challenger Reframe**

Top-performing reps don't just validate pain — they teach the prospect something new about their problem. Based on the Challenger Sale (Dixon & Adamson).

- **What they currently believe:** The prospect's existing mental model of this problem.
- **The insight they're missing:** What they don't know about their own situation. This is the "reframe" — the moment where the status quo starts to feel dangerous.
- **Why their current approach won't work:** Challenge their plan. Not aggressively — with data and logic.
- **The new path:** What the world looks like if they think about this differently.

This reframe is the core of a Challenger-style cold email. Lead with the insight, not the product.

**Cold Email Hooks** (3 variants)

For each pain point, generate three hook variants:

1. **SPIN hook** (Situation > Problem > Implication): "Most [role] at [company type] are still [situation]. The problem is [problem]. When that goes unaddressed for another quarter, [implication]."
2. **Challenger hook** (Insight-first): Lead with the reframe. Something they haven't considered.
3. **Voss hook** (Accusation audit): "You're probably thinking [name their likely objection]. And honestly, [validate it]. But [reframe]."

### SECTION 2: STRATEGIC PAIN POINTS (Top 3)

These are the problems that show up in board decks and quarterly reviews. Target these when emailing VP+ titles.

For each:

#### Strategic Pain: {NAME IT}

- **The business problem** — frame in leadership language. Revenue impact. Market position. Competitive gap.
- **Why nothing has fixed it** — what's been tried? What tools failed? What process was ignored?
- **The win state** — what does the world look like if this disappears? Paint it.
- **Who cares internally** — map to the buying committee. The VP wants the metric, the manager wants the process, the rep wants fewer tabs open.
- **The decision metric** — what KPI would justify the purchase? (Jason Bay: "If you can't name the metric, you don't understand the ICP")
- **Cost of inaction** — what happens if they do nothing for another 6 months? Quantify it. This is more powerful than any benefit statement.

### SECTION 3: OBJECTION PRE-HANDLING

The top 7 objections, structured using Gong's data-driven framework (from 67,149 analyzed sales meetings) and Chris Voss's tactical empathy.

For each objection:

#### Objection: "{EXACT WORDS THEY'D THINK}"

**Objection type** (Gong taxonomy):
- Smokescreen — cover story for the real concern
- Concern — genuine worry about risk/change
- Sales objection — real obstacle (price, timing, competition)
- Condition — true deal-breaker (recognize and skip)
- Complacency — status quo bias (the hardest to break)

**Why they think this** — what past experience or assumption drives it?

**Pre-handling in copy** (deploy BEFORE they object):

Using Chris Voss tactical empathy techniques:

- **Accusation audit opener:** "You're probably thinking [name the objection before they do]." By naming their fear first, you disarm it. This works in email subject lines, opening lines, or follow-ups.

- **Label the emotion:** "It seems like..." / "It sounds like..." — name the dynamic without judging it. Labels diffuse negative emotions.

- **"No"-oriented CTA:** Instead of pushing for "yes," frame the ask where "no" feels safe:
  - "Would it be a terrible idea to..." (instead of "Would you like to...")
  - "Have you given up on trying to fix..." (instead of "Are you interested in...")
  - "Is it ridiculous to suggest that..." (instead of "Can I show you...")

- **Gong reframe technique:** Ask yourself:
  - "What if the opposite of this objection were true?"
  - "Is there a scenario where this objection is actually a reason TO buy?"
  - Then write the reframe as a one-sentence perspective shift.

- **Cost-of-inaction framing:** For urgency objections ("not the right time"), quantify what another month/quarter of inaction costs. "Every month this goes unaddressed, [specific cost]." This creates urgency without fake deadlines.

**Where to deploy:** Email body, subject line, follow-up bump, or breakup email? Match the objection to the right touch in the sequence.

**Objection categories to always cover:**
1. Incumbent ("We already have [tool]") — compete with their RESULTS, not their tool
2. Bandwidth ("I don't have time for this") — show the time cost of NOT acting
3. Trust ("I've never heard of you") — front-load social proof
4. Differentiation ("This sounds like everything else") — lead with the Challenger reframe
5. Burned before ("We tried this and it didn't work") — label the emotion, then separate
6. Complacency ("Things are fine") — make the status quo feel dangerous
7. Authority ("I'm not the right person") — ask for the champion, not the deal

### SECTION 4: PAIN-TO-COPY TRANSLATION TABLE

The direct mapping from research to email copy. Based on how top agencies (Belkins, CIENCE, Martal) translate pain research into campaigns.

For each of the top 3 pain points, provide a row in this format:

| Pain Component | Copy Element | Example Line |
|---|---|---|
| Surface symptom (Layer 1) | Opening hook | "If your team is still manually [doing the thing]..." |
| Business impact (Layer 2) | Implication line | "...that typically costs [role] teams [quantified cost]" |
| Personal consequence (Layer 3) | Emotional resonance | "...and puts the [role] in the hot seat when [consequence]" |
| Quantified gap | Urgency driver | "Teams we work with have recovered [amount] by [change]" |
| Social proof | Credibility anchor | "We just helped [similar company type] cut this from [before] to [after]" |
| Low-friction CTA | Call to action | "Worth a look, or is this not a priority right now?" |

### SECTION 5: EMOTIONAL INTENSITY RANKING

After all pain points and objections, provide the ranked summary:

```
HIGHEST IMPACT FOR COLD EMAIL COPY:
1. {Pain Point} — why this wins for email + which template to use
2. {Pain Point} — backup angle + best for which micro-segment
3. {Strategic Pain} — works for VP+ titles

PAIN INTENSITY MAP:
> Latent: [which pains] — need awareness-building emails
> Acknowledged: [which pains] — need amplification emails
> Active: [which pains] — need differentiation emails
> Urgent: [which pains] — need friction-reduction emails

HARDEST OBJECTIONS TO OVERCOME:
1. {Objection} — type + why it's sticky + best pre-handling approach
2. {Objection} — type + common but addressable

COPY-READY HOOKS (paste directly into email openers):
1. SPIN: "{situation > problem > implication hook}"
2. Challenger: "{insight-first hook}"
3. Voss: "{accusation audit hook}"
4. Gap: "{current state vs future state hook}"
5. Story: "{specific scenario that paints the Tuesday afternoon moment}"
```

## Output Rules

- Write in the prospect's language. If they say "leads" don't write "demand generation pipeline opportunities."
- Pain points should sound like things said over coffee, not in a strategy doc.
- Every workaround should be specific enough that the prospect reads it and thinks "...that's literally what I do."
- Quantified costs should be realistic. Don't inflate. A believable "$2,400/month in wasted SDR time" hits harder than a made-up "$500K in lost revenue."
- The objection map should feel like you've sat through their sales calls. Not theoretical — real.
- All three Sandler layers are required for every pain point. Layer 3 (personal) is where the action happens. Don't skip it.
- If you don't have enough context for a specific number, state your assumption so the user can correct it.
- Challenger reframes should teach something genuinely new. Not "your tool is bad" — that's just criticism. "Your tool is actually making the problem worse because [non-obvious reason]" is a reframe.

## Example

Input: RevOps lead at B2B SaaS, 200 employees, evaluating data enrichment tools

**Daily Pain #1: "The Franken-Stack"**

Three-Layer Depth:
- Layer 1 (Surface): "We're paying for ZoomInfo, Clearbit, AND Apollo and I still can't get a clean phone number for half our target accounts."
- Layer 2 (Business): 3 SDRs x 40 prospects/day x 10 min manual enrichment = 20 hours/week. That's half an SDR salary ($30K/year) spent on copy-pasting between tabs. Hit rate across all 3 tools combined: 62%. Industry standard for waterfall enrichment: 85%+.
- Layer 3 (Personal): "The VP of Sales asked me point-blank why our cost-per-meeting is 3x what it was last year. I had to explain that our data tools cost $85K/year combined and still can't find a direct dial for a Series B CTO in San Francisco. That conversation was not fun."

Gap Quantification:
- Current State: 3 enrichment tools, $85K/year, 62% hit rate, 20 hrs/week manual
- Future State: Single enrichment layer, 85%+ hit rate, zero manual lookups
- The Gap: $30K/year in wasted SDR time + $40K/year in tool consolidation savings + 23% more prospects contacted = roughly $120K/year in recoverable value
- Gap Owner: RevOps Lead (owns the tooling budget and SDR efficiency metrics)

MEDDIC Score: 3 (named, quantified, owner identified)
Pain Intensity: Active (they know, they're shopping, they haven't pulled the trigger)

Challenger Reframe:
- Current belief: "We need better data providers with higher match rates"
- Missing insight: The problem isn't the providers — it's querying them in parallel instead of in a waterfall. The same providers give 85%+ coverage when queried sequentially per field instead of per record.
- Why current approach fails: Adding a 4th provider won't fix a 62% hit rate. The architecture is wrong.
- New path: Enrichment waterfall that cascades providers per field, not per record. Same data budget, 30% better coverage.

Accusation audit: "You're probably thinking 'great, another enrichment tool.' Fair. But this isn't about adding a 4th provider to the stack — it's about making the 3 you already pay for actually work."
