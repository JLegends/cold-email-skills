# Cold Email Skills for Claude Code

3 Claude Code skills that replace 90% of the research before writing a single cold email.

Drop in a product URL. Get a full ICP with buying committee mapping, ranked pain points with gap quantification, and signal-based personalization frameworks with AI prompt templates. In about 15 minutes.

## Why These Exist

Most cold email research is either:
- **Too shallow** — name, company, generic pain point, send
- **Too slow** — 30-60 minutes per prospect doing manual research across 6 tabs

These skills hit the middle: deep enough to generate 15-25% reply rates (signal-based personalization benchmarks), fast enough to prep a full campaign in one sitting.

## What's Inside

### 1. ICP Extractor
Paste a product URL. Get a complete Ideal Customer Profile with:
- Full buying committee (5 roles: economic buyer, champion, end user, technical evaluator, blocker)
- 3-5 micro-segments with distinct pain points and email angles
- Negative ICP (who to explicitly exclude and why)
- 8+ buying triggers categorized by signal type with detection methods
- Technographic profile and intent signal playbook
- ICP scoring rubric (Tier 1/2/3) for account prioritization
- Prospect language bank mined from reviews and communities
- Enrichment roadmap with free and paid sources per data point

**Methodologies:** Clay enrichment waterfall, Apollo persona builder, Warmly ML-based ICP tiering, Common Room dark funnel signals, Ocean.io negative ICP, Kyle Coleman micro-segmentation, Josh Braun Sales Safari, Sam McKenna buying committee mapping, Jason Bay decision metrics.

### 2. Pain Point Mapper
Feed it the ICP output. Get structured pain intelligence:
- 5 pain points with 3-layer depth (Sandler Pain Funnel: surface, business impact, personal/career)
- Gap quantification per pain point (current state, future state, dollar/time figure)
- MEDDIC pain scoring (0-3 scale) and intensity levels (latent to urgent)
- Challenger Sale reframe for each pain (insight the prospect hasn't considered)
- 3 cold email hook variants per pain (SPIN, Challenger, Voss styles)
- 7-point objection map with pre-handling language
- Pain-to-copy translation table (pain component to email element mapping)

**Methodologies:** Sandler Pain Funnel (3 layers), Gap Selling/Keenan (quantified gaps), MEDDIC (pain scoring + champion identification), Challenger Sale (reframes + commercial teaching), SPIN Selling (implication questions), Gong data from 67,149 sales calls (objection handling), Chris Voss tactical empathy (accusation audits, labeling, "no"-oriented CTAs).

### 3. Personalization Angle Generator
Get 5 signal-based personalization frameworks with:
- Frameworks mapped to 5 buying signal categories (career transition, competitive displacement, organizational growth, financial/funding, digital behavior)
- Signal tiering (Tier 1/2/3) with response time targets
- Constrained AI prompt templates for each framework (Clay/Claygent-style, works with any LLM)
- 3 opening line variants per framework (direct, curious, insight)
- Multi-signal stacking guide for 25-40% reply rates
- Reply rate benchmarks per personalization level
- Deliverability-safe patterns (Gmail 2026 spam filter intelligence)
- Speed-to-lead guidance (first-to-contact = 5x win rate)

**Methodologies:** Autobound signal-based selling, Clay/Claygent prompt engineering, Instantly 2026 Benchmark Report, Lavender email coaching data (reading level optimization), Common Room dark funnel, Bombora intent data patterns, Gong conversation intelligence.

## The Data Behind It

| Personalization Level | Reply Rate | These Skills Target |
|---|---|---|
| No personalization | 1-3% | - |
| Basic (name + company) | 5-9% | - |
| Industry pain + news | 9-15% | Pain Point Mapper |
| Signal-based (trigger + value prop) | 15-25% | Personalization Angles |
| Multi-signal stacked | 25-40% | Signal stacking guide |

Sources: Instantly 2026 Benchmark Report, Backlinko 12M email analysis, Autobound signal-based selling data.

## How They Chain Together

```
Product URL
    |
    v
[1. ICP Extractor]
    |  Buying committee, micro-segments, triggers,
    |  negative ICP, scoring rubric
    v
[2. Pain Point Mapper]
    |  3-layer pain, gap quantification, MEDDIC score,
    |  Challenger reframes, objection pre-handling
    v
[3. Personalization Angles]
    |  Signal frameworks, AI prompt templates,
    |  multi-signal stacking, reply rate benchmarks
    v
Ready to write cold emails that hit 15-25% reply rates
```

## Installation

```bash
# Clone the repo
git clone https://github.com/JLegends/cold-email-skills.git

# Copy all skills into your Claude Code directory
cp -r cold-email-skills/skills/* ~/.claude/skills/
```

Or copy individual skills:

```bash
cp -r cold-email-skills/skills/icp-extractor ~/.claude/skills/
cp -r cold-email-skills/skills/pain-point-mapper ~/.claude/skills/
cp -r cold-email-skills/skills/personalization-angles ~/.claude/skills/
```

## Usage

Once installed, the skills trigger automatically based on what you ask:

**Skill 1 -- ICP Extractor:**
```
"Research ICP for https://instantly.ai"
"Who is this product for? https://clay.com"
"Target audience for https://apollo.io"
```

**Skill 2 -- Pain Point Mapper:**
```
"Give me pain points for RevOps leads at mid-market SaaS"
"What are the biggest frustrations for SDR managers?"
(or paste the output from Skill 1)
```

**Skill 3 -- Personalization Angles:**
```
"Generate personalization frameworks for SDR managers at B2B companies"
"How do I personalize cold emails for VP Sales at Series B SaaS?"
(or paste the output from Skills 1 + 2)
```

**Full chain (15 minutes):**
```
1. "Research ICP for https://example.com"
2. "Now give me pain points" (uses ICP output automatically)
3. "Generate personalization angles" (uses both outputs)
```

## Who This Is For

- **SDR teams** spending more time researching than selling
- **Agency operators** launching campaigns for multiple clients per week
- **Founders** doing their own outbound who need to move fast
- **Growth teams** that want signal-based personalization without a $50K data stack
- **RevOps** building playbooks for repeatable outbound motions

## What Makes These Different

Most "cold email prompts" give you generic advice or templates. These skills are different because:

1. **They're methodology-backed.** Every output structure maps to a proven sales framework (Sandler, MEDDIC, Challenger, SPIN, Gap Selling, Gong data). Not vibes -- research.

2. **They include the AI prompt templates.** Each personalization framework comes with a constrained prompt you can drop into Clay, Claude, or any LLM for at-scale generation. Grounded in verified data only -- no hallucinations.

3. **They chain together.** The output of Skill 1 feeds Skill 2, which feeds Skill 3. The context compounds. By the end you have ICP + pain + personalization that all reference the same prospect reality.

4. **They tell you where to look.** Every signal includes the data source (free and paid), the search query, and how long it takes to find. A new SDR can follow the instructions on day one.

5. **They include the benchmarks.** You know what reply rate to expect from each approach before you send a single email. No guessing.

## Research Sources

These skills were built by cross-referencing:

- Clay.com enrichment waterfall and Claygent prompt patterns
- Apollo.io persona builder and intent data
- Instantly.ai 2026 Cold Email Benchmark Report
- Autobound signal-based selling methodology
- Common Room dark funnel and Person360 enrichment
- Warmly ML-based ICP tiering (TAM Agent)
- Ocean.io lookalike and negative ICP modeling
- Gong.io data from 67,149 analyzed sales meetings
- MEDDIC/MEDDPICC qualification framework
- Sandler Pain Funnel (3-layer pain depth)
- Challenger Sale (Dixon & Adamson) commercial teaching
- SPIN Selling (Rackham) implication questions
- Gap Selling (Keenan) quantified gap methodology
- Chris Voss tactical empathy (Never Split the Difference)
- Lavender email coaching (reading level optimization)
- Kyle Coleman (micro-segmentation, negative space ICP)
- Josh Braun (Sales Safari, prospect language mining)
- Sam McKenna (buying committee mapping, "Show Me You Know Me")
- Jason Bay (decision metrics, 3x3 research method)

## Built by

[Jacob Breton](https://linkedin.com/in/jacobbreton) -- building AI-powered GTM systems at AICRO.
