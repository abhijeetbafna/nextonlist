<div align="center">

# NextOnList 📋

**Plan what's next. Track every small step.**

A modern, high-performance task management and productivity workspace designed for deep work, real-time planning, and habit consistency.

[![Website](https://img.shields.io/badge/Website-nextonlist.com-6366f1?style=for-the-badge&logo=google-chrome&logoColor=white)](https://nextonlist.com)
[![React](https://img.shields.io/badge/React_19-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://react.dev)
[![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS_v4-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)](https://supabase.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

</div>

---

## 🌟 Overview

**NextOnList** bridges the gap between high-level project roadmaps and day-to-day execution. Instead of treating tasks as flat, disconnected to-do lists, NextOnList keeps parent goals, nested sub-tasks, emoji buckets, and daily habit streaks on one calm, responsive workspace.

---

## ✨ Key Features

| Feature | Description |
| :--- | :--- |
| 🌳 **Nested Sub-Tasks & Timelines** | Build deep hierarchical task structures with parent-child relationships and visual progress windows. |
| 🪣 **Emoji Project Buckets** | Categorize work into custom buckets with emoji identifiers (🏠 Home, 💼 Work, 🚀 Launch, 🎯 Goals). |
| 📋 **Interactive Kanban Board** | Smooth drag-and-drop workflow across **To Do**, **In Progress**, and **Done** with nested sub-task counters. |
| 🔥 **Habit Tracker & Streaks** | Track daily habits with an interactive 30-day grid, consistency percentages, and streak tracking. |
| 📅 **Multi-View Calendar** | Visualize tasks, start dates, and deadlines across month, week, and day time windows. |
| 📊 **Productivity Insights** | Real-time dashboard showing completion rates, priority mix (Urgent, High, Medium, Low), and weekly workload. |
| 🎨 **Personalization & Settings** | Persistent Dark/Light theme, 12-hour vs. 24-hour time format toggle, global timezone selection, and dynamic SVG avatar presets. |
| 🔒 **Secure Authentication** | Built-in email/password authentication, account verification, and password recovery via Supabase Auth. |

---

## 🛠️ Tech Stack

* **Frontend Framework**: [React 19](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **Routing**: [TanStack Router](https://tanstack.com/router) (file-based type-safe routing)
* **Server State Management**: [TanStack Query](https://tanstack.com/query)
* **Styling & UI**: [Tailwind CSS v4](https://tailwindcss.com/), [Radix UI Primitives](https://www.radix-ui.com/), [Lucide React Icons](https://lucide.dev/)
* **Charts & Analytics**: [Recharts](https://recharts.org/)
* **Backend & Realtime Database**: [Supabase](https://supabase.com/) (PostgreSQL, Realtime, Row Level Security)

---

## 📂 Project Structure

```text
nextonlist/
├── src/
│   ├── components/       # Reusable UI components & dialogs (AppShell, Kanban, Habits, etc.)
│   ├── integrations/     # Supabase client & auto-generated database types
│   ├── lib/              # Utility functions, API mutations/queries, and domain types
│   ├── routes/           # TanStack file-based routes (Dashboard, Board, Calendar, Tasks, Habits, Auth)
│   └── main.tsx          # Application entry point
├── public/               # Static assets & NextOnList favicon
├── supabase/             # Supabase migrations & schema definitions
├── package.json
└── vite.config.ts
```

---

## 🚀 Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (v18 or higher)
* [npm](https://www.npmjs.com/) or [bun](https://bun.sh/)

### 1. Clone the repository

```bash
git clone https://github.com/abhijeetbafna/nextonlist.git
cd nextonlist
```

### 2. Install dependencies

```bash
npm install
# or
bun install
```

### 3. Configure environment variables

Create a `.env` file in the root directory:

```env
VITE_SUPABASE_URL=https://your-project-ref.supabase.co
VITE_SUPABASE_PUBLISHABLE_KEY=your-supabase-anon-or-publishable-key
```

### 4. Run the development server

```bash
npm run dev
# or
npm run start
```

Open [http://localhost:8080](http://localhost:8080) (or the port displayed in your terminal) in your browser.

---

## 🏗️ Production Build

To build the application for production:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 📜 License

Distributed under the **MIT License**. See `LICENSE` for more information.

<div align="center">
  <sub>Built with ❤️ for focused, intentional productivity on <strong>NextOnList</strong>.</sub>
</div>
