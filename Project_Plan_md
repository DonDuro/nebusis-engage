# Nebusis Engage – Project Plan

## Overview
This document outlines both the **12-week baseline plan** and an **AI-accelerated 9-week plan** for building and launching Nebusis Engage.

---

## Baseline Plan – 12 Weeks

**Phase 1: Foundation (Week 1-2)**
- Core Go backend API with MySQL
- Basic CRM functionality
- Stripe integration
- QuickBooks Online integration
- Essential marketing workflows

**Phase 2: Marketing & Sales (Week 3-4)**
- Multi-platform advertising integration
- AI-powered creative generation
- Social media management
- Sales pipeline automation
- Lead-to-sales handoff

**Phase 3: Customer Success (Week 5-6)**
- Health score implementation
- Renewal management
- Mobile app core features
- Basic offline functionality

**Phase 4: AI Enhancement (Week 7-8)**
- Predictive analytics
- Advanced AI features
- Mobile AI capabilities
- Voice-to-text integration

**Phase 5: Advanced Features (Week 9-12)**
- Complete mobile app launch
- Advanced reporting
- Public API
- Multi-tenant architecture

---

## AI-Accelerated Plan – 9 Weeks

We keep the 12-week plan as the **baseline**, but with **two dedicated developers** leveraging **AI-assisted coding** (scaffolding, tests, API stubs, UI screens, n8n flows), this scope can realistically be delivered in **~9 weeks**.

### Assumptions to Achieve 9 Weeks:
- **Team**: 2 full-time devs (Backend/API + Frontend/Mobile/Workflows).
- **Scope control**: MVP freeze; non-critical features deferred.
- **Prep**: OpenAPI + ERD finalized in Week 0; credentials for Stripe/QBO/Ad APIs ready.
- **AI usage**: Daily for scaffolds, tests, docs, and workflow drafts.

### Changes vs. Baseline:
- Parallelization of tracks; fewer handoffs.
- Code generation for handlers, models, clients, tests, and RN screens.
- Earlier n8n automation seeds to validate end-to-end flows sooner.
- Performance/reporting polish consolidated into Week 9.

---

### 9-Week Timeline

| Week | Dev A (Backend/API) | Dev B (Frontend/Mobile/Workflows) | Milestone |
|---|---|---|---|
| 0 (Prep) | Finalize **OpenAPI**, **ERD**, envs/CI | Wireframes, n8n flow diagrams | Scope locked |
| 1 | Go API skeleton, DB migrations | RN scaffold + auth screens | |
| 2 | Stripe + QBO clients; basic CRM endpoints | CRM screens + dashboard wiring | **E2E CRM** |
| 3 | Ads API integrations (Google/Meta/LinkedIn) | AI creative UI, ad scheduling | |
| 4 | Sales pipeline endpoints | Pipeline UI + lead→sales handoff (n8n) | **Pipeline demo** |
| 5 | Health score service | Health score UI (web/mobile) | |
| 6 | Renewal API | Renewal workflows + push notifications | **Renewals E2E** |
| 7 | Predictive analytics (basic) | Voice-to-text + AI helpers in mobile | |
| 8 | Public API exposure + multi-tenant guards | Offline sync + advanced mobile | **Public API + Offline** |
| 9 | Reporting, perf tuning, security hardening | App store prep, docs, handover | **Launch demo** |

---

### Risks & Mitigations
- **3rd-party auth/scopes delays** → Prep Week 0 credentials; use sandbox keys.
- **Offline sync conflicts** → Define merge rules early; test with seed data.
- **Multi-tenant boundaries** → Enforce tenant ID at DB and service layer; add tests.

---

## Conclusion
The **12-week plan** is the conservative, low-risk schedule.  
The **9-week plan** is aggressive but achievable with disciplined scope management, strong AI-assisted development, and readiness of all external integrations.

---
© 2025 Nebusis Cloud Services, LLC. Proprietary and Confidential.  
Unauthorized use, distribution, or reproduction of this material is strictly prohibited.
