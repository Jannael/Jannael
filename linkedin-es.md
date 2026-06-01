# Desarrollador de software

Soy Jannael Orlando.

Desarrollador de software, profesional y apasionado del open-source.

## Experiencia profesional

- **Estudiante de Educación Dual** at **Universidad Tecnológica Fidel Velázquez** (08/23 - 08/24)
- Desarrollé proyectos de automatización e integración de hardware/software, culminando en un invernadero inteligente controlado por visión artificial.
- Invernadero con visión artificial: Desarrollé un sistema de monitoreo de plantas con Python y OpenCV sobre Raspberry Pi, controlando temperatura y humedad mediante comunicación serial con Arduino.
- Interfaz de control en tiempo real: Construí una GUI con Tkinter para operar sensores y actuadores del invernadero, permitiendo ajustar parámetros del ambiente sin intervención manual.
- Concurso internacional RetoPY: Representé a la institución en un concurso internacional de programación en Python, obteniendo el primer lugar como líder de equipo.

## Proyectos destacados

- **Devsync**
- herramienta para sincronizar todos tus documentos para buscar trabajo, github, linkedin, curriculum (con formato hardvard), portafolio y historial académico.
- Arquitectura hexagonal: La lógica de cada comando (init, build, create-template) está aislada en capas domain/app/infra, compartiendo infraestructura común a través del patrón mixin.
- Una sola fuente de datos: Un único DEVSYNC.json mantiene sincronizados el CV en PDF, el perfil de GitHub, el resumen de LinkedIn y el historial académico.
- Generación de PDF con Puppeteer: Renderiza el CV en HTML y lo exporta a PDF por idioma, sin dependencias externas ni servicios de terceros.
- Internacionalización nativa: Cada sección soporta múltiples idiomas; el build genera artefactos separados (CV, LinkedIn) por cada lang configurado.
- GitHub Actions: Un workflow listo para usar, detecta cambios en DEVSYNC.json y regenera y commitea automáticamente todos los artefactos.
- Sistema de plantillas: Crea y publica plantillas completamente personalizables en GitHub; cualquiera puede inicializar su portafolio desde ellas con un solo comando.
- Validación con Zod: El schema de DEVSYNC.json está tipado y validado con errores descriptivos para cada campo requerido del perfil.
- Supply chain security: minimumReleaseAge de 3 días en bunfig.toml bloquea paquetes recién publicados, protegiendo contra ataques a la cadena de dependencias.
- Enlaces: https://github.com/jannael/devsync | https://devsync.work
- **Glinter**
- herramienta para mejorar la experiencia de desarrollo utilizando git.
- Transparent proxy: Usa Bun.spawn con stdio: 'inherit' para conectar los streams de Git directamente al terminal, preservando colores, prompts interactivos y toda la UX nativa.
- Arquitectura hexagonal: Cada comando (add, commit, switch, setup) está organizado en capas domain/app/infra independientes, con interfaces como puertos y Bun como adaptador.
- Staging interactivo: g add sin argumentos abre un multiselect con @clack/prompts mostrando solo los archivos modificados, filtrando automáticamente .env y node_modules.
- Porcelain parsing: Parsea git status --porcelain -z con split por NUL para detección de archivos 100% confiable entre versiones de Git, idiomas de sistema y caracteres especiales.
- Switch interactivo: g switch lista ramas locales y remotas en un selector navegable, ejecutando el checkout sin necesidad de recordar el nombre exacto de la rama.
- Alias multiplataforma: El comando setup configura el alias g en Unix y Windows de forma automática, con implementaciones de infra separadas por sistema operativo.
- Enlaces: https://github.com/jannael/glinter | https://glinter.jannael.com

## Habilidades principales

Python | OpenCV | Raspberry Pi | Arduino | TypeScript | Bun | Astro | Zod | Puppeteer | Vitest | GitHub Actions | Tailwind CSS | Cloudflare Pages | AWS | Amazon S3 | Amazon EC2 | AWS Lambda | CloudFront | Claude Code | Anthropic | React | JavaScript | Vite

## Certificaciones

- Constancia AWS Cloud Practitioner Essentials Santander — https://github.com/jannael/jannael/raw/main/academics/Constancia%20AWS%20Cloud%20Practitioner%20Essentials.pdf
- Claude Code in Action — https://github.com/jannael/jannael/raw/main/academics/Claude%20code%20in%20action.pdf
- Constancia de Participación Academia STEM - RetoPY — https://github.com/jannael/jannael/raw/main/academics/Constacia%20de%20Participacion%20Academia%20STEM.pdf
- React Junior Developer - Certificates.dev — https://github.com/jannael/jannael/raw/main/academics/React%20Junior%20Developer.pdf

## Conectemos

- LinkedIn: https://www.linkedin.com/in/jannael-orlando-44604a349
- Github: https://github.com/jannael
- Perfil de Github: https://github.com/Jannael
