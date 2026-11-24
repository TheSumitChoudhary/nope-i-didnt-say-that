# Evidence Filter

A Codex skill for testing competing explanations. Separate observations from interpretations, rule out candidates that conflict with reliable evidence, and choose the next check that can tell the remaining explanations apart.

**Rule:** Eliminate an explanation only when reliable evidence contradicts a prediction it requires. If several explanations still fit, report what remains open.

## Use the skill

Save [SKILL.md](SKILL.md) as `~/.codex/skills/evidence-filter/SKILL.md`. In a new Codex chat, invoke `$evidence-filter` with the question and what you observed.
