# Software Developer

I am Jannael Orlando.

Software developer, professional and open-source enthusiast.

## Professional Experience

- **Dual Education Student** at **Universidad Tecnológica Fidel Velázquez** (08/23 - 08/24)
- Developed automation and hardware/software integration projects, culminating in a smart greenhouse controlled by computer vision.
- Greenhouse with computer vision: Developed a plant monitoring system with Python and OpenCV on Raspberry Pi, controlling temperature and humidity via serial communication with Arduino.
- Real-time control interface: Built a GUI with Tkinter to operate greenhouse sensors and actuators, allowing environment parameter adjustments without manual intervention.
- RetoPY international contest: Represented the institution in an international Python programming contest, obtaining first place as team leader.

## Selected projects

- **Devsync**
- Tool to sync all your job-seeking documents: GitHub, LinkedIn, CV (Harvard format), portfolio, and academic history.
- Hexagonal architecture: Each command's logic (init, build, create-template) is isolated in domain/app/infra layers, sharing common infrastructure through the mixin pattern.
- Single source of truth: A single DEVSYNC.json keeps your PDF CV, GitHub profile, LinkedIn summary, and academic history in sync.
- PDF generation with Puppeteer: Renders the CV as HTML and exports it to PDF per language, with no external dependencies or third-party services.
- Native internationalization: Each section supports multiple languages; the build generates separate artifacts (CV, LinkedIn) per configured lang.
- GitHub Actions: A ready-to-use workflow detects changes in DEVSYNC.json and automatically regenerates and commits all artifacts.
- Template system: Create and publish fully customizable templates on GitHub; anyone can initialize their portfolio from them with a single command.
- Zod validation: The DEVSYNC.json schema is typed and validated with descriptive errors for each required profile field.
- Supply chain security: 3-day minimumReleaseAge in bunfig.toml blocks recently published packages, protecting against dependency chain attacks.
- Links: https://github.com/jannael/devsync | https://devsync.work
- **Glinter**
- Tool to improve the development experience using git.
- Transparent proxy: Uses Bun.spawn with stdio: 'inherit' to connect Git streams directly to the terminal, preserving colors, interactive prompts, and the full native UX.
- Hexagonal architecture: Each command (add, commit, switch, setup) is organized into independent domain/app/infra layers, with interfaces as ports and Bun as the adapter.
- Interactive staging: g add without arguments opens a multiselect with @clack/prompts showing only modified files, automatically filtering .env and node_modules.
- Porcelain parsing: Parses git status --porcelain -z with NUL splitting for 100% reliable file detection across Git versions, system languages, and special characters.
- Interactive switch: g switch lists local and remote branches in a navigable selector, running checkout without needing to remember the exact branch name.
- Cross-platform alias: The setup command configures the g alias on Unix and Windows automatically, with separate infrastructure implementations per OS.
- Links: https://github.com/jannael/glinter | https://glinter.jannael.com

## Core Skills

Python | OpenCV | Raspberry Pi | Arduino | TypeScript | Bun | Astro | Zod | Puppeteer | Vitest | GitHub Actions | Tailwind CSS | Cloudflare Pages | AWS | Amazon S3 | Amazon EC2 | AWS Lambda | CloudFront | Claude Code | Anthropic | React | JavaScript | Vite

## Certifications

- AWS Cloud Practitioner Essentials Santander — https://github.com/jannael/jannael/raw/main/academics/Constancia%20AWS%20Cloud%20Practitioner%20Essentials.pdf
- Claude Code in Action — https://github.com/jannael/jannael/raw/main/academics/Claude%20code%20in%20action.pdf
- Academia STEM Participation Certificate - RetoPY — https://github.com/jannael/jannael/raw/main/academics/Constacia%20de%20Participacion%20Academia%20STEM.pdf
- React Junior Developer - Certificates.dev — https://github.com/jannael/jannael/raw/main/academics/React%20Junior%20Developer.pdf

## Let's connect

- LinkedIn: https://www.linkedin.com/in/jannael-orlando-44604a349
- Github: https://github.com/jannael
- Github Profile: https://github.com/Jannael
