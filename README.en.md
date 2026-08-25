<div align="right">

[![ES](https://img.shields.io/badge/Idioma-Español-yellow.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-red.svg)](README.en.md)

</div>

<div align="center">

# Marta Vigara

### Full-stack Product Engineer · SaaS 0→1 · TypeScript · React · Next.js

I build SaaS products from problem definition to production operations: discovery, MVPs, user experience, backend systems, payments, security, automation, and continuous improvement.

I combine full-stack engineering with experience in product development, marketing, operations, and client management. I understand how a product is sold, used, and maintained—and translate that into reliable software that solves real business workflows.

**Madrid, Spain · Open to remote or hybrid Full-stack / Product Engineering roles**

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Live product: Distrify.me](https://distrify.me)

</div>

---

## What I’m looking for

I am interested in teams building SaaS products, platforms, internal tools, creator-focused products, or applied AI. I am particularly drawn to environments where I can bring full-stack ownership, product judgement, and operational experience.

I am open to opportunities as a **Product Engineer**, **Full-stack Engineer**, **Founding Engineer**, or **Technical Product Builder**, especially in 0→1 teams or products already iterating with real users.

---

## Featured project — Distrify.me

[Distrify.me](https://distrify.me) is a production music-tech SaaS platform that helps independent artists distribute, promote, and monetize their music.

- 150+ artists.
- 2,000+ distributed tracks.
- Product designed, built, and operated end to end.
- Payments, credit systems, automation, AI-assisted marketing, and product operations.

My role combines product discovery, MVP definition, user and operational workflow design, full-stack architecture, security, deployment, and production support.

### My responsibilities

- User-needs research, product definition, MVP prioritization, and workflow design for artists and internal operations.
- End-to-end product design, development, and operations.
- Subscription and credit flows with Stripe, including idempotent webhooks, retry logic, and audit records.
- AI-assisted workflows that generate marketing strategies tailored to each artist.
- Architecture based on Next.js App Router, Server Components, and streaming experiences.
- Security controls embedded in the delivery lifecycle, including automated OWASP ZAP scans in GitHub Actions.
- Production deployment and operations on Vercel, with monitoring and incident-oriented debugging.

### Selected technical decisions

| Challenge | Implementation | Impact |
|---|---|---|
| Concurrent credit consumption | Optimistic concurrency control through versioned updates in Prisma | Prevents double consumption during simultaneous requests and protects balance consistency |
| Reliable payment events | Idempotent Stripe webhook processing, retries, and audit-log traceability | Enables recoverable reconciliation between external events and transactional database state |
| Security before deployment | OWASP ZAP checks in GitHub Actions; critical findings block pull requests | Identified and fixed more than 15 issues before reaching production |
| Responsive product experience | Server Components for SEO-sensitive routes; Client Components, optimistic updates, and Suspense streaming where interaction is needed | Optimized public routes for SEO and created smoother interactive workflows |

### Stack

**TypeScript · React · Next.js · Tailwind CSS · Prisma · PostgreSQL / Neon · Redis · Stripe · Claude API · Sanity · GitHub Actions · Vercel · Cloudflare**

> The production repository contains proprietary business logic. I can provide a product demonstration, discuss architectural decisions, or share selected and anonymized implementation material on request.

---

## From business problem to production product

My previous experience in product, marketing, operations, and client management allows me to contribute before a technical specification exists: I understand the problem, identify real constraints, and turn the workflow into a measurable, evolvable MVP.

- **0→1 products and MVPs:** I define scope, hypotheses, critical workflows, and a first version that enables learning without overbuilding.
- **Operational products:** I design for exceptions, support, reconciliation, permissions, auditability, and the team’s day-to-day work—not only the happy path.
- **End-to-end delivery:** I can own discovery, full-stack implementation, deployment, usage analysis, and iteration with users.
- **Business automation:** I connect CRM, email, payments, billing, reporting, and internal tools to reduce manual work and errors.

This approach has allowed me to:

- Prevent excessive credit consumption during concurrent requests through optimistic concurrency control.
- Make payment processing recoverable through idempotent Stripe webhooks, retries, and audit records.
- Reduce deployment risk by embedding security checks in CI/CD instead of relying only on manual reviews.
- Automate marketing operations across CRM, email tools, and reporting with n8n.
- Design features around artists’ real workflows rather than isolated technical components.

---

## Additional experience

### Business systems and automation

- Developed custom Odoo modules in Python for project-based time tracking, invoicing, treasury, accounting, and tax processes.
- Built billing integrations aligned with Spain’s Verifactu invoicing requirements.
- Created n8n automations for CRM synchronization, campaign orchestration, event-driven actions, and reporting.
- Designed processes and internal tools focused on reducing manual work, improving traceability, and making daily operations easier.

**Python · Odoo · n8n · PostgreSQL · REST APIs**

### Engineering foundations — 42 Madrid

Completed systems and C++ projects focused on concurrency, networking, containers, and deployment. These projects strengthened how I reason about resource ownership, process isolation, protocol design, infrastructure, and failure modes.

| Project | Main areas |
|---|---|
| Minishell | Unix processes, file descriptors, pipes, signals, and system calls |
| Philosophers | Threads, mutexes, synchronization, and race-condition prevention |
| CPP Modules | Object-oriented design, STL, templates, memory management, and canonical form |
| ft_irc | TCP networking, IRC protocol, client-server architecture, and event-driven I/O |
| Inception | Docker, Docker Compose, NGINX, WordPress, MariaDB, networking, and service isolation |

[View my 42 projects →](https://github.com/martamakes?tab=repositories&q=42)

---

## How I work

- I take ownership from problem definition through implementation, deployment, and iteration.
- I work with users, teams, and operational data to decide what to build before turning it into a technical solution.
- I use AI-assisted development for exploration, test generation, and review while retaining responsibility for architecture, implementation, and validation.
- I value explicit trade-offs, readable TypeScript, automated validation, code review, and production feedback.
- I am especially interested in SaaS, music-tech, creator tools, and applied AI products.

---

## Contact

If you are building a product where full-stack ownership, product judgement, practical security, and production experience matter, I would be happy to talk.

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Live product: Distrify.me](https://distrify.me)
