---
name: sharpen-skill
description: Compare local skills with the user's repeated usage, corrections, and preferred skill handoffs; propose focused improvements to a skill when asked to sharpen it.
---

# Sharpen Skill

Use the current conversation as evidence to identify where a local skill misses the user's working preference.

1. Identify the skill that governs the behavior and read its `SKILL.md` plus any relevant reference. If the behavior spans skills, read both sides of the handoff and locate the instruction that should cue the next step.
2. Compare what the skill says with what the user requested, corrected, or repeatedly did after using it. Point to the specific evidence. A correction is stronger evidence than an unchallenged output; silence is not proof of preference.
3. Express the gap as a scoped decision rule. Distinguish a recurring preference from a one-time constraint, and distinguish the next step's cue from a requirement to run that step every time. 
4. Show the target file, the exact wording to add or replace, and why that location fits. Ask whether the user wants the proposed change applied. If the user already explicitly asked to edit the target skill, apply the focused change without asking again.
5. After an authorized edit, reconcile conflicting wording, validate the skill's structure, and report what changed. Preserve the skill's purpose, invocation behavior, and unrelated requirements.

# Rule
If the relevant history is unavailable, ask for the missing example or analyze what the user provides. Do not present an imagined history as evidence or turn a single example into a universal rule.
