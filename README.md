## Hola, soy Nico 👋

**Desarrollador de software junior (backend / full stack)**: Java · Python/Django · React · Oracle SQL
📍 Sevilla, España · Híbrido en Sevilla o remoto (UE) · Inglés C1 · Incorporación inmediata

- 🎓 Graduado en **Ingeniería del Software** por la Universidad de Sevilla. TFG *BarGAIN*, calificado con **9,1**.
- 💼 **NTT DATA** (prácticas, mayo–octubre 2026): mantenimiento de **SIGLO**, el sistema de gestión logística del Servicio Andaluz de Salud. Más de 300 incidencias resueltas (Java, Oracle SQL, PL/SQL), más de 10 informes automatizados con JasperReports y un **servidor MCP en Python** que permite a un agente de IA consultar Oracle de forma segura, adoptado por el equipo.
- 🤖 Desarrollo con agentes de IA (Claude Code, Codex, Gemini, Copilot) dentro de un proceso de ingeniería: planificación por fases, ADRs, tests y CI.

### 🧭 Cómo trabajo con IA: flujo GSD

Desarrollo con agentes de IA siguiendo [GSD](https://github.com/open-gsd/gsd-core), un framework open source de desarrollo guiado por especificaciones (*spec-driven development*) y *context engineering*. Yo defino el alcance y los criterios de aceptación; los agentes ejecutan; y nada se da por terminado sin verificarlo.

**Discutir → Planificar → Ejecutar → Verificar → Entregar**

- Cada fase deja un artefacto versionado (`CONTEXT`, `PLAN`, `SUMMARY`, `VERIFICATION`, `UAT`) que es la fuente de verdad del siguiente paso, así que la especificación sobrevive entre sesiones y el proceso es auditable.
- Planificar, implementar y verificar se hacen en contextos separados: la revisión no hereda la confianza del código recién escrito.
- Lo he aplicado de principio a fin en **BarGAIN** (12 fases y 38 planes en [`.planning/`](https://github.com/Nicoparri/bargain-tfg/tree/main/.planning)) y en **FinanzaSQLite** (hito v1.0 en 4 fases con auditoría de requisitos).

### Proyectos destacados

| Proyecto | Qué es | Mi papel | Stack |
|---|---|---|---|
| [**BarGAIN**](https://github.com/Nicoparri/bargain-tfg) · [web](https://nicoparri.github.io/bargain-tfg/) | Compra inteligente: calcula la mejor combinación de supermercados según precio, distancia y tiempo. Más de 490 tests y CI/CD | En solitario (TFG, 9,1) | Django REST · PostGIS · React Native · OR-Tools · OCR · LLM |
| [**NutriSur**](https://github.com/Lyoko-CO/nutrisur) | Web para un cliente real (Natursur): tienda y citas con asistentes de IA para usuarios poco digitales | Analista, desarrollador y tester (equipo de 4) | Django · PostgreSQL · Gemini · GitHub Actions |
| [**AURA**](https://github.com/G4-AURA/AURA) | Copiloto para guías turísticos: rutas generadas con IA y sesiones en directo con mapa | Desarrollador (equipo de 13) | Django · PostGIS · LangGraph · Celery · Google Cloud |
| [**FinanzaSQLite**](https://github.com/Nicoparri/FinanzaSQLite) | App móvil de finanzas personales offline-first con transacciones y triggers en SQLite. 77 tests | En solitario | React Native · Expo · SQLite · TypeScript |

### Stack

`Java` `Spring Boot` `Python` `Django` `DRF` `TypeScript` `React` `React Native` `Oracle` `PL/SQL` `PostgreSQL` `PostGIS` `Docker` `GitHub Actions` `Git` `Jira` `Scrum` `GSD` `Claude Code` `Spec-driven development`

### Contacto

[LinkedIn](https://www.linkedin.com/in/nicpargen)

---

🇬🇧 *Junior backend / full-stack developer based in Seville, Spain (English C1, Cambridge). Software Engineering graduate (final-year project graded 9.1) with 6 months at NTT DATA on a public-health logistics system (Java, Oracle, PL/SQL). I build with AI coding agents through GSD, a spec-driven workflow: I set scope and acceptance criteria, agents execute, and every phase is verified before it ships. Open to hybrid roles in Seville or remote for EU companies.*
