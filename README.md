<div align="center">

# Lalman
### Frontend Engineer — React · Next.js · TypeScript

*I build production-grade web interfaces that are fast, accessible, and architecturally sound.*

[![Portfolio](https://img.shields.io/badge/Portfolio-lalman.dev-black?style=flat-square&logo=vercel)](https://www.lalman.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lalman--dev-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/lalman-dev)
[![Twitter](https://img.shields.io/badge/Twitter-@imchaudhary2-1DA1F2?style=flat-square&logo=twitter)](https://x.com/imchaudhary2)
[![Email](https://img.shields.io/badge/Email-lalman.dev7@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:lalman.dev7@gmail.com)

📍 Open to remote roles

</div>

---

## What I Bring

I specialise in the intersection of **frontend architecture** and **user experience** — making complex systems feel simple and trustworthy in the UI.

My focus areas:

- **Rendering strategy** — choosing SSR, CSR, or hybrid in Next.js App Router based on real performance and UX constraints
- **Resilient UIs** — loading, empty, error, retry, and partial states handled thoughtfully, not as afterthoughts
- **Scalable architecture** — reducer-based state, event-driven patterns, and component design that survives codebase growth
- **Accessibility** — semantic HTML, keyboard navigation, screen-reader compatibility built in from the start
- **Clean code** — readable, reviewable, and maintainable by a team

I bias toward boring, reliable solutions over unnecessary cleverness — and toward shipping, then iterating.

---

## Tech Stack

| Layer | Tools |
|---|---|
| **Core** | JavaScript (ES6+), TypeScript, React, Next.js (App Router) |
| **Styling** | Tailwind CSS, responsive layouts, accessible components |
| **Animation** | Framer Motion — transitions, micro-interactions |
| **State & Data** | Reducer-based state, event-driven architecture, REST API integration |
| **Tooling** | Git, GitHub, Vercel, Netlify, ESLint, Prettier, Figma, VS Code |

---

## Flagship Projects

### 🤖 AI Agent Workflow Visualizer
**Real-time frontend system for visualising multi-step AI agent execution**

> Most AI interfaces show a spinner and then a final answer. This project exposes *what actually happens in between* — making agent execution understandable and trustworthy through UI.

The visualizer simulates how modern AI agents operate internally: task spawning, parallel execution, tool usage, streamed outputs, retries, failures, and final synthesis — all rendered incrementally in real time.

**What it solves:**
- Users see *which tasks are running* — not just that something is loading
- Parallel task groups and dependencies are laid out visually
- Partial outputs appear incrementally instead of waiting for completion
- Retry, cancelled, and failure states are preserved in execution history
- A dedicated reasoning panel exposes agent thought process step by step

**Architecture highlights:**
- Custom mock event emitter simulating real agent streaming events
- Reducer-based centralised state for predictable workflow transitions
- Incremental rendering of partial outputs as events arrive
- Handles long-running workflows without losing execution history
- Intentionally aligned with how production AI systems stream events and tool calls

**Stack:** React · TypeScript · Vite · Tailwind CSS · Event-driven architecture

[![Live Demo](https://img.shields.io/badge/Live_Demo-agent--visualizer.vercel.app-black?style=flat-square&logo=vercel)](https://agent-visualizer.vercel.app/)
[![GitHub](https://img.shields.io/badge/GitHub-agent--visualizer-181717?style=flat-square&logo=github)](https://github.com/lalman-dev/agent-visualizer)

---

### 📰 Hacker News Portal
**Production-grade Next.js application with SSR + client-side interactivity**

Built to demonstrate how to handle real-world constraints: unreliable external APIs, meaningful loading and error states, and a clean split between server-rendered content and client-side interactivity.

- Next.js App Router + TypeScript with server-side rendering for fast initial load
- Client-side search, pagination, and filters without full page reloads
- Explicit loading, empty, and error states — no silent failures
- Designed to degrade gracefully when the upstream HN API is slow or unavailable

**Stack:** Next.js (App Router) · TypeScript · React

[![Live Demo](https://img.shields.io/badge/Live_Demo-hn--news--two.vercel.app-black?style=flat-square&logo=vercel)](https://hn-news-two.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-hn--news-181717?style=flat-square&logo=github)](https://github.com/lalman-dev/hn-news)

---

### 📄 AI Resume Studio
**Full-stack resume builder with complex form workflows and auth**

Hands-on experience with the full frontend-to-backend integration cycle: authentication flows, protected routes, complex multi-step form state, and debugging frontend–backend integration issues in production.

- React + TypeScript + Tailwind CSS
- Multi-step form workflows with predictable, validated UI state
- Authentication and route protection
- Real debugging experience across the full stack

**Stack:** React · TypeScript · Tailwind CSS · Full-stack integration

[![Live Demo](https://img.shields.io/badge/Live_Demo-ai--resume--studio-black?style=flat-square&logo=vercel)](https://ai-resume-studio-snowy.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-AI--Resume--Studio-181717?style=flat-square&logo=github)](https://github.com/lalman-dev/AI-Resume-Studio)

---

## How I Work

- **Think in components, data flow, and UX states** — not just markup
- **Comfortable with unfamiliar codebases** — can read, understand, and improve existing code, not just greenfield
- **Async-first communicator** — write clearly, document decisions, don't block team on my work
- **Bias toward shipping** — deliver working software, then refine; avoid scope creep and over-engineering
- **Production mindset** — error states, loading states, edge cases, and accessibility are not optional

---

## Currently Exploring

- Advanced rendering patterns in Next.js App Router (streaming, partial prerendering)
- Frontend performance profiling and optimisation
- Architectural patterns for early-stage startup codebases that need to scale

---

<div align="center">

*Building interfaces that are fast, resilient, and actually make sense to users.*

[lalman.dev](https://www.lalman.dev) · [lalman.dev7@gmail.com](mailto:lalman.dev7@gmail.com)

</div>
