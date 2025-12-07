# ⚡ Workforges ERP — Frontend (React)

Workforges is a **next-generation open-source, multi-tenant ERP** built for small and medium businesses.

Unlike traditional ERPs where screens are fixed and rigid, Workforges allows **each company to design their own ERP screens using drag-and-drop** — no coding required.

This repository contains the **React frontend** for core modules such as CRM, Sales, Inventory, HRM, Dashboard — and many more coming soon.

---

## 🧠 Why Workforges Is Different

Most ERPs = hard-coded screens and expensive customization.  
Workforges = **each company gets its own customized interface.**
Customer drags & drops fields
↓
Screen Builder saves settings (JSON)
↓
UI Engine reads settings
↓
Screen is generated automaticallyWorkforges is not just ERP.  
It is a **no-code ERP builder.**

---

## 📦 Phase-1 Modules (MVP)

- Authentication & Users
- Dashboard
- CRM
- Sales
- Inventory
- HRM

More than **60 applications** will be introduced over time (Projects, Payroll, Banking, Purchase, Support, Tasks, etc.)

---

## 💻 Tech Stack

| Layer | Technology |
|-------|------------|
| UI | React + Vite |
| Language | TypeScript (preferred) / JavaScript |
| Styling | TailwindCSS / Ant Design |
| State | Context API (later Zustand/Redux optional) |
| API | REST (Node.js backend) |
| DB (backend) | PostgreSQL |

---

## 📁 Folder Structure
.
├── src
│   ├── components       # Reusable UI components
│   ├── modules          # CRM, Sales, Inventory, HRM, Dashboard
│   ├── pages            # Routes
│   ├── context          # Auth, Toast, Theme
│   ├── hooks            # Custom hooks
│   ├── services         # API client
│   └── utils            # Helpers
├── docs                 # All documentation
├── public
└── .github              # Issue / PR templates, workflows
---

## 🚀 Local Setup

```bash
git clone https://github.com/Workforges/workforges-frontend.git
cd workforges-frontend
npm install
npm run dev
