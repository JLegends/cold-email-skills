---
name: icp-extractor
description: Generate a complete ICP analysis from a single product URL. USE WHEN user says "research ICP" OR "ICP from URL" OR "who is this product for" OR "target audience" OR pastes a product URL and asks for targeting. Outputs buying committee, micro-segments, negative ICP, intent signals, technographic profile, ICP scoring rubric, and prospect language — modeled on Clay, Apollo, Warmly, and Common Room methodologies.
---

# ICP Extractor

Drop in a product URL. Get a full Ideal Customer Profile — buying committee, micro-segments, intent signals, negative ICP, and scoring rubric. Modeled on the enrichment approaches used by Clay, Apollo, Warmly, and Common Room.

One URL in. Full targeting out. No follow-up questions.

## How to Use

User provides a product URL. You do the rest. No follow-up questions unless the URL is broken.

## Workflow

1. Visit the URL
2. Analyze everything: homepage, pricing, features, case studies, testimonials, about page, careers page, integrations page, and any linked resources
3. Extract the full ICP analysis using the structure below
4. Output in the structured format, filling every section

## What to Extract

### 1. PRIMARY ICP

- **Industry / Vertical** — be specific. "B2B SaaS" is too broad. "B2B SaaS, Series A-C, selling to mid-market and enterprise" is the right level. Include sub-verticals if relevant.
- **Company size** — employee count range AND estimated revenue range. Note growth trajectory if visible (scaling fast vs. steady-state).
- **Funding stage** — Bootstrapped, Seed, Series A-D, PE-backed, Public. Recent funding = budget availability.
- **Business model** — B2B, B2C, B2B2C, marketplace, services, etc.
- **Geographic focus** — HQ region, target markets, language requirements
- **Tech maturity** — modern cloud stack, legacy systems, duct-taping spreadsheets, or transitioning?

### 2. BUYING COMMITTEE (5 Roles)

Map the full buying committee, not just one persona. Most B2B deals involve 3-7 people. Based on Sam McKenna's "Show Me You Know Me" framework and MEDDIC's Champion methodology.

For each role:

- **Economic Buyer** — signs the check. Title, seniority, what metric they're measured on.
- **Champion** — internal advocate who sells for you after you leave the room. Usually the person who feels the pain most directly. Deals with a confirmed Champion close 30% faster (MEDDIC data).
- **End User** — uses the product daily. Their adoption determines renewal.
- **Technical Evaluator** — assesses integration, security, data handling. Often IT, engineering, or ops.
- **Blocker** — who might veto? Legal, procurement, IT security, finance. Name the role and their likely concern.

For each role, include:
- Exact job title(s)
- What they care about (their metric or KPI)
- How they evaluate (ROI spreadsheet? Demo? Free trial? Peer recommendation?)
- Decision process — consensus, top-down, or bottom-up?

### 3. MICRO-SEGMENTS (3-5 Sub-ICPs)

One broad ICP is not enough. Break the primary ICP into 3-5 specific sub-segments, each with distinct characteristics. Based on Kyle Coleman's micro-segmentation approach.

For each micro-segment:
- **Segment name** — descriptive, 3-5 words (e.g. "Scaling SDR teams at Series B SaaS")
- **What makes them different** — from other segments. The specific condition or context.
- **Their #1 pain** — the primary frustration for THIS segment specifically
- **Best email angle** — the hook that resonates for this micro-segment
- **Estimated segment size** — rough order of magnitude (hundreds, thousands, tens of thousands)

### 4. NEGATIVE ICP (Who to Exclude)

Define who NOT to target with as much rigor as who to include. Based on Ocean.io's negative ICP methodology.

- **Company types to exclude** — and why (too small, wrong industry, no budget, wrong business model)
- **Roles to exclude** — titles that look right but aren't buyers or influencers for this product
- **Disqualification signals** — red flags that indicate poor fit (e.g. "company has fewer than 5 employees," "no outbound motion," "already built this in-house")
- **Common false positives** — segments that seem like a fit but historically don't convert

### 5. USE CASES

For every distinct use case mentioned or implied on the site:
- **Who** has the problem (specific role from the buying committee)
- **What** the problem is (in their words, not marketing copy)
- **How** this product solves it (the actual mechanism, not the tagline)
- **Alternative** — what are they doing today without this product?
- **Decision metric** — what KPI would the buyer use to justify this purchase? (Jason Bay: "If you can't name the metric, you don't understand the ICP")

List at least 4 use cases.

### 6. BUYING TRIGGERS (Timed Events)

List at least 8 specific events that would cause someone to actively search for this product. These are moments in time, not ongoing states. Categorize by signal type.

**Career transition triggers:**
- New hire into a buying role (new VP of Sales wants to see the outbound playbook — there isn't one)
- Promotion giving existing contact new budget authority
- Champion from a current customer joins a new company (highest-intent signal)

**Financial triggers:**
- Recent funding round with relevant use-of-capital language
- Board pressure to hit growth targets
- Budget cycle timing (Q1 planning, fiscal year start)

**Organizational growth triggers:**
- Hiring surge in the relevant department (3+ roles posted = investment signal)
- Geographic expansion (new office, remote roles in new regions)
- Team restructuring or new department creation

**Competitive displacement triggers:**
- Competitor raises prices (Clay pricing change, Zapier tier restructuring)
- Competitor product issues (outages, feature removal, bad reviews)
- Contract renewal timing for existing tools

**Process breakdown triggers:**
- System outage or data loss event
- Failed audit or compliance issue
- Key person leaves and takes institutional knowledge with them

For each trigger, include:
- **Detection method** — where/how to spot this signal (LinkedIn, Crunchbase, job boards, G2, news)
- **Response window** — how quickly to act (immediate, within a week, nurture)
- **Signal strength** — Strong (direct buying intent), Medium (relevant context), Weak (awareness only)

### 7. TECHNOGRAPHIC PROFILE

Based on Clay and BuiltWith enrichment patterns:

- **Expected tech stack** — what tools does this ICP typically run? (CRM, email, automation, analytics, data)
- **Compatible technologies** — what in their stack does this product integrate with?
- **Competing technologies** — what tools would they need to replace or complement?
- **Stack signals** — what does their tech stack tell you about their maturity, budget, and priorities?
- **Migration indicators** — if they're running [tool X], they're likely experiencing [pain Y] and ready for [solution Z]

### 8. INTENT SIGNAL PLAYBOOK

Based on Common Room's dark funnel methodology and Bombora/G2 intent data patterns. Tell the user where to monitor for buying signals specific to this ICP.

**First-party signals (if available):**
- Website visitor behavior (pricing page visits, multiple sessions)
- Free trial / freemium signups
- Content downloads

**Dark funnel signals:**
- Community activity (Slack, Discord, Reddit) — which communities does this ICP use?
- G2/Capterra comparison pages — which category pages to monitor?
- Social signals — LinkedIn posts mentioning the problem category
- GitHub activity — if relevant, open-source alternatives being evaluated

**Third-party intent:**
- Bombora topic clusters — which topics would signal buying intent?
- Job postings — which role titles signal this product category investment?
- Technology changes — what installs/removals on BuiltWith would be a trigger?

### 9. PROSPECT LANGUAGE BANK

Based on Josh Braun's "Sales Safari" methodology. Capture how prospects actually describe their problems — not marketing language.

- **Mine these sources** for the specific ICP:
  - G2/Capterra reviews of competitors (1-3 star reviews are gold)
  - Reddit threads in relevant subreddits
  - LinkedIn posts from the target persona
  - Glassdoor reviews mentioning tooling frustrations
  - Community forums (Slack groups, Discord servers)

- **Capture patterns like:**
  - "I wish [product] would..." (unmet need)
  - "The biggest problem with [process] is..." (named frustration)
  - "We switched because..." (trigger event in their words)
  - "I spend [X hours] per week just..." (quantified pain)

- **Output:** 5-10 direct quotes or paraphrased prospect-language phrases that can be used verbatim in cold email copy. These should sound like things a real person says in Slack, not a whitepaper.

### 10. COMPETITIVE LANDSCAPE

- **Direct competitors** — who else solves this exact problem? List 3-5 with:
  - One-line positioning difference
  - Their primary weakness (from G2 reviews if possible)
  - When a prospect would choose them over this product
- **Indirect competitors** — what do teams use instead? (spreadsheets, manual processes, cobbled-together tools, internal builds)
- **Why this product wins** — based on positioning, what's the claimed differentiator?
- **Switching signals** — what to look for that indicates someone is unhappy with a competitor (review sentiment, job postings for new tooling, tech stack changes)

### 11. MARKET SIGNALS

- **Pricing model** — what does the pricing page reveal about their target? (per-seat = team sale, usage-based = scale play, enterprise "contact us" = big deals)
- **Content topics** — what does their blog/resources cover? This reveals who they think their audience is.
- **Integration partners** — what tools do they integrate with? This tells you what stack their users already run.
- **Job postings** — if they're hiring, what roles? This reveals where they're investing.
- **Case study companies** — what do their featured customers have in common? This IS the ICP in action.

### 12. ICP SCORING RUBRIC

Based on Warmly's ML-based tiering approach. Provide a scoring framework for prioritizing accounts.

**Tier 1 (Perfect fit):** All criteria match. Active intent signals present. Score: 9-10.
**Tier 2 (Good fit):** Most criteria match. Some intent signals or relevant triggers. Score: 6-8.
**Tier 3 (Possible fit):** Partial match. Worth testing but not priority. Score: 3-5.
**Not ICP:** One or more disqualification signals. Score: 0-2.

For each tier, provide:
- Which firmographic criteria must match
- Which intent signals elevate an account
- Which disqualification signals drop it
- Suggested outreach approach per tier (personalized vs. scaled vs. skip)

**Scoring dimensions** (weight each 1-5 for the specific ICP):
- Industry fit
- Company size fit
- Tech stack compatibility
- Budget indicators (funding, revenue)
- Intent signals present
- Buying committee accessible
- Timing alignment (trigger events)

### 13. ENRICHMENT ROADMAP

For each section of the ICP, tell the user which data providers or free tools to use for verification and enrichment:

| Data Point | Free Source | Paid Source |
|---|---|---|
| Company firmographics | LinkedIn, Crunchbase (free tier) | Apollo, Clearbit |
| Tech stack | BuiltWith (free tier), Wappalyzer extension | HG Insights, Openmart |
| Buying intent | G2 category pages, LinkedIn activity | Bombora, 6sense |
| Contact data | LinkedIn search | Apollo, ZoomInfo, Lusha |
| Hiring signals | LinkedIn Jobs, Indeed | PredictLeads |
| Funding data | Crunchbase (free tier) | PitchBook |
| Review sentiment | G2, Capterra, Reddit | SparkToro |
| Dark funnel | Reddit, community forums | Common Room |

## Output Rules

- Write in plain language. Not the product's marketing copy.
- If the site doesn't give enough data for a field, say "insufficient data — check G2 reviews, Crunchbase, or customer interviews" rather than guessing.
- Be specific. Vague outputs are useless.
- Buyer personas should feel like real people, not segments in a slide deck.
- Every buying trigger should be something you can picture a specific person experiencing on a specific day.
- Prospect language should sound like things said over coffee, not in a board presentation.
- The scoring rubric should be immediately usable — someone should be able to score their first 10 accounts with it.

## Example

User: "https://instantly.ai"

**Primary ICP:**
- Industry: B2B service companies (agencies, consultancies, lead gen shops) and B2B SaaS with outbound-driven GTM
- Company size: 5-200 employees, $500K-$50M revenue
- Funding: Seed to Series B, or bootstrapped and profitable
- Business model: B2B services or B2B SaaS
- Geographic: US-primary, expanding globally. English-speaking markets.
- Tech maturity: Moderate. They know what cold email is. They've probably tried Mailshake or Lemlist. They want scale.

**Buying committee example:**
- Economic Buyer: CEO/Founder (sub-50) or VP Sales (50-200). Measured on pipeline generated and cost-per-meeting.
- Champion: Head of Growth or SDR Manager. Feels the pain of sending limits and deliverability issues daily.
- End User: SDRs and account executives who send the emails.
- Technical Evaluator: RevOps or growth engineer who manages integrations and data flow.
- Blocker: IT security (data handling), Finance (cost vs. current tool).

**Micro-segment example:**
- "Agency operators managing 5+ client campaigns" — need multi-account management, white-labeling, campaign-level reporting. Best angle: "Managing 5 client campaigns from one dashboard instead of 5 logins."

**Negative ICP example:**
- Companies with no outbound motion (pure inbound or product-led). They don't have the use case.
- Solo consultants sending fewer than 50 emails/month. The scale features aren't worth the price.

**Buying trigger example:**
- "The team just hit the sending limits on their current tool and the founder realized they need infrastructure that can handle 10,000+ emails per day without deliverability tanking."
- Detection: Job posting for "SDR" or "Cold Email Specialist" = they're scaling outbound.
- Response window: Within 1 week. Signal strength: Strong.
