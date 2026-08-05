# Plan de estudio — Ofertas de trabajo vs perfil real

Perfil real de referencia: estudiante de software multiplataforma (09/24–08/26), educación dual (08/23–08/24), mecatrónica (08/21–07/24). Stack real: Python, OpenCV, TypeScript, Node.js, Bun, Astro, React, Tailwind, GitHub Actions, Cloudflare, Zod, AWS (cert. practitioner), Claude Code. ~2–3 años de experiencia práctica acumulada.

---

## Resumen oferta vs CV

### ✅ Aplica (fit alto, defendible con experiencia real)

| Oferta                                       | Por qué                                                                                                                                                                                                                              |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **AI Developer — Balsam Brands**             | El rol pide Claude/ChatGPT, React/JS, AI tooling e internal tooling: es literalmente lo que hace a diario. Solo OpenAI API es aspiracional.                                                                                          |
| **AI-Native Software Developer (Jobgether)** | "Ruby on Rails u otros lenguajes backend" → Node.js/Python/TS califican. El core del rol (usar IA como sistema de desarrollo con workflows y validación) es su día a día con Claude Code. Gap: SQL.                                  |
| **Product Engineer (Jobgether)**             | MVPs desplegados y usados, frontend fuerte, integraciones de APIs, iterar con feedback: todo real. Lo de "health data" es un plus, no requisito.                                                                                     |
| **Software Verification & QA Specialist**    | Python, Node, Git, CI/CD, AWS, HTML/CSS/JS: todo real. Gap menor: MongoDB/SQL/MySQL y práctica formal de QA.                                                                                                                         |
| **Open Source Contributor**                  | GitHub con proyectos propios + contribución real a midudev/autoskills; TypeScript/Python en la lista de lenguajes. "Large-scale distributed codebases" es solo preferido. Contrato flexible 10–40 hrs/semana, ideal como estudiante. |

### ❌ No apliques (todavía) — gap demasiado grande o irreal

| Oferta                                       | Por qué no                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **SFCC Frontend / Full Stack (Devsu-like)**  | Pide **10+ años de SFCC/SFRA**. Imposible de defender: no hay forma de aprender eso en poco tiempo y cualquier entrevista técnica lo delata. Descartar.                                                                                                                                                                                                       |
| **Senior AI Engineer (ITJ)**                 | 4+ años de software + experiencia en producción con LangChain/RAG/vector DBs. Estudiable a mediano plazo, pero hoy es inflación detectable.                                                                                                                                                                                                                   |
| **Senior AI Software Engineer (DaCodes)**    | +5 años software, +3 años de GenAI en producción, y evalúan fundamentos profundos (transformers, attention, LoRA, LLMOps) con justificación de decisiones. Es la más riesgosa de defender.                                                                                                                                                                    |
| **WordPress Developer (Mettano)**            | +2 años reales construyendo sitios WordPress/Elementor. Además el salario (USD 1.1–2.3K/mes) es bajo. Solo aplicaría tras construir 2–3 sitios demo reales.                                                                                                                                                                                                   |
| **HubSpot Developer (Devsu)**                | HubSpot CMS + HubL + marketing automation es un stack ajeno; "strongly preferred" en la oferta. Estudiable (2–3 semanas), pero no es tu camino natural.                                                                                                                                                                                                       |
| **Application Support Engineer**             | C#/.NET + SQL con "working knowledge" + on-call 24/7. C#/.NET es un stack que no conoces; el rol de soporte no es tu perfil. Borderline solo si estudias C# y SQL primero.                                                                                                                                                                                    |
| **Full Stack Dev — Financial Services (US)** | Stack técnico (Python, Ollama, Whisper, PostgreSQL, Salesforce) es aprendible, pero **compliance en industria regulada es requisito duro y explícito** ("please only apply if this matches your background"). Manejan dinero real de clientes: inflar experiencia de compliance aquí es detectable (background checks) y de alto riesgo. Descartar por ahora. |

---

## Plan de estudio por prioridad

### Prioridad 1 — SQL y bases de datos (desbloquea 3+ ofertas)

Necesario para: AI-Native Dev, QA Specialist, Application Support, y casi cualquier rol backend.

- Fundamentos: SELECT, JOINs (INNER/LEFT/RIGHT), GROUP BY + agregaciones (COUNT, SUM, AVG), subqueries, CTEs (WITH), window functions (ROW_NUMBER, RANK), índices y cuándo se usan.
- Diseño de esquemas: normalización (1NF–3NF), claves primarias/foráneas, relaciones 1:N y N:N, constraints, transacciones (ACID).
- Práctica: hacer 1 proyecto con PostgreSQL o SQLite + Node.js (CRUD con queries complejas) o usar SQLBolt/PostgreSQL Exercises.

### Prioridad 2 — C#/.NET (solo si quieres la oferta de Application Support)

- Sintaxis de C# moderna, async/await, LINQ, manejo de excepciones, clases/interfaces.
- ASP.NET Core mínimo: endpoints REST, middleware, inyección de dependencias.
- Leer y modificar código existente de un repo C# en GitHub (ese es el nivel "working knowledge").
- Curso de referencia: documentación oficial de .NET + un proyecto pequeño de consola/API.

### Prioridad 3 — WordPress + Elementor + PHP básico (solo para Mettano)

- WordPress: themes, plugins, page builders; estructura de un theme (header/footer/functions.php), child themes.
- Elementor: construcción de landing pages, templates, responsive, workflows con el builder.
- PHP básico: sintaxis, loops, arrays, hooks de WordPress (actions/filters), edits de functions.php.
- Migraciones: transferir sitio (plugins de migración, wp-cli, cambio de dominio), configuración DNS/email/SMTP.
- Performance: caché (LiteSpeed/WP Rocket), lazy loading, compresión de imágenes, Core Web Vitals.
- Producto mínimo para respaldarlo: 2–3 sitios WordPress/Elementor de muestra (landing page de negocio local con SEO básico + migración real de un sitio de prueba).

### Prioridad 4 — GenAI en producción (solo si apuntas a roles senior de IA: ITJ, DaCodes)

Fundamentos que piden evaluar (preguntas de entrevista seguras):

- Transformers, attention mechanism, context window, temperature, tokenización, fine-tuning, LoRA.
- RAG: embeddings, bases vectoriales, chunking, retrieval vs reranking, cuándo RAG agrega valor y cuándo no.
- Frameworks: LangChain/LangGraph (agents, tool calling, orquestación), Flowise.
- LLMOps: Docker, CI/CD, monitoreo/observabilidad (LangFuse, LangSmith, OpenTelemetry), versionamiento de prompts, optimización de costo/latencia.
- Producto mínimo: un RAG pipeline en Python (ingesta de PDFs → embeddings → query con contexto) + un agente con tool calling desplegado con Docker. Eso da evidencia real y material de entrevista.

### Prioridad 5 — HubSpot CMS + HubL (solo si te interesa Devsu)

- HubL (templating de HubSpot), módulos custom, templates de páginas/blogs/landing pages.
- HubSpot CRM: workflows, formularios, automatización de marketing, integración con REST APIs.
- WCAG + testing con Lighthouse/WAVE.
- Curso: HubSpot Academy tiene certificaciones gratis (HubSpot CMS for Developers).

### Prioridad 6 — Full Stack para industria financiera/regulada (objetivo a mediano plazo)

Stack técnico (aprendible en pocas semanas):

- Python backend de producción: FastAPI, tests, logging, auth, Docker.
- PostgreSQL: ya cubierto en Prioridad 1.
- IA local/offline: Ollama + Open WebUI, Whisper (transcripción de audio), embeddings locales.
- Salesforce API: REST/SOAP, OAuth, sincronización de datos.
- Seguridad de datos: cifrado en reposo/tránsito, manejo de datos sensibles, auditoría.

El bloqueador real no es técnico: es la **experiencia en compliance** (finanzas, seguros, banca o salud). Opciones para conseguirla:

- Cualquier rol en una empresa regulada (aunque sea soporte/QA) para tener el contexto real.
- Certificaciones de privacidad/compliance: CIPP/E, cursos de GLBA/HIPAA awareness, fundamentos de regulación financiera.
- En la entrevista: ser honesto ("no he trabajado en finanzas, pero hice X y tomé Y") — mejor que inflar, porque en industria regulada el humo se detecta con background checks y preguntas de compliance.

### Descartada — SFCC (no estudiar)

- 10+ años de experiencia no se aprenden; cualquier evaluación técnica real lo descubre. No vale la pena.

---

## Notas

- No necesitas estudiar: TypeScript/JS, React, Node.js, Python, Git, CI/CD (GitHub Actions), HTML/CSS, Docker (básico), AWS (fundamentos). Ya son defensibles.
- Antes de cada postulación, refrescar el DEVSYNC.json con las keywords de esa oferta (workflow de la sesión).
- Estrategia recomendada: priorizar las ofertas ✅ (Balsam, AI-Native, Product Engineer, QA) y usar el plan 1 → 2 → 3 para abrir más puertas.
