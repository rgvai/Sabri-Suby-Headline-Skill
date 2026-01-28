# Sabri Suby Headline Hack

A Claude Custom Skill for generating 20 high-CTR direct-response headlines using proven copywriting frameworks.

## What It Does

This skill transforms Claude into a direct-response copywriter that generates headlines across 5 proven angles:

| Angle | Purpose | Example |
|-------|---------|---------|
| **Contrarian** | Challenge assumptions | "Why Your Expensive CRM is Losing You Sales" |
| **Mechanism Reveal** | Tease the "how" | "The 2-Inch Valve That Cuts Water Bills by 40%" |
| **Micro-Story** | Relatable scenarios | "How a Burnt-Out Lawyer Built a 6-Figure Side Hustle" |
| **Efficiency** | Quick wins | "15-Minute Routine That Replaced My Gym Membership" |
| **Urgency/FOMO** | Cost of inaction | "Every Day Without This Tool Costs You 3 Hours" |

Each headline is scored on clarity, specificity, credibility, and CTR potential—with the Top 10 highlighted and A/B test variants suggested.

## Installation

1. Download `sabri-suby-headline-hack.skill`
2. Open Claude → Settings → Capabilities
3. Upload the `.skill` file
4. Enable the skill

## Usage

Simply ask Claude to write headlines for your product or service:

```
Write headlines for my new project management app targeting 
overwhelmed startup founders. Key feature: AI auto-prioritization. 
Proof: 500+ teams use it. Tone: confident but not salesy. 
Platform: LinkedIn ads.
```

Claude will prompt for any missing details, then generate 20 headlines with rankings and recommendations.

### Required Inputs

| Input | Description |
|-------|-------------|
| Product/Service | What you're selling + category |
| Target Audience | Who + their main pain point |
| Unique Mechanism | What makes it different |
| Proof/Claims | Stats, testimonials, results |
| Brand Voice | Tone and compliance rules |
| Platform | Where it runs + word limits |

## Output Format

```
## Top 10 Headlines

1. [Headline] — Score: 9/10
   Angle: Mechanism | Why it works: Specific number creates credibility

2. ...

## A/B Test Variants (for #1)
- Variant A (curiosity): ...
- Variant B (urgency): ...

## Honorable Mentions
...

## Discarded (<7 average)
...
```

## Files

```
sabri-suby-headline-hack/
├── SKILL.md                         # Main skill instructions
└── references/
    └── headline-examples.md         # Detailed examples by angle
```

## Style Rules

- **≤15 words** per headline
- **Single idea** per headline
- **One booster max** (number, urgency, villain, or CTA)
- **No unsubstantiated claims** — calibrate for credibility
- **Avoid overused hype** — no "revolutionary," "game-changing," etc.

## Credits

Based on the direct-response copywriting methodology of Sabri Suby, author of *Sell Like Crazy*.

## License

MIT
