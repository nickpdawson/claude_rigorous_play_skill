# /play — Rigorous Creative Play

A Claude Code skill for structured creative detours.

`/play` rolls four dice — an **unrelated topic**, a **creative exercise**, a **constraint**, and a **reflection move** — and produces *one small textured artifact*: a poem, a dialogue, a field note, a museum label, an invented taxonomy, a ritual, a fragment.

It is not a brainstorm. It is not a list of ideas. It is not "here are five approaches you could take." It is one weird, specific, made thing — and an honest closing move.

---

## Why this exists

Most "be creative" prompts collapse into the same shapes: bullet lists, generic adjectives (*vibrant, journey, ecosystem, tapestry*), the safest possible reading of the brief. The output is technically responsive and totally forgettable.

`/play` is built on the opposite intuition: that real creative leverage comes from *structured strangeness*. A topic you didn't ask for. A constraint that bites. An exercise with a defined frame. A reflection move that lands the run without smoothing the weirdness out.

The bridge back to your current work is optional, and the skill is instructed to say so when no honest bridge exists. Sometimes the value is just that the run made something odd, vivid, or newly available.

---

## The four-slot model

Every run rolls (or accepts overrides for) four slots:

| Slot | What it does |
|---|---|
| **Topic** | An unrelated subject — fungi, lighthouse keeping, courtroom procedure, foley artistry — pulled from a library of ~70 evocative options or invented on the spot. |
| **Exercise** | One of 18 creative mechanics (see below). The primary frame for the output. |
| **Constraint** | A single rule the artifact must obey — *"only verbs," "as a lullaby," "under 80 words," "no abstract nouns."* |
| **Reflection** | How the run closes — pattern harvest, provocation cards, inventory of strangeness, or an honest bridge back to your work. |

By default Claude rolls all four. You can pin any of them:

```
/play
/play topic:fungi
/play exercise:found-poem constraint:as-a-lullaby
```

## Learn before playing

After the topic is picked, Claude does **a small piece of real research** — one or two web searches, at least one full source read — and surfaces 4–6 *field notes* before producing the artifact: specific facts, technical terms, dates, names, jargon, oddities. The artifact is then built from those notes.

This is the difference between "an artifact about fungi" (LLM-internal association, often generic) and "an artifact about fungi that uses the actual word *anastomosis* and the name of the 1990s forest-ecology paper that coined *wood-wide web*." The texture comes from things you didn't already know.

Wikipedia is allowed as a backstop, but the skill is explicitly told to reach for at least one weirder source — niche blogs, museum collection notes, trade publications, oral histories, enthusiast forums. Generic encyclopedia summaries produce generic artifacts.

---

## The 18 mechanics

1. **Constraint Lottery** — roll a medium/mood/era/audience/material/scale/rule and treat it as the whole frame.
2. **Oblique Strategy** — apply a perception-shifting instruction. *Remove the obvious center. Make it heavier. Invert the hierarchy.*
3. **Cross-Domain Analogy** — compare the topic to your project, but only if a real structural rhyme appears.
4. **Improvised Dialogue** — a short exchange between two characters/objects/forces. One should productively misunderstand.
5. **Beginner's Field Notes** — describe the topic as if encountering it for the first time.
6. **Found Poem** — turn terminology, fragments, or stray facts into a poem, chant, spell, or monologue.
7. **Anti-Brief** — design the worst possible version of something related, then extract what the failure reveals.
8. **Museum Label** — describe an ordinary thing as if it were an artifact in a future museum.
9. **Material Translation** — translate the topic into a different material or sensory register. *Clay. Velvet. Rust. Radio static.*
10. **Pattern Harvest** — extract 3 patterns from the topic; ask what new moves they suggest.
11. **Misuse Exercise** — what is this topic accidentally good for?
12. **Tiny Myth** — invent an origin story, superstition, or folk tale around the topic.
13. **Design Provocation Cards** — 3–5 short prompts the user could act on later. Specific, strange, generative.
14. **Wrong Tool Exercise** — approach the topic with an inappropriate method. *Audit a flower like a database. Debug a lullaby.*
15. **Change of Scale** — reimagine the topic at a radically different scale. *Microscopic. Planetary. One-second-long.*
16. **Role Swap** — let the topic become the designer, critic, or client. "What would this thing ask us to change?"
17. **Inventory of Strangeness** — list the most specific, odd, overlooked details.
18. **Borrowed Grammar** — study the topic's structure, then steal its grammar. *Migration patterns. Liturgy. Repair manuals.*

---

## Example runs

Three artifacts from real runs of the skill, included in [`examples/`](examples/):

- [`fungi-as-lullaby.md`](examples/fungi-as-lullaby.md) — Found Poem, topic *fungi*, constraint *as a lullaby*
- [`lighthouse-museum-label.md`](examples/lighthouse-museum-label.md) — Museum Label, topic *lighthouse keeping*, constraint *no abstract nouns*
- [`foley-anti-brief.md`](examples/foley-anti-brief.md) — Anti-Brief, topic *foley artistry*, constraint *only questions*

Each is short. Each obeys the constraint. Each closes with a reflection that doesn't apologize for the strangeness.

---

## Install

This is a [Claude Code](https://claude.com/claude-code) skill. Two ways to install.

### As a user skill (available globally)

```sh
mkdir -p ~/.claude/skills/play
curl -fsSL https://raw.githubusercontent.com/nickpdawson/claude_rigorous_play_skill/main/SKILL.md \
  -o ~/.claude/skills/play/SKILL.md
```

Then type `/play` in any Claude Code session.

### As a project skill (per-repo)

```sh
mkdir -p .claude/skills/play
curl -fsSL https://raw.githubusercontent.com/nickpdawson/claude_rigorous_play_skill/main/SKILL.md \
  -o .claude/skills/play/SKILL.md
```

### Or clone the whole repo

```sh
git clone https://github.com/nickpdawson/claude_rigorous_play_skill.git
cp claude_rigorous_play_skill/SKILL.md ~/.claude/skills/play/SKILL.md
```

---

## Design notes

A few choices worth naming, because they shape how the skill behaves:

**One artifact, not five.** Five ideas is a brainstorm. One weird thing is a move. The skill is instructed to refuse listicle output.

**Constraints must bite.** "Make it poetic" is not a constraint; "only verbs" is. A constraint the artifact obeys without effort is too soft, and the run gets re-rolled.

**No forced bridges.** The reflection step has an explicit out: *"No clean bridge to your work showed up. The artifact stands on its own."* Forced relevance is worse than no relevance — it teaches you to ignore the reflection.

**Stacking mechanics is discouraged.** One strong frame produces a stronger artifact than three muddled ones. The skill resists the urge to use all the toys at once.

**Generic vocabulary is banned on sight.** *Vibrant. Journey. Ecosystem. Tapestry. Vibrant ecosystem of tapestried journeys.* If the output reads like that, it's failing.

---

## Contributing

Pull requests welcome — especially:

- New topics for the topic library (specific, evocative, low-cliché)
- New constraints (single-rule, bite-y, weird)
- New example artifacts that show texture

Please don't add mechanics unless you've run them several times and they reliably produce something different from the existing 18.

---

## License

[CC BY-SA 4.0](LICENSE) — Creative Commons Attribution-ShareAlike 4.0 International.

You may remix, adapt, build on, and redistribute (including commercially), provided you credit the original and share derivatives under the same license.

---

## Credit

Designed by [Nick Dawson](https://github.com/nickpdawson). Drafted with Claude (Anthropic) as collaborator.

The four-slot model and the 18-mechanic library are the contribution; everything else is execution.
