# 🎙️ V.O.I.C.E. Writing Framework

> **A Human-AI Collaborative Writing Framework | Bộ Khung Viết Cộng Tác Người - AI Chuẩn Mực**  
> *Beat the "Average of the Internet" & Craft Irreplaceable Content | Vượt qua "Mẫu số chung nhạt nhẽo" và tạo tác phẩm độc bản.*

[![GitHub Repo](https://img.shields.io/badge/GitHub-hungdxtgdd%2FVoice--Writing-blue?logo=github)](https://github.com/hungdxtgdd/Voice-Writing)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![AI Compatible](https://img.shields.io/badge/AI-ChatGPT%20%7C%20Claude%20%7C%20Gemini%20%7C%20Cursor-orange.svg)](#-quickstart--hướng-dẫn-dùng-nhanh)

---

## 💡 The Core Problem | Căn Nguyên Cốt Lõi

### 🇬🇧 English
Large Language Models (LLMs) operate on next-token prediction. Without constraints, AI writing inevitably converges toward **"The Average of the Internet"**—grammatically flawless yet sterile and generic (*"AI Accent"*). A 2025 Cornell University study (Dhruv Agarwal et al.) proves that unguided AI homogenizes writing toward Western norms and erodes authentic cultural nuance.

### 🇻🇳 Tiếng Việt
Mô hình ngôn ngữ lớn (LLM) dựa trên xác suất đoán từ tiếp theo (*next-token prediction*). Nếu không có khuôn khổ định hướng, AI luôn hội tụ về **"Mẫu số chung của Internet"**—trơn tru nhưng sáo rỗng (*"AI Accent"*). Nghiên cứu của ĐH Cornell (2025) chỉ ra rằng AI làm đồng hóa văn hóa (*Cultural Homogenization*), xóa nhòa bản sắc cá nhân và văn hóa bản địa.

### ⚔️ The Philosophy | Triết Lý: Move 37 vs. Move 78
- **Move 37 (AlphaGo, 2016):** The machine's statistical calculation breaking human patterns.
- **Move 78 (Lee Sedol, 2016):** The human's intuitive masterpiece that broke the machine's certainty.
> *V.O.I.C.E. does not use AI to ghostwrite. It turns AI into an editorial sparring team while preserving your human "Move 78".*

---

## 🏛️ The 5 Pillars | 5 Trụ Cột V.O.I.C.E.

```
       5 AI FLAWS / CĂN BỆNH AI                 V.O.I.C.E. FILTER / BỘ LỌC
┌─────────────────────────────────────┐     ┌─────────────────────────────────────┐
│ 1. Confidently Drunk (Bịa đặt)      │ ──> │ V - VERIFIED (Kiểm chứng nguồn)    │
│ 2. A Broken Record (Rập khuôn)      │ ──> │ O - OWNED (Dấu ấn độc bản)          │
│ 3. Smart & Empty (Sáo rỗng)         │ ──> │ I - INSIGHTFUL (Sâu sắc / So what)  │
│ 4. Lost in Noise (Rườm rà)          │ ──> │ C - CLEAR (Mạch lạc / 9 tuổi hiểu)  │
│ 5. Boring (Thiếu lực hút)           │ ──> │ E - ENGAGING (Nước cờ 78 / Gu riêng)│
└─────────────────────────────────────┘     └─────────────────────────────────────┘
```

| Pillar | AI Flaw | Transformation (EN / VI) |
| :--- | :--- | :--- |
| **V – Verified** | Hallucinations / Ảo giác | **Triple-Tagging Table**: `[Verified]`, `[Unverified]`, `[Disputed]` + primary sources |
| **O – Owned** | Generic clichés / Rập khuôn | **Reverse Interview**: AI interviews author for 3-5 real lived experiences first |
| **I – Insightful** | Smart & Empty / Sáo rỗng | **3-Sentence Contrast Formula** + "Intelligent Skeptic" critique |
| **C – Clear** | Noise & Jargon / Dài dòng | **9-Year-Old Test**: Conversational prose, trim ≥ 30% fluff |
| **E – Engaging** | Boring / Thiếu cảm xúc | **Move 78 Checklist**: Human rhythm, stakes, tension, and unique taste |

---

## 🚀 Quickstart | Hướng Dẫn Dùng Nhanh

### Option 1: Web Chat (ChatGPT, Claude.ai, Gemini Web)
1. Copy the Master Prompt from [`prompts/00-master-prompt.md`](prompts/00-master-prompt.md).
2. Paste into any chat window with your topic.
3. Let AI interview you (Phase O) before drafting!

### Option 2: AI IDEs & CLI (Cursor, Antigravity, Claude Code, Windsurf)
Load [`SKILL.md`](SKILL.md) and [`AGENTS.md`](AGENTS.md) into your workspace:
- **Antigravity / Gemini:** Put into `.agents/skills/voice-writing/SKILL.md`
- **Claude Code:** Link in `.claude/skills/` or `CLAUDE.md`
- **Cursor / Windsurf:** Add reference to `.cursorrules` or `.windsurfrules`

---

## 📂 Repository Structure | Cấu Trúc Thư Mục

- [`SKILL.md`](SKILL.md): Standardized Agent Skill specification (YAML frontmatter).
- [`AGENTS.md`](AGENTS.md) / [`CLAUDE.md`](CLAUDE.md): Universal system instructions.
- [`prompts/`](prompts/): Modular prompt templates for each stage:
  - [`00-master-prompt.md`](prompts/00-master-prompt.md): All-in-one Web Chat prompt.
  - [`01-reverse-interview-owned.md`](prompts/01-reverse-interview-owned.md): Phase O (Reverse Interview).
  - [`02-counter-consensus-insightful.md`](prompts/02-counter-consensus-insightful.md): Phase I (Contrast Formula).
  - [`03-clarity-conciseness-clear.md`](prompts/03-clarity-conciseness-clear.md): Phase C (Lean Drafting).
  - [`04-fact-checking-verified.md`](prompts/04-fact-checking-verified.md): Phase V (Fact-Checking Table).
  - [`05-human-polish-engaging.md`](prompts/05-human-polish-engaging.md): Phase E (Move 78 Polish).
- [`templates/article-workflow-template.md`](templates/article-workflow-template.md): Step-by-step article workbook.

---

## 📄 License

Distributed under the [MIT License](LICENSE).
