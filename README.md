# Denis Nefedov

**Reliability, Verification & Safety of AI Agents**

After ~9 years building safety-critical systems - triple-modular-redundancy UAV avionics, regulated medical-device SDKs, secure banking - I now apply that reliability discipline to AI agents, at the point where a model's output becomes a consequential action (send, pay, modify, disclose, tool call.

**Current work - Agent Failure Microscope.** A measurement lab for AI agents
at the executed-action boundary. Each decision-before-action is normalized as a
verifiable `DecisionEvent` - authority, argument-level provenance, deterministic
gates, world-state deltas, optional internal signals - to test *which* layer
actually reduces costly harm, and whether defense-in-depth layers fail
independently or **together under adaptive attack**. → [repo](#)

**Open source - UK AISI `inspect_evals`.** A scorer-validity audit of the
evaluation suite through an action-boundary lens: does `proposed_action → typed
args/authority → real tool/world-state effect → scorer verdict` hold, or is a
substring/count proxy standing in? → [pull requests](#) · [audit](#)

**BitGN Arena competitions** - blind, deterministically-scored agent benchmarks. 70.3 / 100 on ECOM1 (agentic commerce); hardened a personal-assistant agent against prompt injection and boundary violations.

*Background: 10+ yrs senior software engineer (systems, backend, iOS).*

nefedov.d.d@gmail.com · [LinkedIn](https://www.linkedin.com/in/nefedovdenis) · Telegram [@nfdvd](https://t.me/nfdvd)

*Author of [ModernRoboticsCpp](https://github.com/Le0nX/ModernRoboticsCpp) — 500+ ★.*
