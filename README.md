# Career Discovery Coach 🧭

A [Claude](https://claude.ai) skill that helps confused students and early-career
people uncover **who they really are** and **the work they'd genuinely thrive in** —
not by handing them a personality-quiz result, but by mining their own concrete
experiences for evidence of how they're actually wired, reflecting it back, testing
it, and translating it into realistic direction.

> The goal is the moment someone says *"huh — that's actually true about me, and I
> never saw it."*

## Why this exists

Most career advice fails in one of two ways:

- It asks people **what they want** — and gets a rehearsed, surface answer.
- It runs a **personality test** — too coarse to actually act on.

This skill does the harder, better thing: a Socratic, **one-question-at-a-time**
discovery conversation grounded in psychology, that surfaces the personality,
motivation type, and values underneath — then maps them to concrete career lanes
weighed against real-world constraints (growth, pay, employability, visa, timeline).

## The method (5 movements)

1. **Frame & open** — start from a *flow / peak-moment* story, the least fakeable
   signal of what truly engages someone.
2. **Hypothesize & test** — reflect observations back using the person's own words,
   form hypotheses about their wiring, pressure-test with counterfactuals, and
   *revise openly when wrong*.
3. **Name the bedrock** — synthesize the portrait, surface the uncomfortable truth
   (e.g. a credential that fights the person's actual wiring), reframe "flaws" as
   fit signals.
4. **Map to reality** — 2-3 career lanes scored against real constraints, with a
   clear recommendation and a launchpad → destination sequence.
5. **Activate** — concrete deliverables + an anti-procrastination mechanism tuned
   to the person's psychology.

## Psychology under the hood

Used to ask sharper questions and read answers — never lectured at the user:

- **Flow theory** (Csikszentmihalyi)
- **Self-Determination Theory** (Deci & Ryan)
- **Motivational Interviewing** (Miller & Rollnick) — the conversational engine
- **RIASEC / Holland Codes**, **Big Five**, **Ikigai**
- **Schein's Career Anchors**, **Job Crafting**, strengths / Zone of Genius

## Structure

```
career-discovery-coach/
├── SKILL.md                          # the method, principles, ethics
├── README.md
└── references/
    ├── psychology-frameworks.md      # the theory, with how-to-apply notes
    ├── archetypes-and-signals.md     # how to read motivation type, maker archetype, etc.
    ├── question-bank.md              # probing questions by phase
    └── deliverables.md               # portrait, positioning, lane map, 90-day plan templates
```

## How to use it

This is an [Agent Skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview).
Drop the `career-discovery-coach/` folder into your Claude skills directory (or
bundle it in a plugin), and it triggers automatically when someone expresses career
confusion or asks Claude to be their career mentor. You can also just point Claude
at `SKILL.md` and say "use this to coach me."

To start a session, say something like *"I'm lost about what to do with my
career — be my career coach"* and answer honestly, with real stories.

## A note on scope

This is **coaching, not therapy**. It illuminates direction and respects your
autonomy — it doesn't diagnose or treat mental health, and it builds plans around
your real constraints rather than wishing them away. If someone is in genuine
distress, it points them toward professional support.

## License

MIT — see `LICENSE`. Contributions and forks welcome.
