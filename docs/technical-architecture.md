# Technical Architecture — ProjectTCG

**Version:** 0.1 — Draft
**Last Updated:** May 2026
**Status:** In progress — stack decisions pending finalization

---

## Overview

This document will capture all technical decisions for the ProjectTCG platform — tech stack selection, system architecture, data models, API design, and infrastructure choices.

Architecture decisions will be made with the following priorities:

1. **Mobile first** — the primary interface is iOS and Android
2. **Offline capable** — core workflows must function without internet connectivity
3. **Multi-tenant from day one** — data isolation between stores is a hard requirement
4. **Scalable to web** — the architecture must support adding a web dashboard (Phase 2) without a rewrite
5. **SaaS economics** — infrastructure costs must remain low relative to subscription revenue at early subscriber counts

---

## Contents (In Progress)

- [ ] Tech stack selection — mobile framework, backend, database
- [ ] System architecture diagram
- [ ] Authentication and authorization design
- [ ] Data model — core entities (Card, InventoryItem, Transaction, Customer, RuleSet, etc.)
- [ ] Offline sync strategy
- [ ] Card identification pipeline
- [ ] Pricing API integration architecture
- [ ] Multi-tenant data isolation approach
- [ ] Infrastructure and deployment
- [ ] Third-party services and dependencies

---

*This document will be completed during the architecture planning phase.*
