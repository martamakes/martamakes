<div align="right">

[![es](https://img.shields.io/badge/lang-es-yellow.svg)](README.md)
[![en](https://img.shields.io/badge/lang-en-red.svg)](README.en.md)

</div>

<div align="center">

# ¡Hola, soy Marta! 👋

### Full-Stack Developer | IA-Powered Development | 42 Madrid


De estudiante de programación a construir un **SaaS con +150 artistas y +2,000 canciones distribuidas**

Especializada en **Next.js • TypeScript • Arquitecturas Seguras y Escalables**

---

[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:marta.vigara.gonzalez@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/martavigara)
[![Distrify](https://img.shields.io/badge/Mi_Proyecto-00D9FF?style=flat-square&logo=vercel&logoColor=white)](https://distrify.me)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/martamakes)

🔍 **Buscando**: Primer rol Full-Stack/Frontend Developer • Madrid (presencial/híbrido/remoto)

</div>

---

## 🚀 Mi Proyecto: Distrify.me

**SaaS en producción** que ayuda a artistas independientes a monetizar su música mediante marketing digital y análisis de datos.

**+150 artistas** • **+2,000 canciones distribuidas** • **En crecimiento activo**

> 🔗 **[Ver en vivo](https://distrify.me)** • 📧 **[Demo/Código bajo NDA](mailto:marta.vigara.gonzalez@gmail.com)**

### 📊 Impacto

- 🎯 **+150 artistas** usando la plataforma activamente
- 🎵 **+2,000 canciones** distribuidas a través de distrify
- ⚡ **99.9% uptime** en producción (Vercel)
- 📈 **~13 canciones por artista** en promedio
- 🤖 **Sistema de IA** generando estrategias de marketing personalizadas

### 🛠️ Stack & Arquitectura

```
Frontend:    Next.js 14 (App Router) • React • TypeScript • Tailwind CSS
Backend:     Next.js API Routes • Prisma ORM • PostgreSQL (Neon)
Auth/Pagos:  NextAuth • Stripe (webhooks, subscriptions)
AI:          Claude API (Haiku + Sonnet 4.5) • Claude Code • Prompt engineering
CMS:         Sanity (headless)
Security:    OWASP ZAP • Cloudflare Turnstile • Rate limiting (Redis)
DevOps:      GitHub Actions • Vercel • Monitoring
```

### 💡 Retos Técnicos Que Resolví

**1. Race Conditions en Transacciones 🔒**
- **Problema**: Usuarios podían consumir más créditos de los disponibles con requests concurrentes
- **Solución**: Implementé optimistic locking con versionado en Prisma
- **Resultado**: 0 inconsistencias de balance en 3 meses de producción

**2. CI/CD con Testing de Seguridad Automático 🛡️**
- **Problema**: Detectar vulnerabilidades antes de producción
- **Solución**: Pipeline de GitHub Actions con OWASP ZAP que bloquea PRs con issues críticos
- **Resultado**: 15+ vulnerabilidades detectadas y corregidas antes de deployment

**3. Integración Multi-API Compleja 🔌**
- **Problema**: Sincronizar Stripe webhooks, Claude API y base de datos transaccional
- **Solución**: Sistema de webhooks idempotentes con retry logic y audit logs
- **Resultado**: 100% de webhooks procesados correctamente

**4. Arquitectura Escalable desde Día 1 📈**
- **Diseño**: Next.js App Router con Server Components para SEO + Client Components para interactividad
- **Performance**: Optimistic updates, streaming responses, React Suspense
- **Resultado**: < 2s tiempo de carga en landing pages

**5. Desarrollo Asistido por IA con Claude Code 🤖**
- **Enfoque**: Uso intensivo de Claude Code para acelerar desarrollo
- **Técnicas**: Creación de subagentes especializados (Plan, Explore, Security, Testing)
- **Workflow**: Draft → Critic → Refinement para contenido generado con IA
- **Resultado**: 3x velocidad de desarrollo + código más seguro (detección de race conditions con IA)

---

## 💼 Experiencia Adicional

### Desarrollo en Odoo (ERP/Python)

Implementación de módulos personalizados para gestión empresarial:

- 📊 **Gestión de asistencia por proyectos** - Control de trabajadores remotos
- 💰 **Sistema de facturación completo** - Facturas, cobros y pagos
- 🏦 **Tesorería y contabilidad** - Gestión de flujos de caja
- 📑 **Gestión fiscal** - Automatización de impuestos
- 🔗 **Integración con Verifactu** - Cumplimiento normativa española de facturación

### Automatizaciones con n8n

Workflows automatizados para sistemas de marketing:

- 🤖 Automatización de campañas de email marketing
- 🔄 Sincronización entre CRM y herramientas de marketing
- 📈 Reportes automáticos y notificaciones
- 🎯 Segmentación y triggering de acciones basadas en eventos

**Stack**: Python • Odoo • n8n • PostgreSQL • REST APIs

---

## 💪 Lo Que Puedo Aportar

| Skill | Nivel | Evidencia |
|-------|-------|-----------|
| **Ship rápido** | ⭐⭐⭐⭐⭐ | De idea a MVP en 6 semanas, a producción en 3 meses |
| **Security-first** | ⭐⭐⭐⭐ | OWASP ZAP, optimistic locking, secure webhooks |
| **Problem solver** | ⭐⭐⭐⭐⭐ | Debug full-stack: PostgreSQL → API → React |
| **Fast learner** | ⭐⭐⭐⭐⭐ | Aprendí Next.js 14, Prisma y Stripe construyendo distrify |
| **IA-powered dev** | ⭐⭐⭐⭐⭐ | Claude Code + subagentes = 3x productividad |
| **Autodidacta** | ⭐⭐⭐⭐⭐ | Método peer-to-peer de 42 = aprender haciendo |
| **Code quality** | ⭐⭐⭐⭐ | TypeScript strict, Zod validation, tests automatizados |

---

## 🤖 IA & Claude Code - Mi Superpoder

Soy **early adopter** de desarrollo asistido por IA. No solo uso IA, la integro en mi workflow diario:

### 🎯 Cómo Uso Claude Code

**Subagentes Especializados**
- 🔍 **Explore Agent**: Análisis de codebase y arquitectura
- 📋 **Plan Agent**: Diseño de implementaciones complejas
- 🔒 **Security Agent**: Detección proactiva de vulnerabilidades
- ✅ **Test Agent**: Generación de tests automatizados

**Workflow de Desarrollo**
```
Idea → Plan (IA) → Code Review (IA + humano) → Security Scan (IA) → Deploy
```

**Resultados Medibles**
- ⚡ **3x más rápido** en implementaciones complejas
- 🔒 **Race condition detectada** por IA antes de código en producción
- 📚 **Mejor documentación** generada automáticamente
- 🎯 **Menos bugs** gracias a code review asistido

**Mi Filosofía**
> "La IA no reemplaza al developer, multiplica su impacto. Un buen developer con IA > 3 developers sin IA."

---

## 💻 Formación: 42 Madrid

**Peer-to-peer learning** • C, C++, Algoritmos, Sistemas

<div align="center">

| Proyecto | Skills | Status |
|----------|--------|--------|
| **Minishell** | System calls, Process management | ✅ |
| **Philosophers** | Threads, Mutex, Concurrency | ✅ |
| **CPP Modules** | POO, STL, Templates | ✅ |

[📚 Ver todos los proyectos de 42 →](https://github.com/martamakes?tab=repositories&q=42)

</div>

---

## 🛠️ Tech Stack Completo

<div align="center">

### 💼 Experiencia Real en Producción

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Odoo](https://img.shields.io/badge/Odoo-714B67?style=flat-square&logo=odoo&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

### 🤖 IA & Herramientas

![Claude](https://img.shields.io/badge/Claude_API-8A2BE2?style=flat-square&logo=anthropic&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=flat-square&logo=stripe&logoColor=white)

### 📚 Fundamentos

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## 📊 En Números

<div align="center">

| Métrica | Valor |
|---------|-------|
| 🎯 **Artistas en producción** | +150 |
| 🎵 **Canciones distribuidas** | +2,000 |
| ⚡ **Uptime en producción** | 99.9% |
| 🚀 **Velocidad con IA** | 3x más rápido |
| 📦 **Proyectos en GitHub** | [Ver repos →](https://github.com/martamakes?tab=repositories) |

</div>

---

## 🎯 Qué Busco en mi Próximo Rol

✅ **Equipo técnico sólido** donde pueda aprender de seniors
✅ **Stack moderno** (React/Next.js, TypeScript, arquitectura bien diseñada)
✅ **Code reviews activas** y cultura de calidad
✅ **Producto real** que resuelva problemas reales
✅ **Ownership** de features end-to-end

❌ No busco: Mantener legacy sin aprendizaje, trabajar en silos, proyectos sin usuarios reales

---

## 📫 Hablemos

<div align="center">

**¿Te interesa mi perfil?** Escríbeme y cuéntame sobre tu equipo y producto 👇

[![Email](https://img.shields.io/badge/📧_marta.vigara.gonzalez@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:marta.vigara.gonzalez@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Marta_Vigara-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/martavigara)
[![Portfolio](https://img.shields.io/badge/Portfolio-distrify.me-00D9FF?style=flat-square&logo=vercel&logoColor=white)](https://distrify.me)

---

💼 **Disponibilidad**: Inmediata
📍 **Ubicación**: Madrid (presencial/híbrido/remoto)
💰 **Expectativas**: Junior/Mid Full-Stack Developer

</div>

---

<div align="center">
  <i>💻 De 42 Madrid a Full-Stack Developer. Construyendo el futuro, one commit at a time.</i>
  <br/><br/>
  <sub>⭐ Este README es código abierto. Si te gusta, dale una estrella.</sub>
</div>
