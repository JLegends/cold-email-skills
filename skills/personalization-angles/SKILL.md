---
name: personalization-angles
description: Generate 5 scalable personalization frameworks for cold email with data sources, signals, and ready-to-use opening lines. USE WHEN user says "personalization" OR "personalize at scale" OR "opening lines" OR "first lines" OR "email personalization" OR provides ICP/pain points and wants personalization frameworks. Creates repeatable patterns that work across 500+ prospects.
---

# Personalization Angle Generator

Creates 5 repeatable personalization frameworks you can run at scale. Not "I saw your post about..." — actual patterns tied to real data sources with fill-in-the-blank opening lines. Each one works across hundreds of prospects without sounding templated.

## How to Use

User provides one of:
- Output from ICP Extractor and/or Pain Point Mapper
- A target persona (job title + company type + what they care about)
- A product URL + target description

No follow-up questions. Build frameworks from what you have.

## What to Generate

### 5 PERSONALIZATION FRAMEWORKS

Each framework is a system, not a one-off line. It tells you where to look, what to look for, and what to say when you find it. An SDR should be able to run any framework in under 2 minutes per prospect.

For each framework:

---

**FRAMEWORK {N}: {NAME}** (2-3 words, memorable)

**Data source:**
Where to find this signal. Be specific:
- LinkedIn profile (which section? About? Experience? Activity?)
- Company website (which page? Careers? Blog? Case studies?)
- Job postings (which boards? What search query?)
- Tech stack tools (BuiltWith, Wappalyzer, HG Insights)
- Review sites (G2, Capterra — what to search for)
- Crunchbase / PitchBook (what data point?)
- Press releases / news (what to Google)
- GitHub / open source activity
- Podcast appearances
- Conference speaker lists

List the PRIMARY source and one BACKUP source.

**Signal:**
What specific thing are you looking for? Not "something interesting" — a precise signal.

Good signals:
- "Posted a job for a RevOps Manager in the last 30 days — means they're formalizing ops and likely evaluating tools"
- "Company blog has 3+ posts about outbound in the last quarter — they're investing in this channel"
- "Uses HubSpot (via BuiltWith) but job posting mentions Salesforce migration — they're in transition"
- "Left a G2 review for a competitor complaining about data accuracy — they're dissatisfied and shopping"

Bad signals:
- "Has an interesting LinkedIn profile" (not specific)
- "Recently promoted" (so what?)
- "Company is growing" (everyone says this)

**Signal strength:** Rate it. Strong / Medium / Weak.
- Strong: directly indicates buying intent or a relevant pain point
- Medium: indicates relevance but not urgency
- Weak: creates rapport but doesn't signal need

**Time to find:** How long does it take to find this signal per prospect?
- Target: under 2 minutes. If it takes longer, it doesn't scale.

**Opening line template:**
A fill-in-the-blank first sentence. Include {VARIABLE} placeholders.

Write 3 variants of the opening line:
1. **Direct** — states the signal plainly
2. **Curious** — turns the signal into a question
3. **Insight** — connects the signal to a non-obvious conclusion

**Why it works:**
Which psychological trigger does this hit?
- **Specificity** — proves you did research, not a mail merge
- **Relevance** — connects to something they actually care about right now
- **Timing** — catches them during a moment of need
- **Ego/recognition** — acknowledges something they're proud of
- **Curiosity** — opens a loop they want to close
- **Pattern interrupt** — says something they've never seen in a cold email
- **Social proof** — references peers or competitors

**Full example:**
One completely written opening line with a realistic company name, person name, and specific details. Not generic.

---

### FRAMEWORK RULES

1. **No "I saw your post about..."** — overused. Every AI tool generates this. Instant delete.
2. **No "Congrats on the funding round"** — zero differentiation. Everyone with Crunchbase can do this.
3. **No "I love what you're building at..."** — empty flattery. The prospect knows you didn't use the product.
4. **No "As a fellow {industry} professional..."** — cringe. Never self-reference.
5. **No compliments without specificity** — "Great talk at SaaStr" is lazy. "Your point about ditching MQLs at SaaStr was the only hot take I've seen backed by actual pipeline data" is a framework.
6. **Every framework must scale to 500+ prospects** using publicly available data. If it requires insider knowledge, it's not a framework.
7. **Each framework hits a different psychological trigger.** Don't repeat.
8. **Data sources must be free or commonly available.** Don't assume the user has a $50K data subscription.

### FRAMEWORK DIVERSITY

The 5 frameworks should cover different angles:

- **1 based on company activity** (hiring, funding, product launches, tech stack changes)
- **1 based on personal activity** (content they've created, talks they've given, career moves)
- **1 based on tech/tool signals** (what they use, what they're migrating from/to)
- **1 based on pain indicators** (G2 reviews, Reddit complaints, job postings that reveal process gaps)
- **1 wildcard** — something unexpected that creates a pattern interrupt

## After All 5 Frameworks

### PERSONALIZATION PLAYBOOK

Provide a ranked recommendation:

```
BEST FOR HIGH-VALUE TARGETS (worth 5 min per prospect):
> Framework {N} — why, and when to use it

BEST FOR SCALE (under 90 seconds per prospect):
> Framework {N} — why, and how to systematize it

BEST FOR SENIOR TITLES (VP+):
> Framework {N} — why senior people respond to this

BEST PATTERN INTERRUPT (highest reply rate, lowest volume):
> Framework {N} — why, and the risk if overused

RECOMMENDED STACK (if doing all 5):
> Start with Framework {N} for the first 100 sends
> Layer in Framework {N} for the second batch
> Use Framework {N} for re-engagement of non-responders
```

### ANTI-PATTERNS TO AVOID

List 5 personalization approaches that are commonly taught but actively hurt reply rates. For each:
- What it is
- Why people think it works
- Why it actually backfires
- What to do instead

## Output Rules

- Every opening line must sound like a human typed it in 10 seconds. Not crafted. Not polished. Natural.
- Data sources must be things an SDR can access without special tools or paid subscriptions (LinkedIn, Google, BuiltWith free tier, G2, company websites).
- Signal descriptions should be specific enough that a new SDR could follow them as instructions.
- If a framework requires enrichment tooling (Apollo, Clay, etc.), note it but also provide a manual alternative.
- Time-to-find estimates should be honest. If it takes 5 minutes, say 5 minutes — the user will trust the fast ones more.

## Example

**FRAMEWORK 2: THE STACK SIGNAL**

Data source: BuiltWith (free tier) or Wappalyzer browser extension. Backup: job postings mentioning specific tools.

Signal: Prospect's company uses a tool that's commonly replaced by or integrated with the product you're selling. Example: they use Mailchimp for transactional email but the product is a dedicated transactional email platform.

Signal strength: Strong — indicates they have the need but are using a suboptimal solution.

Time to find: 45 seconds via BuiltWith. 2 minutes via job posting scan.

Opening line variants:
1. Direct: "Noticed {COMPANY} is running {CURRENT_TOOL} for {USE_CASE} — most teams at your size have outgrown it by now."
2. Curious: "{FIRST_NAME}, is {CURRENT_TOOL} still handling {USE_CASE} at {COMPANY}'s volume, or has the team started looking?"
3. Insight: "Teams running {CURRENT_TOOL} for {USE_CASE} tend to hit a wall around {TRIGGER_POINT} — {COMPANY} looks like you might be close."

Why it works: Specificity (proves you looked at their stack) + Relevance (it's about a tool they actually use) + Timing (implies they might be at an inflection point).

Full example: "Noticed Acme Corp is running Mailchimp for transactional emails — most teams pushing 500K+ sends/month have outgrown it by now."
