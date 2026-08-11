# hermes-agent

- URL: https://github.com/NousResearch/hermes-agent
- Added: 2026-08-07
- Why high-potential: daily driver (this very session runs on it). Highest-signal bugs + receptive maintainers. 37 open PRs authored Aug 2026 (see PR log below).

## Signals

- Last push: daily
- Merge rate: high (2k+ PRs/month)
- Labels: real `good first issue` + `help wanted` population, but most tractable openings are unclaimed P2/P3 bugs

## Notes

- CONTRIBUTING: bug fixes first, claim before building, one issue = one PR.
- Dev clone at `~/.hermes/hermes-agent` is a LIVE RUNTIME - all work happens in `~/projects/hermes-agent-dev`.
- Fast repo: claim-check (`gh search prs`) the issue BEFORE building; 60% of a fresh pool is usually already taken.

## My PR log (all authored by thatssoheil, 2026-08-07)

### Open (37)

| # | Title |
|---|---|
| 81361 | fix(display): CLI display toggles honor quoted 'false' in config.yaml |
| 81357 | fix(petdex): quoted 'false' now disables display.pet.enabled on every surface |
| 81354 | fix(display): quoted 'false' now hides show_reasoning in CLI, TUI, and the config report |
| 81349 | fix(monitor): commit the hash before the snapshot so a failed write cannot desync them |
| 81348 | fix(cron): quoted 'false' now disables mirror_delivery and preflight |
| 83930 | fix(model): probe bare custom endpoints with the configured api_key (#83837) |
| 83880 | fix(kanban): refuse session claims of dispatcher-managed tasks (#83736) |
| 83538 | fix(cli): skill commands with instructions get queue feedback while agent is busy (#83209) |
| 83534 | fix(desktop): artifacts page timestamps render 1970 and local images fail (#83380) |
| 83513 | fix(cli): suspend only the CLI process on Ctrl+Z, not the process group (#83006) |
| 81347 | fix(terminal): keep mid-command backgrounded compounds valid shell |
| 81345 | fix(wake): quoted 'false' now disables start_new_session instead of enabling it |
| 81344 | fix(verify): reap the whole process group when a phase command times out |
| 81343 | fix(delegate): subagents get a dedicated SessionDB, not the parent's (#81267) |
| 80334 | fix(desktop): sticky user bubble no longer covers 'show earlier' (#80141) |
| 80324 | fix(mcp): cold-start identical-error parking for deterministically broken servers (#79141) |
| 80321 | fix(gateway): restart_after_turn_timeout default 6h -> 30min (#79133) |
| 80320 | fix(kanban): preserve budget metadata + late-finalizer guard + render iteration exhaustion (#79399) |
| 80316 | fix(gateway): channel_overrides scope model banner + reasoning effort (#79468) |
| 80309 | fix(acp): honor platform_toolsets.acp and agent.disabled_toolsets (#79516) |
| 80304 | fix(desktop): sudo password dialog shows the command being approved (#79874) |
| 80296 | fix(desktop): pinned sessions stay in their project group in grouped sidebar (#80013) |
| 80290 | fix(redact): do not mask shell-expansion env values (over-redaction, #79413) |
| 80286 | fix(kanban): active_pr respawn guard does not block a task's first spawn (#80231) |
| 80278 | fix(skills): search result window keeps per-source diversity (#80176) |
| 80272 | fix(gateway): /reasoning status card reads per-platform show_reasoning override (#79885) |
| 80267 | fix(kanban): kanban_create now accepts and honours scheduled_at (#80119) |
| 80256 | fix(cli): SIGINT during chat startup exits cleanly with code 130 (#80210) |
| 80243 | fix(recovery): bound the salvage upper edge near the data when the high probe fails (#80205) |
| 79786 | fix(kanban): honor auto_promote_children=false in dispatcher sweep (#79608) |
| 79785 | fix(api): serve full compression lineage in session messages endpoints (#79565) |
| 79767 | fix(serve): make ws keepalive ping configurable (#79635) |
| 79766 | fix(cron): stamp session cwd from configured workdir (#79623) |
| 79754 | fix(gateway): fall back to direct credentials when tool gateway unavailable (#79628) |
| 79744 | fix(search): report true total_count when rg fetch truncates (#79530) |
| 79743 | fix(tui): honor checkpoints.enabled from config on desktop (#79625) |
| 79734 | fix(update): gate 'Code updated!' on HEAD actually moving (#79678) |
| 79533 | fix(cli): finalize Relay session in one-shot cleanup (#79471) |
| 78963 | fix(aux): resolve concrete billing provider and retain Anthropic cache tokens |
| 78090 | feat: allow tools to consume prior tool output by reference (#78061) |
| 76470 | fix(config): decode JSON array literals into YAML lists on config set |
| 76463 | fix(desktop): refresh sibling terminals when the shared WebGL atlas is cleared |

### Closed, not merged (9)

| # | Title |
|---|---|
| 80643 | fix(redact): close emission gaps - env suffix keys, control-char splits, process(list) (#77484) |
| 80330 | fix(serve): headless backend exits when the desktop parent dies (#80204) |
| 78982 | fix(cron): degrade lifecycle_guard when HOME is unresolvable |
| 78979 | fix(plugins): auto-add scheme to schemeless Hindsight api_url |
| 78934 | fix(cli): support 'k'/'K' version prefix in model sort |
| 78054 | fix(security): add security.literal_secrets config to redact exact strings in file_read mode (#72778) |
| 77768 | fix(secrets): close redaction gaps - env-name variants, control-char splits, process(list) |
| 58232 | feat: add search/filter to /model picker |
| 58213 | feat: add search/filter to /model picker |
