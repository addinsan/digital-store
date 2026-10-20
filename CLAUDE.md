# digital-store

## Instagram skills

The `ig-*` skills in `.claude/skills/` keep their memory in `.claude/instagram/`
(paths are relative to the repo root, so run their Python tools from here, e.g.
`python3 .claude/skills/ig-viral/swipe.py captured.tsv --out .claude/instagram/swipe.md`):

- `voice.md`: the voice profile every skill reads. Start from `voice.template.md`.
- `log.md`, `swipe.md`, `plan.md`: written by `/ig-reel`, `/ig-comment`, `/ig-viral` and `/ig-plan`.

Cloud sessions are ephemeral, so after creating or changing any of these files,
commit and push them in the same turn, or they are lost.
