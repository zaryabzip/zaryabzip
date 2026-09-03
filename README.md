# Hey, I'm Zaryab

Full-stack developer building software for healthcare — currently Cusp, a modern alternative to Dentally — alongside research on large language models and their reasoning.

## About

I'm a computer science student at LUMS. I build across the stack: React/Next.js and TypeScript on the front end, FastAPI and Python on the back, with PostgreSQL, on a wide variety of platforms like Railway, Vercel, Supabase, AWS, Azure.

My thesis is on chain-of-thought monitorability: how much a model's written reasoning actually tells us about the computation behind it, and what happens to that oversight when reasoning becomes implicit rather than spelled out in tokens. The rest of my time goes to applied AI — agentic pipelines for real clinical workflows, where a wrong answer has consequences. I treat correctness and testing as first-class; patient data isn't the place to cut corners.

## What I'm working on

- **Cusp** — patient records, tooth charting, appointment diary, billing, and NHS claims.
- **Thesis: CoT monitorability** — measuring when stated reasoning is faithful to the underlying process, and how implicit chain-of-thought erodes the assumptions monitoring depends on.
- **Agentic pipelines in healthcare** — multi-step retrieval, tool use, and structured evidence for clinical tasks, with evaluation built to catch the failure modes rather than hide them.

## Technologies

**Web:** React 19, Next.js, TypeScript, Tailwind, shadcn/ui, TanStack Query
**Backend:** Python, FastAPI, SQLAlchemy, PostgreSQL, Supabase
**AI and ML:** PyTorch, Hugging Face Transformers, PEFT/LoRA, LangChain, FAISS, pandas, scikit-learn
**Medical imaging:** BioViL-T, CheXbert, chest radiography, RAG
**Testing and tooling:** pytest, Vitest, Playwright, Docker, GitHub Actions

## Projects

- **Cusp** — a modern alternative to Dentally: cloud practice-management for UK dental practices. React, FastAPI, PostgreSQL. (Private client work.)
- **[Radiology report generation](https://github.com/zaryabzip/iu-cxr-clfir-final)** — a retrieval-augmented pipeline that drafts chest X-ray reports on the IU-Xray dataset: image-first drafting, a fine-tuned BioViL-T retrieval adapter, CheXbert evidence extraction, and an LLM composing the final report. PyTorch, BioViL-T, FAISS.
- **Cross-lingual news summarization (Urdu and English)** — a bilingual summarizer built by fine-tuning a compact language model with PEFT/LoRA. Python, Hugging Face, PEFT/LoRA.
- **Event venue booking system** — a booking platform for an events venue: public landing page, a customer booking flow, and an admin dashboard. Next.js, Supabase. (Private client work.)
- **LUMS campus event app** — a full-stack Android app with organizer and student roles: event listing, ticketing, and integrated payments. Android (Java), REST APIs.

## Work with me

I'm open to freelance and contract work — web apps, AI/ML, or a combination of the two. If you have a project you'd like built, or an idea you want to get started, I'd be glad to hear about it.

- Email: zaryab.gohar.17@gmail.com
- GitHub: github.com/zaryabzip
