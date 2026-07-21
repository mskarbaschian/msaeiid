# 👋 Hi, I'm Saeid Karbaschian

**Full Stack Developer** — Python · Django · DRF · React · TypeScript · Odoo ERP

Full Stack Developer based in the Greater Toronto Area with 4+ years of experience building backend services with **Python/Django**, REST APIs with **Django REST Framework**, and modern frontends with **React + TypeScript** — plus hands-on experience customizing **Odoo ERP (v14–17)** across HR/payroll, inventory, approvals, sales, and accounting.

I care about production-grade patterns: atomic transactions, concurrency safety, background jobs, testing (pytest), linting (Ruff), Docker, and CI/CD. Currently deepening my **AWS** skills (ECS Fargate, RDS, ECR).

🇨🇦 Authorized to work in Canada · Open to Full Stack, Python/Django, Backend, and Odoo Developer roles.

---

## 🛠️ Tech Stack

| Category | Technologies |
| --- | --- |
| **Languages** | Python, TypeScript, JavaScript, SQL, HTML, CSS, XML |
| **Backend** | Django, Django REST Framework, Celery, JWT, Odoo (ORM, QWeb) |
| **Frontend** | React, Vite, React Router, Recharts |
| **Data & Cache** | PostgreSQL, Redis |
| **DevOps** | Docker, Docker Compose, GitHub Actions (CI/CD), Git, Linux, AWS (learning) |
| **Quality** | pytest, Ruff, pre-commit, Swagger/OpenAPI |

---

## 🚀 Featured Project

### [StockFlow](https://github.com/msaeiid/stockflow) — Inventory & Order Management System
Full-stack app that helps small businesses manage products, warehouses, suppliers, and customer orders. Built end-to-end and deployed to production (backend on Render, frontend on Vercel).

- **Atomic multi-item stock deduction** — all items deduct inside one DB transaction; any shortage rolls back the whole order (no partial orders, no negative stock).
- **Concurrency-safe** using `select_for_update()` row locking.
- **Async low-stock alerts** as Celery tasks dispatched via `transaction.on_commit`, with graceful fallback to in-memory cache when Redis is unavailable.
- **JWT auth** with role-based access (admin / manager / staff).
- **CI pipeline** on GitHub Actions: pytest against a PostgreSQL service container + Ruff linting.

**Stack:** Python, Django, DRF, PostgreSQL, Celery, Redis, React, TypeScript, Vite, Docker, GitHub Actions
🔗 **Live demo:** demo / demo12345

---

## 💼 Experience Highlights

- **Freelance Software Engineer** (Nov 2022 – Present) — End-to-end web and ERP solutions for SMB clients: an optic product pricing matrix integrated into Odoo 17 sale orders (cut order-entry clicks ~25–30%), receivable/payable smart buttons for a finance team, HR/payroll and approvals-to-inventory modules, and a full-stack Django + React client app.
- **Python Developer, Aria Beniz Group** (Feb 2022 – Oct 2022) — Custom Odoo 14 modules for sales/inventory/HR; supported an Odoo v8 → v14 migration.
- **IT Support Specialist / Python Developer, Fanavaran Etelaat Pishkhan** (May 2018 – Nov 2021) — Supported national digital-signature and e-Prescription platforms; automated operations with Python.

---

## 🎓 Education

- **Bachelor's Degree, Computer Software Engineering** — Shamsipour Technical and Vocational College
- **Associate's Degree, Computer Systems Networking and Telecommunications** — University of Applied Science and Technology

---

## 📫 Let's Connect

- 📍 **Location:** Greater Toronto Area, ON, Canada
- 📧 **Email:** [mskarbaschian@gmail.com](mailto:mskarbaschian@gmail.com)
- 🔗 **LinkedIn:** [linkedin.com/in/skarbaschian](https://www.linkedin.com/in/skarbaschian/)
