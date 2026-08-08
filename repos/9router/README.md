# 9router

- URL: https://github.com/decolua/9router
- Added: 2026-08-07
- Why high-potential: the AI router/gateway powering agent.thatssoheil.website (deployed + operated daily). Active OSS project, maintainers receptive - 10 open PRs authored Aug 2026.

## Signals

- Last push: active
- Merge rate: unknown (recent PRs still open)
- Labels: n/a

## Notes

- My PRs cluster on auth/settings/streaming compat fixes (3079-3089).
- Issue 2994 (CLI Tools Apply button disabled for OpenAI/Anthropic providers) was worked/commented.

## My PR log

### Open (10)

| # | Title |
|---|---|
| 3089 | fix(gemini): strip stray value key at schema nodes |
| 3088 | fix(kimi): route API-key auth to platform endpoint, not Kimi Code |
| 3087 | feat(headroom): add lossless mode to proxy start |
| 3085 | fix(auth): enforce requireApiKey on GET /v1/models |
| 3084 | fix(compat): normalize NVIDIA/vLLM reasoning to reasoning_content |
| 3083 | fix(usage): read cached_tokens from nested prompt_tokens_details |
| 3082 | fix(gemini): walk schema nodes only in cleanJSONSchemaForAntigravity |
| 3081 | fix(stream): inject stream_options.include_usage for OpenAI-compatible streaming |
| 3080 | fix(settings): bridge REQUIRE_API_KEY env var to requireApiKey setting |
| 3079 | fix(models/test): raise probe max_tokens for reasoning models |

### Closed, not merged (1)

| # | Title |
|---|---|
| 3086 | fix(auth): allow local JWT-less browser on local-only routes when login disabled |
