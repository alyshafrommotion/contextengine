---
name: creative-strategy-engine
description: A systematic framework for generating direct response ad concepts — product and customer in, through the map, ad concepts out. Use this when a user wants to map creative strategy for a brand, generate ad concepts, plan a campaign, cover the full funnel, define messaging angles, choose awareness stages, or go from a product and customer insight to a finished ad concept. Also trigger when the user says "run the engine," "map creative strategy," "build ad concepts," or starts a creative ideation session for a specific brand or product.
stage: 2-ideation
---

# ⚙️ Creative Strategy Engine

*A systematic framework for generating direct response ad concepts.*

---

This is the complete process from understanding your product and customer all the way down to the finished ad concept. It's a full map you can navigate to get to one really intentional ad, or hundreds of ads that cover a full funnel and are mapped strategically. It applies to any brand, any product, any campaign.

You come to this document with a goal: one ad, or many. Usually you enter at the top. Sometimes you enter in the middle, with a format or an angle or a hook you already want to try; there's a section for that below. Either way, the process is this map, and a concept isn't finished until it has walked all of it.

## The map

```
INPUTS  (pull from 1-research/working/<brand>/)
   product-catalog.md · voc-pulls.md · brand-context.md
        │
Step 1  ANCHOR on a pain or desire
        │  research surfaces it, product validates it
Step 2  PERSONA                                  → personas/
        │  group the anchor by life context
Step 3  MICROPERSONA · ends with THE OFFER       → personas/
        │  one layer deeper: the person you write for
Step 4  AWARENESS STAGE
        │  who are you reaching, what must the ad accomplish
Step 5  MESSAGING ANGLE                          → messaging-angles/
        │  the offer told through a strategy from the index
Step 6  VISUAL FORMAT                            → visual-formats/
        │  the container that fits the stage's job
Step 7  HOOK                                     → hooks/ · headlines/ · creative-mechanics/
        │  the opening expression: text and visual
        ▼
AD CONCEPT  → working/<brand>-ad-concepts.md  → 3-briefing
```

One really intentional ad. Or hundreds of ads that cover a full funnel, mapped strategically.

## The inputs: product and customer

Everything starts from two inputs, both produced by research and pulled from `1-research/working/<brand>/`:

- **The product:** the facts-only catalog. What it is, does, contains, costs, includes; its variations; the competitive landscape; the can-say list. If a claim isn't in the catalog, an ad can't make it.
- **The customer:** tagged VOC, with source, floor, and query on every quote. The floor decides which awareness stages a quote can honestly feed. Plus brand context, competitor analysis, and customer psychology as depth demands.

The engine consumes research; it never redoes it.

## Step 1: Anchor on a pain or desire

Any product gets found in two ways: through a pain (a problem they have) or a desire (something they want). Choose one for this run. Research surfaces the candidates: the pains and desires that show up across the VOC in the customer's own words. The product validates the pick: can we credibly solve for it? One lane per run; if two pains keep pulling at you, that's two runs.

## Step 2: Find the persona

**Pull from:** `personas/persona-definitions.md` for what each level means. **Write to:** `personas/working/`.

Group the anchor by life context. A persona is a group of people who share the pain or desire AND a life context. Same pain, different lives means different personas: two people can share a symptom and nothing else about how it shows up, what they blame, or what they'd believe. The test: if two "personas" would get the same stories told to them, they're one persona.

## Step 3: Go one layer deeper: the micropersona

**Pull from and write to:** `personas/`.

Re-read the VOC inside one persona. Different people in it need different stories. A micropersona is a fully realized human at the intersection: what they've tried, what they already do every day, how bad it is, how they see themselves, what they've accepted, what they're afraid of, what they wish they could change. This is the level you write creative from. Only split a micropersona off when the split changes the ads you'd make.

**This step ends with the offer.** The offer is what the product means for this specific person, in words they'd use. There's a meaningful distinction between selling and offering:

**Selling** says: "An electrolyte supplement with 150mg of sodium."
**Offering** says: "The thing that stops the headache before it becomes 48 hours of your life gone."

**Selling** says: "A tween bra with adjustable straps."
**Offering** says: "A bra that grows with your daughter so you don't have to keep buying new ones."

A strong offer names her specific outcome, sounds like something she would say she needs, and sets up the messaging angle directly.

## Step 4: Choose the awareness stage

The stage is a strategic decision made before creative work: who are you reaching, and what does the ad need to accomplish for them? Each stage has a job: make the problem exist (Unaware), validate and agitate it (Problem-Aware), position the category (Solution-Aware), win the comparison (Product-Aware), close (Most-Aware).

**Funnel strategy:** start Product-Aware, the people actively evaluating options. Add Most-Aware only for intentional pushes: a sale, a limited offer, clearing a SKU. Once Product-Aware works, scale upward into Solution-Aware, then Problem-Aware, then Unaware; the upper funnel is where new customers come from. Never let Most-Aware dominate outside sale periods.

One honesty check before moving on: some people can't be met at some stages. Someone who already bought and quit a competitor can't honestly be spoken to as Unaware. Note it and pick a stage that's true.

## Step 5: Choose the messaging angle

**Pull from:** `messaging-angles/messaging-angle-index.md`.

The angle is the offer told through a strategy from the index, for this micropersona, at this moment. The strategy is reusable; the angle is specific. The check: can this angle do this stage's job without contortion? If you're bending it to fit, change the angle or change the stage.

The angle's core truth stays the same wherever it runs; only the expression changes. That's what makes one angle able to serve several stages when you're producing in volume.

## Step 6: Choose the visual format

**Pull from:** `visual-formats/visual-format-index.md` and `visual-formats/formats/`.

Format is the container for the message. Match the container's purpose to the stage's job: formats that reveal for stages that reveal a problem, formats that prove for stages that prove superiority. Any format can work at any stage when the messaging is right; the index's saved examples tell you where each one lives naturally. Executing one angle across multiple formats gives you more chances to connect: different people stop for different things.

## Step 7: Write the hook

**Pull from:** `hooks/hook-index.md` (video), `headlines/headline-index.md` (statics), `creative-mechanics/creative-mechanic-index.md` (moves to deploy inside it).

The hook is the opening expression of the angle, at this stage, in this format. Text and visual together: the words that stop the scroll and the frames that earn the next second. The swipe collections are there to draw from; the mechanics index holds devices that work without words at all.

**Micropersona + offer + angle + stage + format + hook: that's a full ad concept.** Log it as one row in `working/<brand>-ad-concepts.md` and it's ready for briefing.

## Entering in the middle

Usually you enter at the top. Sometimes you arrive mid-map with a component already in hand. That's allowed; entering mid-process doesn't skip the steps, it just changes the order you walk them.

- **A visual format you want to try:** Step 6 is answered. Work backwards: which stage does this container naturally serve, and which micropersona and angle give it something worth saying? A format without an angle is an empty container.
- **A messaging angle you want to try:** Step 5 is answered. Check it against a real micropersona, write the offer if it isn't written, then find the stage where the angle works without contortion.
- **A persona your research didn't surface:** Step 2 arrived early. Go deep enough to write the offer, then walk forward normally. Drop a note in `1-research/working/` so the research catches up to what you noticed.
- **A hook you think is smart:** Step 7 arrived first, which is backwards, and that's fine. A hook implies an angle and usually a stage; name them explicitly. If you can't say who it's for and what it's doing, it's a clever line, not an ad concept yet. Save it to `hooks/hook-index.md` either way.

## One ad or many

One goal, one pass through the map, one concept: that's a complete use of this engine.

When the goal is volume ("cover the funnel for this micropersona," "ten concepts for the sale"), run more passes: one micropersona carries many angles, one angle expresses differently at each stage it honestly serves, and one concept can ride multiple formats. Every concept gets a row in `working/<brand>-ad-concepts.md` so the batch stays visible. If you want a coverage view across everything you've made, `python3 _tools/build-matrix.py <brand>` renders that log as a map. Optional tooling, not the process.

## The loop

The engine is stage 2 of the flywheel: research (stage 1) produces its inputs, briefing (stage 3) receives its concepts, and analysis (stage 7) feeds learnings back into the libraries. A strategy that keeps winning gets its index entry expanded; a format that keeps dying at a stage gets its notes corrected; a hook that gets quoted back goes in the swipe file. An index that never grows means you stopped looking.
