EXMDirect — System Analysis Portfolio

Author: Baldruev Sergei  
Role: System Analyst, ex-Full Stack Developer



	Project Overview

EXMDirect is an educational digital platform designed for schools to automate testing processes. The system supports:
- Flexible test creation by teachers
- Up to 30 automatically generated test variants
- Real-time cheating protection
- QR-based student identification
- Seamless integration with Telegram bot
- Intelligent linkage of lesson content to questions (via “clues” or “зацепки”)

> This project showcases system analysis activities and artifacts created during the system design phase.

---

	Objectives of This Portfolio

This repository presents the system analyst’s view of EXMDirect. It serves as a portfolio case and demonstrates:
- Requirements elicitation and structuring  
- Business process modeling  
- System design with data modeling and use cases  
- API documentation  
- Analyst involvement in decision-making and architecture

---

	Key Features of EXMDirect

- “Clue-based” Testing: Teachers provide semantic anchors ("зацепки") during lessons, which are later used in questions. This method reduces AI-aided cheating.
- Anti-cheating Frontend Module: Detects tab switching, copy-paste, window inactivity.
- Telegram Bot Integration: QR scanning, student login, teacher notifications.
- QR-Code Based Student Identification
- Excel Import of KTP (curriculum plans)
- Instant Result Calculation and error breakdown
- Multi-role Architecture: Admins, Teachers, Students

---

 	What’s Included

| Folder/File                       | Description                                             |
|----------------------------------|---------------------------------------------------------|
| `/docs/EXMDirect_Portfolio.pdf`  | Main portfolio document with overview and analysis      |
| `/docs/diagrams/`                | Diagrams: Use Case, BPMN, and ER model                  |
| `/docs/swagger/openapi.yaml`     | REST API specification (Swagger / OpenAPI format)       |
| `/gpt_assistant.md`              | Collaboration logs with AI for test generation, idea development |
| `/notion_export.md`              | Markdown export for Notion or alternative tools         |
| `/examples/`                     | Sample test structures, Excel formats, API payloads     |




	Project Structure

exmdirect-system-analysis/
├── README.md              This file — portfolio overview
├── CHANGELOG.md           Progress log, feature releases
├── LICENSE                License info (MIT, Apache, etc.)
├── notion_export.md       Exported version for Notion or blog
├── gpt_assistant.md       Collaboration with AI (e.g. test generation)
├── openapi.yaml           REST API definition (Swagger/OpenAPI 3.0)
├── diagrams/              Use Case, BPMN, ER diagrams
├── docs/                  Project documentation and PDF report
├── examples/              Sample payloads, Excel test imports
└── .gitignore             Files to exclude from version control
```




	System Analyst Responsibilities

As a system analyst, I performed the following:
- ✅ Stakeholder communication — clarified pain points and objectives  
- ✅ Requirement gathering — structured functional and non-functional requirements  
- ✅ Business process modeling — BPMN diagrams to describe key flows  
- ✅ Data modeling — ER model for database design  
- ✅ Use case modeling — defined key actors and system behavior  
- ✅ API specification — designed RESTful endpoints and structure  
- ✅ Validation & documentation — ensured developer-readiness and clarity  


	Tech Stack (Reference from Implementation)

- Java 17+, Spring Boot, Spring Security (JWT)  
- PostgreSQL + JPA  
- REST API + Swagger (OpenAPI 3.0)  
- Telegram Bot API  
- Anti-Cheat Frontend Logic (JS/React)  



	Related Repositories

- [EXMDirect Backend (Java)](https://github.com/BaldruevSergei/Exmdirect_back-)
- [EXMDirect Frontend (React)](https://github.com/BaldruevSergei/Testing_site_Front)



	Contact

- Telegram: [@Baldruev_Sergei](https://t.me/Baldruev_Sergei)  
- LinkedIn: [Sergei Baldruev](https://www.linkedin.com/in/sergei-baldruev)  
- Email: baldruev.sergey@email.com  



This project is part of my professional transition from full-stack developer to system analyst. All analysis, documentation, and models were created independently based on real and modeled data.
