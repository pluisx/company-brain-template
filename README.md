# 🧠 AI Company Brain — Template

> Tu contexto maestro portable para cualquier IA. Funciona con Claude, ChatGPT, Claude Code o cualquier plataforma.

## ¿Qué es el AI Company Brain?

Este repositorio es tu **cerebro de empresa en formato texto**. En vez de explicarle tu contexto a cada IA desde cero, tienes todo aquí: quién eres, qué empresas tienes, cómo hablas, qué quieres lograr.

Una vez cargado, cualquier IA entiende tu negocio desde el primer mensaje.

## ¿Por qué funciona?

- **Portable:** Un solo repo, funciona en cualquier plataforma de IA
- **Contextual:** Las IAs son mucho más útiles cuando tienen contexto real de tu negocio
- **Vivo:** Actualízalo cuando tu negocio cambie — nuevos clientes, nuevas metas, nuevas empresas
- **Sin lock-in:** Markdown puro. Funciona en ChatGPT, Claude, Gemini, Claude Code, o cualquier herramienta futura

## Estructura

```
company-brain/
├── context/          ← Quién eres, tus empresas, tu cliente ideal, tu voz
├── agents/           ← Instrucciones para agentes de IA especializados
├── prompts/          ← Prompts listos para usar (outreach, posts, propuestas)
├── skills/           ← Tu voz y reglas de negocio para que las IAs te imiten
└── memory/           ← Log de decisiones y contexto acumulado
```

## Cómo usarlo en 3 pasos

### Paso 1: Clona este repo
```bash
git clone https://github.com/TU_USUARIO/company-brain.git
cd company-brain
```

### Paso 2: Llena los archivos
Reemplaza todos los `[placeholders en corchetes]` con tu información real.  
Cada archivo tiene comentarios `<!-- FILL IN: ... -->` que te guían.

Empieza por:
1. `context/ABOUT.md` — Quién eres
2. `context/COMPANIES.md` — Tus empresas
3. `context/GOALS.md` — Tus metas
4. `context/VOICE.md` — Cómo hablas

### Paso 3: Pega el contexto en tu IA favorita

---

## Cómo conectarlo a cada plataforma

### Claude Code
```bash
# Abre Claude Code en la carpeta del repo
cd company-brain
claude

# Dile a Claude que lea el contexto
# > "Lee todos los archivos en context/ y luego ayúdame con [tarea]"
```

### Claude (web / Projects)
1. Crea un nuevo **Project** en Claude.ai
2. Sube todos los archivos `.md` del repo
3. Desde ese momento, Claude tiene tu contexto en cada conversación

### ChatGPT (Custom GPT o Projects)
1. En **ChatGPT Projects**: carga los archivos como "files" del proyecto
2. En **Custom GPT**: pega el contenido de `context/ABOUT.md` y `context/COMPANIES.md` en las instrucciones del sistema
3. También puedes simplemente pegar el contenido al inicio de cualquier conversación

### Cualquier otra IA
El sistema es texto puro — funciona con Gemini, Mistral, Llama, o cualquier modelo.  
Copia y pega el contenido que necesites al inicio de cada conversación.

---

## Tips de uso

- **Para tareas de contenido:** Carga siempre `context/VOICE.md` + `skills/your-voice.md`
- **Para ventas y outreach:** Carga `context/IDEAL_CLIENT.md` + `skills/business-rules.md`
- **Para contexto completo:** `"Lee todos los archivos en context/ antes de ayudarme"`
- **Para memoria histórica:** `"Lee memory/ para entender el contexto acumulado"`

---

## Crédito

Template creado por [Tu canal de YouTube]

Inspirado en el sistema original de Pedro (@pluisx). Síguelo para aprender más sobre cómo construir con IA.

---

*¿Encontraste esto útil? Dale una ⭐ al repo y compártelo con alguien que lo necesite.*
