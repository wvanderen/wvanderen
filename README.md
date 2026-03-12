## Hey I'm William (Liam) 👋
---

Senior frontend engineer with 5+ years building performant, accessible web experiences. I'm currently shipping features in a headless React PWA at Duluth Trading Co. I specialize in React and TypeScript but I'm comfortable across the stack, and I get a lot of satisfaction from the cross-functional side of the work: partnering with designers, unblocking teams, and mentoring other engineers.

Lately I've been deep in the AI-assisted development space and exploring what modern tooling (and the workflows around it) actually unlocks for solo builders and teams. I'm learning Python with a focus on AI/ML and building a orchestration tool for AI coding workflows. Shipping more than ever and genuinely having a blast. 

When I'm not at the keyboard I'm probably breaking a roguelike, restarting a chapter in Fire Emblem, or jamming on my synthesizer, usuallly being supervised by one of my three cats. 🐱

### Released Projects
- Catalyst (see below) - Ritual Focus Engine
- [PoeAstrology](https://poe.com/PoeAstrology) - [Source code](https://github.com/wvanderen/poe-astrology-bot) - Simple natal chart calculator with rich UI, SVG astrology chart construction, LLM analysis, personalization, and follow up question features.

### Under Construction
- [Otto](https://github.com/wvanderen/otto-mono) - Otto is the Pi-native operating layer for BMAD + td execution.
An automation loop that turns BMAD workflows, td state, and validation evidence into a tighter closed-loop delivery system.
- [mindrave](https://github.com/wvanderen/mindrave) -  MINDRAVE is a terminal-native co-creative music environment where humans direct AI agents through natural language, gesture, and macro control to collaboratively create and perform music in real time. Pi Extension with Integrated SuperCollider Runtime. 
  
### [Catalyst](https://thecatalyst.app) (Private Repository)

A production-oriented focus and session timer app built with a ritual-based UX to help users start, sustain, and complete deep-work sessions with less friction. Still under active development. 

Project Highlights:
- Built a full-stack timer product with **React 19 + TypeScript** frontend and a **Supabase-backed API/service layer**.
- Implemented **drift-compensated timing logic** (Web Worker-based) targeting **±1 second accuracy over 2+ hour sessions**.
- Designed state with **Zustand + IndexedDB persistence** to preserve critical session data reliably across refreshes/restarts.
- Enforced strict architecture boundaries: UI components never call the database directly; all data access flows through a typed service layer.
- Applied secure-by-default data modeling with **Row-Level Security (RLS)** and user-scoped access patterns (`auth.uid()`-filtered policies).
- Maintained high engineering quality via strict TypeScript, lint/type checks, Storybook-driven component development, and automated pre-commit validation.

### Professional Case Studies (under construction)
