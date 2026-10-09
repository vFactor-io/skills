# vFactor Skills

Skills for getting agents to do real work, from the vFactor training courses. They use the open Agent Skills format, so they work in ChatGPT, Claude, Codex, Cursor and other agents that support it.

## Install

Install every skill:

```
npx skills add vFactor-io/skills -g
```

Install one skill:

```
npx skills add vFactor-io/skills --skill lets-plan-it -g
```

The `-g` makes the skill available in every chat, not only in the folder you ran the command from.

If you use the ChatGPT or Claude app rather than a terminal, download the skill's folder as a ZIP and upload it in the app's Skills settings.

## Skills

| Skill | What it does |
|---|---|
| [lets-plan-it](skills/lets-plan-it/SKILL.md) | Interviews you about a piece of work you want an agent to handle end to end, then writes a one-page plan for you to approve. |
