# Contributing

Thanks for helping keep the collection accurate and useful.

## What fits

- Complete, paste-ready prompts: system prompts, persona locks, workspace
  policies, `AGENTS.md` files, config blocks, and Ollama Modelfiles.
- Corrections for prompts that no longer behave as documented.
- New model families where the prompt has been tested and the target surface
  (system message, `AGENTS.md`, Modelfile, or config slot) is stated.

## File conventions

1. **One prompt per file.** Lowercase, hyphens instead of spaces:
   ```text
   model-name.md
   ```
2. **Include the full prompt.** No summaries, excerpts, or placeholders.
3. **State where it goes.** Name the instruction surface in the file or in the
   pull request.
4. **Version significant revisions.** Add a new file (`opus-v3.md`) instead of
   silently overwriting an existing version.
5. **Keep claims testable.** Don't advertise compatibility you haven't checked.

## Pull requests

- Keep each pull request focused on one file or one model family.
- Describe the target model, version, and surface in the PR body.
- If you are correcting an existing file, link the outdated section or behavior.
- Run a quick read-through for broken links and unfinished placeholders.

## Issues

Include the model, the version, the affected file, and what changed. A short
reproduction or a before/after observation is enough.

Changes are tracked in [CHANGELOG.md](./CHANGELOG.md).
