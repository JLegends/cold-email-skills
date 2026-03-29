# Cold Email Skills for Claude Code

3 Claude Code skills that replace 90% of the research before writing a single cold email.

Drop in a product URL. Get a full ICP, ranked pain points, and personalization frameworks in about 15 minutes.

## What's Inside

### 1. ICP Extractor
Paste a product URL. It pulls the target audience, buyer personas, use cases, buying triggers, and competitive landscape straight from the site. No manual research.

### 2. Pain Point Mapper
Feed it the ICP output. It generates the top 5 daily frustrations ranked by emotional intensity, 3 strategic problems, and a 7-point objection map. Written in the prospect's language — not marketing copy.

### 3. Personalization Angle Generator
Creates 5 repeatable personalization frameworks with exact data sources, signals to look for, and fill-in-the-blank opening lines. Each one scales to 500+ prospects without sounding templated.

## How They Chain Together

```
Product URL
    |
    v
[1. ICP Extractor] --> Full ICP profile
    |
    v
[2. Pain Point Mapper] --> Ranked pain points + objection map
    |
    v
[3. Personalization Angles] --> 5 frameworks with opening lines
    |
    v
Ready to write cold emails
```

## Installation

Copy the `skills/` folder into your Claude Code config:

```bash
# Clone the repo
git clone https://github.com/wbreton/cold-email-skills.git

# Copy skills into your Claude Code directory
cp -r cold-email-skills/skills/* ~/.claude/skills/
```

Or copy individual skills:

```bash
# Just the ICP extractor
cp -r cold-email-skills/skills/icp-extractor ~/.claude/skills/

# Just the pain point mapper
cp -r cold-email-skills/skills/pain-point-mapper ~/.claude/skills/

# Just the personalization angles
cp -r cold-email-skills/skills/personalization-angles ~/.claude/skills/
```

## Usage

Once installed, the skills trigger automatically based on what you ask:

**Skill 1 — ICP Extractor:**
```
"Research ICP for https://instantly.ai"
"Who is this product for? https://clay.com"
```

**Skill 2 — Pain Point Mapper:**
```
"Give me pain points for RevOps leads at mid-market SaaS"
(or paste the output from Skill 1)
```

**Skill 3 — Personalization Angles:**
```
"Generate personalization frameworks for SDR managers at B2B companies"
(or paste the output from Skills 1 + 2)
```

**Full chain:**
```
1. "Research ICP for https://example.com"
2. "Now give me pain points" (it uses the ICP output)
3. "Generate personalization angles" (it uses both outputs)
```

15 minutes. Full campaign research done.

## Who This Is For

- SDR teams that spend more time researching than selling
- Agency operators launching campaigns for multiple clients
- Founders doing their own outbound
- Growth teams that want to move faster without cutting corners on personalization

## Built by

[Will Breton](https://linkedin.com/in/wbreton) — building AI-powered GTM systems at AICRO.
