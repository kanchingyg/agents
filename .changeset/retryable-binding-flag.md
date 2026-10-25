---
"agents": patch
---

Honour the Workers AI binding's `retryable` boolean on thrown errors in `normalizeThrownError`, so transient failures like "Network connection lost." participate in AI SDK `maxRetries` and fallback.
