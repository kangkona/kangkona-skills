---
name: strategic-naming
description: Create, stress-test, and present distinctive names for companies, products, features, categories, campaigns, AI systems, and technical projects. Use when the user asks for naming, renaming, brand name ideas, product names, startup names, feature names, codename-to-brand work, name evaluation, or a naming process inspired by Lexicon Branding-style strategic naming.
---

# Strategic Naming

## Overview

Use this skill to run a rigorous naming process instead of a loose brainstorm. Treat names as strategic assets: define what the name must make true, generate across multiple linguistic lanes, screen for sound/meaning/risk, then present a short list with rationale and decision support.

If the user asks for the research behind this process, read `references/lexicon-public-research.md`.

## Operating Modes

Keep the core workflow below as the default. Choose the lightest overlay that fits the user's request:

- `generation`: The user wants new names. Run the full workflow.
- `evaluation`: The user brings existing candidates. Diagnose first, then score and rank them.
- `architecture`: The user needs a system of names: parent brand, product, feature, action verbs, objects, domain, Chinese/local names, or taglines.
- `validation`: The user is close to a decision and needs collision, domain, handle, pronunciation, or trademark-style first-pass checks.
- `handoff`: The name is chosen and the user needs a naming package, launch copy, visual brief, or brand-system guidance.

Do not turn every request into a long workshop. If the user is iterating quickly, answer in tight decision language, but keep the same underlying screen: strategy, distinctiveness, linguistics, and risk.

For fast live naming sessions, keep a lightweight decision trail as the brief changes. Track what the user has accepted, rejected, corrected, and newly emphasized. Treat later corrections as brief updates, not contradictions: update the naming thesis, prune stale lanes, and explain how the strongest candidate changes under the new brief.

## Core Workflow

### 1. Define The Win

Capture the naming brief before generating names. If the user has not provided enough context, make reasonable assumptions and label them.

Answer these questions:

- What is being named: company, product, feature, campaign, category, model, internal tool, or codename?
- Who must adopt it: buyers, users, developers, partners, press, investors, employees, regulators?
- What should the world believe after hearing the name?
- What is materially different from alternatives?
- What feeling should the name create: trust, speed, craft, intelligence, warmth, precision, rebellion, calm, luxury, etc.?
- What must the name never imply?
- What languages, regions, categories, competitors, and trademark classes matter?
- Is the goal descriptive clarity, ownable distinctiveness, category creation, or cultural memorability?

Write a one-paragraph naming thesis before proposing names.

If the product has both an obvious entry feature and a broader long-term promise, separate them explicitly:

- `first impression`: what the user immediately understands or experiences in the first 5 seconds.
- `durable promise`: what the brand should still mean after the product expands.
- `bridge`: the idea that makes the first feature and the long-term promise feel like one product rather than two unrelated claims.

Do not let the durable metaphor hide the entry feature. Conversely, do not let the first feature trap the brand in a narrow utility category if the product has a wider emotional or workflow promise.

### 2. Build Strategic Lanes

Create 4-7 lanes before individual names. Use lanes to prevent a single style from dominating too early.

Common lanes:

- `functional`: names that signal the job, outcome, or category.
- `metaphoric`: names that borrow meaning from nature, movement, craft, physics, mythology, architecture, or tools.
- `experiential`: names that evoke how the product feels to use.
- `foundational`: short invented or semi-invented words that can hold broad meaning over time.
- `compound`: two familiar parts combined into a new, ownable whole.
- `phonetic`: names led by sound symbolism, rhythm, mouthfeel, speed, softness, or strength.
- `contrarian`: names that reject category cliches and create curiosity.

For each lane, state what strategic belief it supports and what risk it carries.

When a user points to an admired reference name, extract the naming mechanism rather than copying the surface. For example, identify whether they like that it is a short real word, an object metaphor, a rescue image, a calm tone, a strong verb, or a memorable mouthfeel. Then generate names that use the same mechanism without imitating the reference.

### 3. Generate Broadly

Produce more raw candidates than needed, then filter. Avoid presenting the first plausible batch as the answer.

Generation rules:

- Generate at least 40 raw candidates internally for standard tasks before selecting.
- Mix real words, blends, compounds, coined words, compressed phrases, foreign-root-inspired forms, and metaphor names.
- Prefer names that can grow beyond the first feature if the product may expand.
- Include unexpected lanes even when the brief seems obvious.
- Avoid generic AI, cloud, data, and productivity cliches unless the user specifically wants category clarity.
- Do not imitate existing famous names, competitor names, private artifacts, or protected marks.

### 4. Screen With The Naming Diamond

Score candidates against four dimensions:

- `strategy`: Does it express the desired positioning or productive tension?
- `distinctiveness`: Is it memorable, ownable, and different from category defaults?
- `linguistics`: Is it pronounceable, rhythmic, spellable enough, and emotionally appropriate?
- `risk`: Does it avoid obvious trademark, competitor, cultural, domain, and negative-association problems?

Use a 1-5 score for each dimension when narrowing. Discard names with severe risk even if they sound good.

For evaluation mode, start by identifying the failure state before scoring:

- `does-not-feel-right`: stakeholders dislike it but cannot explain why.
- `family-mismatch`: names in a system do not sound like they belong together.
- `forgettable`: the name blends into category defaults or has no hook.
- `wrong-signal`: it implies the wrong category, market, tone, or user promise.
- `practical-friction`: hard to say, spell, type, search, own, or localize.

Then analyze four layers:

- `sound`: phonemes, rhythm, mouthfeel, seriousness, speed, warmth, sharpness.
- `meaning`: literal meaning, metaphor, implication, narrative potential.
- `culture`: category conventions, market expectations, cross-language or local associations.
- `function`: spelling, pronunciation, searchability, domains, handles, trademark class risk.

This diagnostic pass prevents taste-only opinions. It should explain why a name works or fails before replacing it.

Use the SMILE/SCRATCH filter as a final quick screen:

- `SMILE`: suggestive, memorable, image-making, has legs, emotionally appropriate.
- `SCRATCH`: spelling-challenged, copycat, restrictive, annoying, tame, curse-of-knowledge, hard to pronounce.

Names do not need to maximize every SMILE dimension, but a finalist should not trigger a serious SCRATCH problem.

### 5. Apply Sound And Shape

Use sound intentionally:

- Plosives (`b`, `p`, `t`, `d`, `k`, `g`) can feel crisp, fast, decisive, technical, or energetic.
- Fricatives (`f`, `v`, `s`, `z`, `sh`) can feel fluid, airy, precise, fast, or modern.
- Liquids/nasals (`l`, `r`, `m`, `n`) can feel warm, smooth, premium, human, or stable.
- Open vowels can feel broad, calm, friendly, or expansive.
- Tight/front vowels can feel small, quick, sharp, light, or precise.
- Short names travel well but can feel empty unless the story is strong.
- Descriptive names are easy to understand but often weak for ownership and long-term extension.

Match sound to strategy; do not decorate names with arbitrary letters.

### 6. Run Practical Checks

Do lightweight checks before recommending a finalist:

- Search the web for exact phrase collisions when possible.
- Check obvious competitor/category conflicts.
- Check obvious domain and handle availability signals when relevant, but do not over-optimize for `.com`.
- Check whether a clever domain hack weakens the actual brand name.
- Inspect DNS, WHOIS/RDAP, registrar pages, and live parking pages when domain ownership matters.
- Flag trademark risk as preliminary; never claim legal clearance unless a qualified search was performed.
- For US software/SaaS contexts, treat Nice classes 9 and 42 as especially relevant first-pass screens; add class 35 if business/marketing services and class 36 if fintech.
- Check pronunciation and spelling friction.
- Check unwanted meanings in priority languages when the user names target geographies.
- Say when a name is a high-upside risk rather than a safe option.

Separate three kinds of risk:

- `collision`: an existing product, repo, company, or open-source project creates confusion.
- `ownability`: domain, handle, searchability, or trademark first-pass problems.
- `semantic`: unwanted meaning, category drift, cultural mismatch, or misleading metaphor.

When evidence is live or time-sensitive, browse before asserting it. When the check is incomplete, label it as a first-pass screen.

Separate brand decision from domain decision:

- Pick the strongest brand first.
- Then design a realistic domain strategy: canonical domain, defensive domains, redirects, watchlist/acquisition targets, and domains not worth chasing.
- Prefer domains that preserve the brand over domains that rename the product. For example, a prefix domain can be acceptable if the product name remains the short brand and the prefix is only the URL.
- Do not present DNS absence, WHOIS/RDAP 404, or registrar search results as legal clearance. State the check date and the confidence boundary.

### 7. Present Decision-Ready Names

Do not dump a giant list. Present 8-15 strong candidates unless the user requests more.

For each finalist include:

- Name
- Lane
- Why it works
- Sound/structure note
- Risk or caveat
- Best-fit use case

End with:

- Top 3 recommendation
- Names to reject and why
- Next validation steps: audience test, legal search, domain/handle search, pronunciation test, internal stakeholder story

In iterative sessions, maintain a compact reject ledger. Do not re-suggest names the user has rejected unless the brief has materially changed and you explain why the name deserves reconsideration under the new constraint.

If the user is near a decision, produce a compact naming package:

- `finalist`: name, pronunciation, spelling notes.
- `positioning line`: what the name should make people believe.
- `brand architecture`: parent brand, product object, action verbs, feature names, local-language layer.
- `domain strategy`: canonical domain, redirects, defensive registrations, and what not to use as canonical.
- `first impression`: the entry feature or immediate user takeaway that the name must not obscure.
- `proof`: why it wins against the strongest alternatives.
- `risks`: collision, ownability, semantic, cultural, and legal-first-pass risks.
- `next checks`: legal counsel, buyer/user pronunciation test, domain/handle acquisition, and naive-audience association test.

## Output Template

```markdown
## Naming Thesis
[One paragraph: what the name must accomplish and what tradeoff we are choosing.]

## Lanes
- **[Lane]**: [strategic idea] | Risk: [risk]

## Shortlist
| Name | Lane | Why It Works | Sound/Shape | Risk |
| --- | --- | --- | --- | --- |
| [Name] | [Lane] | [Rationale] | [Phonetic note] | [Caveat] |

## Top 3
1. **[Name]** - [why this should win]
2. **[Name]** - [why this is a strong alternate]
3. **[Name]** - [why this is a different strategic route]

## Reject
- **[Name/style]**: [why it should not be chosen]

## Validation
- [Concrete next check]
```

## Quality Bar

Good naming work should feel inevitable after the rationale, but not obvious before it.

Reject names that:

- Merely describe the feature.
- Sound like a generic SaaS, AI, crypto, or productivity template.
- Depend on a long explanation to avoid confusion.
- Are too close to a competitor or famous brand.
- Optimize only for domain availability.
- Flatten the product into a smaller category than it can become.
- Please internal stakeholders but create no external memory.

Prefer names that:

- Carry a crisp strategic point of view.
- Create a memorable mental picture or feeling.
- Have phonetic energy that matches the product.
- Can support a brand story, visual identity, and product expansion.
- Are different enough to be noticed but not so strange that adoption becomes the whole job.

## Common Anti-Patterns

- `beauty-contest testing`: Asking people which name they like usually selects the least offensive option. Test what people remember, infer, and can spell.
- `inside-joke naming`: Names that only make sense to the founding team create avoidable adoption cost.
- `domain-led naming`: Do not pick the weaker brand just because a domain is cheaper; choose the brand, then design a realistic domain strategy.
- `suffix chasing`: Trendy endings such as `-ly`, `-ify`, `-io`, `-hub`, and `-labs` can work, but only when they serve the strategy rather than disguise generic thinking.
- `single-feature trap`: Avoid names that make the product sound smaller than its future scope unless the user explicitly wants a narrow feature brand.
- `metaphor-before-entrypoint`: A beautiful metaphor can still fail if users cannot understand the first product use. Pair abstract names with a sharp first-impression line.
- `untracked-iteration`: In fast naming chats, failing to remember rejected names, changed audiences, or newly stated core features causes circular recommendations. Keep the decision trail current.
- `over-coining`: Invented names need sound, shape, and story. If the whole value depends on explanation, keep generating.

## Brand-System Handoff

When a name is chosen and the user asks for next steps, hand off cleanly:

- For copy: write one-line positioning, homepage hero, tagline options, and a short founder explanation.
- For visual identity: define the core metaphor, symbol logic, color/typography mood, and what visual cliches to avoid.
- For product language: define the verbs and objects users will see in UI, docs, CLI, and sales copy.
- For localization: decide whether the local-language name is a translation, expressive layer, or separate brand; avoid literal translations that flatten the story.
- For artifacts: if the user asks to write the package into a document, deck, issue, or repo file, preserve the decision trail and include the chosen name, first-impression promise, brand story, domain strategy, risks, and next checks.

Names should leave behind a vocabulary system, not just a word.
