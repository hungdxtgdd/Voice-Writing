# 🎙️ V.O.I.C.E. Writing Framework

> **Bộ Khung Viết Cộng Tác Người - AI Chuẩn Mực | A Human-AI Collaborative Writing Framework**  
> *Vượt qua "Mẫu số chung nhạt nhẽo" & Tạo tác phẩm độc bản | Beat the "Average of the Internet" & Craft Irreplaceable Content.*

[![GitHub Repo](https://img.shields.io/badge/GitHub-hungdxtgdd%2FVoice--Writing-blue?logo=github)](https://github.com/hungdxtgdd/Voice-Writing)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![AI Compatible](https://img.shields.io/badge/AI-ChatGPT%20%7C%20Claude%20%7C%20Gemini%20%7C%20Cursor-orange.svg)](#-hướng-dẫn-sử-dụng-nhanh)

---

# 🇻🇳 TIẾNG VIỆT

## 💡 Căn Nguyên Cốt Lõi: Tại Sao AI Viết Ngày Càng Nhạt?

Mô hình ngôn ngữ lớn (LLM) hoạt động dựa trên cơ chế dự đoán từ tiếp theo (*next-token prediction*). Nếu không có khuôn khổ định hướng, văn bản của AI luôn hội tụ về **"Mẫu số chung của Internet"**—trơn tru, đúng ngữ pháp nhưng vô hồn (*"AI Accent"*). 

Nghiên cứu của ĐH Cornell (2025 - Dhruv Agarwal et al.) chứng minh rằng việc lạm dụng AI sẽ dẫn đến **Đồng hóa văn hóa (*Cultural Homogenization*)**, xóa nhòa góc nhìn cá nhân và bản sắc bản địa.

### ⚔️ Triết Lý: Nước Cờ 37 vs. Nước Cờ 78
- **Nước cờ 37 (AlphaGo, 2016):** Cỗ máy tính toán xác suất lạnh lùng, phá vỡ quy chuẩn cũ.
- **Nước cờ 78 (Lee Sedol, 2016):** Con người dùng trực giác và sự liều lĩnh tạo nên nước đi bất hủ làm cỗ máy hoảng loạn.
> *V.O.I.C.E. không dùng AI để viết thay, mà biến AI thành đội ngũ biên tập viên phản biện, giữ lại "Nước cờ 78" (linh hồn bài viết) cho con người.*

---

## 🏛️ 5 Trụ Cột V.O.I.C.E.

```
       5 CĂN BỆNH CỦA AI                       BỘ LỌC V.O.I.C.E.
┌───────────────────────────────┐     ┌────────────────────────────────┐
│ 1. Confidently Drunk (Bịa đặt)│ ──> │ V - VERIFIED (Kiểm chứng nguồn)│
│ 2. A Broken Record (Rập khuôn)│ ──> │ O - OWNED (Dấu ấn độc bản)     │
│ 3. Smart & Empty (Sáo rỗng)   │ ──> │ I - INSIGHTFUL (Sâu sắc / So what)
│ 4. Lost in Noise (Rườm rà)    │ ──> │ C - CLEAR (Mạch lạc, súc tích) │
│ 5. Boring (Thiếu lực hút)     │ ──> │ E - ENGAGING (Căng thẳng & Gu) │
└───────────────────────────────┘     └────────────────────────────────┘
```

| Trụ Cột | Căn Bệnh Triệt Hạ | Chuyển Hóa & Hành Động Cụ Thể |
| :--- | :--- | :--- |
| **V – Verified** | Ảo giác tự tin, bịa số liệu | **Bảng Triple-Tagging**: Gắn nhãn `[Verified]`, `[Unverified]`, `[Disputed]` + trích dẫn nguồn sơ cấp |
| **O – Owned** | Đồng hóa văn hóa, sáo mòn | **Phỏng vấn ngược (Reverse Interview)**: Ép AI hỏi 3-5 câu để lấy chi tiết sống thực tế trước khi viết |
| **I – Insightful** | Nghe hay nhưng vô giá trị | **Công thức tương phản 3 câu** + biến AI thành "Kẻ phản biện khó tính" (So What?) |
| **C – Clear** | Rườm rà, lạm dụng biệt ngữ | **Bài kiểm tra 9 tuổi**: Hành văn đàm thoại, cắt bỏ ít nhất 30% từ thừa |
| **E – Engaging** | Nhàm chán, ru ngủ | **Nước cờ 78 (Move 78)**: Tự tay chỉnh nhịp điệu (câu ngắn/dài), tạo xung đột, gài cắm tò mò |

---

## 🚀 Hướng Dẫn Sử Dụng Nhanh

### Cách 1: Dùng trên Web Chat (ChatGPT, Claude.ai, Gemini Web)
1. Mở file [`prompts/00-master-prompt.md`](prompts/00-master-prompt.md) và copy nội dung.
2. Dán vào ô chat kèm chủ đề bạn muốn viết.
3. Trả lời các câu hỏi phỏng vấn của AI (Phase O) trước khi để AI dựng khung!

### Cách 2: Dùng trong AI IDEs (Cursor, Antigravity, Claude Code, Windsurf)
Nạp file [`SKILL.md`](SKILL.md) và [`AGENTS.md`](AGENTS.md) vào dự án của bạn:
- **Antigravity / Gemini:** Đặt tại `.agents/skills/voice-writing/SKILL.md`
- **Claude Code:** Liên kết trong `.claude/skills/` hoặc `CLAUDE.md`
- **Cursor / Windsurf:** Khai báo vào `.cursorrules` hoặc `.windsurfrules`

---

# 🇬🇧 ENGLISH

## 💡 The Core Problem: Why AI Writing Feels Hollow

Large Language Models (LLMs) operate on next-token prediction. Without constraints, AI output naturally converges toward **"The Average of the Internet"**—grammatically correct yet bland and generic (*"AI Accent"*). 

A 2025 Cornell University study (Dhruv Agarwal et al.) demonstrates that unguided AI leads to **Cultural Homogenization**, wiping out personal voice and local cultural context.

### ⚔️ The Philosophy: Move 37 vs. Move 78
- **Move 37 (AlphaGo, 2016):** Machine probability breaking centuries of Go wisdom.
- **Move 78 (Lee Sedol, 2016):** Human intuition producing a legendary tesuji that broke the machine's certainty.
> *V.O.I.C.E. does not use AI to ghostwrite. It turns AI into a sparring partner while preserving your human "Move 78".*

---

## 🏛️ The 5 Pillars of V.O.I.C.E.

| Pillar | AI Flaw | Concrete Transformation |
| :--- | :--- | :--- |
| **V – Verified** | Confidently Drunk (Hallucinations) | **Triple-Tagging**: `[Verified]`, `[Unverified]`, `[Disputed]` table + primary links |
| **O – Owned** | Broken Record (Generic cliches) | **Reverse Interview**: AI extracts 3-5 real lived experiences before drafting |
| **I – Insightful** | Smart & Empty (Truisms) | **3-Sentence Contrast Formula** + "Intelligent Skeptic" (So What?) critique |
| **C – Clear** | Lost in Noise (Jargon & fluff) | **9-Year-Old Test**: Conversational prose, cut ≥ 30% filler words |
| **E – Engaging** | Boring (Flat monotone) | **Move 78 Polish**: Human rhythm, tension, stakes, and unique taste |

---

## 📂 Repository Structure | Cấu Trúc Thư Mục

- [`SKILL.md`](SKILL.md): Standardized Agent Skill specification.
- [`AGENTS.md`](AGENTS.md) / [`CLAUDE.md`](CLAUDE.md): Universal AI rules for IDE assistants.
- [`prompts/`](prompts/):
  - [`00-master-prompt.md`](prompts/00-master-prompt.md): Master 1-Click prompt for Web Chat.
  - [`01-reverse-interview-owned.md`](prompts/01-reverse-interview-owned.md): Phase O (Reverse Interview).
  - [`02-counter-consensus-insightful.md`](prompts/02-counter-consensus-insightful.md): Phase I (Contrast Formula).
  - [`03-clarity-conciseness-clear.md`](prompts/03-clarity-conciseness-clear.md): Phase C (Lean Drafting).
  - [`04-fact-checking-verified.md`](prompts/04-fact-checking-verified.md): Phase V (Fact-Checking Table).
  - [`05-human-polish-engaging.md`](prompts/05-human-polish-engaging.md): Phase E (Move 78 Polish).
- [`templates/article-workflow-template.md`](templates/article-workflow-template.md): Step-by-step article workbook.

---

## 📄 License

Distributed under the [MIT License](LICENSE).
