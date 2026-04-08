<div align="right">

[![es](https://img.shields.io/badge/lang-es-yellow.svg)](README.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

</div>

<div align="center">

# Hi, I'm Marta! 👋

### Full-Stack Developer | AI-Powered Development | 42 Madrid

From programming student to building a **SaaS with +150 artists and +2,000 songs distributed**

Specialized in **Next.js • TypeScript • Secure and Scalable Architectures**

---

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:marta.vigara.gonzalez@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/martavigara)
[![Distrify](https://img.shields.io/badge/My_Project-00D9FF?style=flat-square&logo=vercel&logoColor=white)](https://distrify.me)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/martamakes)

🔍 **Open to Collan in**: Full-Stack/Frontend Developer role in new adventures • Madrid (remote)

</div>

---

## 🚀 My Project: Distrify.me

**Production SaaS** helping independent artists monetize their music through digital marketing and data analytics.

**+150 artists** • **+2,000 songs distributed** • **Actively growing**

> 🔗 **[See it live](https://distrify.me)** • 📧 **[Demo/Code under NDA](mailto:marta.vigara.gonzalez@gmail.com)**

### 📊 Impact

- 🎯 **+150 artists** actively using the platform
- 🎵 **+2,000 songs** distributed through distrify
- ⚡ **99.9% uptime** in production (Vercel)
- 📈 **~13 songs per artist** on average
- 🤖 **AI system** generating personalized marketing strategies

### 🛠️ Stack & Architecture

```
Frontend:    Next.js 14 (App Router) • React • TypeScript • Tailwind CSS
Backend:     Next.js API Routes • Prisma ORM • PostgreSQL (Neon)
Auth/Pay:    NextAuth • Stripe (webhooks, subscriptions)
AI:          Claude API (Haiku + Sonnet 4.5) • Claude Code • Prompt engineering
CMS:         Sanity (headless)
Security:    OWASP ZAP • Cloudflare Turnstile • Rate limiting (Redis)
DevOps:      GitHub Actions • Vercel • Monitoring
```

### 💡 Technical Challenges I Solved

**1. Race Conditions in Transactions 🔒**
- **Problem**: Users could consume more credits than available with concurrent requests
- **Solution**: Implemented optimistic locking with versioning in Prisma
- **Result**: 0 balance inconsistencies in 3 months of production

**2. CI/CD with Automated Security Testing 🛡️**
- **Problem**: Detect vulnerabilities before production
- **Solution**: GitHub Actions pipeline with OWASP ZAP that blocks PRs with critical issues
- **Result**: 15+ vulnerabilities detected and fixed before deployment

**3. Complex Multi-API Integration 🔌**
- **Problem**: Synchronize Stripe webhooks, Claude API, and transactional database
- **Solution**: Idempotent webhooks system with retry logic and audit logs
- **Result**: 100% webhooks processed correctly

**4. Scalable Architecture from Day 1 📈**
- **Design**: Next.js App Router with Server Components for SEO + Client Components for interactivity
- **Performance**: Optimistic updates, streaming responses, React Suspense
- **Result**: < 2s load time on landing pages

**5. AI-Assisted Development with Claude Code 🤖**
- **Approach**: Intensive use of Claude Code to accelerate development
- **Techniques**: Creation of specialized sub-agents (Plan, Explore, Security, Testing)
- **Workflow**: Draft → Critic → Refinement for AI-generated content
- **Result**: 3x development speed + more secure code (race condition detection with AI)

---

## 💼 Additional Experience

### Odoo Development (ERP/Python)

Custom module implementation for business management:

- 📊 **Project-based attendance management** - Remote worker tracking
- 💰 **Complete invoicing system** - Invoices, collections, and payments
- 🏦 **Treasury and accounting** - Cash flow management
- 📑 **Tax management** - Automated tax handling
- 🔗 **Verifactu integration** - Spanish invoicing regulation compliance

### Automation with n8n

Automated workflows for marketing systems:

- 🤖 Email marketing campaign automation
- 🔄 Synchronization between CRM and marketing tools
- 📈 Automated reports and notifications
- 🎯 Segmentation and event-based action triggering

**Stack**: Python • Odoo • n8n • PostgreSQL • REST APIs

---

## 💪 What I Can Bring

| Skill | Level | Evidence |
|-------|-------|-----------|
| **Ship fast** | ⭐⭐⭐⭐⭐ | From idea to MVP in 6 weeks, to production in 3 months |
| **Security-first** | ⭐⭐⭐⭐ | OWASP ZAP, optimistic locking, secure webhooks |
| **Problem solver** | ⭐⭐⭐⭐⭐ | Full-stack debugging: PostgreSQL → API → React |
| **Versatility** | ⭐⭐⭐⭐⭐ | Next.js, Python/Odoo, n8n - Complete full-stack |
| **Fast learner** | ⭐⭐⭐⭐⭐ | Learned Next.js 14, Prisma and Stripe while building distrify |
| **AI-powered dev** | ⭐⭐⭐⭐⭐ | Claude Code + sub-agents = 3x productivity |
| **Self-taught** | ⭐⭐⭐⭐⭐ | 42's peer-to-peer method = learning by doing |
| **Code quality** | ⭐⭐⭐⭐ | TypeScript strict, Zod validation, automated tests |

---

## 🤖 AI & Claude Code - My Superpower

I'm an **early adopter** of AI-assisted development. I don't just use AI, I integrate it into my daily workflow:

### 🎯 How I Use Claude Code

**Specialized Sub-Agents**
- 🔍 **Explore Agent**: Codebase and architecture analysis
- 📋 **Plan Agent**: Complex implementation design
- 🔒 **Security Agent**: Proactive vulnerability detection
- ✅ **Test Agent**: Automated test generation

**Development Workflow**
```
Idea → Plan (AI) → Code Review (AI + human) → Security Scan (AI) → Deploy
```

**Measurable Results**
- ⚡ **3x faster** in complex implementations
- 🔒 **Race condition detected** by AI before production code
- 📚 **Better documentation** automatically generated
- 🎯 **Fewer bugs** thanks to AI-assisted code review

**My Philosophy**
> "AI doesn't replace the developer, it multiplies their impact. A good developer with AI > 3 developers without AI."

---

## 💻 Education: 42 Madrid

**Peer-to-peer learning** • C, C++, Algorithms, Systems

<div align="center">

| Project | Skills | Status |
|----------|--------|--------|
| **Minishell** | System calls, Process management | ✅ |
| **Philosophers** | Threads, Mutex, Concurrency | ✅ |
| **CPP Modules** | OOP, STL, Templates | ✅ |

[📚 See all 42 projects →](https://github.com/martamakes?tab=repositories&q=42)

</div>

---

## 🛠️ Complete Tech Stack

<div align="center">

### 💼 Real Production Experience

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

### 🤖 AI & Tools

![Claude](https://img.shields.io/badge/Claude_API-8A2BE2?style=flat-square&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)

### 📚 Fundamentals

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 📊 By The Numbers

<div align="center">

| Metric | Value |
|---------|-------|
| 🎯 **Artists in production** | +150 |
| 🎵 **Songs distributed** | +2,000 |
| ⚡ **Production uptime** | 99.9% |
| 🚀 **Speed with AI** | 3x faster |
| 📦 **Projects on GitHub** | [View repos →](https://github.com/martamakes?tab=repositories) |

</div>

---

## 🎯 What I'm Looking For

✅ **Strong technical team** where I can learn from seniors
✅ **Modern stack** (React/Next.js, TypeScript, well-designed architecture)
✅ **Active code reviews** and quality culture
✅ **Real product** solving real problems
✅ **Ownership** of end-to-end features

❌ Not looking for: Legacy maintenance without learning, working in silos, projects without real users

---

## 📫 Let's Talk

<div align="center">

**Interested in my profile?** Write me and tell me about your team and product 👇

[![Email](https://img.shields.io/badge/📧_marta.vigara.gonzalez@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:marta.vigara.gonzalez@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marta_Vigara-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/martavigara)
[![Portfolio](https://img.shields.io/badge/Portfolio-distrify.me-00D9FF?style=flat-square&logo=vercel&logoColor=white)](https://distrify.me)

---

💼 **Availability**: Immediate
📍 **Location**: Madrid (on-site/hybrid/remote)
💰 **Expectations**: Junior/Mid Full-Stack Developer

</div>

---

<div align="center">
  <i>💻 From 42 Madrid to Full-Stack Developer. Building the future, one commit at a time.</i>
  <br/><br/>
  <sub>⭐ This README is open source. If you like it, give it a star.</sub>
</div>
