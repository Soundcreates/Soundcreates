<div align="center">

# Shantanav Mukherjee

**AI Systems · Backend · Infrastructure**

I build AI products and the systems behind them: agent workflows, backend services, event-driven data paths, and performance-sensitive software.

[Portfolio](https://shantanav.in) · [LinkedIn](https://linkedin.com/in/shantanav-mukherjee/) · [Email](mailto:shantanav7@gmail.com) · [LeetCode](https://leetcode.com/u/ShantanavM)

Mumbai, India · Computer Science, KJ Somaiya School of Engineering · Class of 2028

</div>

My work spans AI application engineering and lower-level systems work. At Craon AI, I helped cut video-rendering latency by **40%** with a shared Rust/WebAssembly pipeline and GPU parallelization. I also contribute fixes upstream to projects including **Google ADK Go, gVisor, ORAS, Hugo, and Vello**.

## Engineering experience

### Craon AI — Full Stack AI Engineer Intern · Jun–Aug 2026

- Built a Rust/WebAssembly rendering pipeline shared by browser previews and backend exports, eliminating preview/export drift.
- Used GPU parallelization to reduce rendering latency by **40%**.

## Selected projects

### [VCR Protocol](https://vcrprotocol.xyz) — Verifiable Capability Routing

Policy infrastructure for autonomous agent wallets. Combines identity resolution with IPFS-backed policies to enforce transaction caps, recipient allowlists, and daily limits. At ETH Mumbai 2026, the project placed **1st in BitGo DeFi** and **2nd in Base AIx Onchain** among 200+ teams.

### [AURA](https://aura-fit.tech) — Multi-agent fitness coach

An AI fitness product using LangGraph agents, asynchronous Python workers, Redis event pipelines, and PostgreSQL to deliver workout, nutrition, and recovery guidance.

### [CurriculumOS](https://github.com/Soundcreates/CurriculumOS) — RAG study-roadmap builder

Turns PDFs, web pages, and YouTube material into personalized study roadmaps with a Go API gateway and a FastAPI retrieval service. [Live demo](https://curriculum-os-one.vercel.app).

## Open source

### Merged

- **Google ADK Go:** retained usage metadata across streaming chunks ([#1257](https://github.com/google/adk-go/pull/1257)), propagated workflow cancellation ([#1258](https://github.com/google/adk-go/pull/1258)), and enforced remote-agent isolation scope ([#1259](https://github.com/google/adk-go/pull/1259)).
- **gVisor:** included a generated changelog in the Debian `runsc` package ([#14083](https://github.com/google/gvisor/pull/14083)).
- **ORAS:** added safe rolling tags for stable container releases without letting prereleases or backports move tags backward ([#2184](https://github.com/oras-project/oras/pull/2184)).
- **Hugo:** fixed `staticcheck` lookup after installation with `go install` ([#15148](https://github.com/gohugoio/hugo/pull/15148)).
- **Linebender Vello:** documented the crate’s public Cargo features ([#1807](https://github.com/linebender/vello/pull/1807)).

### Open contributions

- **ORAS:** multi-platform image selection for `oras cp`, including selected-platform referrer preservation ([#2191](https://github.com/oras-project/oras/pull/2191)).
- **kind:** a local Markdown lint target and changed-file CI workflow ([#4268](https://github.com/kubernetes-sigs/kind/pull/4268)).
- **Kubeflow Testing:** a reusable Kind-cluster GitHub Action for test workflows ([#1087](https://github.com/kubeflow/testing/pull/1087)).
- **Google ADK Go:** stale database-session recovery with a two-writer regression test ([#1256](https://github.com/google/adk-go/pull/1256)).

## Toolkit

- **AI systems:** Python, LangGraph, RAG, embeddings, vector search, evaluation
- **Backend and systems:** Go, Rust, TypeScript, PostgreSQL, Redis, async workers, gRPC
- **Infrastructure:** Docker, Kubernetes, Linux, GitHub Actions, CI/CD, observability

## Leadership and awards

- **KJSSE CodeCell, Committee Head:** delivered a two-day Go backend workshop and organized hackathons for 300+ students.
- **Solana Blitz V7:** 2nd place among 300+ international teams.

I’m especially interested in ML systems, distributed systems, operating-system internals, and performance engineering. For engineering opportunities or collaborations, [get in touch](mailto:shantanav7@gmail.com).
