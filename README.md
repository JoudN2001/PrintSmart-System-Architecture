# PrintSmart: Unified Print Estimation & Inventory System 🖨️📊

Welcome to the **PrintSmart** System Architecture repository. This project is a comprehensive Case Study and System Design documentation for a modern, automated print shop management system.

## 📌 Project Overview
Print shops often suffer from manual calculation bottlenecks, reliance on static pricing sheets, and untracked inventory waste. **PrintSmart** is designed to digitize and automate these core processes. It features a dynamic pricing engine, tiered B2B/B2C logic, and real-time inventory deduction using Role-Based Access Control (RBAC).

## 📂 Repository Structure
- **`/docs`**: Contains the detailed project phases (Phase 1, 2, and 3) covering the System Proposal, PERT/Gantt analysis, and full architectural documentation in PDF format.
- **`/diagrams`**: Contains all high-resolution system models (DFDs, Use Cases, Network Diagrams).

## 🛠️ Methodology (Water-Scrum-Fall)
We adopted a **Hybrid SDLC Methodology**. Project management and budgeting were handled using structured Waterfall principles, while the core logical components (pricing algorithms) were engineered using agile, iterative Scrum practices.

---

## 📐 System Architecture & Modeling

### 1. Business Logic (Context & Logical DFD)
The system boundary and internal business processes were modeled to ensure zero managerial bottleneck for front-desk employees.
*(Showing the Context Diagram)*
![Context Diagram](diagrams/context.drawio.png)

### 2. Physical Implementation (Physical DFD)
Bridging the gap between business logic and software engineering, the physical DFD maps out HTTP POST payloads, JSON objects, and SQL Update queries.
![Physical DFD](diagrams/physicalDFD.png)

### 3. Behavioral Modeling (UML Use Case)
Illustrates the Object-Oriented design principles and Role-Based Access Control (RBAC), ensuring sensitive financial metrics remain hidden from non-administrative staff.
![Use Case Diagram](diagrams/usecase.png)

### 4. Project Management (PERT & Gantt)
Task dependencies, critical path (27 weeks), and parallel execution schedules were calculated using Three-Point Estimation.
![Network Diagram](diagrams/Network.png)
![Gantt Chart](diagrams/gantt%20chart.png)

---

## 👥 The Development Team
This architecture was designed and documented by:
- **Joud Kayyali** (Team Lead) - [Portfolio/Website](https://joudkayyali.vercel.app/)
- **Zaid Alassaf** (System Analyst)
- **Hamzah Altoom** (System Analyst)
- **Ibraheem Abdullah** (Technical Architect) - [Portfolio/Linkedln](https://www.linkedin.com/in/ibraheem-abdullah)
