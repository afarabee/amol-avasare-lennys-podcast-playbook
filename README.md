# Anthropic-Inspired Operating Playbook v2

This is a stricter operating version of the playbook.

## What changed in v2
Only files with a clear action trigger, repeatable workflow, and consistent output contract remain in `/skills`.

Material that is valuable but not reliably invoke-able as a just-in-time behavior module has been moved to:
- `/frameworks` for structured strategic analyses
- `/doctrine` for operating beliefs, heuristics, and decision principles

## Folder rules

### /skills
A file belongs here only if all of the following are true:
- it has a specific task trigger
- it defines a repeatable procedure
- it produces a consistent output shape
- it is something the model can reliably choose in the moment
- it is more than a belief, preference, or leadership principle

### /frameworks
A file belongs here if it helps structure strategic thinking or assessment, but does not behave like a triggerable execution skill.

### /doctrine
A file belongs here if it represents an operating belief, norm, heuristic, or leadership principle that should shape decisions across multiple skills.

## Skills retained in v2
- good_friction_onboarding
- activation_routing_for_ai_products
- quality_drives_growth
- misalignment_detection
- proportionate_process
- automate_growth_experimentation
- machine_readable_guardrails
- ai_manager_coaching
- product_minded_engineer_delegation
- cold_outreach_for_high_value_roles

## Frameworks moved out of /skills
- bigger_bets_for_ai_native_products
- continuous_tool_revalidation
- focus_through_constraints
- interdisciplinary_advantage_building

## Doctrine moved out of /skills
- deliberate_money_left_on_table
- visible_leadership_thoughts

## Supporting doctrine files
- best_practices.md
- decision_rules.md
- skill_classifier.md
