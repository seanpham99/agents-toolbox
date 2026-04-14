---
name: research-verification
description: "Run targeted external verification when confidence is low or facts may be stale. Use for API changes, version-specific behavior, and domain facts that need citations."
argument-hint: "What claims or entities need verification?"
---

# Research Verification

Validate uncertain claims with focused external research.

## When To Use

- Knowledge confidence is low or medium with risk
- User asks for latest behavior, policy, pricing, or version-specific details
- Decision quality depends on current external facts

## Procedure

1. List claims that need verification.
2. Prioritize highest-risk claims first.
3. Run targeted lookups for each claim.
4. Record findings with source links and date.
5. Flag contradictions against prior assumptions.
6. Return a short verification summary and confidence level.

## Output Format

1. Claim
2. Verified finding
3. Source
4. Confidence
5. Impact on decision

## Anti-Patterns

- Do not run broad, unfocused searches.
- Do not present unverified claims as facts.
- Do not continue with high-risk assumptions without explicit warning.
