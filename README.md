# BACKEND with JAVASCRIPT

> `// course summary · web dev`
>
> **The basics that actually stick**

```
╔══════════════════════════════════════════════════════╗
║                                                      ║
║   01 · JAVASCRIPT    02 · EXPRESS    03 · DATABASE   ║
║                                                      ║
╚══════════════════════════════════════════════════════╝
```

A quick tour of what we covered in the course — JavaScript fundamentals, how Express handles the back-end, and how databases store all the stuff that matters.

Nothing fancy, just the bits worth remembering. If you're a classmate skimming for revision or a friend wondering what I've been up to — this is it. *Make sense?* Cool.

🔗 **[View the live site →](https://saragram-ux.github.io/backend-js-summary/)**

---

## What's in here

| Part | Covers |
|------|--------|
| **01 · JavaScript** | Datatypes · `var` / `let` / `const` · `undefined` vs `null` · `===` vs `==` · functions · constructors · `"use strict"` · Array vs Map · callbacks · modules · control flow |
| **02 · Express** | What Express does · MVC pattern · layouts & partials · middleware · HTTP methods · status codes |
| **03 · Database** | Relational databases · SQL basics · primary keys · foreign keys · relationships · cascading delete · indexes |

---

## Stack

```js
// nothing exotic
const stack = {
  html:  'vanilla',
  css:   'vanilla, custom properties',
  js:    'none — pure static',
  fonts: ['Orbitron', 'Share Tech Mono', 'Exo 2'],
  vibe:  'cyberpunk / retro terminal',
};
```

One file. No build step. No dependencies. Drop it anywhere and it works.

---

## Run it locally

Clone and open:

```bash
git clone https://github.com/saragram-ux/backend-js-summary.git
cd backend-js-summary
open index.html
```

That's it. No install, no `npm`, no nothing.

---

## Design notes

Built to be readable on a phone in bed and on a laptop at a desk. Three breakpoints:

- **Mobile** → single column, stacked
- **Tablet** → two columns where it makes sense
- **Desktop** → full three-column grid

The aesthetic is cyberpunk / retro-terminal — neon on near-black, scanline overlay, monospace for code, all the good stuff. Color-coded sections so you can find things by vibe (pink = JS quirks, green = database, cyan = HTTP, etc).

---

## Author

**Sara Gramstad** — `2026-05-08`

Backend with JavaScript course summary.

```
> coding the future_
```
