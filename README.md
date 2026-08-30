# Summer Internship Evaluation - B.Tech CSE (2024-28)

[![Institution](https://img.shields.io/badge/Institution-IILM%20University%2C%20Greater%20Noida-0F172A?style=for-the-badge)](https://iilm.edu/greater-noida/)
[![Next.js](https://img.shields.io/badge/Next.js-14.0-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![n8n](https://img.shields.io/badge/Automation-n8n%20Engine-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)](https://n8n.io/)
[![Deployment](https://img.shields.io/badge/Deployed%20on-Vercel%20Edge-000000?style=for-the-badge&logo=vercel)](https://vercel.com/)

---

## 📌 Executive Summary

This public repository hosts the complete academic documentation, project deliverables, and official records for the Summer Internship Evaluation submitted to the **School of Computer Science and Engineering, IILM University, Greater Noida**.

* **Project Title:** Full-Stack Web Application Development, n8n Workflow Automation & Cloud Deployment
* **Host Organization:** Zeta Galaxy (Samridhi Grand Avenue, Greater Noida, U.P.)
* **Role:** Software & Automation Engineer Intern
* **Internship Tenure:** 1st June 2026 - 30th July 2026 (2 Months)

---

## 👨‍🎓 Candidate Profile

| Attribute | Details |
| :--- | :--- |
| **Student Name** | Aman Kumar Jha |
| **Enrollment / Roll Number** | `2410030417` |
| **Program & Department** | B.Tech in Computer Science & Engineering |
| **Academic Session / Batch** | 2024-28 |
| **Current Semester & Section** | 5th Semester (Section: 3CSE7) |
| **Institution** | School of Computer Science & Engineering, IILM University |

---

## 📂 Official Submission Documents

All primary evaluation documents are organized below in both PDF and source formats:

| Document Type | Primary File (PDF) | Source Format | Description |
| :--- | :--- | :--- | :--- |
| **1. Internship Report** | [📄 `Internship_Report_Aman_Kumar_Jha.pdf`](./Internship_Report_Aman_Kumar_Jha.pdf) | [📘 `.docx`](./Aman_Kumar_Jha_Internship_Report.docx) | 14-page formal report prepared strictly according to IILM University guidelines, containing signed declarations, system architecture, n8n workflows, and 13 IEEE references. |
| **2. Presentation Deck** | [📊 `Internship_Presentation_Aman_Kumar_Jha.pdf`](./Internship_Presentation_Aman_Kumar_Jha.pdf) | [💻 `.pptx`](./Internship_Presentation_Aman_Kumar_Jha.pptx) | 12-slide modern 16:9 widescreen presentation deck featuring the university logo, student metadata, project workflow, and quantifiable results. |
| **3. Completion Certificate** | [📑 `Internship_Certificate_Aman_Kumar_Jha.pdf`](./Internship_Certificate_Aman_Kumar_Jha.pdf) | [📄 `PDF`](./Aman_Offer_Letter_Updated.pdf) | Official appointment and engagement verification documentation issued by Zeta Galaxy confirming the 2-month summer internship. |

---

## 🏗️ System Architecture & Engineering Flow

The project implements a modern, decoupled cloud-native architecture combining an edge-rendered frontend, serverless API microservices, event-driven n8n background automations, and relational database persistence:

```text
+-----------------------------------------------------------------------+
|                    CLIENT INTERFACE & PRESENTATION                    |
|       Next.js 14 App Router | React 18 | TypeScript | Tailwind CSS    |
+-----------------------------------+-----------------------------------+
                                    |
                                    v (HTTP / JSON REST)
+-----------------------------------------------------------------------+
|                       SERVERLESS API & AUTH LAYER                     |
|           Node.js Route Handlers | JWT Auth | Zod Validation          |
+-------------------+-------------------------------+-------------------+
                    |                               |
                    v (Asynchronous Webhooks)       v (Type-Safe ORM)
+---------------------------------------+   +---------------------------+
|      n8n AUTOMATION ENGINE            |   |     DATABASE STORAGE      |
|  - Event Webhook Trigger Nodes        |   |  - PostgreSQL Database    |
|  - Asynchronous Data Processing       |   |  - Prisma ORM             |
|  - Automated Multi-Service Sync       |   |  - Connection Pooling     |
+---------------------------------------+   +---------------------------+
                    |                               |
                    +---------------+---------------+
                                    |
                                    v (Continuous Delivery)
+-----------------------------------------------------------------------+
|                      VERCEL GLOBAL EDGE PIPELINE                      |
|       GitOps CI/CD | Preview Deployments | Sub-90s Production Build   |
+-----------------------------------------------------------------------+
```

---

## 🛠️ Technology Stack Breakdown

* **Frontend:** Next.js 14, React 18, TypeScript, Tailwind CSS, Lucide React
* **Backend & APIs:** Node.js, Next.js Serverless Route Handlers, REST APIs, JSON Web Tokens (JWT)
* **Workflow Automation:** n8n Workflow Automation Engine, Webhook Triggers, Custom JS Transform Nodes
* **Database & ORM:** PostgreSQL Cloud Database, Prisma ORM, Schema Migrations
* **DevOps & Hosting:** Vercel Global Edge Network, GitHub Actions CI/CD, ESLint, Prettier
* **Testing:** Jest, React Testing Library, Postman API Testing

---

## 🎯 Key Outcomes & Measurable Impact

* **100% Automated Deployment:** Implemented automated GitOps delivery pipelines on Vercel, reducing production deployment time to under 90 seconds.
* **Event-Driven Automation:** Designed n8n workflows that automated background data synchronization and communication dispatches without adding server latency.
* **Core Web Vitals:** Achieved a Google Lighthouse score of `96+` across Performance, Accessibility, and Best Practices.
* **Code Quality & Reliability:** Maintained `> 85%` test coverage across critical application and API routes.

