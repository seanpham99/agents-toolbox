---
name: design-doc-writing
description: "Write production-ready design docs. Use when the user wants a spec, architecture doc, technical proposal, or implementation plan saved as a document."
argument-hint: "What system or feature should the design doc cover?"
---

# Design Doc Writing

Create a clear, implementation-ready design document.

## When To Use

- User asks for a design doc, spec, proposal, or architecture write-up
- Team needs a handoff-ready document before implementation
- Work requires explicit trade-offs, risks, and validation plan

## Procedure

1. Confirm objective, scope, and non-goals.
2. Confirm constraints and success criteria.
3. Define at most one recommended approach unless alternatives are explicitly requested.
4. Write the doc with these sections:
   - Problem
   - Goals and non-goals
   - Proposed design
   - Data and interfaces
   - Risks and mitigations
   - Rollout and validation
5. Ask for review and capture requested revisions.

## Output Rules

- Prefer concise, concrete language.
- Use consistent terminology throughout.
- Include only context the reader needs to execute the plan.

## Anti-Patterns

- Do not add unnecessary alternatives by default.
- Do not include implementation details unrelated to the chosen design.
- Do not leave acceptance criteria undefined.
