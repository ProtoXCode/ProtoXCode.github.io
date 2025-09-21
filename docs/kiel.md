# 🏭 Atlas KIEL – Kanban Intent Execution Layer

Welcome to **KIEL**: the stabilizing force beneath the Atlas Protocol execution stack.  
Like the keel of a ship, KIEL keeps your manufacturing flow balanced, pointed forward, and aligned with material reality.

---

## 🏗️ What is KIEL?

KIEL is a real-time interface and logic layer for surfacing only the work that’s actually possible right now, given materials, machines, and upstream progress.

- See what can be built.
- See what can’t, and why.
- Per station, per process, real-time.

---

## 🧰 Core Features

- **Feasible Work Orders:**  
  Top 5 jobs that can be started immediately (all parts and dependencies ready).  
  Color-coded status for each required part/step.

- **Unfeasible Work Orders:**  
  Next 5 jobs, blocked for any reason.  
  Transparent display of why (missing parts, incomplete steps, maintenance).

- **Station-Specific Task Queues:**  
  Every process/machine sees its own Top 5 feasible jobs, sorted by what’s actually doable.

- **Efficiency Tracker:**  
  See how long each job should take (from ERP), and how long it actually took.  
  Performance visible per operator and manager.

---

## 🏭 MVP Tech Stack

- Backend: FastAPI + ERP Client
- Frontend: Dash (can upgrade to React+Tailwind)
- Data: In-memory or SQLite (local cache for MVP)
