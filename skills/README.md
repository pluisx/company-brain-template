# 🛠️ Skills

Instrucciones especializadas para que las IAs repliquen tu voz y respeten las reglas de tu negocio.

## Available Skills

| File | What It Does |
|------|-------------|
| `your-voice.md` | Detailed instructions to replicate your writing voice |
| `business-rules.md` | Business rules every AI must follow when acting on your behalf |

## When to Use Each File

- **your-voice.md:** Cuando necesitas que una IA escriba en tu nombre (emails, posts, propuestas)
- **business-rules.md:** Cuando una IA toma decisiones por ti (pricing, deals, operaciones)

## Usage in Claude Code

```bash
> "Read skills/your-voice.md and then write [content] in my voice"
> "Read skills/business-rules.md before suggesting any sales strategy"
```

## How to Customize

Both files have `<!-- FILL IN: -->` comments guiding you.

The more specific and personal you make these files, the harder it becomes for an AI to sound generic when it writes as you.
