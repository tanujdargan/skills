---
name: humanize-text
description: Use when asked to "humanize" text, make AI-generated text sound natural, reduce AI detection scores, rewrite robotic prose, or make writing sound more human. Triggers on "humanize", "make it sound human", "less robotic", "AI detection", "natural prose".
---

# Humanize Text

## Overview

Targeted editing of AI-generated text to read as natural human prose. Removes AI writing patterns (hedging phrases, formulaic connectors, tidy conclusions) while preserving meaning and substance. Validated across 24 controlled samples against humanizeai.pro — achieves 100% AI-pattern removal with ~20% word reduction.

## When to Use

- User asks to "humanize" or "make less robotic" any text
- User wants text to pass AI detection tools
- User provides AI-generated text that needs to sound natural
- User asks to rewrite in a "human" voice

**Do NOT use for:** Original writing from scratch, creative writing style changes unrelated to AI patterns, translation, or summarization.

## Core Approach

You are making **targeted edits**, NOT rewriting from scratch. Most sentences survive with minor modifications. Only remove or restructure sentences with obvious AI patterns.

## Prompt Template

When humanizing text, follow these rules:

```
1. Delete all "It is [adjective] to [verb] that" hedging constructions — remove the preamble, keep the claim
2. Remove or replace formulaic connectors (Furthermore, Moreover, Additionally, Subsequently, Consequently, Nevertheless) with simpler alternatives or nothing
3. Remove concluding sentences that start with "In conclusion," "In summary," "In essence," or "Ultimately"
4. Drop redundant qualifiers: remarkably, significantly, fundamentally, arguably, comprehensive, extensive
5. Replace grandiose vocabulary with everyday equivalents (e.g. "paradigm shift" → "major shift", "leverage" → "use")
6. Restructure sentences to front-load the subject — reduce nested clauses and passive constructions
7. Remove self-referential phrases ("I am writing to inform you," "The following outlines")
8. For persuasive text: rewrite "It could be argued... however" patterns more directly
9. For creative text: reduce stacked metaphors but preserve core imagery
10. For business/technical text with 3+ sequential items: convert to bullet points, but EACH BULLET MUST BE A COMPLETE SENTENCE retaining the detail from the original
```

## Word Count Constraint

- Rules 1-4 already reduce word count. After applying them, tighten remaining wordy or passive sentences.
- Do NOT compress or summarize — tighten. A 20-word sentence that works in 14 words is good. Dropping entire sentences unless pure filler is bad.
- **FLOOR: 10%** — less than 10% shorter means you left filler in.
- **CEILING: 30%** — more than 30% shorter means you cut substance.
- **Target: 15-25% reduction overall.**
- Business/professional text: aim for 15-20%. Preserve all data, rationale, context, and diplomatic tone.
- After rewriting, verify output is between 70-90% of original length.

## Genre-Specific Targets

| Genre | Target | Max |
|---|---|---|
| Expository/Educational | 15-25% | 30% |
| Persuasive/Argumentative | 15-25% | 30% |
| Professional/Business | 10-20% | 25% |
| Creative/Narrative | 10-20% | 25% |
| Technical/Analytical | 15-25% | 30% |

## Quick Reference — Kill on Sight

**Hedging phrases (delete entirely):**
"It is widely acknowledged that", "It is important to note that", "It is worth noting that", "It is essential to understand that", "It could be argued that", "It should be noted that", "It is increasingly clear that", "It is undeniable that", "It is widely recognized that"

**Formulaic connectors (replace or drop):**
"Furthermore," "Moreover," "Additionally," "Subsequently," "Consequently," "Nevertheless," "First and foremost," "In light of these considerations,"

**Conclusion phrases (delete phrase or whole sentence):**
"In conclusion," "In summary," "In essence," "Ultimately," "To summarize," "All things considered,"

**Intensifiers to drop:**
remarkably, arguably, undeniably, profoundly, fundamentally, significantly, considerably, essentially, comprehensive, extensive

**Connector replacements:**

| Drop | Replace with |
|---|---|
| Furthermore, | (nothing) or "Also," |
| Moreover, | (nothing) or "On top of that," |
| Additionally, | "Also," or drop |
| Subsequently, | "Next," / "After that," |
| Consequently, | "As a result," / "So," |
| Nevertheless, | "Still," / "Yet," |

## Preservation Rules

Do NOT cut:
- Technical terms, exact figures, proper nouns
- Data points, percentages, metrics
- Rationale sentences in business text
- Stakeholder-facing diplomatic language
- Any sentence introducing new information

Do NOT:
- Add new information
- Change factual claims
- Simplify domain-specific vocabulary
- Rewrite from scratch — edit the existing text

## Common Mistakes

| Mistake | Fix |
|---|---|
| Cutting >30% of word count | Restore substantive content; you removed more than filler |
| Bullet points as bare fragments | Each bullet must be a complete sentence with original detail |
| Over-flattening creative text | Preserve core imagery; only cut stacked metaphors and AI hedging |
| Losing business context/rationale | "Despite challenging conditions" etc. is substantive, not filler |
| Changing meaning | "The cruel passage of time" must not become "the cruelty of nature" |

See reference.md for full rules with before/after examples from the 24-pair validation dataset.
