---
name: icp-extractor
description: Generate a complete ICP analysis from a single product URL. USE WHEN user says "research ICP" OR "ICP from URL" OR "who is this product for" OR "target audience" OR pastes a product URL and asks for targeting. Pulls buyer personas, use cases, buying triggers, company profile, and market positioning from the product site.
---

# ICP Extractor

Drop in a product URL. Get a full Ideal Customer Profile — buyer personas, use cases, buying triggers, and market positioning. No manual research. No tab-switching. One URL in, full targeting out.

## How to Use

User provides a product URL. You do the rest. No follow-up questions unless the URL is broken.

## Workflow

1. Visit the URL
2. Analyze everything: homepage, pricing, features, case studies, testimonials, about page, careers page, and any linked resources
3. Extract the full ICP analysis
4. Output in the structured format below

## What to Extract

### PRIMARY ICP

- **Industry / Vertical** — be specific. "B2B SaaS" is too broad. "B2B SaaS, Series A-C, selling to mid-market and enterprise" is the right level.
- **Company size** — employee count range AND estimated revenue range
- **Buying department** — which team owns the budget?
- **Decision maker** — exact job title of the person who signs the check
- **End user** — exact job title of the person who uses it daily (often different from decision maker)
- **Geographic focus** — if the product targets specific regions or is US-only, note it
- **Tech maturity** — are these teams running modern stacks or duct-taping spreadsheets?

### SECONDARY ICPs (up to 2)

Same structure as primary. Only include if the product clearly serves multiple distinct audiences. Don't force it — if there's one ICP, say so.

### USE CASES

For every distinct use case mentioned or implied on the site:
- **Who** has the problem (specific role)
- **What** the problem is (in their words, not marketing copy)
- **How** this product solves it (the actual mechanism, not the tagline)
- **Alternative** — what are they doing today without this product?

List at least 4 use cases. Pull from case studies, feature pages, and testimonials. If a testimonial says "we used to do X manually," that's a use case.

### BUYING TRIGGERS

List at least 6 specific events that would cause someone to actively search for this product. These are moments in time, not ongoing states.

Good triggers:
- "Just hired a 3rd SDR and realized there's no system for who gets which leads"
- "Lost a deal because the follow-up sequence died in someone's inbox"
- "Board asked for pipeline attribution data and the team pulled numbers from 4 different spreadsheets"
- "New VP of Sales starts and wants to see the outbound playbook — there isn't one"

Bad triggers:
- "Wants to grow revenue" (too vague)
- "Needs better tools" (not actionable)
- "Looking to scale" (says nothing)

### COMPETITIVE LANDSCAPE

- **Direct competitors** — who else solves this exact problem? List 3-5 with one-line positioning difference.
- **Indirect competitors** — what do teams use instead? (spreadsheets, manual processes, cobbled-together tools)
- **Why this product wins** — based on positioning, what's the claimed differentiator?

### MARKET SIGNALS

- **Pricing model** — what does the pricing page reveal about their target? (per-seat = team sale, usage-based = scale play, enterprise "contact us" = big deals)
- **Content topics** — what does their blog/resources cover? This reveals who they think their audience is.
- **Integration partners** — what tools do they integrate with? This tells you what stack their users already run.
- **Job postings** — if they're hiring, what roles? This reveals where they're investing.

## Output Rules

- Write in plain language. Not the product's marketing copy.
- If the site doesn't give enough data for a field, say "insufficient data — check G2 reviews, Crunchbase, or customer interviews" rather than guessing.
- Be specific. Vague outputs are useless outputs.
- Buyer personas should feel like real people, not segments in a slide deck.
- Every buying trigger should be something you can picture a specific person experiencing on a specific day.

## Example

User: "https://instantly.ai"

**Primary ICP:**
- Industry: B2B service companies (agencies, consultancies, lead gen shops) and B2B SaaS with outbound-driven GTM
- Company size: 5-200 employees, $500K-$50M revenue
- Buying department: Sales / Growth / Founder (at smaller cos, the founder IS the sales team)
- Decision maker: Head of Sales, VP Growth, CEO/Founder (sub-50 employees)
- End user: SDRs, account executives, growth marketers, agency operators
- Geographic: US-primary, expanding globally. English-speaking markets.
- Tech maturity: Moderate. They know what cold email is. They've probably tried Mailshake or Lemlist. They want scale.

**Buying trigger example:**
"The team just hit the sending limits on their current tool and the founder realized they need infrastructure that can handle 10,000+ emails per day without deliverability tanking."
