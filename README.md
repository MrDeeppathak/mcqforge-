# MCQ Forge ⚡
### AI-Powered University Question Bank Generator

A free, open-source web application that generates high-quality Multiple Choice Questions (MCQs) for university-level courses using AI. Paste your syllabus, configure your topics, and get an Excel-ready question bank in seconds.

---

## 🔴 Live Demo
👉 **[mcqforge.github.io]([https://mcqforge.github.io](https://mrdeeppathak.github.io/mcqforge-/)**

---

## ✨ Features

- **4 AI Providers** — Claude (Anthropic), ChatGPT (OpenAI), Gemini (Google, **FREE**), OpenRouter (**FREE credits**)
- **University-grade questions** — Bloom's Taxonomy mapped, challenging distractors, no guessable answers
- **Mixed question types** — Standard MCQ, True/False, Fill in the Blank, Match the Column
- **Excel-ready export** — 32-column TSV format for direct LMS upload
- **History** — Every generated bank is saved locally in your browser
- **Preview** — Review all questions before downloading
- **Zero setup** — No installation, no backend, just open the HTML file

---

## 🚀 How to Use

### Option 1 — GitHub Pages (Live URL)
1. Fork this repository
2. Go to **Settings → Pages → Source → main branch**
3. Your live URL: `https://YOUR_USERNAME.github.io/mcqforge`

### Option 2 — Local (Offline)
1. Download the repository as a ZIP
2. Open `index.html` in any modern browser
3. Done!

---

## 🔑 Getting a Free API Key

| Provider | Free? | Link |
|----------|-------|------|
| **Gemini** | ✅ Yes — no credit card | [aistudio.google.com/apikey](https://aistudio.google.com/apikey) |
| **OpenRouter** | ✅ Free credits on signup | [openrouter.ai/keys](https://openrouter.ai/keys) |
| Claude | Paid credits required | [console.anthropic.com](https://console.anthropic.com) |
| ChatGPT | Paid credits required | [platform.openai.com](https://platform.openai.com/api-keys) |

> 💡 **Recommended for free use:** Start with **Gemini** — completely free, no card needed, excellent quality.

---

## 📊 Output Format

The generated TSV file contains 32 columns matching university LMS upload templates:

| Column | Description |
|--------|-------------|
| Question | Full question text (supports HTML for Match the Column) |
| Option1–4 | Answer choices with challenging distractors |
| Answer | Correct option number (1–4) |
| Solution | 2–3 line explanation |
| Blooms_level | 1=Recall, 2=Understand, 3=Apply, 4=Analyze |
| Difficulty_level | 1=Easy/Moderate, 2=Hard/Analytical |
| Topic_tags | JSON array of topic labels |

---

## 🛠 Tech Stack

- **Pure HTML, CSS, JavaScript** — no frameworks, no dependencies
- **Anthropic Claude API** — claude-sonnet-4-20250514
- **OpenAI API** — gpt-4o
- **Google Gemini API** — gemini-2.0-flash
- **OpenRouter API** — multi-model gateway
- **localStorage** — browser-based history (no server needed)

---

## 📁 Project Structure

```
mcqforge/
├── index.html      # Landing page
├── app.html        # Main generator application
└── README.md       # This file
```

---

## 📸 Screenshots

### Landing Page
Clean, professional landing page with features overview and how-it-works section.

### Generator App
Full-featured app with AI model selector, syllabus input, topic builder, progress tracking, and preview table.

---

## 🎓 Designed For

- University professors and lecturers
- Academic question paper setters
- Instructional designers
- EdTech developers

---

## 📄 License

MIT License — free to use, modify, and distribute.

---

## 👨‍💻 Built With

Built using HTML/CSS/JavaScript with AI assistance from Claude (Anthropic).

*Part of a portfolio project demonstrating AI API integration, frontend development, and educational technology.*
