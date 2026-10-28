# HILD-onboarding-ipad-2026-10 plan

## Goals

- Learn HILD by adopting it here: a repository ready to use HILD, and a first experience of agreeing, reviewing and accepting work ([scope #1](https://github.com/opherdonchin/HILD-onboarding-ipad-2026-10/issues/1)).
- Project scientific and software goals: none set yet; this is a disposable test repository.

## Current state

- HILD (upstream [bb299d2](https://github.com/Motor-Learning-Lab/HILD/tree/bb299d242e6de85861609f7b834919c5ed81f0d7)) is installed for Claude Code and merged to `main` ([PR #2](https://github.com/opherdonchin/HILD-onboarding-ipad-2026-10/pull/2), [937a036](https://github.com/opherdonchin/HILD-onboarding-ipad-2026-10/commit/937a036d2cca34018c2a16cef79dcb0b4d39a86b)); `--verify` passes.
- `.claude/skills` is a symlink; clones with `core.symlinks=false` get a plain file and lose skill discovery. Fixed locally; see the journal.
- Untested: skill discovery in a fresh session, onboarding validation, recovery from plan and journal.
- GitHub: squash merge allowed but not enforced (merge and rebase also allowed); `main` is unprotected.
- The wiki exists with only the default `Home` page.

## Next steps

1. Draft a `Process-HILD` wiki page (researcher alone marks it `understood`).
2. Try a fresh Claude Code session to see whether it recovers this state from the plan and journal; record the result.
3. Researcher decides whether to restrict merge methods and protect `main`.
4. Report the symlink finding upstream, if the researcher agrees.
