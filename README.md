# Saudi eLeague — Reaction Bolt

A tiny browser reaction-time game themed for the Saudi eLeague, set against a
stylized Riyadh night skyline.

## Game
- Numbers flash in random colors.
- Hit **SPACE** the moment a number turns the eLeague **mint green** (`#00f5a0`).
- Pressing space on the wrong color is a **false start**.
- 5 rounds. The best (fastest) reaction wins.

## Run locally
Open `index.html` in a browser. No build step.

```bash
# optional: any static server works
npx serve .
```

## Deploy to Vercel

### Option A — Vercel CLI
```bash
npm i -g vercel
cd eleague-reaction
vercel        # follow prompts (project name etc.)
vercel --prod # promote to production URL
```

### Option B — Drag & drop
1. Go to https://vercel.com/new
2. Drag this folder onto the page.
3. Framework preset: **Other** (it's a plain static site).
4. Deploy.

That's it — the page is purely static (HTML + inline CSS/JS + SVG), so no
build, no environment variables, no backend.
