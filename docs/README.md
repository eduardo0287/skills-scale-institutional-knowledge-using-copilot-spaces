# OctoAcme — Documentación de Gestión de Proyectos

Este conjunto de documentos centraliza las prácticas de gestión de proyectos usadas por OctoAcme. Aquí encontrarás un resumen de alto nivel y enlaces rápidos a cada guía de proceso en la carpeta docs/.

## Resumen
OctoAcme sigue un enfoque iterativo y centrado en el cliente con roles claramente definidos y artefactos que facilitan la toma de decisiones. La fase de iniciación utiliza un One‑pager para validar la necesidad y definir métricas de éxito; tras la autorización se crea un plan más detallado en la fase de planificación (kickoff, backlog priorizado, estimaciones y Definition of Done). La ejecución se organiza en sprints/milestones con un tablero de trabajo que mantiene la trazabilidad desde el backlog hasta la entrega.

## Flujos de trabajo clave y control de calidad
Se fomenta trabajo en pequeños incrementos y PRs disciplinados (PRs pequeños, enlace al issue, criterios de aceptación, CI pasando antes de solicitar revisión). Las releases siguen un checklist (staging, smoke tests, notas de release y plan de rollback) y hay un playbook para incidentes. En términos de calidad, OctoAcme requiere pruebas unitarias e integración cuando proceda, smoke/end‑to‑end en caminos críticos, escaneo de seguridad en CI y QA manual cuando sea necesario. Las métricas (velocity, burndown, dashboards) se usan para monitorizar progreso y resultados.

## Comunicación y roles
La comunicación se estructura con ritmos regulares: standups diarios cortos, sincronización semanal de entrega, demos/reviews por sprint y actualizaciones mensuales a stakeholders. El registro de riesgos y las plantillas de estado estandarizan los informes. Los roles principales son Product Manager (visión y métricas), Project Manager (coordinación, planificación y riesgos), desarrolladores (implementación y pruebas), QA/testing (validación) y stakeholders (aprobaciones y prioridades). Las dependencias y riesgos se registran y se escalan por niveles definidos.

## Enlaces rápidos
- docs/octoacme-project-management-overview.md
- docs/octoacme-project-initiation.md
- docs/octoacme-project-planning.md
- docs/octoacme-execution-and-tracking.md
- docs/octoacme-risks-and-communication.md
- docs/octoacme-release-and-deployment.md
- docs/octoacme-retrospective-and-continuous-improvement.md
- docs/octoacme-roles-and-personas.md

## Cómo usar
Coloca este README en la carpeta docs/ como punto de entrada para el equipo. Mantén los enlaces actualizados cuando los documentos cambien y usa este README para orientar a nuevos miembros y alinear revisiones de procesos.
