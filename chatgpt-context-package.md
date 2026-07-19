# DIGART — ChatGPT Public Context Package

**Paquete:** DCOS Public Context Package para ChatGPT
**Proyecto:** digart.mx / DIGART Studio
**Consumidor objetivo:** ChatGPT (rol Conductor, C-02 §9)
**Clasificación:** Público — seguro para enlace RAW de GitHub
**Versión de formato:** 1.0
**Generado:** 2026-07-19T13:21:15.000Z
**Rama de origen:** feature/navigation-v2
**Commit de origen:** f8c45451d2fba66d8e408d9a17e9a09b9ed2913a

> Archivo generado automáticamente. No editar manualmente. Regenerar desde la raíz del repositorio con `npm.cmd run public-context:chatgpt --prefix dcos` en Windows o `npm run public-context:chatgpt --prefix dcos` en otros entornos.

## Mapa de actualización del paquete

- **Metadatos técnicos** (fecha, rama, commit): dinámicos, recalculados en cada generación.
- **Autoridades documentales**: derivadas automáticamente del Framework Profile vigente (`dcos/profiles/digart-framework-profile.js`).
- **Trazabilidad** ("Fuentes utilizadas y trazabilidad"): parcialmente derivada — rutas resueltas en tiempo de ejecución; secciones y notas descriptivas curadas manualmente.
- **Secciones narrativas curadas** (Identidad, Arquitectura comercial, Arquitectura técnica, Reglas Frontend, Reglas operativas, Restricciones): **curadas manualmente**, protegidas por huella SHA-256 de las fuentes oficiales que las respaldan. Si una fuente narrativa cambia, el generador falla (`SINTESIS_CURADA_DESALINEADA`) hasta que la síntesis se revise y la huella se apruebe de forma explícita.
- **Secciones de estado operativo** (Estado actual, Sprint/siguiente paso, Implementaciones concluidas): **derivadas automáticamente** en cada generación desde O-01 a O-06 (`dcos/closure/operational-state-resolver.js`, D-050), nunca literales fijados en este módulo. Un elemento resuelto no se presenta como pendiente, una decisión sustituida no se presenta como vigente y toda contradicción entre autoridades detiene la generación.

**Huellas de fuentes narrativas (SHA-256, primeros 12 caracteres):**

| Fuente | Ruta | Huella |
|---|---|---|
| C-01 | `project/01-CONSTITUTION/C-01-IDENTITY.md` | `5117749fcbc1` |
| C-02 | `project/01-CONSTITUTION/C-02-AI-FRAMEWORK.md` | `bbfb3fba21e0` |
| G-03 | `project/02-GOVERNANCE/G-03-METHODOLOGY.md` | `c4c7e42a78d8` |
| P-01 | `project/03-PRODUCT/P-01-SYSTEM-ARCHITECTURE.md` | `ef1e2b5c4465` |
| P-02 | `project/03-PRODUCT/P-02-FRONTEND.md` | `f9958c34d0c0` |

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

En desarrollo. Sitio Web Corporativo digart.mx. Rama Git activa: `feature/navigation-v2`. La navegación v2, las páginas institucionales, Especialidades y el Blog Editorial v2 están implementados localmente. El sprint del Blog Editorial v2 queda cerrado con validación técnica (60/60 pruebas) y visual Desktop/Mobile aprobada.

El sprint "Blog Editorial v2" está **cerrado** (O-02).

## Sprint / siguiente paso vigente

Sprint cerrado. Requiere autorización del propietario para iniciar el siguiente sprint.

**Pendientes priorizados vigentes (O-04):**

- Desarrollar rutas individuales de Portafolio cuando exista alcance y contenido aprobados.

## Implementaciones concluidas relevantes

- **D-043** — Arquitectura de Especialidades de dos niveles aprobada — **D-043**. `/especialidades.php` se establece como página matriz de soluciones por industria y se aprueban las rutas `/digart-business.php`, `/digart-medical.php` y `/digart-food.php`. Cada ruta profundi…
- **D-044** — DCOS Framework Profile se alinea con el Mapa de Autoridad oficial de G-02 §5 — **D-044**. El perfil deja de usar autoridades heredadas y declara exclusivamente las catorce autoridades canónicas del corpus vigente.
- **D-045** — Se aprueba Blog editorial basado en Markdown v1 — **D-045**: publicaciones administradas como archivos versionados en `content/blog/`, índice automático (`public/blog.php`) y una plantilla reutilizable de artículo (`public/articulo.php`); sin base de datos ni …
- **D-046** — Se aprueba Contacto v2 — **D-046**: formulario de proyecto con envío SMTP autenticado, sin base de datos, configuración de credenciales fuera de Git y controles mínimos de seguridad y privacidad. Implementados localmente el rediseño de `public/contacto.php` (H…
- **D-047** — Se aprueba Portafolio v1 — **D-047**: vitrina editorial de seis casos reales, implementada localmente en `public/portafolio.php` mediante los Patterns `portfolio-hero`, `portfolio-introduction`, `portfolio-grid` y `portfolio-closing`. Se integran los seis recu…
- **D-048** — Se aprueba el cierre de la expansión visual de Especialidades y la renovación visual del Home — **D-048**. Las páginas DIGART Business, DIGART Medical y DIGART Food integran sus recursos finales WebP; la Home incorpora recursos finales WebP para Hero, El inici…
- **D-049** — Se aprueba la incorporación normativa del remapeo Responsive RWD-08 y la revisión formal de C-01 — **D-049**. La decisión aprueba conjuntamente: (a) la incorporación de la norma de remapeo de spans a P-02 §16 ("en Tablet y Mobile, toda utilidad de columna basa…
- **D-050** — Adopción del cierre certificado de DCOS — **D-050**. La decisión sustituye, para todo sprint o implementación que actualice el estado público, el cierre desacoplado de D-035 por una sola operación controlada que integra QA, SGD, SSD, validación semántica de O-…

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
- **O-01** (`project/04-OPERATIONS/O-01-PROJECT-SNAPSHOT.md`, Estado general, Sprint vigente) — estado vigente del proyecto (derivado, D-050).
- **O-02** (`project/04-OPERATIONS/O-02-CURRENT-SPRINT.md`, Sprint, Siguiente acción) — estado y siguiente paso del sprint (derivado, D-050).
- **O-04** (`project/04-OPERATIONS/O-04-ROADMAP.md`, Pendientes inmediatos, Pendientes de decisión de gobernanza) — cola priorizada de pendientes (derivado, D-050).
- **O-06** (`project/04-OPERATIONS/O-06-HISTORY.md`, Decisiones e historia) — decisiones oficiales e hitos recientes (derivado, D-050).

---

Este paquete es un producto temporal del DCOS (docs/package/DCOS-CONTEXT-PACKAGE-v1.0.md §8); no sustituye al conocimiento del proyecto ni se convierte en autoridad.
