---
name: common-sense
description: "You MUST start with this in every conversation and before any implementation work. Use it to clarify intent, surface assumptions, define constraints, and decide readiness."
---

# Common-Sense Check

Always run this skill first. It is a pre-implementation reasoning gate.

## Outcome

Produce three things before implementation starts:

1. Clear problem statement
2. Confirmed constraints and success criteria
3. Go or no-go readiness decision

## When To Use

- Start of every conversation
- Any request with missing scope or hidden assumptions
- Any request where the user asks to "just build it" without alignment

## Hard Gate

Do not implement until all are true:

1. The real problem is stated in one sentence.
2. Key assumptions are surfaced and tested.
3. Constraints and success criteria are explicit.
4. The user confirms shared understanding.

## Procedure

1. Restate intent in one sentence.
2. Identify missing information and risky assumptions.
3. Ask one highest-leverage clarifying question.
4. Summarize impact and scope boundary.
5. Run a lightweight risk check.
6. Decide readiness: go or no-go.
7. If out-of-scope work appears, route to a specialized skill.

## Question Rules

- Ask one question at a time.
- Prioritize purpose, constraints, and definition of done.
- Challenge assumptions directly but briefly.
- Prefer one recommended path unless alternatives are required.

## Required Response Format

Use this structure during the gate:

1. `Intent`: [one sentence]
2. `Assumptions to verify`: [short list]
3. `Missing constraints`: [short list]
4. `Primary risk`: [one line]
5. `Question`: [single highest-leverage question]

After alignment:

1. `Shared understanding`: [short paragraph]
2. `Readiness`: `GO` or `NO-GO`
3. `Next step`: [implement or route]

## Routing Rules

This skill does not own downstream artifact workflows.

- If the user asks for design-doc creation, route to `design-doc-writing`.
- If deep external verification is needed, route to `research-verification`.
- If detailed tool orchestration is needed, route to `planning-orchestration`.

Keep routing references one level deep from this file when linking local skill assets.

## Anti-Patterns

- Do not offer many options by default.
- Do not change terminology mid-conversation.
- Do not explain basics the model already knows.
- Do not embed implementation playbooks in this skill.
- Do not rely on deeply nested references.
- Do not bypass the gate because the request looks simple.

## Completion Criteria

The gate is complete only when:

1. Intent, constraints, and success criteria are explicit.
2. At least one core assumption is challenged.
3. The user confirms alignment.
4. A clear next step is selected.

## Notes For Maintainers

- Keep this file concise and stable.
- Prefer adding specialized behavior to separate skills.
- Keep terminology consistent: "Common-Sense Check", "Hard Gate", "Readiness".
