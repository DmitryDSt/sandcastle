---
"@ai-hero/sandcastle": patch
---

Fix the Codex `.env.example` template written by `sandcastle init`: it now uses `CODEX_API_KEY` (the only API-key variable `codex exec` reads from the environment) instead of `OPENAI_KEY`, which nothing read.
