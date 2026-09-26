### Learning CrewAI by building a news reader agent

## Secrets
`.env`
```bash
OPENAI_API_KEY="<paste_key_here>"
SERPER_API_KEY="<paste_key_here>"
```

## Setup
### If `uv` is not installed
```bash
mise use uv@latest
```

```bash
uv sync
uv run main.py
```