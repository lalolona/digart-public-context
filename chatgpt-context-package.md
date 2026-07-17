# DIGART — ChatGPT Public Context Package

**Paquete:** DCOS Public Context Package para ChatGPT
**Proyecto:** digart.mx / DIGART Studio
**Consumidor objetivo:** ChatGPT (rol Conductor, C-02 §9)
**Clasificación:** Público — seguro para enlace RAW de GitHub
**Versión de formato:** 1.0
**Generado:** 2026-07-17T23:05:27.097Z
**Rama de origen:** feature/navigation-v2
**Commit de origen:** 197353d

> Archivo generado automáticamente. No editar manualmente. Regenerar desde la raíz del repositorio con `npm.cmd run public-context:chatgpt --prefix dcos` en Windows o `npm run public-context:chatgpt --prefix dcos` en otros entornos.

## Mapa de actualización del paquete

- **Metadatos técnicos** (fecha, rama, commit): dinámicos, recalculados en cada generación.
- **Autoridades documentales**: derivadas automáticamente del Framework Profile vigente (`dcos/profiles/digart-framework-profile.js`).
- **Trazabilidad** ("Fuentes utilizadas y trazabilidad"): parcialmente derivada — rutas resueltas en tiempo de ejecución; secciones y notas descriptivas curadas manualmente.
- **Secciones narrativas** (Identidad, Arquitectura comercial, Arquitectura técnica, Reglas Frontend, Estado actual, Sprint/siguiente paso, Implementaciones concluidas, Reglas operativas, Restricciones): **curadas manualmente**, protegidas por huella SHA-256 de las fuentes oficiales que las respaldan. Si una fuente narrativa cambia, el generador falla (`SINTESIS_CURADA_DESALINEADA`) hasta que la síntesis se revise y la huella se apruebe de forma explícita.

**Huellas de fuentes narrativas (SHA-256, primeros 12 caracteres):**

| Fuente | Ruta | Huella |
|---|---|---|
| C-01 | `project/01-CONSTITUTION/C-01-IDENTITY.md` | `e55478e42da1` |
| C-02 | `project/01-CONSTITUTION/C-02-AI-FRAMEWORK.md` | `bbfb3fba21e0` |
| G-03 | `project/02-GOVERNANCE/G-03-METHODOLOGY.md` | `fbb0b2989234` |
| P-01 | `project/03-PRODUCT/P-01-SYSTEM-ARCHITECTURE.md` | `ef1e2b5c4465` |
| P-02 | `project/03-PRODUCT/P-02-FRONTEND.md` | `ca1df531912a` |
| O-01 | `project/04-OPERATIONS/O-01-PROJECT-SNAPSHOT.md` | `33b8c17ef6e7` |
| O-02 | `project/04-OPERATIONS/O-02-CURRENT-SPRINT.md` | `ac9a5ee20fc7` |
| O-04 | `project/04-OPERATIONS/O-04-ROADMAP.md` | `aad069b2686a` |
| O-06 | `project/04-OPERATIONS/O-06-HISTORY.md` | `dee104cea9ff` |

## Instrucciones de uso para ChatGPT

Este documento es una síntesis compacta del conocimiento vigente de digart.mx, no el corpus completo. Úsalo como marco de referencia inicial; para profundizar en cualquier punto, consulta la fuente citada en "Fuentes utilizadas y trazabilidad" bajo demanda, nunca por inferencia propia. No propongas cambios de arquitectura, alcance o autoridad a partir de este resumen: toda decisión sigue rigiéndose por la Governance del proyecto (G-01). Al emitir instrucciones hacia Claude Code (rol Implementador), incorpora siempre la Directiva de ahorro de tokens (C-02 §7).

## Identidad vigente de DIGART Studio

DIGART Studio existe para ayudar a personas y organizaciones a comunicar mejor quiénes son; su producto real es la confianza que sus entregables hacen visible, no los entregables mismos. Dieciocho Principios Fundacionales (C-01 §8, no reproducidos aquí) rigen toda decisión de producto, marca o proceso.

**Arquitectura comercial aprobada:** DIGART Studio es la marca principal, el negocio principal y el punto único de entrada del ecosistema. Clientes de Mostrador es la línea de negocio permanente y estratégica atendida directamente por DIGART Studio. DIGART Business, DIGART Medical y DIGART Food son capacidades especializadas que se activan según el proyecto; no son unidades paralelas ni de igual jerarquía.

## Arquitectura técnica vigente

Stack: HTML5, CSS3 y JavaScript Vanilla; PHP participa exclusivamente como motor de ensamblado del marcado (sin frameworks, MVC, CMS, ORMs, routing, lógica de negocio ni acceso a base de datos). Arquitectura en capas de dependencia estricta: `Foundations → Components → Patterns → Pages`. Dominio de producción `digart.mx`; dominio de desarrollo `html.digart.mx`.

## Reglas visuales / Frontend esenciales

Toda implementación consume exclusivamente Design Tokens (ninguna capa declara un valor de diseño propio). Familia tipográfica oficial única: Manrope Variable. Grid de doce columnas para contenido editorial; las secciones inmersivas de viewport completo operan fuera del Grid. Motion comunica, nunca decora: catálogo cerrado de ocho tipos, siempre accesible (reducible/suprimible sin perder el significado del estado). Accesibilidad transversal conforme a WCAG 2.2. Gobernanza de crecimiento única para Componentes, Estados, Motion, Responsive y Accesibilidad: reutilizar lo existente → extender o parametrizar → crear nuevo, sin invertir el orden.

## Autoridades documentales vigentes

Derivadas del Framework Profile operativo (`dcos/profiles/digart-framework-profile.js`), catorce dominios con autoridad única cada uno:

- **C-01** — Identidad, principios, promesa y arquitectura de marca → `project/01-CONSTITUTION/C-01-IDENTITY.md`
- **C-02** — Conducta, protocolo y adaptadores de IA → `project/01-CONSTITUTION/C-02-AI-FRAMEWORK.md`
- **G-01** — Aprobación humana, control de alcance y precedencia → `project/02-GOVERNANCE/G-01-GOVERNANCE.md`
- **G-02** — Arquitectura documental, autoridad y reconstrucción de contexto → `project/02-GOVERNANCE/G-02-DOCUMENTATION-ARCHITECTURE.md`
- **G-03** — Flujo de desarrollo, sprints, Git, despliegue y asset intake → `project/02-GOVERNANCE/G-03-METHODOLOGY.md`
- **P-01** — Stack, capas Frontend y principios arquitectónicos → `project/03-PRODUCT/P-01-SYSTEM-ARCHITECTURE.md`
- **P-02** — Sistema visual, componentes, responsive y accesibilidad → `project/03-PRODUCT/P-02-FRONTEND.md`
- **P-03** — Especificación y dirección de arte de Home → `project/03-PRODUCT/P-03-HOME.md`
- **O-01** — Estado vigente del proyecto → `project/04-OPERATIONS/O-01-PROJECT-SNAPSHOT.md`
- **O-02** — Sprint activo → `project/04-OPERATIONS/O-02-CURRENT-SPRINT.md`
- **O-03** — Ideas no autorizadas → `project/04-OPERATIONS/O-03-BACKLOG.md`
- **O-04** — Pendientes priorizados y decisiones futuras → `project/04-OPERATIONS/O-04-ROADMAP.md`
- **O-05** — Incidencias y hallazgos abiertos → `project/04-OPERATIONS/O-05-INCIDENTS.md`
- **O-06** — Decisiones oficiales e hitos históricos → `project/04-OPERATIONS/O-06-HISTORY.md`

## Estado actual del proyecto

En desarrollo. Rama Git activa de referencia: `feature/navigation-v2`. El sprint "Expansión de páginas institucionales y Especialidades v1.0" está **cerrado** (D-048): navegación v2, páginas institucionales y la capa de Especialidades (matriz, Business, Medical, Food) están implementadas localmente con recursos finales y QA transversal aprobado. Páginas activas: Home, Nosotros, Servicios, Especialidades (+ Business/Medical/Food), Portafolio, Blog, Contacto y Aviso de privacidad.

## Sprint / siguiente paso vigente

El sprint cerrado requiere autorización del propietario para iniciar el siguiente. Pendiente inmediato: desarrollar rutas individuales de Portafolio y contenido editorial de Blog cuando exista contenido aprobado. Pendientes de decisión de gobernanza (no ejecutables sin decisión oficial): incorporación normativa del remapeo Responsive RWD-08 a P-02 §16; traducciones visuales pendientes del Principio Fundacional 6 (parcial) y del Principio 12 (C-01 §11).

## Implementaciones concluidas relevantes

Navegación v2 (D-042) y Especialidades de dos niveles (D-043); Blog editorial basado en Markdown v1 (D-045); Contacto v2 con envío SMTP autenticado (D-046); Portafolio v1, refinamiento premium del Footer y formato editorial de artículos del Blog (D-047); cierre de la expansión visual de Especialidades y renovación visual de Home con recursos finales WebP (D-048).

## Reglas operativas para asistentes de IA

Principios de trabajo: Documentation First, Architecture First, Reuse Before Creation, Low Token Consumption (G-03 §3). Flujo obligatorio: `Definir → Diseñar → Aprobar → Construir → Validar → Continuar`. Git: ramas `feature/<nombre-descriptivo>`, commits en español en modo imperativo, integración a `main`/`develop` solo mediante Pull Request revisado; push y merge requieren aprobación explícita del propietario (G-03 §9). Ninguna IA modifica el corpus documental normativo sin decisión oficial (C-02 §10, G-01).

## Restricciones vigentes y límites del paquete público

- Esta síntesis no reemplaza al corpus documental de `project/` ni al Context Package interno certificado del DCOS.
- No contiene credenciales, tokens, rutas del sistema del operador ni datos personales de clientes o del equipo.
- No constituye una decisión oficial ni autoriza cambios de alcance, arquitectura o sprint.
- Su vigencia se limita al momento de generación (rama/commit indicados); para el estado más reciente, regenerar el paquete.

## Fuentes utilizadas y trazabilidad

- **C-01** (`project/01-CONSTITUTION/C-01-IDENTITY.md`, §3-4, §12) — razón de existir y arquitectura de marca (Principios Fundacionales del §8 solo referenciados, no reproducidos).
- **C-02** (`project/01-CONSTITUTION/C-02-AI-FRAMEWORK.md`, §7, §9) — directiva de ahorro de tokens y colaboración entre modelos de IA.
- **G-02** (`project/02-GOVERNANCE/G-02-DOCUMENTATION-ARCHITECTURE.md`, §3-5) — arquitectura y Mapa de Autoridad del corpus (usado para la sección Autoridades).
- **G-03** (`project/02-GOVERNANCE/G-03-METHODOLOGY.md`, §3, §9) — principios de trabajo y flujo Git.
- **P-01** (`project/03-PRODUCT/P-01-SYSTEM-ARCHITECTURE.md`, §3-4, §8) — stack, arquitectura en capas y entornos.
- **P-02** (`project/03-PRODUCT/P-02-FRONTEND.md`, §4-5, §15, §17, §19) — componentes, tokens, motion, accesibilidad y gobernanza de crecimiento.
- **O-01** (`project/04-OPERATIONS/O-01-PROJECT-SNAPSHOT.md`, Estado general, Fase actual, Estado del Frontend) — estado vigente del proyecto.
- **O-02** (`project/04-OPERATIONS/O-02-CURRENT-SPRINT.md`, Sprint, Siguiente acción) — estado y siguiente paso del sprint.
- **O-04** (`project/04-OPERATIONS/O-04-ROADMAP.md`, Pendientes inmediatos, Pendientes de decisión de gobernanza) — cola priorizada de pendientes.
- **O-06** (`project/04-OPERATIONS/O-06-HISTORY.md`, 2026-07-14 a 2026-07-17 (D-042 a D-048)) — decisiones oficiales recientes.

---

Este paquete es un producto temporal del DCOS (docs/package/DCOS-CONTEXT-PACKAGE-v1.0.md §8); no sustituye al conocimiento del proyecto ni se convierte en autoridad.
