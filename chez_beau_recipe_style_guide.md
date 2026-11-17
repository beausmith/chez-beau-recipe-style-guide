# Chez Beau Recipe Style Guide

*Reference works: Chicago Manual of Style, 16th edition; The Deluxe Food Lover's Companion, 2015; UC Food Style Guide.*

*Where this guide is silent, refer to Chicago.*

---

## Introduction

This guide governs the format, language, and organization of all Chez Beau recipes. Its purpose is consistency, clarity, and a clean professional voice across every recipe, whether written by a chef, an editor, or a contributor.

The guide is a living document. Conventions are developed iteratively through real recipe work and documented as edge cases surface, rather than designed in the abstract.

---

## 1. Voice & Tone

Chez Beau recipes are written in a clean, professional register — culinary school in standard, not home-cook casual. The goal is clarity and instruction, not personality. Recipes should read as if written by a confident, knowledgeable cook who respects the reader's intelligence.

Avoid casual filler, rhetorical questions, and unnecessary encouragement. Step labels and headings stay terse and imperative — avoid charming or cute phrasing (see _Step Labels & Lead-Ins_, Section 3).

The Description (when used) and Notes may take a slightly more personal tone. Use them to provide context, technique tips, or sourcing notes. Keep them concise.

Avoid direct address everywhere — including the Description and Notes. Refer to things directly (e.g., "the oven"), never through the reader (e.g., "your oven").

Where a technique benefits from explanation, explain the why — the purpose is to teach technique, not merely to direct action. See _Technique Notes Within Steps_ in Section 3 for placement rules.

---

## 2. Recipe Structure

### File Order

A recipe file is structured top-to-bottom in the following order. Sections marked _(optional)_ appear only when relevant; all other sections are required. Use a horizontal rule (`---`) to separate top-level sections.

1. **Title** (`#` heading)
2. **Source attribution** — italicized line, immediately after the title (see Section 10)
3. **Yield and Time Metadata** — bold-labeled lines (see _Yield_ and _Time Metadata_ below)
4. **Log** _(optional)_ — `## Log` (see _Log_ below)
5. **Description** _(optional)_ — `## Description` (see _Description_ below)
6. **Ingredients** — `## Ingredients`
7. **Equipment** — `## Equipment`
8. **Instructions** — `## Instructions`
9. **Notes** _(optional)_ — `## Notes`

The instruction steps are headed **Instructions**, not "Directions." _Rationale: "Instructions" is the more precise term for step-by-step procedure, and it is the term used by the Wikipedia page for "Recipe."_

### Recipe Title

The title names the core dish. Use "&" to join equal components. Use "with" to append a distinct secondary preparation or accompaniment. Sides and garnishes never appear in the title.

> *"Halal Cart Chicken & Rice" — equal components*
> *"Mouthwatering Chicken with Mouth-Numbing Vinaigrette" — secondary preparation*

### Yield

Express yield tersely.

- Use **"Serves"** for serving-based quantities: *"Serves 4"* / *"Serves 6–8"*
- Use a plain measurement for volume-based quantities (sauces, dressings, condiments): *"2 cups"*
- When yield depends on portion size, state the range and the basis: *"10–16 cookies, depending on portion size"* / *"Serves 3–4 (4 slices per person)"*

### Time Metadata

Immediately after the yield, optionally include **Active time** and **Total time** on consecutive lines, formatted as bold labels with the time as plain text.

> **Serves 4**  
> **Active time:** About 30 minutes  
> **Total time:** About 1 hour

When a recipe includes substantial hands-off time (marinating, resting, chilling), call it out within the total time line:

> **Total time:** About 1 hour, plus 1–4 hours marinating

Each line — including the yield line — ends with two trailing spaces so the lines render consecutively without paragraph breaks. Use "About" before single time estimates and en dashes for ranges (consistent with Section 4).

### Log

The Log captures dated session notes — observations, modifications, and lessons saved for the next time the recipe is made. It appears as a top-level (`##`) section between the time metadata and the Ingredients.

> ## Log
> 2026-May-05:
> - Made a double batch for family.
> - Tossed in 4 smashed cloves of garlic.
> - Reduced in the oven at 300°F with the lid ajar for an hour.
> - Modified recipe: reduced unsalted butter by 1 tablespoon so the recipe uses a half-stick of butter.

Format conventions:

- **Date format:** `YYYY-Mon-DD` (e.g., `2026-May-05`). Month is a three-letter abbreviation, capitalized.
- **Entry header:** the date on its own line, followed by a colon.
- **Notes:** a flat bulleted list beneath the date, one observation per bullet.
- **Multiple entries:** separated by a blank line, with the **newest entry at the top** so the most recent learning is the first thing read.
- Recipe modifications applied as a result of a session may be flagged inline within the relevant bullet (e.g., _"Modified recipe: …"_).

_Rationale: A Log preserves the cook's evolving relationship with the recipe — what was tried, what worked, what to remember next time. Placing it near the top puts the most recent lesson in front of the cook before they begin._

### Description

The Description is an optional prose introduction to the recipe. It appears as a top-level (`##`) section between the Log and the Ingredients.

Reserve the Description for recipes that are unusual or have unique knowledge or history worth preserving — a backstory, a cultural origin, a non-obvious technique premise, or context that materially shapes how the cook should think about the dish. Skip it for ordinary recipes; the recipe itself should speak for itself.

> ## Description
> Marcella Hazan's tomato sauce reduces canned tomatoes, butter, and a halved onion into a silky, deeply flavored sauce with no chopping and no garlic. The technique runs counter to most Italian-American tradition and was first published in _Essentials of Classic Italian Cooking_ (1992).

Keep the Description concise — one short paragraph in most cases. It may take a slightly more personal tone than the rest of the recipe (see Section 1), but never direct address.

### Ingredient List

The Ingredient list appears before the Equipment list in the recipe file. _Rationale: ingredients drive shopping; equipment is a downstream check once the cook is back in the kitchen with the groceries._

The ingredient list is intended for shopping and must be kept clean and scalable. It assumes cooking from zero; a chef holding pre-prepped components is trusted to substitute per their experience.

List ingredients in the order they are first used in the cooking steps.

When a recipe has multiple distinct components (e.g., the dish, a sauce, a garnish), use bold headers to label each group. Headers are terse Title Case noun phrases naming the component and always end with a colon.

> **Zucchini Sauce:** / **Pasta:** / **Garnishes:**

A blank line precedes each group header; no blank line follows it — the header sits directly atop its ingredient lines. The header line ends with two trailing spaces, like the ingredient lines beneath it, so it breaks cleanly.

When a recipe has only one component, omit group headers and list all ingredients in a single flat list ordered by use.

The **Garnishes:** section is treated as its own labeled subgroup and always appears with its label, even when the rest of the recipe has no group headers. It is presented at the end of the Ingredients section.

**For Serving:** is the alternate heading for this subgroup when the recipe is clearly meant to be added to a prepared base that needs no instructions — pasta, rice, potatoes, a grain. The base belongs under **For Serving:**, not **Garnishes:**; a base is not a garnish. Use **Garnishes:** when the items only top or finish the dish.

An ingredient may appear more than once in the list if it is used across multiple components. List it separately under each component where it appears.

Each ingredient line ends with two trailing spaces to produce a line break in Markdown rendering. This keeps each ingredient on its own line without adding blank space between entries. _Rationale: Ingredient lists are not formatted as hyphenated bullet lists, so the trailing two spaces are required to force line breaks. This convention also supports clean import into Paprika Recipe Manager (see Section 11). Do not remove the trailing spaces when editing files directly._

Ingredients are listed in their raw, unprepared state. Do not include preparation instructions in the ingredient list — all preparation belongs in the Mise en Place step.

> *"1 pound chicken breast" — not "1 pound chicken breast, cut into 1-inch pieces"*

**Product form is not preparation.** "Sliced bacon" and "ground beef" describe how an item is purchased and are permitted.

Olives are assumed purchased whole ("pitted" is a purchased form and may be stated). Sliced, chopped, or minced olives exist as products but are not assumed — chopping olives is preparation and belongs in the Mise en Place.

Do not include qualifiers that describe how an ingredient is divided or used across steps in the directions.

> *"2 tablespoons olive oil" — not "2 tablespoons olive oil, divided"*

**Exception:** Ingredients in the "Garnishes:" or "For Serving:" section may include brief preparation suggestions, as these are serving recommendations rather than required steps.

> *"Iceberg lettuce, roughly shredded"*
> *"Tomatoes, chopped"*

**Quantification.** Quantify every ingredient. Package-count units are permitted where that is how the item is bought, with the quantity range in parentheses immediately after the count.

> *"1 pack (12–16 ounces) sliced bacon"*

_Rationale: An experienced cook scales or adapts from a stated quantity, but an unstated one cannot be logged in a food tracking application or reproduced by anyone else._

**Line format.** Quantity precedes the ingredient name. When a substitution is available for an ingredient, list it in parentheses after the primary ingredient. Never embed a derived absolute quantity — a process benchmark, an intermediate yield — later in the line: Paprika scales only the leading amount, so anything after it falls out of sync when the recipe is scaled (see _Process Checkpoints_, Section 3).

> *"2 tablespoons parsley (or dill)"*
> *"0.5 cup crème fraîche (sour cream)"*

### Equipment List

The Equipment list appears after the Ingredient list and before the Instructions.

**Order.** List equipment in the order it is first used in the recipe, counting use within the Mise en Place. This mirrors the order-of-first-use convention for ingredients. When two items enter use simultaneously — a parchment-lined baking sheet — list the vessel before the consumable.

**Assumed kitchen baseline.** The following are assumed present in any kitchen. They are never listed in the equipment list and are not named in the instructions:

chef's knife, paring knife, cutting board, measuring cups and spoons, mixing bowls, tongs, spatula, wooden spoon, whisk, colander, kitchen towels.

**Scope.** List all non-baseline equipment critical to the preparation, whether or not the instructions name it — the tool-mention rule (Section 3) may omit a tool from the steps for concision without deleting it from the list. Consumables specific to a recipe — parchment paper, butcher's twine, toothpicks — are not baseline and are always listed.

_Rationale: Without the baseline rule, the tool-mention rule and the equipment-list scope would chain together such that editing a step for concision silently deletes an equipment line._

**Annotation.** After each item, note the recipe component(s) it will be used for in parentheses. Keep these notes concise.

> *"Large ovenproof skillet with lid (chicken, rice)"*
> *"Small bowl (white sauce)"*

Omit the annotation entirely when all equipment serves the same component — an annotation appearing identically on every line disambiguates nothing.

See Section 5 for preferred equipment terminology.

### Mise en Place

The Mise en Place is always presented as a step within the instruction sequence — not as a separate section. It is among the first steps of a recipe, but not necessarily the first: equipment setup with lead time — the oven preheat, bringing water to a boil — precedes it (see _Integrating Prep & Equipment Setup_, Section 3). In recipes with extended prerequisite preparation, the Mise en Place step can be a later step. _Rationale: once the cooking begins the chef must focus on the cooking to ensure the dish cooks correctly._

The oven preheat is always its own step. It is never folded into the Mise en Place.

A recipe with a distinct make-ahead component (e.g., a salsa or sauce prepared before the main dish begins) may carry a separate **Mise en Place** step per component. Each opens that component's phase and covers only that component's prep, so the component can be made on its own.

The label for this step is: **Mise en Place** — presented as a bold label followed by a colon, consistent with the step label system (see _Step Labels & Lead-Ins_, Section 3).

> *"**Mise en Place:**"*

When the Mise en Place contains only a single preparation task, omit the **Mise en Place** label entirely and present the task as a regular step. The label exists to group multiple prep tasks under one heading; for a single task it adds no clarity.

**Omit the Mise en Place step entirely when** no ingredient requires cutting, slicing, or other preparation and the setup is purely equipment.

**Baking recipes** where the work is measuring into a bowl, mixing, portioning, and baking all at once do not take a Mise en Place step — shared measuring tools and order of addition make separate steps the clearer structure. When multiple ingredients need preparation before entering the bowl, the Mise en Place step applies.

The Mise en Place contains a bulleted list of all preparation tasks that should be completed before cooking begins — ingredient prep and equipment setup without lead time. The goal is to ensure the cook can focus entirely on the cooking process without stopping mid-recipe. Only items requiring actual preparation are listed.

Each item begins with a verb and describes a single preparation task. The ingredient name is bolded, consistent with the call-out bolding rule throughout the recipe (see _Bold at Every Call-Out_, Section 3).

> *"Cut the **chicken breast** into 1-inch pieces."*
> *"Finely chop the **yellow onion**."*

Mise en Place items follow the order in which the ingredients appear in the recipe. Do not include steps for ingredients that require no preparation (e.g., pre-measured dry spices, liquids used straight from the container).

When similar preparation tasks apply to ingredients used in distinct steps, list them separately rather than combining them.

> *"Grate the **sharp cheddar cheese**." / "Grate the **Parmesan cheese**." — not "Grate both cheeses."*

Do not include preparation of suggested or optional serving ingredients in the Mise en Place.

### Notes

The Notes section appears at the bottom of the recipe file, after the Instructions, as a top-level (`##`) section. Use it to preserve static, recipe-level context that supports the recipe but does not belong in the body — most commonly:

- Original-work attribution when the immediate source republishes from a cookbook or other original work
- Sourcing notes, reference pointers, or other reader-facing context that does not shape the cooking itself

> ## Notes
> Originally from Marcella Hazan, _Essentials of Classic Italian Cooking_.

Notes is distinct from the **Log**: Notes is durable, recipe-level context; the Log is a stack of dated session annotations.

---

## 3. Instructions

### Step Format

Instructions are written as a sequence of unnumbered steps — one step per paragraph, separated by blank lines. Do not number the steps.

_Rationale: Step numbers are more confusing and distracting than useful. A number is a simple abstract way to refer to a specific step, but it is more useful to describe what to do than to require the reader to resolve a reference to another step by number. Managing step numbers also creates more work when editing a recipe._

When a later instruction depends on an earlier one, refer to it by what it does, not by a number.

> *"Return the bacon flipped earlier to the oven." — not "Return the bacon from step 5 to the oven."*

Sub-lists are the exception to blank-line separation: they attach directly beneath their parent step with no blank line (see _Variable Timing_ below).

### Step Labels & Lead-Ins

Every step opens with bold text so a cook returning mid-task can re-anchor by scanning for the marker.

**Label (the default):** a terse, imperative, Title Case phrase ending with a colon, followed by the step.

> _"**Caramelize the Zucchini:** Cook, stirring and scraping the bottom of the pan, until..."_
> _"**Combine Pasta and Sauce:** With the heat under the zucchini set to medium, add..."_

**Lead-in (for short steps):** when the step is a single brief action and a label would merely restate the sentence, bold the opening imperative verb instead — the verb only, not its object. A compound verb phrase is bolded in full ("**Continue baking**"). An ingredient object takes its own call-out bold.

> _"**Flip** each slice when the tops are nicely browned, about halfway through."_
> _"**Arrange** the **sliced bacon** on a parchment-lined baking sheet in a single layer."_
> _"**Garnish** with **basil leaves**, **Parmesan cheese**, and **black pepper**."_

Labels name the work, not the mood. Keep them terse and imperative; avoid charming, cute, or whimsical labels.

> _"**Combine Pasta and Sauce:**" — not "**Everything in the Pot:**"_

Step-opening bold and ingredient call-out bold (see _Bold at Every Call-Out_) are separate systems and are never merged: a label never absorbs an ingredient call-out, and a lead-in bolds only the verb — an ingredient that follows takes its own call-out bold ("**Arrange** the **sliced bacon**...").

The **Mise en Place:** label (Section 2) follows this system.

### Sentence Structure

Begin sentences with a verb. Write short, declarative sentences. A recommended structure is:

> verb → subject → equipment → treatment → technique → doneness cue → time
> *"Heat the milk in a small saucepan over low heat, stirring frequently, until hot and just beginning to bubble (about 8 minutes)."*

### One Task Per Step

Each step should contain one primary task. If a step contains a secondary action that happens simultaneously (e.g., stirring while something simmers), that may be included in the same step. Sequential distinct tasks belong in separate steps.

An action and the placement it necessarily implies constitute a single task. Removing a hot pan from the oven presumes setting it down, so the instruction for where to set it belongs in the same step.

**Labeled steps relax this rule.** A labeled step may contain a short sequence of actions when they form one continuous stage at a single station — same vessel, no intervening wait. The label carries the summary: a cook returning mid-task re-anchors on the bold label rather than on a half-finished paragraph. Lead-in steps remain strictly one task.

*Rationale: Chez Beau recipes function as teaching tools, not just procedures. Multi-task steps obscure technique by burying secondary actions. Separating tasks makes each one visible and learnable. A cook reads a step, executes it, and returns; two tasks in one step means returning to a half-finished instruction.*

Do not begin sentences with "Then." Sequence is implied by the order of the steps.

### Technique Notes Within Steps

Technique explanations follow the instruction — never precede it. State the instruction and its doneness cue first, then explain the technique and its purpose in a trailing clause or a separate sentence. Never open a sentence with a purpose clause.

> *"Stir frequently during the first 2 minutes of cooking to prevent the pasta from sticking." — not "To prevent the pasta from sticking, stir frequently during the first 2 minutes of cooking."*

> *"Add the yellow onion and cook until slightly translucent (about 2 minutes). Avoid browning — the goal is to soften the onion without developing color, which would alter the flavor of the sauce."*

Timing and condition clauses are not purpose clauses and may open a sentence — they tell the cook when to act, not why (see _Parallel Steps & Timing Triggers_).

> *"When browned bits build up on the bottom of the pan, deglaze with water."*

### Doneness Cues & Timing

Every cooking step should specify a visual or physical doneness cue, followed by a time estimate in parentheses. The cue is primary; the time is a reference.

> *"Cook, turning once, until golden brown on each side (about 6 minutes total)."*
> *"Broil until the topping is golden brown and crispy (1–2 minutes)."*

Use "about" before a single time estimate. Omit "about" when giving a range — the range itself implies approximation.

> *"until tender (about 3 minutes)" — single estimate*
> *"until just shy of al dente (6–8 minutes)" — range, no "about"*

Open-ended times ("40 minutes or more") are acceptable when variation in equipment or ingredients makes an upper bound unreliable. As with any timing, the doneness cue is written first and governs; the time is a reference.

> *"Cook until the zucchini is deeply browned and jammy (40 minutes or more)."*

### Multi-Step Timing

When a single cooking time spans several steps, describe the span by its actions — its starting and ending points — rather than by step numbers.

> *"Total baking time, from entering the oven until evenly browned, varies with the thickness of the bacon."*

### Parallel Steps & Timing Triggers

Do not use "Meanwhile." Open a parallel step with an explicit timing trigger tied to the concurrent process, so the cook knows when to start the step and what its timing depends on.

> *"As the zucchini nears completion, bring a large pot of water to a boil." — not "Meanwhile, bring a large pot of water to a boil."*

### Variable Timing

When timing varies by ingredient specification rather than by technique, the steps carry the timing for the benchmark specification named in the ingredient list. Alternates go in an unordered sub-list beneath the step.

> Bake until the fat has rendered and the slices sizzle steadily. Total baking time, from entering the oven until evenly browned, varies with the thickness of the bacon.
> - Regular-cut: 18 minutes
> - Thick-cut: 24 minutes
> - Sidfläsk: 40 minutes

Sub-lists sit directly beneath the parent step with no blank line separating them, so they read as part of the step.

The step introducing a sub-list ends with a period — not a colon or an ellipsis. Write the sentence so it stands complete on its own; the attached sub-list does the introducing. _Rationale: Paprika Recipe Manager renders any non-heading line ending in a colon as bold (see Sections 8 and 11), and an ellipsis reads as informal trailing-off._

### Component Naming via Labels

When a step produces a named component — a topping, a sauce, a marinade — name the component in the step label (see _Step Labels & Lead-Ins_). This gives the component a name that can be referenced naturally in later steps.

> *"**Make the Marinade:** In the blender, combine all the marinade ingredients."*
> *"**Make the Crunchy Topping:** In the small bowl, combine all the topping ingredients."*

When a step uses all the ingredients from a named group, reference them collectively rather than listing each individually.

> *"Combine all the marinade ingredients." — not "Combine the lemon juice, garlic, oregano, coriander, olive oil, salt, pepper, and MSG."*

When only a subset of a group's ingredients are used in a step, list them individually as normal.

Once a component has been named, refer to it consistently by that name in all subsequent steps.

A sub-recipe made within a larger recipe — a sauce, a marinade, a spice blend — is handled with this pattern: its ingredients get their own group header (Section 2), and its steps are introduced by component-named labels. A sub-recipe used across multiple recipes graduates to its own recipe file and is referenced by link.

### Bold at Every Call-Out

Bold an ingredient every time a step calls it into action — adding, stirring in, seasoning, garnishing. This applies in every step, not just the first use.

> *"Add the **grated zucchini**, **smashed garlic cloves**, and half the **basil leaves**."*
> *"Return the **cooked chicken** to the skillet."*
> *"Toss with the **reserved marinade** and any juices from the plate."*

If an ingredient name is used as a location reference, a state check, or other passive context rather than a direct call-out, do not bold it.

> *"Add the **sumac** to the squash and onions." — "squash" and "onions" are locations here and would not be bolded.*
> *"Gently stir until the pasta is glossed with sauce." — "pasta" is a state check here, not a call-out.*

Refer to a transformed or set-aside ingredient by its current state, and bold the state qualifier with the name: **grated zucchini**, **cooked pasta**, **reserved pasta water**, **remaining basil leaves**.

*Rationale: A cook scanning the page mid-task is looking for the next ingredient action. Bolding every call-out makes each one findable without hunting back for a first use, keeps reserved and reintroduced ingredients visible at the moment they matter, and removes first-use bookkeeping when editing steps.*

### Integrating Prep & Equipment Setup

Steps that require preheating — an oven, broiler, or skillet — or other lead time (bringing water to a boil) appear as early as possible in the cooking sequence, before the Mise en Place, so the equipment is ready when needed. The oven preheat is always its own step, never folded into the Mise en Place.

When using the same pan across multiple steps, open the subsequent step with context.

> *"In the same skillet over medium heat, add the onion and cook until softened."*

### Tool Mention

Name a tool in a step when it is crucial to the technique. Omit it where any competent cook would select the right tool unprompted. Concision is preferred wherever trust is warranted. (Omitting a tool from a step does not remove it from the Equipment list — see Section 2.)

### Articles

When equipment is first introduced in the instructions, use the indefinite article ("a" or "an"). Subsequent references use the definite article ("the").

> _"In **a** large saucepan over medium-high heat, combine..."_
> _"Reduce **the** heat to a gentle simmer."_

Articles may be omitted for brevity when meaning remains clear, particularly when listing **Garnishes:** or **For Serving:** ingredients in the final step.

> _"Serve over **pasta** and garnish with **Parmesan cheese** and **black pepper**."_

### Full Ingredient Names per Step

Use the full ingredient name — including color, variety, or other modifiers — on the first mention within each step. Subsequent mentions within the same step may shorten the name.

> _"...combine the **whole peeled tomatoes**, the **unsalted butter**, the white onion halves, and a pinch of **kosher salt**."_

_Rationale: A reader scanning a single step needs unambiguous reference to the ingredient. Short names (e.g., "the onion") work for the second reference within a step but can lose precision when steps are read in isolation._

### Optional Dispositions

When an ingredient or component would otherwise be discarded but has useful alternative uses, offer them in parentheses after the primary instruction.

> _"Remove the onion halves. (Optionally, blend or cut them into the sauce, or save them for another use.)"_

### Scalability in Instructions

Recipes are designed to scale. The ingredient list carries the exact total quantity of each ingredient; the instructions reference portions of that total relatively. When a source adds an ingredient in measured increments across steps, list the total and make each addition a relative reference.

Instructions never state an absolute ingredient measurement in any form — not as a decimal (0.5 teaspoon), not as a fraction (½ teaspoon), and not spelled out ("a half teaspoon"). Spelling a measurement out is not a workaround; it breaks scaling just the same, because it no longer tracks the ingredient list.

> *"Add half the kosher salt" — not "Add 0.5 teaspoon," "Add ½ teaspoon," or "Add a half teaspoon of kosher salt"*
> *"Add the remaining kosher salt" — not "Add the remaining 0.5 teaspoon of kosher salt"*
> *"Add a quarter of the mixture" — relative proportions of a listed whole are spelled out and permitted*

Use exact measurements in instructions only where precision is genuinely required for technique — salt for pasta water ("1 tablespoon of kosher salt per quart of water"), a measured liquid for sauce consistency ("1 cup of the reserved pasta water").

**Process checkpoints.** An intermediate weight or yield checkpoint (e.g., a roasted weight) is expressed relatively in the instructions — as a percentage or fraction of the starting quantity — so it survives scaling. Do not state the absolute benchmark anywhere: not in the instructions, and not attached to the ingredient line, where Paprika's scaling (which adjusts only the leading amount of a line) would leave it out of sync.

> *"The mushrooms should have lost about 60% of their raw weight; weigh them to check." — not "The roasted mushrooms should weigh 400–425 g"*

Per-unit specifications — the weight of one portion, one truffle, one cookie — are not batch checkpoints and may stay exact in the instructions; scaling a recipe changes the count of units, not their size.

This rule governs ingredient quantities. Physical dimensions in technique — pan sizes, slice thickness, headspace — are not ingredient measurements and follow the numeral conventions of Section 4 ("1-inch cubes"). Fractional dimensions are written as decimals, never spelled out or given as fraction symbols: *"0.5 inch from the top," "slices 0.125 inch thick."*

### Standard Phrases

- Increase the heat (not "turn up the heat")
- Remove from the heat (not "take off the heat")
- Let the meat rest (not "rest the meat")
- Set aside — use only if the ingredient will not be used in the next step
- **Flip** — the underside becomes the top
- **Rotate** — repositioning without inverting
- **Turn** — avoid; ambiguous between flip and rotate

---

## 4. Measurements & Numbers

### Numerals

Use numerals for all quantities: *4 tablespoons, 2 cups, 3 cloves.*

### Units

Spell out unit names in full: ounce, pound, tablespoon, teaspoon, cup.

Write out "inch" or "inches" — do not use the inch symbol (").

Use the degree symbol (°) and Fahrenheit abbreviation together for temperatures: *325°F*

When measurements or amounts are used as adjectives preceding a noun, hyphenate them.

> *"half-inch pieces" / "one-inch cubes"*

### Metric Equivalents

**Standard recipes (savory):** Imperial is the primary unit. When a source recipe includes metric equivalents, preserve them in parentheses after the imperial measurement. Do not add or remove metric equivalents independently of the source.

> *"2 tablespoons (30 ml) lemon juice"*

**Baking recipes:** Metric is the primary unit. Imperial equivalents appear in parentheses.

*Rationale: Baking is sensitive to precision in a way savory cooking is not. Volume measurements for flour and sugar are notoriously inconsistent — a cup of flour can vary by 20–30% depending on how it is scooped. Grams are unambiguous. The metric-primary exception for baking is intentional and should not be "corrected" to match the savory convention.*

> *"330 g (2.67 cups) all-purpose flour"*

**Recipe classification.** A baking recipe is defined by category — bread, pastry, desserts — not by technique. An oven-cooked savory dish is not a baking recipe. *Rationale: ratio precision governs doughs and batters; an oven alone does not make a recipe demand that precision.*

**Fermentation and other precision recipes** — shio koji, brines, cures, and enzyme- or hydrocolloid-driven preparations (transglutaminase, gels) — follow the baking convention: metric is primary, with imperial equivalents in parentheses. *Rationale: these preparations are governed by ingredient ratios by weight; grams keep the ratio exact where volume measures vary by salt brand and ingredient form.*

If a metric equivalent in a source recipe appears inaccurate, flag it with a note rather than silently correcting it.

### Oven Temperature

Fahrenheit is primary; Celsius follows in parentheses.

Convert oven temperatures using the standard table regardless of what the source states:

| °F | °C |
|---|---|
| 300 | 150 |
| 325 | 160 |
| 350 | 180 |
| 375 | 190 |
| 400 | 200 |
| 425 | 220 |
| 450 | 230 |
| 475 | 240 |

This overrides the preserve-source-metric rule for oven temperatures only. Ingredient weights continue to preserve the source.

*Rationale: Oven temperatures are a small closed set where house consistency outweighs source fidelity, and the variance is immaterial to the result.*

### Internal Temperature

Internal temperatures indicating doneness give Fahrenheit with an exact Celsius conversion in parentheses, never normalized to a table.

> *"165°F (74°C)"*

*Rationale: An oven temperature is an approximate setting and may flex. An internal temperature is the doneness criterion itself and may not.*

### Decimals

Use decimals for all measurements in the ingredient list. Do not use fraction symbols or spelled-out fractions. Round repeating decimals to the nearest practical value (0.33 cup, 0.67 cup).

*Rationale: Decimals are easier to scale. When doubling or halving a recipe, 0.5 cup × 2 = 1 cup is immediate arithmetic. ½ cup × 2 requires a mental conversion step first. This is especially valuable for recipes intended to be scaled by volume or batch size.*

> *0.5 cup — not ½ cup or one-half cup*
> *0.25 cup — not ¼ cup or one-quarter cup*
> *1.5 cups — not 1½ cups*
> *0.33 cup — not ⅓ cup*
> *0.67 cup — not ⅔ cup*

Instructions never reference a numeric decimal for an ingredient quantity — see _Scalability in Instructions_, Section 3. Fractional physical dimensions in instructions are written as decimals: *"0.5 inch," "slices 0.125 inch thick."*

### Ranges

For ranges of time or quantity, use an en dash (–).

> *"6–8 minutes" / "2–4 tablespoons" / "12–16 ounces" / "Serves 3–4"*

When cooking pasta, include a specific salt measurement as a benchmark.

> *"Add 1 tablespoon of kosher salt per quart of water."*

---

## 5. Equipment

Use consistent equipment names throughout all recipes. Do not substitute informal or alternate terms.

- **Skillet** — not "frying pan," "sauté pan," or "pan"
- **Baking sheet** — not "sheet pan," "sheet tray," or "half sheet pan"
- **Saucepan** — for smaller-volume tasks (heating sauces, warming grains)
- **Pot** — for large-volume tasks (boiling pasta, making stock)

Always specify the size of the skillet or saucepan where relevant: *"a 10-inch skillet," "a small saucepan."*

Two-dimension sizes — standard pans, sheets, and cuts of parchment — use the multiplication sign (×) with no surrounding spaces: *"8×13-inch," "8.5×4.5-inch loaf pan"* — not "8- by 13-inch," "8 x 13 inch," or "8 by 13 inches."

---

## 6. Ingredients

### Capitalization

Ingredient names are lowercase, except for proper nouns. Reference: UC Food Style Guide and The Deluxe Food Lover's Companion, 2015.

### Singular & Plural Consistency

The number (singular or plural) of an ingredient must remain consistent from its first mention through all subsequent references in the instructions.

> *If you say "dice the onion," say "add the onion" — not "add the onions."*

### Specificity

Name specific ingredients rather than general categories.

> *"Chop the parsley and the dill." — not "Chop the herbs."*

Clarify ingredient names that may be ambiguous.

> *"pork carnitas" not "carnitas"*
> *"feta cheese" not "feta"*
> *"Parmesan cheese" not "parmesan" (also acceptable: "Parmigiano-Reggiano")*

For canned, jarred, or otherwise packaged ingredients sold in multiple variants, name the specific variant matching the headline label on the package.

> *"whole peeled tomatoes" — not "whole tomatoes" or "tomatoes" — when the can specifies "whole peeled"*
> *"unsalted butter" — not "butter" — when the package specifies "unsalted"*

### Preferred Terminology

- Green onions — not "scallions"
- Sugar snap peas — not "snap peas"
- Vegetables — not "veggies" or "veg"

**Chile vs. chili.** The spelling follows the referent:

- **Chile** (with an "e") — the pepper fruit and plant, and dish names of Latin-American origin (*"Chile Verde"*)
- **Chili** (with an "i") — the American spiced meat stew (*chili con carne*) and powdered spice blends of dried chiles (*chili powder*)

When it is unclear which spelling a recipe calls for, ask for clarification rather than guessing.

### Ingredient Assumptions

**Salt.** The house salt is **Diamond Crystal kosher salt**. Use it wherever salt is called for unless a recipe specifically requires another salt (a flaky finishing salt, a curing salt). Table salt and iodized salt are never carried into a recipe — drop them, or convert the quantity to kosher salt (Diamond Crystal measures roughly twice the volume of table salt: 1 teaspoon table salt ≈ 2 teaspoons Diamond Crystal). Remove source parentheticals that accommodate other salts (e.g., "half as much if iodized"). In baking recipes, name the brand in the ingredient line — volume-per-gram differs by brand, and baking demands the precision; in savory recipes, "kosher salt" alone implies Diamond Crystal.

The following ingredients are assumed to be used as a matter of course and should never be labeled "(optional)":

- **MSG** — a standard seasoning in professional kitchens. Include without qualification. *Rationale: Labeling MSG "optional" implicitly endorses its undeserved reputation as a problematic ingredient — it implies the ingredient is a compromise rather than a seasoning used deliberately. It is not optional in the same way salt is not optional. Hedging on it is a culinary apology Chez Beau does not make.*

### General Assumptions (Unstated)

The following do not need to be stated in the recipe:

- Onions and garlic are peeled.
- All produce is washed.
- Ingredients are removed from packaging before use.

### Diacriticals & Special Characters

Foreign ingredient names always retain their diacritical marks, including words naturalized into English:

- crème fraîche
- crêpe
- sauté / sautéed
- frisée
- jalapeño
- sidfläsk
- habanero (not habañero)

---

## 7. Cook Competency Assumptions

Chez Beau recipes assume a baseline level of kitchen competency. Do not include warnings or reminders about things a reasonable cook should already know.

Do not warn about:

- Hot equipment — if heat is involved, the cook understands handles and baking sheets will be hot
- Steam from boiling water or covered pots
- Sharp knives
- The need to use oven mitts when removing items from the oven or broiler
- Oil splatter during sautéing or frying

Safety information that is genuinely non-obvious — a technique-specific hazard the cook would not reasonably anticipate — may be included in the Notes, not inline in the instructions.

### Storage Instructions

Storage instructions are omitted by default — a competent cook understands how to refrigerate, freeze, and store food to maintain quality. Include storage notes only when the recipe requires unusual handling (e.g., a fermentation that needs a specific temperature, a sauce that breaks if frozen, a component that must rest for a defined period before use).

---

## 8. Punctuation & Grammar

- Use the serial comma: *"green onions, garlic, and ginger."* Exception: no serial comma when using an ampersand — the ampersand provides sufficient separation.
- Commas and periods always go inside double quotation marks.
- Use definite and indefinite articles consistently: *"Preheat the oven." / "Pour the soup into a small bowl."*
- Use a hyphen when two words together modify a noun (*"high-heat oil," "bite-sized pieces"*) and when meaning would otherwise be unclear (*"re-cover," not "recover"*). For edge cases (e.g., no hyphen after "-ly" adverbs), follow Chicago.
- Do not hyphenate permanent compounds: *"ovenproof," "nonstick."*
- Add only one space after all punctuation, including periods.
- Do not use a dash in place of "to" in ranges — use an en dash: *"6–8 minutes."*
- Use a semicolon to combine two tightly related sentences. Reserve the em dash for strong emphasis or an abrupt break in thought: *"The slow simmer emulsifies the butter into the tomato liquid; this is what gives the sauce its silky body."*
- Do not end a non-heading line with a colon — Paprika Recipe Manager renders such lines as bold (see Section 11). Lines that are bold by design and end in a colon (ingredient group headers such as **Zucchini Sauce:**) are unaffected, as are step labels whose colon falls mid-line (*"**Make the Marinade:** In the blender..."*).

---

## 9. Markdown Formatting Conventions

- **Italic:** use single underscores: `_italic_` — not `*italic*`
- **Bold:** use double asterisks: `**bold**` — not `__bold__`
- **Bold italic:** combine the two: `**_bold italic_**`
- **Ingredient line breaks:** end each ingredient line with two trailing spaces (see Section 2, Ingredient List).
- **Ingredient group headers:** blank line above, none below; the header line also ends with two trailing spaces (see Section 2, Ingredient List).
- **Step spacing:** instruction steps are unnumbered paragraphs, separated by blank lines (see Section 3, Step Format).
- **Step openers:** every step opens with a bold label or bold lead-in (see Section 3, Step Labels & Lead-Ins).
- **Sub-lists:** a bulleted sub-list sits directly beneath its parent step with no blank line separating them (see Section 3, Variable Timing).

---

## 10. Source Attribution

When a recipe is adapted from an external source, preserve the source name and URL **at the top of the recipe file, immediately after the title**. This keeps provenance visible and supports future reference.

> _Source: [Recipe Name](https://example.com/recipe-url) — Publication or Author_

### Storage

Storage information from a source recipe is omitted by default, consistent with Section 7 — a competent cook knows how to refrigerate, freeze, and store food. Preserve it as a final `## Storage` section (level-2 heading, after the Instructions) only when it describes genuinely unusual handling the cook would not anticipate — a fermentation temperature, a sauce that breaks when frozen, a defined rest before use.

---

## 11. Future Goal: Paprika Recipe Manager Integration

The long-term goal of the Chez Beau Recipe Converter project is to read and write recipes directly to and from **Paprika Recipe Manager**, so Paprika becomes the canonical storage location for the recipe collection. In the interim, recipes are stored as Markdown files because the format is simple, portable, and effective.

Several conventions in this style guide are influenced by eventual Paprika compatibility — most notably the trailing two-space ingredient-list convention, which preserves clean line breaks when recipes are imported, and the rule against ending non-heading lines with a colon, since Paprika renders any such line as bold (see Section 8).

---

## 12. Word List & Quick Reference

### Preferred Terms

| Use | Avoid |
|-----|-------|
| Skillet | pan, frying pan, sauté pan |
| Baking sheet | sheet pan, sheet tray, half sheet pan |
| Green onions | scallions |
| Sugar snap peas | snap peas |
| Vegetables | veggies, veg |
| Chile (pepper; Latin-American dish names) | "chili" for peppers |
| Chili (American stew; spice blends) | "chile" for the stew |
| Kosher salt (Diamond Crystal) | table salt, iodized salt |
| Flip / Rotate | turn (ambiguous between the two) |
| Increase the heat | turn up the heat |
| Remove from the heat | take off the heat |
| Let the meat rest | rest the meat |
| Prep | prepare |

### Words to Avoid

- **Then** — do not use to begin a sentence; sequential steps are implied
- **Meanwhile** — open parallel steps with an explicit timing trigger instead (see _Parallel Steps & Timing Triggers_, Section 3)
- **Turn** — ambiguous; use "flip" (invert) or "rotate" (reposition)
- **If necessary** — teach the cook when to act instead of hedging
- **Pan** — always specify: skillet, saucepan, or pot

---

## 13. Open Areas

Not yet formalized. Decisions pending as recipes surface them.

- Editorial and testing checklists
