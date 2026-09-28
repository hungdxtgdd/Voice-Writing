# 🎙️ V.O.I.C.E. Writing Framework

> **A Human-AI Collaborative Framework to Beat the "Average of the Internet" and Craft High-Impact, Irreplaceable Content.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![AI Compatibility](https://img.shields.io/badge/AI-Claude%20%7C%20ChatGPT%20%7C%20Gemini%20%7C%20Cursor-success.svg)](#compatibility)

---

## 💡 The Core Problem: Why AI Writing Feels Hollow

Large Language Models (LLMs) operate on next-token prediction. Without active constraints, AI text naturally converges toward the **statistical average of the internet**—smooth, grammatically correct, but generic, sterile, and stripped of cultural and personal nuances (*"AI Accent"* / *Cultural Homogenization* - Cornell University, 2025).

### ⚔️ The Philosophy: Move 37 vs. Move 78
- **Move 37 (AlphaGo, 2016):** The machine's cold, statistical calculation that broke conventional rules.
- **Move 78 (Lee Sedol, 2016):** The human's intuitive, audacious masterpiece that broke the machine's certainty.

**V.O.I.C.E.** does not treat AI as a "ghostwriter", but as an **editorial sparring team**. The human writer retains full ownership of taste, emotion, and the final *Move 78*.

---

## 🏛️ The 5 Pillars of V.O.I.C.E.

```
       5 AI FLAWS                               V.O.I.C.E. FILTER
┌───────────────────────────────┐        ┌────────────────────────────────┐
│ 1. Confidently Drunk (Lies)   │  ───>  │ V - VERIFIED (Ground Truth)    │
│ 2. A Broken Record (Clichés)  │  ───>  │ O - OWNED (Unique Fingerprint) │
│ 3. Smart & Empty (Truisms)    │  ───>  │ I - INSIGHTFUL (So What?)      │
│ 4. Lost in Noise (Fluff)      │  ───>  │ C - CLEAR (9-Year-Old Test)    │
│ 5. Boring (Flat Tone)         │  ───>  │ E - ENGAGING (Human Taste/Move 78)
└───────────────────────────────┘        └────────────────────────────────┘
```

| Pillar | AI Anti-Pattern | Transformation & Action |
| :--- | :--- | :--- |
| **V – Verified** | Hallucinations, fake citations | Triple-tagging (`[Verified]`, `[Unverified]`, `[Disputed]`) + primary sources |
| **O – Owned** | Western homogenization, generic tone | **Reverse Interview**: AI extracts 5 raw lived experiences before writing |
| **I – Insightful** | Superficial truisms | **3-Sentence Contrast Formula** & "Intelligent Skeptic" critique |
| **C – Clear** | Buzzword soup, passive voice | **9-Year-Old Test**: conversational style, trim ≥ 30% filler words |
| **E – Engaging** | Monotonous rhythm, no stakes | **Move 78**: Human adds tension, pacing, curiosity, and authentic voice |

---

## 🚀 Quickstart: How to Use

### 1. Web Chat (ChatGPT, Claude.ai, Gemini)
Copy the Master Prompt in [`prompts/00-master-prompt.md`](prompts/00-master-prompt.md) and paste it into your chat.

### 2. AI IDEs & CLI (Cursor, Antigravity, Claude Code, Windsurf)
Add [`SKILL.md`](SKILL.md) to your workspace's skill/rule directory:
- **Antigravity / Gemini:** `.agents/skills/voice-writing/SKILL.md`
- **Claude Code:** Copy to `.claude/skills/voice-writing.md`
- **Cursor:** Reference in `.cursorrules` or `.cursor/rules/`

---

## 📂 Repository Structure

- [`SKILL.md`](SKILL.md): Standardized Agent Skill definition.
- [`AGENTS.md`](AGENTS.md): Universal system instruction for AI assistants.
- [`prompts/`](prompts/): Individual modular prompt templates for each stage.
  - `00-master-prompt.md`: One-shot prompt for Web Chat users.
  - `01-reverse-interview-owned.md`: Phase O extraction.
  - `02-counter-consensus-insightful.md`: Phase I sparring.
  - `03-clarity-conciseness-clear.md`: Phase C simplification.
  - `04-fact-checking-verified.md`: Phase V verification.
  - `05-human-polish-engaging.md`: Phase E human touch checklist.
- [`templates/article-workflow-template.md`](templates/article-workflow-template.md): Draft workbook template.

---

## 📄 License
MIT License. Created for writers, researchers, and engineers who care about authentic voice in the age of AI.
