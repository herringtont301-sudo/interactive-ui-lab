01 — Interactive UI Lab
Phase: Now till Jan | Goal: x.ai AI Tutor SWE - "Strong proficiency in relevant frameworks and libraries"
A collection of 3 polished, interactive UIs that prove frontend depth for the x.ai portfolio review.
🎯 What x.ai screeners see
Proficiency in React / component architecture
State management, performance optimization
Accessibility + testing mindset (preferred in JD)
🧱 Repo Structure
src/
  components/  # Reusable, tested UI primitives
  hooks/       # Custom hooks (useDebounce, useLocalStorage)
  pages/       # 3 demo apps
public/
tests/
🚀 3 Builds (Do these in order)
Data Table Explorer — Sortable, filterable, virtualized table (10k rows) with keyboard nav
Code Diff Viewer — Like x.ai uses for model evaluation — side-by-side diff, syntax highlight, comments
Prompt Playground UI — Chat-style UI with streaming response mock, token counter, copy-as-markdown
✅ Checklist for README
 Live demo on Vercel
 Lighthouse 95+ / a11y checks
 Jest + React Testing Library (1 test per component)
 README GIFs
Tech Stack
React + TypeScript + Tailwind + Vite + Vitest
How to run
bash
npm install
npm run dev
npm run test