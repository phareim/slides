# Slides

Presentation decks. Each subfolder is one deck — a self-contained Vite + React + TS app scaffolded by the [`react-presentations`](../sleeper/claude/skills/react-presentations/) skill.

## Create a new deck

Ask Claude: *"Create a new presentation called <name>."* The skill walks through theme selection (plain / miles / zaptec / almanac) and scaffolds into a new subfolder here.

## Per-deck commands

(All run from inside a deck folder.)

```bash
npm install
npm run dev          # http://localhost:5173
npm run build        # -> dist/
npm run test         # vitest
npm run export-pdf   # -> dist/<deck>.pdf  (first run downloads Chromium)
npm run deploy       # idempotent Cloudflare Pages deploy -> <deck>.pages.dev
```

## Decks

One subfolder per deck. Each has its own README with the same commands above.
