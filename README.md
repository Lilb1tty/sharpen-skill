# Sharpen Skill

Sharpen Skill helps refine a local Codex skill from evidence in your conversation. It compares a skill's current instructions with your requests, corrections, and repeated workflow choices, then proposes a focused change to the relevant `SKILL.md`.

It can spot differences within one skill, such as a preference to use one commit for a small cohesive change and multiple commits when work spans several modules. It can also spot a handoff between skills, such as routinely using `grill-me` after brainstorming and before writing a spec.

The skill shows the proposed wording and asks whether to apply it. If you have already explicitly requested the edit, it makes the change and validates the skill. It does not treat an unchallenged output or a single example as a permanent preference.

## Install

```bash
npx skills add Lilb1tty/sharpen-skill
```

## Use

After using another skill, invoke `$sharpen-skill` and describe the behavior you preferred or corrected. For example:

> `$sharpen-skill` — I usually run `grill-me` after brainstorming and before writing the spec. Suggest how to reflect that in the brainstorming skill.

The skill needs access to the relevant conversation and local skill files. If earlier context is unavailable, provide the request, output, or correction you want it to compare.
