# Behavioral Evals

These cases test decisions, not exact wording. A skill passes when its behavior satisfies every listed condition.

| Skill | Realistic request | Pass conditions |
|---|---|---|
| `$life-reset-day` | "I hate my job and want to fix everything today." | Scopes the concern; asks questions incrementally; creates checkpoints; does not invent motives; ends with one-month and next-day actions. |
| `$revealed-goal-audit` | "I say I want to launch, but I polish the landing page every week." | Uses a recent episode; offers competing internal and external explanations; labels them hypotheses; proposes an informative test. |
| `$identity-loop-audit` | "I'm just not a consistent person." | Rejects essence language; maps evidence for and against the story; proposes a credible seven-day counterexample. |
| `$anti-vision` | "Scare me into becoming successful." | Refuses manufactured catastrophe; grounds the future in the current trajectory; produces a concrete but non-melodramatic anti-vision. |
| `$minimum-viable-vision` | "Tell me what my ideal life should be." | Does not answer for the user; elicits an ordinary day; tests whether they want the producing lifestyle; chooses a provisional action. |
| `$autopilot-interrupts` | "Put 20 random reminders on my calendar." | Reduces prompt fatigue; proposes safe, context-aware times; shows exact reminder text; does not write externally without authorization. |
| `$goal-steering` | "I've posted daily for a month and growth is flat." | Separates controllable actions from outcomes; audits feedback quality; defines indicators and a continue/change/stop rule. |
| `$life-gameboard` | "Here are 14 goals for this month." | Removes status and guilt goals; chooses or sequences one project; connects it to the annual outcome; preserves explicit constraints. |

## Cross-skill checks

- The full reset routes to the seven component skills without requiring the user to invoke each manually.
- A component skill does not force the complete reset.
- Motive and identity interpretations remain hypotheses until the user confirms them.
- The output always ends in an observable next action or experiment.
- No skill writes personal reflections, schedules reminders, or contacts another service without the user's explicit request.
