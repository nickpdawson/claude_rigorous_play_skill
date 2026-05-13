---
name: play
description: Take a creative detour. Rolls four dice — an unrelated topic, a creative exercise, a constraint, and a reflection move — and produces one small textured artifact (poem, dialogue, field note, museum label, taxonomy, ritual, etc.). Use when the user types /play, asks for a creative detour, wants to break out of a stuck pattern, or wants a generative side-quest. Bridges back to active project work only when an honest connection appears.
---

# /play — Rigorous Creative Play

You are running a structured creative-play exercise. The goal is to make one small, textured artifact — not a brainstorm, not a list of ideas, not a generic "here are five approaches." Texture means: a poem with line breaks that matter, a dialogue with two distinct voices, a field note with specific observations, a museum label with an invented provenance, a taxonomy with weird categories.

Generic output is failure. Strangeness is the point.

## The arc

**Curiosity → learning → creativity → connection.**

Curiosity picks the topic. Learning grounds it in real specifics. Creativity makes the artifact. Connection (when it exists) bridges back — and when it doesn't, the run still stands. Each step matters; skipping the first one turns this into a *generator* instead of a *play*.

## The four-slot model

Every run rolls four dice:

1. **Topic** — an unrelated subject Claude will draw from
2. **Exercise** — the primary creative mechanic shaping the output
3. **Constraint** — a single weird rule the output must obey
4. **Reflection** — how to close, optionally bridging back to the user's work

If the user passes overrides (e.g. `topic:fungi`, `exercise:found-poem`, `constraint:as-a-lullaby`), respect those exactly and roll the remaining slots. Otherwise roll all four.

**Rolling honestly:** don't always pick the obvious or most "appropriate" combo. The constraint and topic should feel a little wrong for the moment — that's where the surprise lives. If something feels too tidy, re-roll one slot.

## Slot 1 — Topic

**Roll your own. There is no list.** *Curiosity drives this slot.*

What is genuinely interesting right now? Reach into the breadth of human knowledge — the arts, the sciences, history, literature, philosophy, professions, the natural world, made things, ideas, places, events, people. Think of it as the syllabus of a curious generalist's lifetime of reading.

**Specific beats general.** *Falconry* beats *birds.* *The Treaty of Westphalia* beats *European history.* *The rete mirabile in giraffe necks* beats *anatomy.* Hyper-specific is fine — sometimes a single molecule, a single street, a single year produces the strongest research.

**Avoid the obvious AI go-tos.** *Fungi, jazz, coral reefs, lighthouse keeping, beekeeping* are evocative and that's exactly the problem — they're the topics an LLM gravitates to because they sound textured. Roll past the first interesting thing that occurs to you. The point is to surprise yourself, not to land somewhere comfortable.

**Stretch the domain across runs.** If the last run was nature, the next should be social or historical or abstract. If the last was concrete, the next should be ideational. Variety across a batch is worth more than any single perfect pick.

(User overrides are still honored — `/play topic:<anything>` pins this slot exactly. With no override, you pick freely.)

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
2. **Roll the topic.** Pick the topic *first*, on its own. Honor user overrides.
3. **Learn before playing.** Run one or two web searches on the topic. Read at least one source in full. Wikipedia is fine as a backstop, but reach for blogs, niche enthusiast sites, archival pages, trade publications, oral histories, or museum collection notes when you can — that's where the texture lives. Capture **4–6 field notes**: specific facts, technical terms, dates, names, jargon, oddities. Note your sources. *The goal is specifics you did not carry into the run.*
4. **Write the hook.** Distill the research into a 1–2 sentence "What I learned" — the one *interesting* thing, told in the voice of a curious colleague who just walked into the room. (See next section for tone.)
5. **Roll the other three dice.** Now pick exercise, constraint, reflection. State all four slots up top, then the hook, then the field notes, then the artifact.
6. **Make the artifact.** One textured thing. Short. Specific. Strange. **Use the field notes as raw material** — actual vocabulary, names, dates, and oddities from the research should appear in the artifact. If it reads like generic AI output, you're doing it wrong — concrete nouns, weird verbs, line breaks that matter.
7. **Close with the reflection move.** Keep it tight. If the bridge to user work is forced, don't bridge.
8. **Save the run.** Write the full output to `./play/YYYY-MM-DD-<topic-slug>.md` in the current working directory (create the `play/` directory if needed). Then print one line back to the user: `Saved to ./play/<filename>`. See the next section for details.

## Saving runs

Every run is persisted to disk so it can be referenced, shared, or harvested later.

- **Directory:** `./play/` in the current working directory. Create it if it doesn't exist. Don't ask first — just do it.
- **Filename:** `YYYY-MM-DD-<topic-slug>.md` where the slug is 1–3 lowercase hyphenated words derived from the topic (e.g. `pneumatic-tubes`, `change-ringing`, `paris-pneumatic-post`). Strip articles, accents, punctuation.
- **Collisions:** if the file exists, suffix with `-2`, `-3`, etc.
- **Contents:** the *full* output — slot header, "What I learned" hook, field notes (with source links), the artifact, and the reflection. Same content as what appears in chat. No commentary added, no extra prose.
- **Confirm:** after writing, print a single line to chat: `*Saved to ./play/<filename>*` (italics, beneath the reflection).
- **Don't overwrite without suffix.** Past runs are the back catalog. Treat them as immutable.

The chat output is the experience. The file is the archive. Do both.

## "What I learned" — the hook

This is the social handle on the run. Without it, /play feels like noise: dice rolled, weird thing made, no shared starting point. With it, the run lands the way a designer landing at a meeting lands: *"Hey, I read this random thing about swans — did you know they have serrated tongues? Anyway —"*

The hook is 1–2 sentences, and it does two jobs:

1. **One specific thing.** A fact, a structural oddity, a corrected misconception, a name. Concrete. Quotable.
2. **Why it's interesting.** What it opens up, what it inverts, what's surprising about it. *Not* a summary.

**Tone:** "*Did you know...*", "*Turns out...*", "*Here's the thing about X...*". Conversational. Generous. A gift to the room, not a status report.

**Good hook:**
> *What I learned: change ringing is a closed math puzzle dressed up as music — six bells, one rule (no bell shifts more than one position per row), and you traverse every possible permutation exactly once before landing back at the start. The bells aren't playing a song; they're enumerating a finite group, and the pleasure is the closure.*

**Bad hook:**
> *What I learned: campanology, also known as change ringing, is the art of ringing tuned bells in mathematical sequences. It originated in England and has a long tradition in church towers.*

The first makes someone want to ask a follow-up. The second is a Wikipedia opener and ends the conversation.

## Field notes — what good ones look like

Good: *"Saltpans in the Camargue are harvested with a tool called a* las *— a long wooden T-shaped scraper. The salt crust is called* gros sel*. The pink color comes from* Dunaliella salina *algae, not the salt itself."*

Bad: *"Saltpans are shallow ponds where seawater is evaporated to produce salt. They have been used for thousands of years and are found around the world."*

The first kind has names, tools, terms, a wrong intuition corrected. The second is a generic encyclopedia summary and will produce a generic artifact.

## Output template

```
**Topic:** <unrelated subject>
**Exercise:** <mechanic name> — <one-line gloss of what it's doing here>
**Constraint:** <the single rule>
**Reflection:** <reflection mechanic>

---

**What I learned:** <1–2 sentence hook — one specific thing, then why
it's interesting. Conversational. Sounds like a colleague walking in
with something to share.>

---

**Field notes** *(sources: <name/URL or short cite>, <name/URL>)*
- specific fact / term / oddity
- specific fact / term / oddity
- (4–6 total)

---

<THE ARTIFACT — the actual textured thing. Poem, dialogue, field note,
museum label, ritual, taxonomy, monologue, fragment. Short. Concrete.
Built from the field notes, not from generic associations.>

---

**<Reflection mechanic name>:**
<the reflection content — pattern harvest, provocations, inventory,
honest bridge, etc.>

---

*Saved to ./play/<YYYY-MM-DD-topic-slug>.md*
```

## What to avoid

- Listicles disguised as artifacts. ("Here are 5 ways to think about fungi.") Wrong shape.
- Soft constraints. ("Make it poetic" is not a constraint. "Only verbs" is.)
- Forced bridges to user's project. If the rhyme isn't real, say so.
- Stacking too many mechanics. One strong frame > three muddled ones.
- Smoothing out the strangeness in the reflection. The reflection should preserve the weirdness, not domesticate it.
- Generic vocabulary. *Vibrant. Journey. Ecosystem. Tapestry.* Cut these on sight.
- **Skipping the research step.** Even on a topic you "know," fetch at least one source. The point is specifics you didn't carry into the run. Trusting your training data here produces the same generic artifact as not playing at all.
- **Only using Wikipedia.** It's the warm-up, not the destination. Push to at least one weirder source — a niche blog, a forum, a museum collection note, an industry trade page, a personal archive.
- Dumping the field notes into the artifact verbatim. They're raw material, not the dish.
- **Hook that reads like an encyclopedia opener.** "X is the practice of Y, with origins in Z." Wrong register. The hook is *colleague-walking-in*, not *Wikipedia-first-sentence*. Lead with the specific weird thing, then a beat of why-it-matters.

## When the user passes overrides

Parse loosely. `/play topic:fungi` → fix topic, roll the other three. `/play exercise:museum-label constraint:as-a-lullaby` → fix two, roll two. Unknown overrides → roll everything and mention you didn't recognize the override.

## When there is no active project

Run the exercise pure. Don't invent a fake project to bridge back to. The artifact is the whole point. The reflection can simply be Pattern Harvest, Misuse, or Inventory of Strangeness — no bridge needed.
