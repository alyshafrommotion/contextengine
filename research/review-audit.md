---
name: review-audit
description: Analyzes customer reviews to surface deep customer insights for ad ideation. Use this whenever a user provides customer reviews and wants to understand their customers better, extract VOC (voice of customer), find ad-ready language, or build messaging strategy from real customer language. Trigger for any request involving "analyze these reviews," "what are customers saying," "VOC analysis," or any variation of wanting to mine customer reviews for creative strategy inputs.
stage: 1-research
---

# Review Audit

This system mines customer reviews to extract the insights that make ad copy actually work: the real language, real pain, real moments, and real transformations that customers experienced. The output feeds directly into creative strategy and hook writing.

**The goal is not to summarize reviews. The goal is to find the raw material for ads.**

---

## What You Need Before Starting

If multiple products are present in the review set, identify them before beginning. All output is separated by product.

If product attribution is ambiguous, ask before proceeding.

---

## Step 1: Count the Reviews — Hard Gate

Count the total number of reviews provided (rows in a spreadsheet, discrete reviews in pasted text) before doing anything else.

**If the total is fewer than 100 reviews, do not run this audit.** Tell the user how many reviews were provided, explain that this analysis requires a minimum of 100 reviews to surface reliable patterns, and stop. Do not produce a partial audit.

If the total is 100 or more, record the count and proceed.

---

## Step 2: Group by Product

If the brand sells multiple products, sort all reviews by product first. Every subsequent step runs separately per product.

Record the review count per product — this determines whether that product qualifies for persona identification in Step 6 (100+ reviews required).

If all reviews are for a single product, skip grouping and proceed.

---

## Step 3: Score Review Quality (1–5)

Before analysis, score every review for quality. This determines what gets analyzed and what gets discarded.

| Score | What it looks like |
|---|---|
| **1** | Garbage — gibberish, swear words, 2–3 meaningless words, zero signal ("great product", "love it", "👍") |
| **2** | Low signal — very short, vague, no specific detail or emotion |
| **3** | Moderate — mentions the product, some specificity, but no vivid detail or emotional depth |
| **4** | High quality — specific, describes a real experience, references a before/after or a feeling |
| **5** | Gold — long, emotional, vivid, paragraph-level detail; the customer was so moved they wrote an essay about it |

**Score 5 reviews are the priority.** They contain the most usable language and the deepest insight.

---

## Step 4: Filter

Discard all reviews scored **1**. Do not include them in analysis.

Analyze scores **2–5**, with emphasis on 4s and 5s. Low-scoring reviews (2–3) can contribute to pattern identification but should not be the source of pulled quotes.

---

## Step 5: Extract Insights by Bucket

Run this analysis separately for each product. Within each bucket, group similar insights together and write a brief summary of the pattern. Then pull the best word-for-word quotes that exemplify it.

Do not editorialize the quotes. Pull them exactly as written.

---

### Bucket 1: Pain Points
*What problem were they experiencing before they found this product?*

Look for: descriptions of the problem they had, how long they'd had it, what they'd tried before, how it affected their life, the emotional weight of living with it.

For each pain theme identified:
- Name the theme
- Write a 2–3 sentence summary of the pattern across reviews
- Flag the strongest quotes for the swipe file

---

### Bucket 2: Trigger Moments
*What finally made them buy?*

Look for: the specific moment, event, or realization that pushed them over the edge. This is the thing that turned a maybe into an add-to-cart. It could be a life event (wedding, diagnosis, vacation), a recommendation (friend, doctor, TikTok), hitting a breaking point, or running out of patience with other solutions.

For each trigger theme identified:
- Name the theme
- Write a 2–3 sentence summary of the pattern
- Flag the strongest quotes for the swipe file

---

### Bucket 3: Objections Before Purchasing
*What almost stopped them from buying?*

Look for: skepticism they mention having had, comparisons to other products they'd tried, price hesitation, disbelief that this would actually work, fear of wasting money again.

Note: In positive reviews, objections are almost always mentioned in past tense — "I was skeptical but..." or "I almost didn't try it because..." These are gold for objection-handling ad copy.

For each objection theme identified:
- Name the theme
- Write a 2–3 sentence summary of the pattern
- Flag the strongest quotes for the swipe file

---

### Bucket 4: Transformations
*What changed for them after using the product?*

Look for: the specific result they experienced, how their life is different now, the emotional shift (confidence, relief, freedom, pride), and — most importantly — how they describe the transformation in their own words. The more specific and visceral, the better.

For each transformation theme identified:
- Name the theme
- Write a 2–3 sentence summary of the pattern
- Flag the strongest quotes for the swipe file

---

### Bucket 5: Standout Language & Ad-Ready Phrases
*Exact language worth stealing for ads.*

This bucket is different from the others. It is not organized by theme — it is a curated collection of the most vivid, emotionally charged, specific, and scroll-stopping phrases pulled from across all buckets. These are the lines that made you stop while reading. The ones that don't need to be rewritten. The ones a copywriter would highlight and build an ad around.

Pull these verbatim. Note which product they're from.

What to look for:
- Unusually specific descriptions of pain or transformation
- Phrases that capture an emotion in a way you couldn't have written yourself
- Before/after language that is visceral and concrete
- Lines that could work as a hook with zero editing
- Anything that made you feel something while reading it

---

## Step 6: Build Customer Personas

**Only for products with 100 or more reviews.** If a product falls below this threshold, skip this step for that product and note it in the output.

For each qualifying product, identify **3–5 distinct customer personas** that emerge from the reviews — so it's clear exactly which personas exist within each product. Personas are clusters of who is buying, why they bought, and what changed for them. They must be grounded in patterns actually present in the reviews. Do not invent personas the reviews don't support — if only 3 genuinely exist, present 3; never pad to 5.

For each persona, define:

- **Persona name** — a short, evocative label (e.g., "The Burned-Out New Mom," "The Skeptical Serial Returner")
- **Who they are** — 2–3 sentences on life context, situation, and identity signals visible in the reviews
- **Their pain** — the primary pain point driving them (drawn from Bucket 1)
- **Their trigger** — what typically pushes them to buy (drawn from Bucket 2)
- **Their objection** — what almost stopped them (drawn from Bucket 3)
- **Their transformation** — the change they describe (drawn from Bucket 4)
- **How they talk** — distinctive vocabulary, tone, and phrases characteristic of this persona
- **Estimated share** — rough proportion of the product's reviews this persona represents

### Then Go One Level Deeper: Micro-Personas

A persona describes the person. A micro-persona catches that person in a specific **moment** — the exact life stage, role, and circumstance they're in when the product enters their life, today and this week.

One persona usually contains several micro-personas. The same person is a different buyer at 2am on a work night than on a slow Saturday morning — and their awareness stage shifts with the moment. This is why awareness stage lives at the micro-persona level, not the persona level.

For each persona, extract **1–3 micro-personas** where the reviews carry enough situational detail. For each:

- **The moment** — name it by circumstance, not category ("Sunday night before the first week of school," not "back-to-school season")
- **Life stage** — where they are in life right now
- **Role** — who they're being in this moment: the advocate, the fixer, the researcher, the one holding it together
- **Circumstance** — the specific situation unfolding this week
- **Environment & context** — where they are, who's around, what else is happening in their family and personal life
- **Emotional state** — what they're feeling in that moment, in their own words where possible
- **Needs vs. wants** — what they need functionally vs. what they want emotionally
- **Awareness stage** — unaware / problem-aware / solution-aware / product-aware / most aware, as evidenced in that moment
- **Product intersection** — how the product enters this exact moment
- **Evidence** — the review lines that establish this moment

Micro-personas must come from the reviews. Stacking more attributes onto a persona does not make a micro-persona — the move is circumstance and moment, not more qualifiers. If the review set doesn't carry this situational depth, say so plainly — that's a real finding. Never manufacture a moment.

---

## Output Format

Produce a separate full output for each product. Structure:

```
─────────────────────────────────────
PRODUCT / SERVICE: [Name]
Reviews received: [X] | Analyzed: [X] | Discarded (score 1): [X]
─────────────────────────────────────

BUCKET 1: PAIN POINTS

[Theme Name]
Summary: [2–3 sentences on the pattern]

[Theme Name]
Summary: [2–3 sentences on the pattern]

---

BUCKET 2: TRIGGER MOMENTS

[Theme Name]
Summary: [2–3 sentences on the pattern]

---

BUCKET 3: OBJECTIONS BEFORE PURCHASING

[Theme Name]
Summary: [2–3 sentences on the pattern]

---

BUCKET 4: TRANSFORMATIONS

[Theme Name]
Summary: [2–3 sentences on the pattern]

---

BUCKET 5: STANDOUT LANGUAGE & AD-READY PHRASES

"[Exact quote]"
"[Exact quote]"
"[Exact quote]"
[etc.]

---

PERSONAS — [X] identified
(Only if this product/service has 100+ reviews. Otherwise: "Personas skipped — under 100 reviews.")

[Persona Name] — ~[X]% of reviews
Who: [2–3 sentences]
Pain: [primary pain point]
Trigger: [what pushes them to buy]
Objection: [what almost stopped them]
Transformation: [what changed for them]
Voice: [distinctive phrases and tone]

  Micro-personas:

  [The Moment — named by circumstance]
  Life stage: [where they are in life]
  Role: [who they're being in this moment]
  Circumstance: [what's unfolding this week]
  Environment & context: [setting, family life, personal life]
  Emotional state: [what they're feeling, in their words]
  Needs vs. wants: [functional need / emotional want]
  Awareness stage: [unaware / problem-aware / solution-aware / product-aware / most aware]
  Product intersection: [how the product enters this exact moment]
  Evidence: "[review line that establishes this moment]"

  [Repeat for each micro-persona, 1–3 per persona — or: "Reviews don't carry enough situational depth for micro-personas."]

[Repeat for each persona, 3–5 total]

─────────────────────────────────────
```

All word-for-word quotes are collected in Bucket 5. Do not scatter quotes throughout buckets 1–4 — keep the summaries clean and let the swipe file be the dedicated place for raw language.

---

## How This Feeds the Rest of the Stack

The output of this analysis plugs directly into creative strategy and execution:

- **Pain Points → Creative Strategy Engine** — pain buckets map directly to the pain/desire anchor layer
- **Trigger Moments → Hook Writing** — trigger moments are often the most powerful hook material; they capture the exact moment of emotional readiness
- **Objections → Hook Writing / Creative Mechanics** — objections inform Borrowed Enemy, Reframe, and Risk Reversal mechanics and hook tactics
- **Transformations → Hook Writing** — transformation language feeds aspirational and social proof hooks
- **Standout Language → Hook Voice Patterns** — the best phrases can be added directly to the swipe file as native voice patterns pulled from real customers
- **Personas → Creative Strategy Engine** — personas plug directly into the persona layer of the pain/persona matrix, grounded in real customers instead of assumptions
- **Micro-personas → Hook Writing** — micro-persona moments are the deepest hook material available; the moment sets the awareness stage
- **Personas + Micro-personas → Gap Analysis** — the full persona output is the source of truth the gap-analysis skill compares live ads against

---

## Notes on Quality

- Score 5 reviews should be read in full and treated as primary sources
- Score 2–3 reviews are useful for pattern confirmation but not quote sourcing
- If a single product's review set is small (under 20 reviews), note this — patterns may not be statistically meaningful but language is still usable
- If a product has too few quality reviews to surface meaningful patterns, flag it rather than manufacturing themes that aren't there
