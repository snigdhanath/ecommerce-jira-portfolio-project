# 🚀 Jira Portfolio Project : Agile Framework Implementation for E-Commerce

## 📌 Executive Summary
* **Project Name:** E-Commerce Shopping Application (ESCA)
* **Role:** IT Project Manager (Simulation)
* **Methodology:** Scrum (Agile)
* **Core Tooling:** Jira Cloud 

## 🛠️ Deep Dive: Jira Architecture

### 1. Requirements Hierarchy & Visual Governance
I established a strict issue hierarchy to separate high-level business goals from technical execution:
* **Color-Coded Epics:** Used as strategic buckets to map major system initiatives (*User Account, Shopping Interface, Product Search*).
* **User Stories:** Written from the user perspective to deliver functional business value.
* **Color-Coded Components:** Tagged specific architectural modules (`SHOPPING CART`, `PRODUCT SEARCH`) to give the development team immediate contextual visibility and allow for quick board filtering.

### 2. Backlog Grooming & Predictable Estimation
* **Backlog Refinement:** Managed and prioritized user stories based on business value and technical dependencies.
* **Story Pointing:** Enforced Fibonacci estimation ($1, 2, 3, 5, 8, 13$) mapped strictly against issue priority to ensure team capacity planning is backed by realistic effort metrics.

> <img width="1880" height="858" alt="image" src="https://github.com/user-attachments/assets/f452bc54-56f3-4c35-85cd-5e674070daa0" />

---

### 3. Release & Version Tracking (Milestones)
To manage stakeholder expectations and establish a clear Minimum Viable Product (MVP), I configured **Fix Versions** to track release cycles:
* `Version 1`: Core MVP checkout and core search functionality.
* `Version 2.0` & `Version 3`: Sequential lifecycle improvements (Advanced account metrics, wish lists).

---

### 4. Sprint Execution & Custom Workflow Engineering
Instead of using Jira's default template, I engineered a custom workflow tailored to modern DevOps team structures:
* **Sprint History:** Successfully planned, executed, and closed **Sprint 1**.
* **Active Cycle:** Currently managing **Sprint 2** in an active state.
* **The "To Verify" Status Lane:** Engineered a custom column between *In Progress* and *Done*. This acts as a formal Quality Assurance (QA) gate, ensuring no code reaches production without passing predefined acceptance criteria (Definition of Done).

<img width="1880" height="840" alt="image" src="https://github.com/user-attachments/assets/18a2f829-632b-461c-8531-a1d1e7f2a5a5" />


---

### 5. Data-Driven Reports & Summary Dashboard
To maintain absolute transparency for stakeholders, I configured the Jira **Summary Dashboard** to track delivery performance over rolling 7-day windows:
* **Work Item Distribution:** Balanced the technical scope at **$60\%$ Stories, $18\%$ Epics, $13\%$ Sub-tasks, and $9\%$ Bugs** to ensure continuous value delivery while managing technical debt.
* **Status Analytics:** Monitored the real-time status donut chart to audit team throughput and proactively identify column bottlenecks.

<img width="1397" height="776" alt="image" src="https://github.com/user-attachments/assets/a27f5ce5-852a-486c-b6d0-3d81bcedab20" />

---
