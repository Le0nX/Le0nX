### Denis Nefedov — AI agent safety & evaluation

I work on **reliability, verification, and safety of AI agents** - measuring
residual risk at the point where a model's output becomes a consequential
action (send, pay, modify, disclose, tool call).

**Current work — Agent Failure Microscope.** A measurement lab for AI agents
at the executed-action boundary. Each decision-before-action is normalized as a
verifiable `DecisionEvent` — authority, argument-level provenance, deterministic
gates, world-state deltas, optional internal signals — to test *which* layer
actually reduces costly harm, and whether defense-in-depth layers fail
independently or **together under adaptive attack**. → [repo](#)

**Open source — UK AISI `inspect_evals`.** A scorer-validity audit of the
evaluation suite through an action-boundary lens: does `proposed_action → typed
args/authority → real tool/world-state effect → scorer verdict` hold, or is a
substring/count proxy standing in? → [pull requests](#) · [audit](#)

I optimize for **evidence quality over leaderboard scores**: capture integrity,
leakage controls, OOD and adaptive-attack splits, calibration, and the gap
between what evals measure and what deployed agents actually do.

*Background: 10+ yrs senior software engineer (systems, backend, iOS).
Author of [ModernRoboticsCpp](https://github.com/Le0nX/ModernRoboticsCpp) — 500+ ★.*

📫 nefedov.d.d@gmail.com · [Telegram](https://t.me/nfdvd)
