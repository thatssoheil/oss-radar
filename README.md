# oss-radar

A hand-maintained log of high-potential open-source repositories and issues worth contributing to.

No automation, no scripts, no CI. Every entry is found and vetted in an AI session (Hermes), then committed by hand. This repo is the memory: it records what was surveyed, why it looked promising, and what happened to it - so the same ground is never re-surveyed twice.

## How entries get added

1. An AI session (the model chosen in Hermes) surveys candidate repos/issues using the council approach: maintainer appetite, user impact, verifiability, strategic fit.
2. You approve the candidate.
3. The entry is committed: `repos/<repo>/README.md` for the repo, `repos/<repo>/issues/<n>.md` for each issue.
4. Status updates are APPENDED as dated lines. Entries are never edited in place.

## Layout

```
repos/
  _template.md            # copy this shape for new entries
  <repo-name>/
    README.md             # repo entry: why high-potential, signals, date added
    issues/
      <n>.md              # one file per issue: reasoning + dated status lines
```

## Status vocabulary

- `candidate` - surfaced, not yet vetted
- `claimed` - you said you'd fix it
- `PR open` - fix submitted, reference the PR number
- `merged` - done
- `dead` - already fixed elsewhere, duplicate, or superseded
- `skipped` - rejected with a one-line reason (owner is on it, needs-repro, wrong fit)
