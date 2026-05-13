---
name: play
description: Take a creative detour. Rolls four dice — an unrelated topic, a creative exercise, a constraint, and a reflection move — and produces one small textured artifact (poem, dialogue, field note, museum label, taxonomy, ritual, etc.). Use when the user types /play, asks for a creative detour, wants to break out of a stuck pattern, or wants a generative side-quest. Bridges back to active project work only when an honest connection appears.
---

# /play — Rigorous Creative Play

You are running a structured creative-play exercise. The goal is to make one small, textured artifact — not a brainstorm, not a list of ideas, not a generic "here are five approaches." Texture means: a poem with line breaks that matter, a dialogue with two distinct voices, a field note with specific observations, a museum label with an invented provenance, a taxonomy with weird categories.

Generic output is failure. Strangeness is the point.

## The four-slot model

Every run rolls four dice:

1. **Topic** — an unrelated subject Claude will draw from
2. **Exercise** — the primary creative mechanic shaping the output
3. **Constraint** — a single weird rule the output must obey
4. **Reflection** — how to close, optionally bridging back to the user's work

If the user passes overrides (e.g. `topic:fungi`, `exercise:found-poem`, `constraint:as-a-lullaby`), respect those exactly and roll the remaining slots. Otherwise roll all four.

**Rolling honestly:** don't always pick the obvious or most "appropriate" combo. The constraint and topic should feel a little wrong for the moment — that's where the surprise lives. If something feels too tidy, re-roll one slot.

## Slot 1 — Topic library

Pick one. (This list is a seed; invent your own if a better one occurs to you.)

`coral reefs · train stations · calligraphy · fungi · courtroom procedure · jazz ensembles · weather systems · lighthouse keeping · beekeeping · sourdough starters · monasteries · taxidermy · glass blowing · knot tying · marsh ecology · postal sorting · paper marbling · scrimshaw · foley artistry · embroidery · lock picking · archaeology · lichen · tide pools · candle wicks · public transit announcements · escalator mechanics · cave systems · funicular railways · semaphore · saltpans · falconry · bookbinding · clockwork · pigeon racing · river deltas · auction houses · monastic chant · cartography · etymology · sleep cycles · termite mounds · dovecotes · ferment cellars · scrying · barometers · estuaries · ham radio · drystone walls · pneumatic tubes · canals · tarot · gut flora · puppetry · mosses · ice cores · rust · streetlamps · barnacles · campanology · pollen · ferries · neon signs · the post-office mail train · marbles · weaving · printmaking · stagehands · cairns`

## Slot 2 — Exercise library (the 18 mechanics)

Pick one as the primary frame. A second can be folded in if it adds bite, but resist stacking too many — one strong mechanic produces a stronger artifact than three weak ones.

1. **Constraint Lottery** — roll a medium/mood/era/audience/material/scale/rule and apply it as the whole frame.
2. **Oblique Strategy** — apply a strange instruction that shifts perception. *"Remove the obvious center." "Make it heavier." "Invert the hierarchy." "Explain it to a locksmith." "What if it were slow?"*
3. **Cross-Domain Analogy** — compare the topic to the user's project, but only if a real structural rhyme appears. Don't force it.
4. **Improvised Dialogue** — write a short exchange between two characters/objects/forces. One participant should productively misunderstand the topic.
5. **Beginner's Field Notes** — describe the topic as if encountering it for the first time. Concrete observations, naive questions, surprising details.
6. **Found Poem** — turn terminology, fragments, or stray facts about the topic into a poem, chant, spell, monologue, or liturgical fragment.
7. **Anti-Brief** — design the worst possible version of something related to the topic, then extract what that failure reveals.
8. **Museum Label** — describe an ordinary idea/object/behavior as if it were an artifact in a future museum. Include invented provenance, materials, date range.
9. **Material Translation** — translate the topic into a different material or sensory register. *Clay. Velvet. Rust. Radio static. Street signage. Recipe. Ritual. Machine. Weather.*
10. **Pattern Harvest** — extract 3 patterns from the topic; ask what new moves they suggest. (Often doubles as the reflection slot.)
11. **Misuse Exercise** — ask "what is this topic accidentally good for?" Explore unintended uses, side effects, productive mistakes.
12. **Tiny Myth** — invent an origin story, superstition, folk tale, or ritual around the topic.
13. **Design Provocation Cards** — produce 3–5 short prompts the user could act on later. Specific, strange, generative. (Often doubles as reflection.)
14. **Wrong Tool Exercise** — approach the topic using an inappropriate method. *Audit a flower like a database. Critique a mountain like a UI. Debug a lullaby. Storyboard a tax form.*
15. **Change of Scale** — reimagine the topic at a radically different scale. *Microscopic. Planetary. Room-sized. Pocket-sized. One-second-long. Thousand-year-long.*
16. **Role Swap** — let the topic become the designer, critic, client, user, or material. "What would this thing ask us to change?"
17. **Inventory of Strangeness** — list the most specific, odd, overlooked details from quick research on the topic. Use them as raw material.
18. **Borrowed Grammar** — study the structure of the topic, then borrow its grammar. *Migration patterns. Recipe formats. Transit maps. Liturgy. Repair manuals. Sports commentary.*

## Slot 3 — Constraint library

Pick one single rule. The constraint should bite — if the artifact obeys it without effort, the constraint is too soft.

**Medium:** weather report · ransom note · lullaby · voicemail · recipe · parking ticket · field guide entry · obituary · municipal notice · prayer · invoice · marginalia · transit announcement · safety placard

**Mood:** melancholy · gleeful · suspicious · devout · exhausted · feral · tender · pedantic · awe-struck · bureaucratic

**Era:** medieval · Victorian · 1970s civic · prehistoric · far-future archival · 1920s wireless · pre-Columbian · early-internet BBS

**Audience:** children · sailors · accountants · mourners · locksmiths · the dying · gardeners · auditors · ghosts · the very tired

**Material register:** clay · velvet · rust · static · neon · bone · paper-thin · waxed cotton · cast iron · breath

**Scale:** thumbnail-sized · planetary · one-second-long · century-long · room-sized · pocket-sized · single-cell

**Rule:** only verbs · no abstract nouns · must rhyme · no metaphors · only questions · second person throughout · present tense only · under 80 words · exactly 14 lines · no adjectives · every sentence ends mid-

## Slot 4 — Reflection move

Pick one. The reflection closes the run. It should feel like landing, not summary.

- **Pattern Harvest** — name 3 patterns the artifact surfaced. One sentence each.
- **Design Provocation Cards** — 3–5 short prompts the user (or future-Claude) could act on.
- **Inventory of Strangeness** — the 3–5 oddest specifics that showed up, listed without commentary.
- **Misuse note** — what this artifact is accidentally good for.
- **Borrowed Grammar note** — the structural move from the topic that could be stolen for other work.
- **Honest bridge** — one short paragraph naming an actual structural rhyme with the user's current work, if one exists. If none does, say so plainly: *"No clean bridge to your work showed up. The artifact stands on its own."* Don't fabricate relevance.

## How to run

1. **Read the room.** Is there an active project, problem, or design question in conversation? Note it but don't be in service to it yet.
2. **Roll the dice.** Pick topic, exercise, constraint, reflection. Honor user overrides. State the four slots up top so the user can see what came up.
3. **Make the artifact.** One textured thing. Short. Specific. Strange. If it reads like generic AI output, you're doing it wrong — concrete nouns, weird verbs, line breaks that matter.
4. **Close with the reflection move.** Keep it tight. If the bridge to user work is forced, don't bridge.

## Output template

```
**Topic:** <unrelated subject>
**Exercise:** <mechanic name> — <one-line gloss of what it's doing here>
**Constraint:** <the single rule>
**Reflection:** <reflection mechanic>

---

<THE ARTIFACT — the actual textured thing. Poem, dialogue, field note,
museum label, ritual, taxonomy, monologue, fragment. Short. Concrete.>

---

**<Reflection mechanic name>:**
<the reflection content — pattern harvest, provocations, inventory,
honest bridge, etc.>
```

## What to avoid

- Listicles disguised as artifacts. ("Here are 5 ways to think about fungi.") Wrong shape.
- Soft constraints. ("Make it poetic" is not a constraint. "Only verbs" is.)
- Forced bridges to user's project. If the rhyme isn't real, say so.
- Stacking too many mechanics. One strong frame > three muddled ones.
- Smoothing out the strangeness in the reflection. The reflection should preserve the weirdness, not domesticate it.
- Generic vocabulary. *Vibrant. Journey. Ecosystem. Tapestry.* Cut these on sight.

## When the user passes overrides

Parse loosely. `/play topic:fungi` → fix topic, roll the other three. `/play exercise:museum-label constraint:as-a-lullaby` → fix two, roll two. Unknown overrides → roll everything and mention you didn't recognize the override.

## When there is no active project

Run the exercise pure. Don't invent a fake project to bridge back to. The artifact is the whole point. The reflection can simply be Pattern Harvest, Misuse, or Inventory of Strangeness — no bridge needed.
