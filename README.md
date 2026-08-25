<div align="right">

[![ES](https://img.shields.io/badge/Idioma-Español-yellow.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-red.svg)](README.en.md)

</div>

<div align="center">

# Marta Vigara

### Full-stack Product Engineer · SaaS 0→1 · TypeScript · React · Next.js

Construyo productos SaaS desde la definición del problema hasta la operación en producción: discovery, MVP, experiencia de usuario, backend, pagos, seguridad, automatización y mejora continua.

Combino ingeniería full-stack con experiencia en desarrollo de producto, marketing, operaciones y gestión de clientes. Entiendo cómo se vende, se usa y se mantiene un producto, y lo traduzco en software fiable que resuelve flujos de negocio reales.

**Madrid, España · Abierta a puestos remotos o híbridos de Full-stack / Product Engineering**

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Producto en producción: Distrify.me](https://distrify.me)

</div>

---

## Qué busco

Me interesan equipos que construyan SaaS, plataformas, herramientas internas, productos para creadores o IA aplicada; especialmente contextos en los que pueda aportar ownership full-stack, criterio de producto y experiencia operativa.

Busco oportunidades como **Product Engineer**, **Full-stack Engineer**, **Founding Engineer** o **Technical Product Builder**, especialmente en equipos 0→1 o productos que ya estén iterando con usuarios reales.

---

## Proyecto destacado — Distrify.me

[Distrify.me](https://distrify.me) es un SaaS music-tech en producción que ayuda a artistas independientes a distribuir, promocionar y monetizar su música.

- Más de 150 artistas.
- Más de 2.000 canciones distribuidas.
- Producto diseñado, construido y operado de extremo a extremo.
- Pagos, créditos, automatización, IA aplicada a marketing y operaciones de producto.

Mi papel combina discovery de producto, definición de MVP, diseño de flujos de usuario y operaciones, arquitectura full-stack, seguridad, despliegue y soporte de producción.

### Mi responsabilidad

- Investigación de necesidades, definición de producto, priorización de MVPs y diseño de flujos para artistas y operaciones internas.
- Diseño, desarrollo y operación del producto de extremo a extremo.
- Flujos de suscripción y créditos con Stripe, incluyendo webhooks idempotentes, lógica de reintentos y registros de auditoría.
- Flujos asistidos por IA que generan estrategias de marketing adaptadas a cada artista.
- Arquitectura basada en Next.js App Router, Server Components y experiencias de streaming.
- Controles de seguridad integrados en el ciclo de entrega, incluidos escaneos automatizados con OWASP ZAP en GitHub Actions.
- Despliegue y operaciones de producción en Vercel, con monitorización y depuración orientada a incidencias.

### Decisiones técnicas seleccionadas

| Reto | Implementación | Impacto |
|---|---|---|
| Consumo concurrente de créditos | Control de concurrencia optimista mediante actualizaciones versionadas en Prisma | Evita el doble consumo ante solicitudes simultáneas y protege la consistencia del saldo |
| Fiabilidad de eventos de pago | Procesamiento idempotente de webhooks de Stripe, reintentos y trazabilidad con registros de auditoría | Conciliación recuperable entre eventos externos y el estado transaccional de la base de datos |
| Seguridad antes del despliegue | Comprobaciones con OWASP ZAP en GitHub Actions; los hallazgos críticos bloquean los pull requests | Identificación y corrección de más de 15 incidencias antes de producción |
| Experiencia de producto ágil | Server Components en rutas sensibles para SEO; Client Components, actualizaciones optimistas y streaming con Suspense donde hace falta interacción | Rutas públicas optimizadas para SEO y una experiencia de uso más fluida en flujos interactivos |

### Stack

**TypeScript · React · Next.js · Tailwind CSS · Prisma · PostgreSQL / Neon · Redis · Stripe · Claude API · Sanity · GitHub Actions · Vercel · Cloudflare**

> El repositorio de producción contiene lógica de negocio propietaria. Puedo realizar una demostración del producto, explicar decisiones de arquitectura o compartir material de implementación anonimizado y seleccionado bajo petición.

---

## De problema de negocio a producto en producción

Mi experiencia previa en producto, marketing, operaciones y gestión de clientes me permite participar antes de que exista una especificación técnica: entiendo el problema, identifico restricciones reales y convierto el flujo en un MVP medible y evolutivo.

- **Productos 0→1 y MVPs:** defino alcance, hipótesis, flujos críticos y una primera versión que permita aprender sin sobredimensionar la solución.
- **Producto operable:** diseño pensando en excepciones, soporte, conciliación, permisos, auditoría y trabajo diario del equipo, no solo en el happy path.
- **Ciclo completo:** puedo asumir discovery, implementación full-stack, despliegue, análisis de uso e iteración posterior con usuarios.
- **Automatización de negocio:** conecto CRM, email, pagos, facturación, reporting y herramientas internas para reducir trabajo manual y errores.

Este enfoque me ha permitido:

- Evitar el consumo excesivo de créditos ante solicitudes concurrentes mediante control de concurrencia optimista.
- Hacer recuperable el procesamiento de pagos con webhooks idempotentes de Stripe, reintentos y registros de auditoría.
- Reducir riesgo de despliegue al integrar controles de seguridad en CI/CD, en lugar de depender solo de revisiones manuales.
- Automatizar flujos operativos de marketing entre CRM, herramientas de email y reporting con n8n.
- Diseñar funcionalidades alrededor del flujo de trabajo real de artistas, no como componentes técnicos aislados.

---

## Experiencia adicional

### Sistemas de negocio y automatización

- Desarrollo de módulos personalizados de Odoo en Python para asistencia por proyectos, facturación, tesorería, contabilidad y procesos fiscales.
- Integraciones de facturación orientadas a Verifactu para requisitos de facturación en España.
- Automatizaciones con n8n para sincronización de CRM, orquestación de campañas, acciones disparadas por eventos y reporting.
- Diseño de procesos y herramientas internas con foco en reducir tareas manuales, mejorar trazabilidad y facilitar la operación diaria.

**Python · Odoo · n8n · PostgreSQL · REST APIs**

### Fundamentos de ingeniería — 42 Madrid

Proyectos completados de sistemas y C++ centrados en concurrencia, redes, contenedores y despliegue. Han reforzado mi forma de razonar sobre ownership de recursos, aislamiento de procesos, diseño de protocolos, infraestructura y modos de fallo.

| Proyecto | Áreas principales |
|---|---|
| Minishell | Procesos Unix, descriptores de archivo, pipes, señales y system calls |
| Philosophers | Hilos, mutexes, sincronización y prevención de race conditions |
| CPP Modules | Diseño orientado a objetos, STL, templates, gestión de memoria y forma canónica |
| ft_irc | Redes TCP, protocolo IRC, arquitectura cliente/servidor y E/S dirigida por eventos |
| Inception | Docker, Docker Compose, NGINX, WordPress, MariaDB, redes y aislamiento de servicios |

[Ver mis proyectos de 42 →](https://github.com/martamakes?tab=repositories&q=42)

---

## Forma de trabajar

- Asumo ownership desde la definición del problema hasta la implementación, el despliegue y la iteración.
- Trabajo con usuarios, equipos y datos operativos para decidir qué construir antes de convertirlo en una solución técnica.
- Uso desarrollo asistido por IA para exploración, generación de tests y revisión, manteniendo la responsabilidad sobre arquitectura, implementación y validación.
- Valoro los trade-offs explícitos, TypeScript legible, validación automatizada, code review y feedback de producción.
- Me interesan especialmente SaaS, music-tech, herramientas para creadores y productos con IA aplicada.

---

## Contacto

Si estás construyendo un producto en el que importen el ownership full-stack, el criterio de producto, la seguridad práctica y la experiencia en producción, estaré encantada de hablar.

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Producto en producción: Distrify.me](https://distrify.me)
