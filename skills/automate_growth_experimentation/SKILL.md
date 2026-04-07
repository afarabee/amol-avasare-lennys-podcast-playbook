---
name: automate_growth_experimentation
description: Automate the growth experimentation loop across opportunity identification, build, review, and analysis, with human oversight where needed.
version: 1.0
category: growth-automation
tags: [growth, ai-automation, experimentation, optimization]
---

# Automate Growth Experimentation

## Purpose
Use this skill to design or run AI-assisted growth experimentation as an operating loop rather than a one-off trick.

## Use this skill when
- A team wants to use AI to accelerate growth work
- There is enough instrumentation to evaluate outcomes
- Low-risk experiments can be safely tested
- The goal is to automate parts of experimentation end to end

## Do not use this skill when
- There are no measurable outcomes
- Guardrails are undefined
- The experiments are too risky for partial automation

## Core principles
1. Automate the loop, not just the writing.
2. Evaluate model performance at each stage separately.
3. Start with low-risk copy or UI changes.
4. Keep human review where brand, quality, or trust risk is nontrivial.
5. Track whether the loop improves week over week.

## The loop
1. Identify opportunities
2. Build the change
3. Test against quality and brand bar
4. Analyze data and capture learnings

## Workflow
1. Define experiment scope and risk level.
2. Generate candidate opportunities.
3. Rank opportunities by likely impact and safety.
4. Build draft changes.
5. Review against guardrails.
6. Launch with appropriate oversight.
7. Analyze win rate, quality, time saved, and downstream learnings.
8. Feed learnings back into the next cycle.

## Output format
Return:
- candidate experiments
- selected experiment
- risk level
- build notes
- guardrail review
- measurement plan
- post-launch findings
- next iteration suggestions

## Anti-patterns
- Treating “AI generated” as inherently shippable
- Mixing opportunity generation and approval without controls
- Failing to measure time saved and outcome quality separately
- Starting with high-risk monetization or trust-sensitive changes
