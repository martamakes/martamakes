<div align="right">

[![ES](https://img.shields.io/badge/Idioma-Español-yellow.svg)](README.md)
[![EN](https://img.shields.io/badge/Language-English-red.svg)](README.en.md)

</div>

<div align="center">

# Marta Vigara

### Full-stack Product Engineer · TypeScript · React · Next.js · PostgreSQL

Construyo productos SaaS en producción de extremo a extremo: desde la definición de producto y la experiencia de usuario hasta sistemas backend, pagos, seguridad y operaciones.

Mi fortaleza es entender flujos de negocio completos, identificar puntos de fallo y cuellos de botella operativos, y convertirlos en software fiable y escalable.

**Madrid, España · Abierta a puestos remotos o híbridos de Full-stack / Product Engineering**

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Distrify.me](https://distrify.me)

</div>

---

## Proyecto destacado — Distrify.me

[Distrify.me](https://distrify.me) es un SaaS music-tech en producción que ayuda a artistas independientes a distribuir, promocionar y monetizar su música.

**Más de 150 artistas · Más de 2.000 canciones distribuidas · Producto en producción**

### Mi responsabilidad

- Diseño, desarrollo y operación del producto de extremo a extremo.
- Flujos de suscripción y créditos con Stripe, incluyendo webhooks idempotentes, lógica de reintentos y registros de auditoría.
- Flujos asistidos por IA que generan estrategias de marketing adaptadas a cada artista.
- Arquitectura basada en Next.js App Router, Server Components y experiencias de streaming.
- Controles de seguridad integrados en el ciclo de entrega, incluidos escaneos automatizados con OWASP ZAP en GitHub Actions.
- Despliegue y operaciones de producción en Vercel, con monitorización y depuración orientada a incidencias.

### Decisiones técnicas seleccionadas

| Reto | Implementación | Resultado |
|---|---|---|
| Consumo concurrente de créditos | Control de concurrencia optimista mediante actualizaciones versionadas en Prisma | Se evitó el doble consumo ante solicitudes simultáneas; sin inconsistencias de saldo registradas durante tres meses de operación en producción |
| Fiabilidad de eventos de pago | Procesamiento idempotente de webhooks de Stripe, reintentos y trazabilidad mediante registros de auditoría | Conciliación segura entre eventos de pago y estado transaccional de la base de datos |
| Seguridad antes del despliegue | Comprobaciones con OWASP ZAP en GitHub Actions; los hallazgos críticos bloquean los pull requests | Identificación y corrección de más de 15 incidencias antes de llegar a producción |
| Experiencia de producto ágil | Server Components en rutas sensibles para SEO; Client Components, actualizaciones optimistas y streaming con Suspense donde hace falta interacción | Landing pages públicas con tiempos de carga inferiores a 2 segundos |

### Stack

**TypeScript · React · Next.js · Tailwind CSS · Prisma · PostgreSQL / Neon · Redis · Stripe · Claude API · Sanity · GitHub Actions · Vercel · Cloudflare**

> El repositorio de producción contiene lógica de negocio propietaria. Puedo realizar una demostración del producto, explicar decisiones de arquitectura o compartir material de implementación anonimizado y seleccionado bajo petición.

---

## Cómo aporto valor

Empiezo por mapear el flujo real: quién realiza cada paso, qué datos se mueven entre sistemas, dónde se toman decisiones y dónde puede fallar el proceso.

Este enfoque me ha permitido:

- Evitar el consumo excesivo de créditos causado por solicitudes concurrentes mediante control de concurrencia optimista.
- Hacer recuperable el procesamiento de pagos con webhooks de Stripe idempotentes, reintentos y registros de auditoría.
- Reducir el riesgo de despliegue al integrar controles de seguridad en CI/CD en lugar de depender solo de revisiones manuales.
- Automatizar flujos operativos de marketing entre CRM, herramientas de email y reporting con n8n.
- Diseñar funcionalidades centradas en el flujo de trabajo de artistas, en lugar de construir componentes técnicos aislados.

---

## Experiencia adicional

### Sistemas de negocio y automatización

- Desarrollo de módulos personalizados de Odoo en Python para asistencia por proyectos, facturación, tesorería, contabilidad y procesos fiscales.
- Integraciones de facturación orientadas a Verifactu para requisitos de facturación en España.
- Automatizaciones con n8n para sincronización de CRM, orquestación de campañas, acciones disparadas por eventos y reporting.

**Python · Odoo · n8n · PostgreSQL · REST APIs**

### Fundamentos de ingeniería — 42 Madrid

Proyectos completados de sistemas y C++ centrados en concurrencia, redes, contenedores y despliegue. Estos proyectos reforzaron mi forma de razonar sobre ownership de recursos, aislamiento de procesos, diseño de protocolos, infraestructura y modos de fallo.

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
- Uso desarrollo asistido por IA para exploración, generación de tests y revisión, manteniendo la responsabilidad sobre arquitectura, implementación y validación.
- Valoro los trade-offs explícitos, TypeScript legible, validación automatizada, code review y el feedback de producción.
- Me interesan especialmente SaaS, music-tech, herramientas para creadores y productos con IA aplicada.

---

## Contacto

Si estás construyendo un producto en el que importen el ownership full-stack, la seguridad práctica y la experiencia en producción, estaré encantada de hablar.

[Email](mailto:marta.vigara.gonzalez@gmail.com) ·
[LinkedIn](https://linkedin.com/in/martavigara) ·
[Producto en vivo](https://distrify.me)
