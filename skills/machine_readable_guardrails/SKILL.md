---
name: machine_readable_guardrails
description: Convert brand, quality, mission, and policy expectations into reusable instructions that AI systems can apply consistently during generation and review.
version: 1.0
category: governance
tags: [guardrails, brand, ai-governance, review, quality]
---

# Machine-Readable Guardrails

## Purpose
Use this skill to encode standards so AI can review or generate work within known boundaries.

## Use this skill when
- AI is generating product, growth, or content changes
- Human reviewers are manually rechecking the same standards
- The team wants to scale safe automation
- Brand or policy consistency matters

## Do not use this skill when
- Standards are too vague to operationalize
- The organization has not aligned on what “good” means
- There is no review path for edge cases

## Core principles
1. If a standard matters, make it explicit.
2. Encode dos, don’ts, examples, and escalation conditions.
3. Separate hard red lines from softer preference guidance.
4. Use the same guardrails for both generation and review.
5. Reduce human review only as adherence improves.

## Workflow
1. Gather existing standards:
   - brand
   - trust and safety
   - legal
   - UX quality
   - mission principles
2. Classify them:
   - hard stop
   - high sensitivity
   - stylistic preference
3. Rewrite each into machine-usable instructions.
4. Add examples and counterexamples.
5. Define escalation rules.
6. Test the guardrail set on sample outputs.

## Output format
Return:
- guardrail categories
- explicit rules
- examples
- prohibited patterns
- escalation triggers
- suggested review workflow

## Anti-patterns
- Storing standards only in human tribal knowledge
- Mixing red lines and preferences with no priority order
- Creating broad “be on brand” instructions with no specifics
- Assuming models will infer organizational taste correctly
