# Skill Classifier

Use this classifier before creating or installing a new skill.

## A file is a true skill only if:
1. It has a concrete, actionable trigger.
2. It has a repeatable workflow.
3. It produces a predictable output structure.
4. It can be selected at runtime with reasonable confidence.
5. It is not primarily a belief system, leadership norm, or abstract strategy principle.

## Put it in /skills if:
- the user asks to perform a task
- the task has recognizable entry conditions
- the sequence of steps is reusable
- the model should invoke it directly

## Put it in /frameworks if:
- the content helps analyze or structure a decision
- it is useful, but not usually invoked automatically
- it is more diagnostic or strategic than operational

## Put it in /doctrine if:
- the content is a principle, heuristic, or norm
- it should influence many other skills
- it does not stand alone as a triggered procedure

## Fast test
Ask:
- “What exact user request would make this fire?”
- “Would two different operators run roughly the same process from it?”
- “Does it return a recognizable deliverable?”
- “Is this a procedure rather than a worldview?”

If the answers are weak, it probably is not a skill.
