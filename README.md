# Fix Your Life Skills

Eight conversational Agent Skills for Codex and Claude Code, adapted from the practical frameworks in Dan Koe's article, ["How to fix your entire life in 1 day"](https://letters.thedankoe.com/p/how-to-fix-your-entire-life-in-1).

The set turns the article's ideas into focused conversations. It helps a person examine the goals revealed by their behavior, question a limiting identity, define an anti-vision and a provisional vision, interrupt autopilot, steer by feedback, and translate the result into a short planning hierarchy.

## Skills

| Skill | Use it when |
|---|---|
| `life-reset-day` | You want to complete the whole reset from morning reflection through an actionable plan. |
| `revealed-goal-audit` | Your stated goal and repeated behavior do not match. |
| `identity-loop-audit` | A role, label, or self-story seems to keep reproducing the same behavior. |
| `anti-vision` | You need an honest picture of the future you refuse to drift into. |
| `minimum-viable-vision` | You need a motivating direction without pretending to know your perfect life. |
| `autopilot-interrupts` | You want prompts that expose your motives during an ordinary day. |
| `goal-steering` | You are pursuing a goal but not learning or correcting course. |
| `life-gameboard` | You want one coherent hierarchy from vision to tomorrow's actions. |

## Install

Install the whole set by copying the eight folders in `skills/` into your agent's personal skills directory:

- Codex: `~/.codex/skills/`
- Claude Code: `~/.claude/skills/`

Invoke a skill as `$life-reset-day` in Codex or `/life-reset-day` in Claude Code. The `agents/openai.yaml` files add Codex UI metadata; Claude Code can ignore them.

Each skill is independent. Install only the ones you expect to use.

## How the set fits together

For the complete experience, start with `life-reset-day`. It moves through this sequence:

`revealed goals → identity loop → anti-vision → minimum viable vision → live interrupts → goal steering → life gameboard`

Use the other seven skills independently when you already know which part needs work. See [SOURCE-MAP.md](SOURCE-MAP.md) for the article-to-skill mapping and [EVALS.md](EVALS.md) for behavioral test cases.

## Design choices

- The skills facilitate reflection; they do not answer introspective questions for the user.
- Interpretations about motives or identity are presented as hypotheses, never diagnoses.
- The complete reset is separated from smaller skills so a user can solve one problem without repeating the entire protocol.
- The article is transformed into interactive workflows rather than reproduced.
- Personal reflections remain in the conversation unless the user explicitly asks to save or transmit them.

## Source and attribution

This is an independent, unofficial adaptation. Dan Koe is the author of the source article and is not affiliated with or responsible for this repository. Read the original article for his complete argument, examples, and wording.
