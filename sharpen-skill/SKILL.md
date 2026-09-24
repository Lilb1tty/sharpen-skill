---
name: sharpen-skill
description: Review and improve an existing SKILL.md using engineering design principles or evidence from the user's actual skill usage, corrections, and preferred handoffs. Use when asked to sharpen a skill.
---

# Sharpen Skill

Sharpen an existing skill in either of two ways: review its instructions as an engineered interface, or compare them with the user's actual workflow. Use both when the evidence supports it.

1. Identify the target skill and read its `SKILL.md` and references relevant to the behavior. For a handoff, read the skills on both sides and locate where the cue belongs.
2. Review the skill as an interface: can its description trigger the right requests, can an agent tell when each instruction applies and when the work is done, and do the instructions serve the skill's purpose? Look for conflicting rules, duplicated guidance, vague bounds, and details better kept in a conditional reference. Propose only changes that would affect behavior; a shorter file is not automatically better.
3. When usage evidence exists, compare the skill with the user's requests, corrections, and repeated choices. Point to the evidence. A correction is stronger evidence than an unchallenged output; silence is not proof of preference. Separate a recurring preference from a one-time constraint.
4. Turn each supported gap into a scoped change at the smallest appropriate location. 
5. Show the target file, proposed wording, and reason. Ask whether to apply it unless the user already requested the edit. After editing, reconcile conflicting wording, validate the skill, and report the change. Preserve unrelated requirements and invocation settings unless the evidence calls for changing them.

An engineering review can proceed without conversation history. For a usage-based change, ask for a missing example when the necessary history is unavailable. Do not invent usage evidence or turn a single example into a universal rule.
