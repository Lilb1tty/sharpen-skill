# Sharpen Skill

Sharpen Skill reviews and improves an existing `SKILL.md` in two ways:

- **Engineering review:** Check whether the description triggers the right requests, instructions have clear scope and completion criteria, and the file avoids conflicting or duplicated guidance.
- **Usage review:** Compare instructions with your requests, corrections, repeated choices, and handoffs between skills.

It proposes a focused change with the target file, wording, and reason. It asks before applying the proposal unless you already requested the edit. It does not treat silence or a single example as a permanent preference.

## Install

```bash
npx skills add Lilb1tty/sharpen-skill
```

## Use

Invoke `$sharpen-skill` with the skill you want reviewed. Ask for an engineering review, describe a recurring difference between the skill and your workflow, or request both.

An engineering review can use the skill files alone. For a usage review, provide relevant requests, outputs, or corrections if the earlier conversation is unavailable.
