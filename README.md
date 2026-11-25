# 🧠 Prompt Forge Pro

> Turn a rough idea into a structured, copy-paste-ready prompt for ChatGPT, Claude, Gemini, Midjourney and more — in a single HTML file.

[![Live App](https://img.shields.io/badge/demo-GitHub%20Pages-2AABEE?logo=github)](https://aghorbani84.github.io/APromptEngenier/)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![No build step](https://img.shields.io/badge/build-none-0D9488)
![UI: FA / EN](https://img.shields.io/badge/UI-فارسی%20%2F%20English-9333EA)

**Live app:** https://aghorbani84.github.io/APromptEngenier/

## Overview

Prompt Forge Pro (پرامپت‌ساز حرفه‌ای) is a client-side web tool for prompt engineering. You write a raw request, pick a target model and a behavioral "protocol", and it assembles a structured prompt — a role, a set of rules, your task and output preferences — ready to paste as a system prompt or at the start of a chat.

Everything runs in the browser. There is no backend and no build step; the whole app is one `index.html` with inline CSS and JavaScript.

## Features

- **8 target models** — ChatGPT, Claude, Gemini, DeepSeek, Llama, Qwen (text) and Midjourney, DALL·E (image); output is formatted per model
- **5 protocols**, each adding a role and a set of rules:
  - 🏛️ Principal Engineer (7 rules) · 💻 Senior Developer · ✍️ Creative Writer · 📊 Data Analyst · 🔬 Deep Research
- **Image mode** for Midjourney / DALL·E — art styles, lighting, aspect ratio (16:9, 1:1, 9:16, 4:5, 3:2, 21:9) and Midjourney version; image prompts are always generated in English
- **Output options** — response language (auto / Persian / English), length (short / medium / detailed), and toggles for step-by-step reasoning, ask-questions-first, examples, no fluff, and fenced code blocks
- **Quick presets** to start from an example
- **Prompt quality meter** that rates the raw prompt as you type
- **Copy to clipboard** or **download as `.txt`**
- **Bilingual UI** — Persian (RTL) and English (LTR), switchable instantly
- **Auto-save** of your settings and draft to `localStorage`

## Tech Stack

| Layer | Technology |
| --- | --- |
| Markup | HTML5 |
| Styling | Vanilla CSS (glassmorphism, CSS Grid, RTL-aware) |
| Logic | Vanilla JavaScript (inline) |
| Fonts | [Vazirmatn](https://github.com/rastikerdar/vazirmatn) and Inter via jsDelivr CDN |
| Persistence | Browser `localStorage` |
| Hosting | GitHub Pages |

## Getting Started

Use the [live app](https://aghorbani84.github.io/APromptEngenier/), or run it locally — there is nothing to install:

```bash
git clone https://github.com/aghorbani84/APromptEngenier.git
cd APromptEngenier

# open index.html in your browser
xdg-open index.html   # Linux
open index.html       # macOS
start index.html      # Windows
```

Or serve the folder with any static server, for example `python3 -m http.server 8000`, then visit http://localhost:8000.

> Fonts load from a CDN, so the first load needs an internet connection; the app itself makes no other network requests.

## How to Use

1. Type your raw request in the prompt box (or pick a preset).
2. Choose the target model.
3. Choose a protocol (or none).
4. Adjust the output options — or the image settings if you picked Midjourney / DALL·E.
5. Copy the final prompt or download it as a text file.

## Customizing

Protocols live in the `PROTOCOLS` array and models in the `MODELS` array inside `index.html`. Each protocol has an `id`, `icon`, bilingual `name` / `desc` / `role`, and a `laws` list — add an entry to create your own.

## Project Structure

```text
APromptEngenier/
├── index.html   # The entire app: markup, styles, i18n strings and prompt builder
└── README.md
```

## License

No license file has been added yet, so all rights are reserved by default. Open an issue if you would like to reuse the code.

## Author

Built by [@aghorbani84](https://github.com/aghorbani84).
