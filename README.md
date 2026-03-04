## Hey I'm William (Liam) 👋
---

Senior frontend engineer with 5+ years building performant, accessible web experiences. I'm currently shipping features in a headless React PWA at Duluth Trading Co. I specialize in React and TypeScript but I'm comfortable across the stack, and I get a lot of satisfaction from the cross-functional side of the work: partnering with designers, unblocking teams, and mentoring other engineers.

Lately I've been deep in the AI-assisted development space and exploring what modern tooling (and the workflows around it) actually unlocks for solo builders and teams. I'm learning Python with a focus on AI/ML, poking around in Go and Elixir, and building a TUI orchestration tool for AI coding workflows. Shipping more than ever and genuinely having a blast.

When I'm not at the keyboard I'm probably breaking a roguelike, restarting a chapter in Fire Emblem, or jamming on my synthesizer, usuallly being supervised by one of my three cats. 🐱

### Released Projects
- Catalyst (see below) - Ritual Focus Engine
- [PoeAstrology](https://poe.com/PoeAstrology) - [Source code](https://github.com/wvanderen/poe-astrology-bot) - Simple natal chart calculator with rich UI, SVG astrology chart construction, LLM analysis, personalization, and follow up question features.

### Under Construction
- [Babysitter](https://github.com/wvanderen/babysitter) - Babysitter is a workflow orchestration engine for AI coding agents. It keeps terminal sessions alive, sequences work across td issues, and intelligently guides development from one task to the next—enabling autonomous, multi-step development workflows that can run overnight or across multiple sessions.
- [bmad-module-td](https://github.com/wvanderen/bmad-module-td) - A BMAD Method module for integrating with td CLI task management.
  
### [Catalyst](https://thecatalyst.app) (Private Repository)

A production-oriented focus and session timer app built with a ritual-based UX to help users start, sustain, and complete deep-work sessions with less friction.

Project Highlights:
- Built a full-stack timer product with **React 19 + TypeScript** frontend and a **Supabase-backed API/service layer**.
- Implemented **drift-compensated timing logic** (Web Worker-based) targeting **±1 second accuracy over 2+ hour sessions**.
- Designed state with **Zustand + IndexedDB persistence** to preserve critical session data reliably across refreshes/restarts.
- Enforced strict architecture boundaries: UI components never call the database directly; all data access flows through a typed service layer.
- Applied secure-by-default data modeling with **Row-Level Security (RLS)** and user-scoped access patterns (`auth.uid()`-filtered policies).
- Maintained high engineering quality via strict TypeScript, lint/type checks, Storybook-driven component development, and automated pre-commit validation.
