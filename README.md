# GradePath
Module Ranker

Visualize where you stand in each module and what you need to hit your target classification (First, 2:1, etc.).
Punch in assessment weights + results, set a goal, and get an immediate “you are here → you need this” breakdown with simple charts.

✨ Features

Add modules and assessments (quizzes/tests/exams) with custom weights

Enter scores for completed items; see live weighted average

Set a target (First / 2:1 / custom %) and get the required scores for remaining items

Visual progress chart: current vs target

Multiple modules, multiple scenarios (e.g., “what if I ace the exam?”)

Local save + optional cloud sync (Supabase)

🧱 Tech Stack

Frontend: Next.js (App Router), React, TypeScript, Tailwind

Charts: Recharts (or Chart.js)

Backend/DB (optional cloud): Supabase (Postgres + Auth)

State: Zustand or Redux Toolkit (pick one)

Testing: Vitest / Jest + React Testing Library

CI: GitHub Actions (build, lint, test)