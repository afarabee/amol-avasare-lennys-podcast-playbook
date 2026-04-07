---
name: misalignment_detection
description: Detect likely project or organizational misalignment early by scanning priorities, communications, and workstreams for overlap, conflict, missing stakeholders, or hidden dependency risk.
version: 1.0
category: operating-model
tags: [alignment, management, product-ops, ai-workflows, coordination]
---

# Misalignment Detection

## Purpose
This skill helps surface coordination risks before they become rework, delays, or duplicate effort.

## Use this skill when
- A leader wants a weekly scan for alignment risk
- There are many cross-functional initiatives moving at once
- Teams are shipping quickly and coordination may be the bottleneck
- A user asks for help identifying hidden dependencies or overlap

## Do not use this skill when
- The work is fully self-contained
- There is no meaningful project context to analyze
- The request is only for a project status summary

## Core principles
1. Fast-moving orgs often fail through coordination, not lack of effort.
2. Misalignment is easier to prevent than unwind.
3. AI can be useful as an early-warning system.
4. Good detection requires current priorities and real communication context.
5. Outputs should be framed as likely risks, not certainty claims.

## Required inputs
- current priorities
- active projects or workstreams
- key stakeholder list
- recent communication context if available
- known deadlines or launches

## Workflow
1. Summarize active priorities and in-flight work.
2. Scan for:
   - conflicting assumptions
   - overlapping work
   - mismatched timelines
   - missing stakeholder involvement
   - unresolved decisions
   - unacknowledged dependencies
3. Flag each issue by severity:
   - monitor
   - moderate risk
   - urgent intervention
4. Recommend the minimum intervention needed:
   - confirm with X
   - hold short kickoff
   - align scope
   - clarify owner
   - resolve dependency
5. Return a concise risk memo.

## Output format
Return:
- detected risk
- why it may be misaligned
- evidence or signals
- confidence level
- recommended next action
- who should be involved

## Anti-patterns
- Presenting guesses as facts
- Flagging everything as urgent
- Returning only generic “communicate more” advice
- Ignoring stakeholder ownership
