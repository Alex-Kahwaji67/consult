# Consult

A Codex skill for thinking through an idea, one focused question at a time. It uses relevant context, tests assumptions, and helps you reach a decision and a practical next step.

## Install

Install globally using either method. If `~/.agents/skills/consult` already exists, review it before replacing it.

- **Clone:** Clone this repository, then copy the clone's root folder to `~/.agents/skills/consult`.
- **ZIP:** Download and extract the ZIP, then copy the extracted repository folder (usually `consult-main`) to `~/.agents/skills/consult`.

In both cases, `SKILL.md` and `agents/` must sit directly inside `~/.agents/skills/consult`.

Codex detects skills automatically. Restart Codex if Consult does not appear.

## Use

Mention `$consult` in your prompt or choose Consult from the `/skills` picker:

> $consult Help me think through this idea: ...

Consult uses Humanizer in embedded mode when available, with a plain-language fallback. Humanizer is optional and is not bundled.

See the [official skills guide](https://learn.chatgpt.com/docs/build-skills) for installation and invocation details.

MIT licensed. See [LICENSE](LICENSE).
