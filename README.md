# ai-ollama

Ollama driver for the togo `ai` plugin — a unified LLM interface (chat + embeddings) for togo apps.

## Install
```bash
togo install togo-framework/ai-ollama
```

## Configure
Set `AI_DRIVER=ollama` and:
```env
OLLAMA_API_KEY=...
# optional: OLLAMA_BASE_URL=http://localhost:11434/v1
```

Then the `ai` plugin routes `Chat`/`Embed` through Ollama. Token usage is reported via `ai.Usage` (for the billing plugin).

MIT © ToGO
