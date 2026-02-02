# ¡Hola, soy Marta! 👋

**Full-Stack Developer** • **42 Madrid** • **Fundadora de distrify.me**

De estudiante de programación a construir un **SaaS con +150 artistas y +2,000 canciones distribuidas**. Especializada en **Next.js, TypeScript y arquitecturas seguras y escalables**.

🔍 **Buscando**: Primer rol como Full-Stack/Frontend Developer donde pueda aportar mi experiencia construyendo productos reales y seguir creciendo en un equipo técnico sólido.

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

Mientras construyo distrify.me, también completo proyectos de bajo nivel en 42:
- **Minishell**: Shell tipo Bash (pipes, redirects, signals)
- **Philosophers**: Sincronización con threads y mutex
- **CPP Modules**: POO y STL en C++

> 📚 [Ver todos los proyectos de 42 →](https://github.com/martamakes?tab=repositories&q=42)

---

## 🛠️ Tech Stack Completo

<div align="center">

### 💼 Experiencia Real en Producción
![Next.js](https://img.shields.io/badge/Next.js%2014-000000?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

### 🔧 Herramientas & DevOps
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)

### 📚 Fundamentos (42 Madrid)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=martamakes&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" height="170" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=martamakes&theme=radical&hide_border=true" alt="GitHub Streak" height="170" />
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

¿Te interesa mi perfil? Escríbeme y cuéntame sobre tu equipo y producto 👇

<a href="mailto:marta.vigara.gonzalez@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
</a>
<a href="https://linkedin.com/in/martavigara">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://distrify.me">
  <img src="https://img.shields.io/badge/Mi_Proyecto-00D9FF?style=for-the-badge&logo=vercel&logoColor=white" alt="Distrify" />
</a>
<a href="https://github.com/martamakes">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</a>

**Disponibilidad**: Inmediata • **Ubicación**: Madrid (presencial/híbrido/remoto)

</div>

---

<div align="center">
  <i>💻 De 42 Madrid a Full-Stack Developer. Construyendo el futuro, one commit at a time.</i>
  <br/><br/>
  <sub>⭐ Este README es código abierto. Si te gusta, dale una estrella.</sub>
</div>
