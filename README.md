# Ignacio Barboza Espinoza

Estudiante de **Ingeniería en Tecnologías de la Información y Comunicaciones** — TecNM, Instituto
Tecnológico Superior de Zamora, Michoacán.

Construyo software con agentes de código y **desarrollo guiado por especificación**: la
especificación y los criterios de aceptación se escriben antes que el código, y un cambio no se
cierra sin evidencia. Me interesa la parte de ingeniería de la IA — integrarla, acotarla y hacerla
verificable — más que el modelo en sí.

**Disponible para residencia profesional: agosto – diciembre 2026.** Presencial en Michoacán o remoto.

---

## Proyectos

### [PlanearIA](https://github.com/RitualBoat/PlanearIA) — Suite docente offline-first con IA
Aplicación para profesores en México: planeaciones, clases, seguimiento y comunicación sin salir de
la app y sin depender de la conexión. Desarrollador único.

`React Native` `Expo SDK 54` `TypeScript` `Node.js serverless` `MongoDB Atlas` `Jest` `Playwright` `GitHub Actions`

| | |
|---|---|
| Líneas de TypeScript | 101,231 |
| Pruebas automatizadas | 902 en 132 archivos |
| Pull requests integrados | 51 |
| Especificaciones archivadas con evidencia | 48 |
| Pipelines de CI que bloquean el merge | 5 |

- Toda la IA pasa por un gateway de backend con cascada de proveedores compatibles con OpenAI,
  timeouts y límite de uso por usuario: **ninguna llave de proveedor vive en el cliente**.
- Capa offline-first con cola de sincronización idempotente y aislamiento de datos por usuario,
  probada en el recorrido offline → reconexión → segundo dispositivo.

### [project-engineering-os](https://github.com/RitualBoat/project-engineering-os) — Gobernanza de repositorios como CLI · MIT
Publicado en npm como
[`create-project-engineering-os`](https://www.npmjs.com/package/create-project-engineering-os).
Prepara un repositorio nuevo con gobernanza, especificaciones, harness de agentes y control de deuda
técnica en un solo comando. Es el método que ya usaba en PlanearIA, extraído para que sea reutilizable.

- Cada modificación automática es reversible: journal, hash y comando de rollback por transacción.
- Los archivos se clasifican por propiedad (administrado / humano / del proyecto) y la ejecución se
  detiene antes de sobrescribir trabajo humano.
- Una sola fuente de reglas genera instrucciones para Claude Code, Codex, Cursor, OpenCode y GitHub Copilot.

### [Cute Seals](https://github.com/RitualBoat/Cute_Seals_BP) — Add-on de Minecraft Bedrock
Entidad personalizada con 4 variantes por bioma, 10 comportamientos de IA priorizados, 7 animaciones,
domesticación, montura anfibia y tablas de botín, sobre la Script API de Minecraft Bedrock 1.21+.
Tres versiones publicadas, empaquetadas a `.mcaddon` con un script de PowerShell.

### [Salas API](https://github.com/RitualBoat/salas-api) — REST API en FastAPI
Servicio para administrar salas, mantenimientos, actividades y materiales de un campus, con
validación de esquema en base de datos y documentación OpenAPI automática. Proyecto académico de
Arquitectura de Servicios.

---

## Cómo trabajo

- **Especificación antes que código.** Criterios de aceptación observables, y un cambio no se archiva
  sin evidencia que lo respalde.
- **Agentes con herramientas propias.** Skills, reglas y subagentes configurados y versionados en el
  repositorio, no prompts sueltos.
- **Contexto recuperado, no adivinado.** RAG sobre el propio código mediante servidores MCP, para que
  el agente responda sobre el repositorio real.
- **CI que bloquea.** Typecheck, lint, pruebas, backend y QA visual por breakpoint; si algo falla, no
  entra.
- **Deuda técnica gobernada.** Los hallazgos se verifican y clasifican antes de convertirse en deuda;
  un warning sin verificar no autoriza un cambio.

## Stack

**Lenguajes:** TypeScript · JavaScript · Python · SQL
**Móvil y web:** React Native · Expo · React Navigation
**Backend y datos:** Node.js serverless · FastAPI · MongoDB · MySQL · JWT con sesiones de refresco
**IA aplicada:** integración de LLMs vía gateway propio · RAG sobre código con MCP · Claude Code · Ollama
**Calidad y DevOps:** Jest · Playwright · GitHub Actions · Vercel · Git

## Certificaciones

Cisco **CCNA 1** y **CCNA 2** completados · **CCNA 3** (Enterprise Networking, Security and
Automation) en curso.

## Contacto

itic_ibarboza@accitesz.com · Zamora, Michoacán, México

<details>
<summary>English</summary>

<br>

**ICT Engineering student** at TecNM, Instituto Tecnológico Superior de Zamora, Mexico.

I build software with coding agents and **spec-driven development**: specifications and acceptance
criteria come before the code, and no change closes without evidence. My interest is the engineering
side of AI — integrating it, bounding it and making it verifiable — more than the model itself.

**Available for a 500-hour engineering internship: August – December 2026.** On-site in Michoacán or remote.

- **[PlanearIA](https://github.com/RitualBoat/PlanearIA)** — Offline-first teaching suite. Sole
  developer. 101,231 lines of TypeScript, 902 automated tests, 51 merged pull requests, 5 blocking CI
  pipelines. All AI calls routed through a backend gateway with an OpenAI-compatible provider
  cascade — zero provider keys in the client.
- **[project-engineering-os](https://github.com/RitualBoat/project-engineering-os)** — Repository
  governance CLI, published on npm under MIT. Every automated change is reversible through a
  per-transaction journal, hash and rollback command.
- **[Cute Seals](https://github.com/RitualBoat/Cute_Seals_BP)** — Minecraft Bedrock add-on: custom
  entity with 4 biome variants, 10 prioritized AI behaviors and 7 animations. 3 published releases.
- **[Salas API](https://github.com/RitualBoat/salas-api)** — FastAPI + MongoDB
  REST service with database-level schema validation and auto-generated OpenAPI docs.

</details>
