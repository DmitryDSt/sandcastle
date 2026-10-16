---
"@ai-hero/sandcastle": patch
---

Fix the Codex `.env.example` template written by `sandcastle init`: it now uses `OPENAI_API_KEY` (the variable the Codex CLI reads) instead of `OPENAI_KEY`, which nothing read.
