# Humanize Text — Detailed Reference

Full rules with before/after examples. Derived from 24-pair controlled comparison (AI-generated samples vs. humanizeai.pro Ultra/Simple-Flowing output).

## Rule 1 — Strip Hedging & Distancing Phrases

The single most impactful change (25+ instances across 24 samples). AI text uses impersonal constructions to distance the author from claims. Delete them.

### Kill List

| AI Phrase | Action |
|---|---|
| "It is widely acknowledged that" | Delete; start with the actual claim |
| "It is important to note that" | Delete |
| "It is worth noting that" | Delete |
| "It is worth mentioning that" | Delete |
| "It is worth highlighting that" | Delete |
| "It is worth emphasizing that" | Delete |
| "It is essential to understand that" | Delete |
| "It is important to understand that" | Delete |
| "It is important to recognize that" | Delete |
| "It is important to emphasize that" | Delete |
| "It is interesting to note that" | Delete |
| "It is interesting to observe that/how" | Delete or simplify |
| "It could be argued that" | Delete; state counterargument directly |
| "It could be observed that" | Delete |
| "It could be said that" | Delete |
| "It should be acknowledged that" | Delete |
| "It should be noted that" | Delete |
| "It should be emphasized that" | Delete |
| "It is increasingly clear/evident that" | Delete; make the statement directly |
| "It is undeniable that" | Delete |
| "It is widely recognized that" | Delete |
| "It is anticipated that" | Replace with direct statement |
| "It is estimated that" | Replace with direct statement |
| "It is recommended that" | Replace with direct recommendation |
| "It is reasonable to conclude that" | Delete |

### Examples

**Before:** "It is widely acknowledged that photosynthesis is one of the most fundamental biological processes on Earth."
**After:** "One of the most significant biochemistry processes in the world is called photosynthesis."

**Before:** "It is essential to understand that the revolution was driven by a complex interplay of social, economic, and political factors."
**After:** "The revolution was sparked by several economic, political, and social factors that converged."

**Before:** "It could be argued that concerns about collaboration and company culture are valid; however, modern communication tools have largely mitigated these challenges."
**After:** "Collaborations and corporate culture are still major concerns of many managers, yet communication technologies have addressed most of them."

---

## Rule 2 — Replace or Remove Formulaic Connectors

35+ instances. AI over-relies on a small set of academic transitions. Replace with simpler alternatives or drop entirely.

| AI Connector | Replace With |
|---|---|
| "Furthermore," | Drop, or "Also," / "On top of that," |
| "Moreover," | Drop, or "On top of that," / "Plus," |
| "Additionally," | "Also," / "In addition," / drop |
| "Subsequently," | "Next," / "This was followed by" / "After that," |
| "Consequently," | "As a result," / "So," / drop |
| "Nevertheless," | "Still," / "Even so," / "Yet," |
| "First and foremost," | "First," / "To begin with," |
| "In light of these considerations," | "In general," / "Overall," |

Not every sentence needs a connector. Two sentences next to each other often imply their relationship.

**Before:** "Furthermore, this process serves as the foundation of most food chains, as it converts inorganic carbon dioxide into organic compounds."
**After:** "Photosynthesis provides the foundation for most food chains through the formation of organic materials from carbon dioxide."

---

## Rule 3 — Remove Conclusion Phrases

12+ instances. AI always wraps up with a tidy bow. Humans often just stop.

| AI Phrase | Action |
|---|---|
| "In conclusion," | Delete phrase (often the whole sentence) |
| "In summary," | Delete phrase (often the whole sentence) |
| "In essence," | Delete phrase |
| "Ultimately," | Replace with "Finally," or delete |
| "To summarize," | Delete |
| "All things considered," | Delete |

**Before:** "In conclusion, photosynthesis is arguably one of the most critical biochemical pathways, without which life as we know it would not be possible."
**After:** *(Entire sentence removed.)*

---

## Rule 4 — Word Count Targets

Average target: ~20% reduction. Never exceed 30%.

| Genre | Target | Max |
|---|---|---|
| Expository/Educational | 15-25% | 30% |
| Persuasive/Argumentative | 15-25% | 30% |
| Professional/Business | 10-20% | 25% |
| Creative/Narrative | 10-20% | 25% |
| Technical/Analytical | 15-25% | 30% |

**Cut:** Concluding sentences, redundant qualifiers, throat-clearing ("There are several compelling reasons why..."), meta-commentary, redundant restatements.

**Preserve:** All data/metrics, rationale in business text, diplomatic language, supporting "why" details, any sentence with new information.

---

## Rule 5 — Vocabulary Simplification

| AI Word/Phrase | Humanized To |
|---|---|
| "paradigm shift" | "radical shift" |
| "pathogens" | "microbes" |
| "sophisticated" | "complicated" |
| "substantially lower" | "much lower" |
| "dramatically decreased" | "dropping sharply" |
| "disproportionately" | "paid the bulk of" |
| "gained considerable traction" | "widely accepted" |
| "immutable record" | "evidence of every transaction" |
| "leverage" (verb) | "use" |
| "facilitate" | "help with" |
| "comprehensive" | often dropped entirely |

Do NOT simplify: proper technical terms (TCP/IP, CRM, CI/CD), domain vocabulary expected in context (qubits, chloroplasts), exact figures.

---

## Rule 6 — Drop Intensifiers

| Word | Action |
|---|---|
| remarkably | Drop |
| arguably | Drop |
| undeniably | Drop |
| profoundly | Drop |
| fundamentally | Drop or simplify |
| significantly | Drop when clear without it |
| considerably | Drop or simplify |
| essentially | Drop |
| comprehensive | Drop |
| extensive/extensively | Drop or simplify |

**Before:** "The human immune system is a remarkably complex and sophisticated defense mechanism"
**After:** "The immune system of the human body is a complicated protection mechanism"

---

## Rule 7 — Prose Lists to Bullet Points

For business/technical text with 3+ sequential items. Each bullet retains full detail from the original sentence.

**Before:** "Phase one involves the deployment of an AI-powered chatbot for handling routine inquiries. Phase two focuses on integrating the system with our existing CRM platform. Phase three encompasses advanced analytics and continuous improvement capabilities."

**After:**
- Phase I: Implementation of an artificial intelligence chatbot that will answer basic customer inquiries.
- Phase II: Integration with our existing CRM.
- Phase III: Addition of analytics and continuous improvement functionality.

---

## Rule 8 — Break Long Paragraphs

Split at natural topic shifts: positive → negative, description → recommendation, between conceptually distinct points. Business text: roughly every 3-4 sentences.

---

## Rule 9 — Make Sentences Direct

**Relative clause → direct:** "The French Revolution, which took place from 1789 to 1799, is widely regarded as..." → "The French Revolution occurred between 1789 and 1799 and is considered..."

**Impersonal → direct:** "It is anticipated that the proposed system will reduce resolution times by approximately 60%" → "Our new customer service system will reduce ticket resolution time by 60%"

**Long compound → two simple:** "The innate immune system provides the first line of defense through physical barriers such as skin and mucous membranes, as well as through various immune cells like neutrophils and macrophages." → "Innate immunity is the primary type of protection. It includes physical barriers (e.g., skin, mucus), and immune cells (neutrophils, macrophages)."

---

## Rule 10 — Remove Meta-Commentary

| AI Phrase | Action |
|---|---|
| "There are several compelling reasons why" | Delete; just state the reasons |
| "There is a growing body of evidence suggesting" | "There is increasing proof" or just state it |
| "The following is a summary of" | "Minutes of" or just begin |
| "I am writing to provide a comprehensive overview of" | Just start |
| "Please do not hesitate to reach out" | Drop or simplify |

---

## Rule 11 — Flatten Creative Literary Language

Reduce stacked metaphors to simpler descriptions. Keep one evocative word per sentence, not three.

| Poetic Original | Humanized |
|---|---|
| "flour-dusted workers shaped dough in the amber glow of industrial ovens" | "flour-covered bakers molded dough in the heat of their large ovens" |
| "threads of gold through grey fabric" | "weaved in and out of the general noise" |
| "faded to a soft sepia" | "become light brown" |
| "ethereal and otherworldly" | "magical and otherworldly" |
| "a privilege and a transgression" | "an honor and a sin" |

Apply selectively — aggressive flattening reduces writing quality.

---

## Rule 12 — Explicit Enumeration

Replace flowing transitions with numbered markers: "First and foremost... Additionally... Furthermore..." → "First,... Second,... Third,..."

---

## Rule 13 — Rewrite Counterargument-Dismissal Pattern

Replace "It could be argued... however" with grounded attribution.

**Before:** "Critics often argue that UBI is financially unfeasible; however, it is worth noting that the consolidation of existing welfare programs..."
**After:** "Other skeptics argue that UBI requires an excessive budget, yet merging present welfare programs and employing progressive taxation might offset the expenses."

The hedging phrase ("It could be argued") becomes grounded ("Other skeptics argue"). "However" becomes "yet" or "but."

---

## Validation Data

Tested across 4 iterations on 24 samples (5 categories: expository, persuasive, business, creative, technical).

| Metric | Result |
|---|---|
| Hedging phrase removal | 100% (45/45) |
| Formulaic connector removal | 100% (42/42) |
| Conclusion phrase removal | 100% (8/8) |
| Average word reduction | 19.2% (target: ~20%) |
| Samples exceeding 30% ceiling | 2/24 (92% compliance) |
