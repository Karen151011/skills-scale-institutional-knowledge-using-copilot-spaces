# OctoAcme Roles and Personas

This document defines the key personas and roles involved in OctoAcme's project management processes and how they collaborate.

## Existing Roles

### Project Manager (PM)
- **Responsibilities:** Owns project planning, timeline, scope, and stakeholder communication.
- **Interacts with:** All roles to coordinate delivery.

### Product Owner
- **Responsibilities:** Defines requirements, prioritizes backlog, and ensures business value.
- **Interacts with:** PM, Engineering, QA, Customer Success.

### Developer
- **Responsibilities:** Implements features, writes tests, and participates in code reviews.
- **Interacts with:** Engineering Lead, QA Lead, Security Lead.

## New Roles and Personas

### 1. Líder de Ingeniería / Engineering Lead
- **Responsibilities:** Technical architecture, engineering standards, mentoring developers, unblocking technical risks.
- **Objetivos:** Ensure scalable, maintainable delivery.
- **Interacción:** Works closely with Project Manager on planning, with QA Lead on quality gates, and with Security/Compliance Lead on secure coding.

### 2. Líder de Control de Calidad / QA Lead
- **Responsibilities:** Define test strategy, manage test cases, own bug triage, quality metrics.
- **Objetivos:** Reduce defects in production, improve release confidence.
- **Interacción:** Collaborates with Engineering Lead on test automation, with Product Owner on acceptance criteria, and with Operations/Launch on release readiness.

### 3. Líder de Seguridad/Cumplimiento / Security/Compliance Lead
- **Responsibilities:** Security reviews, compliance checks (GDPR, SOC2), threat modeling, dependency scanning.
- **Objetivos:** Minimize security risk and ensure compliance.
- **Interacción:** Interacts with Engineering Lead during design reviews, with QA Lead for security testing, and with Project Manager to include security tasks in timeline.

### 4. Enlace de Éxito/Soporte al Cliente / Customer Success / Support Link
- **Responsibilities:** Voice of the customer, gather feedback, manage customer issues, document FAQs.
- **Objetivos:** Improve customer satisfaction and retention.
- **Interacción:** Works with Product Owner to prioritize customer requests, with QA to reproduce customer issues, and with Operations during launches.

### 5. Gerente de Operaciones/Lanzamientos / Operations/Launch Manager (Optional)
- **Responsibilities:** Release planning, deployment runbooks, monitoring, rollback plans, post-launch support.
- **Objetivos:** Ensure smooth, zero-downtime releases.
- **Interacción:** Coordinates with Engineering Lead, QA Lead, Security Lead, and Customer Success for go/no-go decisions.

## How Roles Collaborate

- **Planning:** PM + Product Owner + Engineering Lead + QA Lead + Security Lead define scope and risks.
- **Execution:** Developers build, QA validates, Security reviews, Customer Success validates customer impact.
- **Release:** Operations/Launch Manager orchestrates deployment with all leads.
- **Retrospective:** All roles contribute to continuous improvement.

This structure scales institutional knowledge by clarifying who owns what and how information flows across OctoAcme.

