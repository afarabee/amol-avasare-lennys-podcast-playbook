---
name: activation_routing_for_ai_products
description: Improve AI-product activation by routing users toward the most relevant capability, workflow, or use case based on who they are and what they need. Treat activation as a capability-diffusion problem, not just a faster signup problem.
version: 1.0
category: ai-product
tags: [ai, activation, onboarding, product-growth, capability-discovery]
---

# Activation Routing for AI Products

## Purpose
This skill helps map users to the right first-use experience in AI products, especially where the product has broad or rapidly changing capability.

## Use this skill when
- A user asks how to improve activation for an AI product
- A team has a strong model but weak first-run adoption
- New capabilities are shipping quickly and onboarding has fallen behind
- Users are not reaching an “aha” moment fast enough

## Do not use this skill when
- The product is not AI-centered and does not rely on capability discovery
- The request is purely about pricing or packaging
- There is no meaningful variation in use case or audience

## Core principles
1. AI activation is about teaching users what is newly possible.
2. Model capability evolves faster than most onboarding flows.
3. Generic prompt boxes are weak activation mechanisms.
4. Route users based on role, intent, and expected job-to-be-done.
5. Revisit activation whenever model capability materially changes.

## Workflow
1. Identify the product’s top user segments.
2. For each segment, define:
   - likely intent
   - likely level of AI fluency
   - highest-value near-term use case
3. Identify which capabilities the current onboarding does not surface well.
4. Design segment-specific on-ramps:
   - examples
   - templates
   - workflows
   - starter actions
5. Recommend what to ask users up front to support routing.
6. Suggest a review cadence tied to capability changes.

## Output format
Return:
- top user segments
- likely entry intent for each segment
- recommended first-use experience by segment
- missing capabilities not currently surfaced
- onboarding questions to ask
- metrics for activation success

## Anti-patterns
- One-size-fits-all onboarding
- Assuming users will naturally discover the best use cases
- Leaving activation unchanged after major capability upgrades
- Showing too many use cases at once
- Treating activation as only a time-to-first-message problem
