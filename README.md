<!--
  This is the GitHub-facing README. Paste this content into your GitHub
  repo's README.md (overwriting any existing one). Update the YOUR_USERNAME
  and YOUR_REPO placeholders at the top, then push.
-->

<div align="center">

# 📕 From Tokens to Platforms

### The Engineer's Complete Guide to Modern AI Systems

*A 537-page field manual for building, deploying, scaling, and operating real-world AI systems.*

<br/>

<p>
  <a href="./From-Tokens-to-Platforms.pdf">
    <img alt="Download PDF" src="https://img.shields.io/badge/📥_Download_Full_PDF-1.59_MB-f4a323?style=for-the-badge&logoColor=white">
  </a>
  <a href="./From-Tokens-to-Platforms-LinkedIn-Preview.pdf">
    <img alt="Carousel preview" src="https://img.shields.io/badge/📑_Carousel_Preview-22_slides-6da9ff?style=for-the-badge&logoColor=white">
  </a>
</p>

<p>
  <img alt="Pages" src="https://img.shields.io/badge/Pages-537-0d1117?style=flat-square">
  <img alt="Chapters" src="https://img.shields.io/badge/Chapters-33-0d1117?style=flat-square">
  <img alt="Appendices" src="https://img.shields.io/badge/Appendices-12-0d1117?style=flat-square">
  <img alt="Words" src="https://img.shields.io/badge/Words-100K%2B-0d1117?style=flat-square">
  <img alt="License" src="https://img.shields.io/badge/License-CC_BY--NC_4.0-blue?style=flat-square">
  <img alt="Edition" src="https://img.shields.io/badge/Edition-First_(2026)-f4a323?style=flat-square">
</p>

<br/>

<a href="./From-Tokens-to-Platforms.pdf">
  <img src="./cover.svg" alt="From Tokens to Platforms book cover" width="380">
</a>

</div>

---

## 🎯 What this book is

> *"There's a real distance between 'I can call an LLM API' and 'I can ship AI to millions of users.' Most resources either drown you in equations or stay too shallow to help on a Tuesday afternoon when something's broken in prod. This is the field manual I wish I'd had."*

This book teaches how modern AI systems actually work internally and how large-scale enterprise AI products are built, deployed, scaled, and monitored in production.

Every chapter starts in **plain English**, builds intuition with **analogies**, then deepens into **production engineering**. No jargon left unexplained. No production gotcha left unflagged.

---

## 👥 Who this is for

| You are... | This book helps you... |
|---|---|
| 👨‍💻 **An engineer** building AI features into real products | Stop hitting walls. Understand the patterns Big Tech uses. |
| 📊 **A product manager** leading an AI roadmap | Talk to engineers fluently. Make better build-vs-buy calls. |
| 🏛️ **An architect** designing an enterprise AI platform | See the full stack, layer by layer, with real tradeoffs. |
| 🚀 **A founder** evaluating AI infrastructure | Decide what to build, what to buy, what to skip. |
| 🎓 **A senior engineer** prepping for interviews | Every chapter has an interview-questions section. |

If you can write a Python loop, understand what a model is at a high level, and have heard of "transformers" — you are ready.

---

## ⚡ Quick start

### 📥 I just want to read it
Download [**From-Tokens-to-Platforms.pdf**](./From-Tokens-to-Platforms.pdf) (1.59 MB, 537 pages).

### 🌐 I want to skim online
Start with [**Appendix A0: Concepts in Plain English**](./appendix/A0-concepts-in-plain-english.md) — every key idea in the book explained as if a friend were walking you through it over coffee.

### 📑 I want to share it
Use the [**22-slide carousel preview**](./From-Tokens-to-Platforms-LinkedIn-Preview.pdf) — square format, designed for LinkedIn / Instagram / social sharing.

### 🛠 I want to rebuild it
```bash
pip install weasyprint markdown pypdf
python3 build_pdf.py                    # builds the full book
python3 build_linkedin_carousel.py      # builds the swipeable preview
python3 split_book.py                   # splits into 2 parts for LinkedIn
```

---

## 📚 What's inside

### 🌟 Before you start
- [**A0 — Concepts in Plain English**](./appendix/A0-concepts-in-plain-english.md) · 66 ideas explained simply

### Section 1 — Foundations of Modern AI
- [Chapter 1 — Evolution of AI Systems](./chapters/ch01-evolution-of-ai-systems.md)
- [Chapter 2 — Understanding Foundation Models](./chapters/ch02-understanding-foundation-models.md)
- [Chapter 3 — How LLMs Actually Work](./chapters/ch03-how-llms-actually-work.md)

### Section 2 — Embeddings & Vector Representation
- [Chapter 4 — Embeddings Explained Simply](./chapters/ch04-embeddings-explained-simply.md)
- [Chapter 5 — Vector Databases & Retrieval](./chapters/ch05-vector-databases-and-retrieval.md)

### Section 3 — Fine Tuning Fundamentals
- [Chapter 6 — What Is Fine Tuning?](./chapters/ch06-what-is-fine-tuning.md)
- [Chapter 7 — Types of Fine Tuning](./chapters/ch07-types-of-fine-tuning.md)
- [Chapter 8 — The Training Pipeline Step by Step](./chapters/ch08-training-pipeline-step-by-step.md)

### Section 4 — RAG Systems & Knowledge Retrieval
- [Chapter 9 — What Is RAG?](./chapters/ch09-what-is-rag.md)
- [Chapter 10 — Advanced RAG Systems](./chapters/ch10-advanced-rag-systems.md)

### Section 5 — Recommendation Systems
- [Chapter 11 — How Recommendation Systems Work](./chapters/ch11-how-recommendation-systems-work.md)
- [Chapter 12 — Ranking Systems Used by Big Tech](./chapters/ch12-ranking-systems-used-by-big-tech.md)
- [Chapter 13 — Feature Engineering for Recommendations](./chapters/ch13-feature-engineering-for-recommendations.md)

### Section 6 — Search Systems
- [Chapter 14 — How Search Engines Work](./chapters/ch14-how-search-engines-work.md)
- [Chapter 15 — Modern Semantic Search](./chapters/ch15-modern-semantic-search.md)

### Section 7 — AI Infrastructure Fundamentals
- [Chapter 16 — AI Infrastructure Explained](./chapters/ch16-ai-infrastructure-explained.md)
- [Chapter 17 — GPU Architecture Simplified](./chapters/ch17-gpu-architecture-simplified.md)
- [Chapter 18 — Cloud Infrastructure for AI](./chapters/ch18-cloud-infrastructure-for-ai.md)
- [Chapter 19 — Storage, Networking & Distributed Systems](./chapters/ch19-storage-networking-distributed-systems.md)

### Section 8 — Model Serving & Production Deployment
- [Chapter 20 — Model Serving & Inference](./chapters/ch20-model-serving-and-inference.md)
- [Chapter 21 — Inference Optimization](./chapters/ch21-inference-optimization.md)
- [Chapter 22 — Deploying AI Systems in Production](./chapters/ch22-deploying-ai-systems-in-production.md)

### Section 9 — AI Agents & Enterprise Agentic Systems
- [Chapter 23 — How AI Agents Work](./chapters/ch23-how-ai-agents-work.md)
- [Chapter 24 — Enterprise Agent Architecture](./chapters/ch24-enterprise-agent-architecture.md)
- [Chapter 25 — RAG + Agents in Enterprise Systems](./chapters/ch25-rag-plus-agents-in-enterprise.md)

### Section 10 — Scaling AI Systems
- [Chapter 26 — Scaling AI to Millions of Users](./chapters/ch26-scaling-ai-to-millions-of-users.md)
- [Chapter 27 — AI Observability & Monitoring](./chapters/ch27-ai-observability-and-monitoring.md)
- [Chapter 28 — AI Security & Governance](./chapters/ch28-ai-security-and-governance.md)

### Section 11 — Real World Case Studies
- [Chapter 29 — How Big Tech AI Systems Work](./chapters/ch29-how-big-tech-ai-systems-work.md)

### Section 12 — Building Real AI Applications
- [Chapter 30 — Building a Fine-Tuned LLM](./chapters/ch30-building-a-fine-tuned-llm.md)
- [Chapter 31 — Building a Recommendation Engine](./chapters/ch31-building-a-recommendation-engine.md)
- [Chapter 32 — Building Semantic Search & RAG](./chapters/ch32-building-semantic-search-and-rag.md)
- [Chapter 33 — Building an Enterprise AI Platform](./chapters/ch33-building-an-enterprise-ai-platform.md)

### Appendix — Professional Reference
| | | | |
|---|---|---|---|
| [A1 — Common Beginner Mistakes](./appendix/A1-common-beginner-mistakes.md) | [A2 — AI Myths vs Reality](./appendix/A2-ai-myths-vs-reality.md) | [A3 — Interview Prep Guide](./appendix/A3-interview-preparation-guide.md) | [A4 — Deployment Checklist](./appendix/A4-production-deployment-checklist.md) |
| [A5 — Build vs Buy](./appendix/A5-build-vs-buy-decisions.md) | [A6 — Open vs Closed Models](./appendix/A6-open-vs-closed-source-models.md) | [A7 — GPU Selection Guide](./appendix/A7-gpu-selection-guide.md) | [A8 — Cost Optimization](./appendix/A8-cost-optimization-strategies.md) |
| [A9 — Debugging Guide](./appendix/A9-ai-debugging-guide.md) | [A10 — Responsible AI](./appendix/A10-responsible-ai-and-governance.md) | [A11 — Fine-Tuning Framework](./appendix/A11-fine-tuning-decision-framework.md) | |

---

## 🏗 How each chapter is structured

```
1. Plain-English explanation (start here, no jargon)
2. Intuition with analogies
3. The deep dive (technical mechanics)
4. Architecture diagrams (Mermaid + ASCII)
5. Tradeoffs and decision tables
6. Practical code or pseudocode
7. How Big Tech actually does this
8. Common beginner mistakes
9. Interview questions
10. Practical exercises
11. Chapter summary + key takeaways
```

---

## 🏢 Real architectures broken down

The book details what's publicly known about how these companies ship AI in production:

| Company | What you'll learn |
|---|---|
| **Netflix** | Per-row models · thumbnail bandits · A/B testing culture |
| **YouTube** | Two-tower retrieval · multi-task ranking · satisfaction signals |
| **TikTok** | Sub-second feedback loops · completion-rate dominant signals |
| **LinkedIn** | Graph + content + reciprocity · two-tower job matching |
| **Uber** | Streaming-first · Michelangelo platform · multi-system coordination |
| **Amazon** | Conversion-aware ranking · ads + organic integration |
| **OpenAI** | Multi-model routing · prompt caching · safety classifiers |
| **Anthropic** | Constitutional AI · extended thinking · safety research |
| **Meta** | DLRM · open-weights strategy · custom MTIA accelerators |
| **Spotify** | Audio embeddings · session-based · editorial layer |
| **Microsoft** | Permission-aware RAG over Microsoft Graph |
| **GitHub Copilot** | Sub-200ms inline UX · privacy tiers |
| **Perplexity** | Citation-first generative search |
| **Glean** | Enterprise hybrid search with multi-source connectors |

---

## 📑 The full table of contents at a glance

<details>
<summary><b>Click to expand the 12-section roadmap</b></summary>

| § | Section | Chapters |
|---|---|---|
| 1 | Foundations of Modern AI | 1, 2, 3 |
| 2 | Embeddings & Vector Representation | 4, 5 |
| 3 | Fine Tuning Fundamentals | 6, 7, 8 |
| 4 | RAG Systems & Knowledge Retrieval | 9, 10 |
| 5 | Recommendation Systems | 11, 12, 13 |
| 6 | Search Systems | 14, 15 |
| 7 | AI Infrastructure Fundamentals | 16, 17, 18, 19 |
| 8 | Model Serving & Production Deployment | 20, 21, 22 |
| 9 | AI Agents & Enterprise Agentic Systems | 23, 24, 25 |
| 10 | Scaling AI Systems | 26, 27, 28 |
| 11 | Real World Case Studies | 29 |
| 12 | Building Real AI Applications | 30, 31, 32, 33 |

</details>

---

## 🗂 What's in this repo

```
ebook-foundation-models-ai/
├── 📕 From-Tokens-to-Platforms.pdf            # Full book (537 pages)
├── 📑 From-Tokens-to-Platforms-LinkedIn-Preview.pdf   # 22-slide carousel
├── 📕 From-Tokens-to-Platforms-Part-1.pdf     # Half 1 (LinkedIn-friendly)
├── 📕 From-Tokens-to-Platforms-Part-2.pdf     # Half 2 (LinkedIn-friendly)
├── 🎨 cover.svg                                # Standalone cover
├── 🎨 cover.html                               # Interactive cover (front + back)
│
├── chapters/                                   # All 33 chapter markdowns
├── appendix/                                   # All 12 appendix markdowns
│
├── build_pdf.py                                # Builds the full book PDF
├── build_linkedin_carousel.py                  # Builds the carousel preview
├── split_book.py                               # Splits PDF in half
│
├── LINKEDIN_POST.md                            # Ready-to-paste launch kit
└── README.md                                   # You are here
```

---

## 🎁 Sample — what the writing actually feels like

> **What is an embedding?**
>
> An embedding is a list of numbers that captures the meaning of something — a word, a sentence, a movie, a user, a song — such that *similar things produce similar numbers*.
>
> ```
> "king"  → [0.2, -0.5, 0.7, 0.1, ...]   (a list of 1536 numbers)
> "queen" → [0.2, -0.4, 0.7, 0.1, ...]   (very close to "king")
> "banana"→ [0.8, 0.9, -0.3, 0.4, ...]   (very different)
> ```
>
> Why care? Because once everything is a list of numbers, you can do math:
> — **Search:** "find the document whose meaning is closest to this query"
> — **Recommend:** "find songs whose embedding is close to this user's taste vector"
> — **Cluster:** "group all messages with similar meaning together"
>
> Embeddings turn meaning into math. That's the magic.

*(From Appendix A0 — Concepts in Plain English)*

---

## 🤝 Contributing

This is a v1. The architectural patterns are durable; specific numbers and vendor specifics will keep moving. **Pull requests are very welcome** for:

- 🐛 Typos, broken links, formatting fixes
- 🔄 Updated numbers, prices, model names (with a source)
- 📝 Clearer explanations or better analogies
- 🆕 New "How Big Tech does this" examples (with public sources)
- 🌍 Translations

Open an [issue](../../issues) first for substantial changes so we can align before you do the work.

### Sources & verification note

The book was written from a combination of published papers, conference talks, engineering blogs, and industry knowledge. **Specific numbers (pricing, GPU counts, user statistics) are snapshots from training data** and should be verified for any decision-critical use. Treat it as a field manual, not gospel.

---

## ⭐ If this is useful

- Star this repo so other engineers find it
- Share it with your team
- Post about it ([LinkedIn launch kit included](./LINKEDIN_POST.md))
- Open an issue with the AI concept you wish was explained more clearly — I'll cover it in v2

---

## 📜 License

This work is licensed under [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/).

You're free to:
- ✅ **Share** — copy and redistribute in any medium or format
- ✅ **Adapt** — remix, transform, and build upon the material
- ✅ **Use in your work** — read, learn, apply at your job, teach with it

Under these terms:
- 📝 **Attribution** — credit the author and link back to this repo
- 🚫 **NonCommercial** — don't sell the book or use it in paid products without permission

For commercial licensing, training materials, or corporate distribution, contact the author.

---

## 👋 About the author

**Tushar Prasad**

Building AI systems · Writing about what works · Available for advisory, talks, and consulting.

- 💬 Open an [issue](../../issues) for book questions
- 💼 [LinkedIn](#) *(replace with your URL)*
- 📧 [tusshaarprasad@gmail.com](mailto:tusshaarprasad@gmail.com)

---

<div align="center">

### *Build the systems thinking that separates engineers who play with AI from engineers who ship it.*

<br/>

**[📥 Download the PDF →](./From-Tokens-to-Platforms.pdf)**

<sub>From Tokens to Platforms · First Edition · 2026 · Built for engineers who ship.</sub>

</div>
