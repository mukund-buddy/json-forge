# 🧪 JSON Forge

![vanilla JS](https://img.shields.io/badge/vanilla-JS-f7df1e?logo=javascript&logoColor=black)
![client-side](https://img.shields.io/badge/privacy-100%25-3dff9e)
![license](https://img.shields.io/badge/license-MIT-4dd0e1)

**A browser-based JSON toolkit — format, validate, and inspect JSON instantly. No uploads, no server, no nonsense.**

> Part of [The Antigle](https://github.com/mukund-buddy) 🔥 — built with AI assistance, tested and refined by hand.

**Live demo:** _coming soon_ · [Repository](https://github.com/mukund-buddy/json-forge)

---

## ✨ Features

- **Formatter / Beautifier** — messy JSON → clean, indented, readable JSON
- **Validator** — instant error messages with line numbers when JSON is broken
- **Tree Viewer** — expandable tree view of your JSON structure
- **Minifier** — strip whitespace for production payloads
- **100% client-side** — your JSON never leaves the browser (privacy-first, like everything I build)

## 🚀 How It Works

JSON parsing and validation happens in a single JavaScript file (`app.js`).
If you can read HTML and JSON, you can read this whole project — that's the point.

```
index.html   →  the layout (3 panes: input, output, tree)
style.css    →  the look (same vibe as AntigleForge)
app.js       →  the brain (parse, format, validate, render tree)
```

## 🎯 Why This Exists

Every JSON tool I tried online was either bloated, full of ads, or wanted to
upload my data to a server somewhere. This one:

1. Runs entirely offline after load
2. Shows **where** your JSON breaks (line + reason), not just "invalid"
3. Is simple enough to learn from — no frameworks, no build step

## 🗺️ Roadmap

- [x] Formatter + validator (v1)
- [x] Tree view
- [ ] JSON ⇄ CSV converter
- [ ] JSON Schema validator
- [ ] Diff two JSON files
- [ ] Path query (like `$.users[0].name`)

## 🧑‍💻 Built Differently (Honest Note)

This project is **AI-assisted**. I direct the build, then I test every feature
by hand and fix what feels wrong. I keep the code readable on purpose —
if you're learning, this repo is meant to be read.

## 🏷️ Suggested GitHub Topics

`json` `formatter` `validator` `minifier` `developer-tools` `vanilla-js` `privacy` `client-side` `the-antigle`

## 📄 License

MIT — do whatever you want, just don't blame me if your JSON explodes. 😄
