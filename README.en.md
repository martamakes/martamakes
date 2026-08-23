<div align="right">

[![ES](https://img.shields.io/badge/Idioma-Español-yellow.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-red.svg)](README.en.md)

</div>

<div align="center">

# Marta Vigara

### Full-stack Product Engineer · TypeScript · React · Next.js · PostgreSQL

I build production SaaS products end to end: from product definition and user experience to backend systems, payments, security and operations.

My strength is understanding end-to-end business workflows, identifying failure points and operational bottlenecks, and turning them into reliable, scalable software.

**Based in Madrid, Spain · Open to remote or hybrid Full-stack / Product Engineering roles**

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Distrify.me](https://distrify.me)

</div>

---

## Featured project — Distrify.me

[Distrify.me](https://distrify.me) is a production music-tech SaaS that helps independent artists distribute, market and monetise their music.

**150+ artists · 2,000+ tracks distributed · Live product**

### What I own

- Design, development and operation of the product end to end.
- Subscription and credit flows with Stripe, including idempotent webhooks, retry logic and audit logs.
- AI-assisted workflows that generate tailored marketing strategies for artists.
- Application architecture based on Next.js App Router, Server Components and streaming experiences.
- Security controls integrated into the delivery lifecycle, including automated OWASP ZAP scans in GitHub Actions.
- Production deployment and operations on Vercel, including monitoring and incident-oriented debugging.

### Selected engineering decisions

| Challenge | Implementation | Outcome |
|---|---|---|
| Concurrent credit consumption | Optimistic concurrency control with versioned Prisma updates | Prevented double-spending from simultaneous requests; no recorded balance inconsistencies during three months of production operation |
| Payment event reliability | Idempotent Stripe webhook handling, retry logic and audit trails | Safe reconciliation between payment events and transactional database state |
| Security before deployment | OWASP ZAP checks in GitHub Actions; critical findings block pull requests | Identified and remediated 15+ issues before production deployment |
| Responsive product UX | Server Components for SEO-sensitive routes; Client Components, optimistic updates and Suspense streaming where interaction requires it | Public landing pages load in under two seconds |

### Stack

**TypeScript · React · Next.js · Tailwind CSS · Prisma · PostgreSQL / Neon · Redis · Stripe · Claude API · Sanity · GitHub Actions · Vercel · Cloudflare**

> The production repository contains proprietary business logic. I can provide a product walkthrough, discuss architectural decisions, or share selected anonymised implementation material on request.

---

## How I create value

I begin by mapping the actual workflow: who performs each step, what data moves between systems, where decisions are made and where the process can fail.

This approach has helped me:

- Prevent credit overspending caused by concurrent requests through optimistic concurrency control.
- Make payment processing recoverable through idempotent Stripe webhooks, retries and audit logs.
- Reduce deployment risk by moving security controls into CI/CD rather than relying only on manual review.
- Automate marketing operations across CRM, email tools and reporting with n8n.
- Build features around artists’ actual workflows rather than disconnected technical components.

---

## Additional experience

### Business systems and automation

- Built custom Odoo modules in Python for project attendance, invoicing, treasury, accounting and fiscal processes.
- Implemented Verifactu-oriented invoicing integrations for Spanish billing requirements.
- Designed n8n automations for CRM synchronisation, campaign orchestration, event-triggered actions and reporting.

**Python · Odoo · n8n · PostgreSQL · REST APIs**

### Engineering foundations — 42 Madrid

Completed systems and C++ projects focused on concurrency, networking, containers and deployment. These projects strengthened how I reason about resource ownership, process isolation, protocol design, infrastructure and failure modes.

| Project | Main areas |
|---|---|
| Minishell | Unix processes, file descriptors, pipes, signals and system calls |
| Philosophers | Threads, mutexes, synchronisation and race-condition prevention |
| CPP Modules | Object-oriented design, STL, templates, memory management and canonical form |
| ft_irc | TCP networking, IRC protocol, client/server architecture and event-driven I/O |
| Inception | Docker, Docker Compose, NGINX, WordPress, MariaDB, networking and service isolation |

[View my 42 projects →](https://github.com/martamakes?tab=repositories&q=42)

---

## How I work

- I take ownership from problem definition through implementation, deployment and iteration.
- I use AI-assisted development for exploration, test generation and review, while retaining responsibility for architecture, implementation and validation.
- I value explicit trade-offs, readable TypeScript, automated validation, code review and production feedback.
- I am particularly interested in SaaS, music-tech, creator tools and AI-enabled products.

---

## Contact

If you are building a product where full-stack ownership, practical security and production experience matter, I would be happy to talk.

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Live product](https://distrify.me)

