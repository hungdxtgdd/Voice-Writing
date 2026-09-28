# 🛡️ Phase V: Verified (Kiểm chứng dữ liệu & Nguồn gốc)

## 🎯 Purpose
Solves **Confidently Drunk** AI hallucinations. LLMs optimize for fluency, not truthfulness.

---

## 📋 Triple-Tagging System

All non-trivial assertions must receive one of three tags:
- `[Verified]`: Backed by primary empirical sources, peer-reviewed data, or firsthand data.
- `[Unverified]`: Plausible claim lacking verified source.
- `[Disputed]`: Contested perspective or conflicting data.

---

## 📋 Prompt Template

```markdown
Act as a Chief Fact-Checking Editor for the draft below:
[INSERT DRAFT]

Tasks:
1. Extract every statistic, date, factual claim, quote, and named entity.
2. Categorize each into a Triple-Tagging Table:
   | Claim in Text | Tag ([Verified] / [Unverified] / [Disputed]) | Primary Source URL / Proof |
3. Flag any claim that appears to be an AI hallucination or unverified generalization.
```
