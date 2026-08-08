# hermes-agent

- URL: https://github.com/NousResearch/hermes-agent
- Added: 2026-08-07
- Why high-potential: daily driver (this very session runs on it). Highest-signal bugs + receptive maintainers. Proven merge history: 9 PRs merged in Aug 2026 (#81343-#81361).

## Signals

- Last push: daily
- Merge rate: high (2k+ PRs/month)
- Labels: real `good first issue` + `help wanted` population, but most tractable openings are unclaimed P2/P3 bugs

## Notes

- CONTRIBUTING: bug fixes first, claim before building, one issue = one PR.
- Dev clone at `~/.hermes/hermes-agent` is a LIVE RUNTIME - all work happens in `~/projects/hermes-agent-dev`.
- Fast repo: claim-check (`gh search prs`) the issue BEFORE building; 60% of a fresh pool is usually already taken.

## PR log (no source issue - direct fixes)

- 81344: fix(verify) - reap the whole process group when a phase command times out (2026-08-07)
- 81345: fix(wake) - quoted 'false' now disables start_new_session instead of enabling it (2026-08-07)
- 81346: fix(telegram) - keep code blocks on legacy path to preserve copy affordance (2026-08-07)
- 81347: fix(terminal) - keep mid-command backgrounded compounds valid shell (2026-08-07)
- 81348: fix(cron) - quoted 'false' now disables mirror_delivery and preflight (2026-08-07)
- 81349: fix(monitor) - commit the hash before the snapshot so a failed write cannot desync them (2026-08-07)
- 81351: fix(desktop) - keep-alive hidden panes can no longer paint through (2026-08-07)
- 81352: fix(buzz) - discover new DMs over WebSocket (2026-08-07)
- 81354: fix(display) - quoted 'false' now hides show_reasoning in CLI, TUI, and the config report (2026-08-07)
- 81357: fix(petdex) - quoted 'false' now disables display.pet.enabled on every surface (2026-08-07)
- 81359: fix(desktop) - distinguish auto-discovered repos from explicit projects in the sidebar overview (2026-08-07)
- 81360: feat(desktop) - bundle Theme Forge, forge desktop themes from any image (2026-08-07)
- 81361: fix(display) - CLI display toggles honor quoted 'false' in config.yaml (2026-08-07)
