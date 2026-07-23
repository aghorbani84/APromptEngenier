<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0-blue" alt="Version 1.0" />
  <a href="https://github.com/aghorbani84/APromptEngenier/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green" alt="License: MIT" /></a>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Zero_Deps-0D9488" alt="Zero Dependencies" />
  <img src="https://img.shields.io/badge/i18n-FA%2FEN-9333EA" alt="i18n" />
</p>

<h1 align="center">🧠 Prompt Forge Pro — پرامپت‌ساز حرفه‌ای</h1>

<p align="center">
  <em>پرامپت‌هات رو به سطح مهندس Principal ارتقا بده</em><br/>
  <em>Upgrade your prompts to Principal Engineer level</em>
</p>

<p align="center">
  <a href="https://aghorbani84.github.io/APromptEngenier/">🚀 Live App</a> &nbsp;·&nbsp;
  <a href="https://github.com/aghorbani84/APromptEngenier/issues">🐛 Report Bug</a> &nbsp;·&nbsp;
  <a href="https://github.com/aghorbani84/APromptEngenier/issues">✨ Request Feature</a>
</p>

---

## 📑 Table of Contents

- [🧠 About](#-about)
- [✨ Features](#-features)
- [📜 Protocols](#-protocols)
- [🤖 Supported Models](#-supported-models)
- [🚀 Quick Start](#-quick-start)
- [📖 Usage Guide](#-usage-guide)
- [🧰 Tech Stack](#-tech-stack)
- [🏗️ Architecture](#️-architecture)
- [🤝 Contributing](#-contributing)
- [❓ FAQ](#-faq)
- [📄 License](#-license)
- [👤 Author](#-author)

---

## 🧠 About

**Prompt Forge Pro** is a single-file, zero-dependency web application that takes your raw, unpolished prompt and transforms it into an engineered, copy-paste-ready prompt for any AI model.

Write your raw idea → pick a behavioral protocol → choose your target model → get a structured, optimized prompt ready to paste as a System Prompt or at the start of a chat.

Built for developers, writers, analysts, and anyone who wants consistently high-quality AI outputs — without memorizing prompt engineering frameworks.

## ✨ Features

| Feature | Description |
|---|---|
| 📜 **5 Expert Protocols** | Principal Engineer, Senior Developer, Creative Writer, Data Analyst, Image Engineer — each with specific laws and role assignments |
| 🤖 **8 Target Models** | ChatGPT, Claude, Gemini, DeepSeek, Llama, Qwen, Midjourney, DALL·E — output formatted for each model's conventions |
| 🎨 **Image Generation Mode** | When Midjourney or DALL·E is selected, shows art style, lighting, aspect ratio, and model version controls |
| 📊 **Prompt Quality Score** | Real-time health bar that rates your raw prompt from Weak → Good → Excellent |
| 🌍 **i18n (فارسی / English)** | Full bilingual UI — switch instantly between Persian (RTL) and English (LTR) |
| 📋 **One-Click Copy** | Copy the final engineered prompt to your clipboard |
| ⬇️ **Download TXT** | Export the prompt as a UTF-8 text file |
| 🎯 **4 Quick Presets** | Pre-filled examples: React debug, API design, Blog post, Logo design |
| ⚙️ **Output Options** | Response language (auto/fa/en), length (short/medium/detailed), plus toggleable switches for step-by-step reasoning, ask-questions-first, request examples, no fluff, code in fenced blocks |
| 🌙 **Dark Glassmorphism UI** | Animated blobs, grid backdrop, glass panels — premium aesthetic |
| 📱 **Fully Responsive** | 2-column on desktop, single-column on mobile/tablet |
| 🔌 **Zero Dependencies** | Pure HTML + CSS + JS — no frameworks, no build step, no Node |
| 💾 **Auto-Save** | All settings persisted to `localStorage` — resume where you left off |

## 📜 Protocols

Each protocol assigns a specific role and a set of enforceable laws to the AI model:

| Protocol | Role | Laws | Best For |
|---|---|---|---|
| 🏛️ **Principal Engineer** | Principal Software Engineer with 15+ years experience | 7 laws: Zero hallucination, "I don't know" clause, senior mindset, modern tech doctrine, security-first, no yes-man behavior, step-by-step reasoning | Architecture, debugging, code review, security audits |
| 💻 **Senior Developer** | Senior Software Engineer writing production-ready code | 5 laws: Clean code (SOLID/DRY/KISS), test-aware engineering, performance consciousness, explain the why, production-ready default | Feature implementation, refactoring, code quality |
| ✍️ **Creative Writer** | Award-winning writer and editor | 5 laws: Hook in first line, show don't tell, audience calibration, originality mandate, ruthless editing | Blog posts, marketing copy, social media, storytelling |
| 📊 **Data Analyst** | Senior Data Analyst turning messy data into insights | 5 laws: Question the data, statistical rigor, correlation ≠ causation, visual first, actionable output | Data analysis, metrics, research, decision-making |
| 🎨 **Image Engineer** | Expert prompt engineer for image generation | Optimized for Midjourney/DALL·E with style, lighting, aspect ratio, and version parameters | Logo design, illustrations, product shots, concept art |

## 🤖 Supported Models

| Model | Icon | Output Format |
|---|---|---|
| ChatGPT | 🤖 | Markdown |
| Claude | 🎭 | XML-style |
| Gemini | ✨ | Markdown |
| DeepSeek | 🐋 | Markdown |
| Llama | 🦙 | Markdown |
| Qwen | 🌐 | Markdown |
| Midjourney | 🎨 | Midjourney prompt syntax |
| DALL·E | 🖼️ | DALL·E prompt syntax |

Text models receive a structured markdown prompt. Image models receive an English-optimized prompt with art style, lighting, aspect ratio, and version parameters.

## 🚀 Quick Start

### Option 1 — Use it online (recommended)

Open 👉 **[aghorbani84.github.io/APromptEngenier](https://aghorbani84.github.io/APromptEngenier/)** in your browser. Zero install.

### Option 2 — Use it locally

```bash
# Clone the repository
git clone https://github.com/aghorbani84/APromptEngenier.git
cd APromptEngenier

# Open in browser
# macOS
open index.html
# Linux
xdg-open index.html
# Windows
start index.html
```

> 💡 No `npm install`, no build step. The entire app is one HTML file with embedded CSS and JS.

## 📖 Usage Guide

### 1. Write Your Raw Prompt

Type or paste your raw, unpolished request in the text area. The quality health bar on the right updates in real-time:
- 🔴 **Weak** — add more detail
- 🟡 **Good** — decent
- 🟢 **Excellent** — precise and complete

### 2. Pick a Target Model

Click one of the 8 model chips in the sidebar. The output format adapts automatically:
- Text models (ChatGPT, Claude, Gemini, etc.) → structured markdown/XML prompt
- Image models (Midjourney, DALL·E) → English-optimized prompt with art parameters

### 3. Choose a Protocol

Select a behavioral protocol that matches your task. Each protocol adds a role definition and enforceable laws to the output. Protocols can be toggled off for a simple, unstructured prompt.

### 4. Configure Options

- **Response language**: Auto-detect, Persian, or English
- **Length**: Short, Medium, or Detailed
- **Toggles**: Step-by-step reasoning, ask questions first, request examples, no fluff, code in fenced blocks

### 5. Image Mode (Midjourney / DALL·E)

When an image model is selected, a new section appears with:
- **Art style**: Photorealistic, Digital art, Oil painting, 3D render, etc.
- **Lighting**: Natural, Dramatic, Soft, Studio, Neon
- **Aspect ratio**: 1:1, 16:9, 9:16, 4:3, 3:4
- **Model version**: v5, v6, etc.

### 6. Export

- **📋 Copy** — copies the final prompt to your clipboard, paste into your model's chat
- **⬇ Download TXT** — saves the prompt as a `.txt` file

## 🧰 Tech Stack

| Layer | Technology | Why |
|---|---|---|
| Markup | HTML5 | Semantic, accessible, zero build |
| Styling | Vanilla CSS3 | `color-mix()`, `backdrop-filter`, CSS Grid, custom scrollbars, RTL-aware |
| Logic | Vanilla JavaScript (ES2020+) | No framework overhead, i18n engine, prompt builder, quality scorer — all inline |
| Typography | [Vazirmatn](https://github.com/rastikerdar/vazirmatn) + [Inter](https://rsms.me/inter/) via CDN | Persian + English fonts |
| Persistence | `localStorage` | Auto-save, auto-restore, zero server |

## 🏗️ Architecture

```
┌──────────────────┐   user input    ┌──────────────────┐
│   Control Panel   │ ─────────────▶  │   State Object   │
│  (model, protocol,│                 │  (model, protocol,│
│   raw text, opts) │                 │   text, options)  │
└──────────────────┘                 └────────┬─────────┘
                                              │ oninput + 120ms debounce
                                              ▼
                                      ┌───────────────┐
                                      │ buildPrompt() │
                                      │  (pure fn)    │
                                      └───────┬───────┘
                                              │
                                   ┌──────────┼──────────┐
                                   ▼          ▼          ▼
                            ┌───────────┐ ┌──────┐ ┌──────────┐
                            │ Live      │ │ Q/S  │ │ Download │
                            │ Preview   │ │ Cnt  │ │ / Copy   │
                            └───────────┘ └──────┘ └──────────┘
```

1. Every input updates a single in-memory state object.
2. `buildPrompt()` is a pure function that concatenates the role, laws, and user request based on the selected model's output format.
3. The preview panel renders the final prompt in real-time with a live quality score.
4. State auto-saves to `localStorage` with a 400ms debounce.

## 🤝 Contributing

1. 🍴 **Fork** the repository
2. 🌿 Create your feature branch — `git checkout -b feature/amazing-thing`
3. ✏️ **Commit** your changes — `git commit -m 'feat: add amazing thing'`
4. 🚀 **Push** to the branch — `git push origin feature/amazing-thing`
5. 🎯 Open a **Pull Request**

Please follow [Conventional Commits](https://www.conventionalcommits.org/). For major changes, open an issue first.

## ❓ FAQ

**Q: Do I need to install anything?**
A: No. Open `index.html` in any modern browser. That's the whole setup.

**Q: Does it send my data anywhere?**
A: No. Everything runs locally in your browser. No telemetry, no analytics, no server.

**Q: How does the quality score work?**
A: It analyzes your raw prompt for keywords, specificity, length, and structure. Longer, more specific prompts score higher.

**Q: Can I add my own protocols?**
A: Yes. Add a new protocol object to the `PROTOCOLS` array in the source `index.html`. Each protocol needs an `id`, `icon`, `name`, `desc`, `role`, and `laws` array.

**Q: What's the difference between protocols?**
A: Each protocol assigns a specific expert role and enforceable laws to the AI. Choose the one that matches your task — coding → Principal/Senior, writing → Creative, data → Analyst, images → Image Engineer.

**Q: Why are image prompts always in English?**
A: Image generation models (Midjourney, DALL·E) produce the best results with English prompts. The tool auto-translates the language setting for image mode.

**Q: Can I use this offline?**
A: Yes. After opening the app once, all assets (fonts, code) are loaded. If you save the HTML file locally, it works entirely offline.

## 📄 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for the full text.

## 👤 Author

**Abolfazl Ghorbani** — Software Engineer · Flutter × Rust

[![GitHub](https://img.shields.io/badge/🐙_GitHub-@aghorbani84-black?logo=github)](https://github.com/aghorbani84)
[![Website](https://img.shields.io/badge/🌐_Website-abolfazlghorbani84.ir-blue)](https://abolfazlghorbani84.ir)
[![YouTube](https://img.shields.io/badge/▶️_YouTube-@abolfazl_ghorbani-red?logo=youtube)](https://youtube.com/@abolfazl_ghorbani)
[![Email](https://img.shields.io/badge/📧_Email-abolfazlghorbani369@proton.me-purple)](mailto:abolfazlghorbani369@proton.me)

---

<p align="center">
  Made with ❤️ for the AI community · <b>Prompt Forge Pro</b> 🧠<br/>
  © 2026 — Released under the MIT License
</p>
