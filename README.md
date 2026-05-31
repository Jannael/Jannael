# Software Developer

![Status](https://img.shields.io/badge/Looking%20for%20work-brightgreen?style=flat)

Software developer, professional and open-source enthusiast.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jannael-orlando-44604a349)[![Github](https://img.shields.io/badge/Github-000000.svg?style=flat&logo=Github&logoColor=ffffff)](https://github.com/jannael)[![Academics](https://img.shields.io/badge/Academics-9C27B0?style=flat&logo=education&logoColor=white)](https://github.com/Jannael/Jannael/tree/main/academics)![Languages](https://img.shields.io/badge/English-4A90D9)![Languages](https://img.shields.io/badge/Spanish-E63946)

## Professional Experience

<table>
      <tr>
        <td>
          <h3>Universidad Tecnológica Fidel Velázquez</h3>

[![Web](https://img.shields.io/badge/Web-000000?logo=googlechrome&logoColor=fff)](http://casautfv.net/)[![Recommendation Letter](https://img.shields.io/badge/Recommendation%20Letter-0A66C2?logo=linkedin&logoColor=fff)](https://github.com/jannael/jannael/raw/main/academics/Juan%20Carlos%20Corte%20-%20en.pdf)[![Recommendation Letter](https://img.shields.io/badge/Recommendation%20Letter-0A66C2?logo=linkedin&logoColor=fff)](https://github.com/jannael/jannael/raw/main/academics/Juan%20Carlos%20Corte%20-%20es.pdf)
<p>Developed automation and hardware/software integration projects, culminating in a smart greenhouse controlled by computer vision.</p>
Featured Projects
<ul>
<li><strong>Greenhouse with computer vision</strong> Developed a plant monitoring system with Python and OpenCV on Raspberry Pi, controlling temperature and humidity via serial communication with Arduino.</li><li><strong>Real-time control interface</strong> Built a GUI with Tkinter to operate greenhouse sensors and actuators, allowing environment parameter adjustments without manual intervention.</li><li><strong>RetoPY international contest</strong> Represented the institution in an international Python programming contest, obtaining first place as team leader.</li>
</ul>
</br>

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=fff)![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?logo=raspberrypi&logoColor=fff)![Arduino](https://img.shields.io/badge/Arduino-00878A?logo=arduino&logoColor=fff)
</td>

<td width="40%">
  <a href="http://casautfv.net/" target="_blank" rel="noopener noreferrer">
    <picture>
      <img alt="Universidad Tecnológica Fidel Velázquez" src="https://imgs.search.brave.com/RuIC75wZGFDm9xsUgRv6bSZzEXp6XtlLl0E0QSyQ11s/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9taXIt/czMtY2RuLWNmLmJl/aGFuY2UubmV0L3By/b2plY3RzLzQwNC8x/ZGNmZDQxNDQ4ODQy/MjUuWTNKdmNDdzFO/elV6TERRMU1EQXNN/VE15TkN3dy5wbmc" width="100%"/>
    </picture>
  </a>
</td>
      </tr></table>

## Projects

<table>
      <tr>
        <td>
          <h3>Devsync</h3>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/jannael/devsync)[![Demo](https://img.shields.io/badge/Demo-22c55e)](https://devsync.work)
<p>Tool to sync all your job-seeking documents: GitHub, LinkedIn, CV (Harvard format), portfolio, and academic history.</p>
Features
<ul>
<li><strong>Hexagonal architecture</strong> Each command's logic (init, build, create-template) is isolated in domain/app/infra layers, sharing common infrastructure through the mixin pattern.</li><li><strong>Single source of truth</strong> A single DEVSYNC.json keeps your PDF CV, GitHub profile, LinkedIn summary, and academic history in sync.</li><li><strong>PDF generation with Puppeteer</strong> Renders the CV as HTML and exports it to PDF per language, with no external dependencies or third-party services.</li><li><strong>Native internationalization</strong> Each section supports multiple languages; the build generates separate artifacts (CV, LinkedIn) per configured lang.</li><li><strong>GitHub Actions</strong> A ready-to-use workflow detects changes in DEVSYNC.json and automatically regenerates and commits all artifacts.</li><li><strong>Template system</strong> Create and publish fully customizable templates on GitHub; anyone can initialize their portfolio from them with a single command.</li><li><strong>Zod validation</strong> The DEVSYNC.json schema is typed and validated with descriptive errors for each required profile field.</li><li><strong>Supply chain security</strong> 3-day minimumReleaseAge in bunfig.toml blocks recently published packages, protecting against dependency chain attacks.</li>
</ul>
</br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=fff)![Bun](https://img.shields.io/badge/Bun-fbf0df?logo=bun&logoColor=000)![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=fff)![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=fff)![Puppeteer](https://img.shields.io/badge/Puppeteer-4285F4?logo=puppeteer&logoColor=fff)![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=fff)![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=fff)![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff)![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-F38020?logo=cloudflare&logoColor=fff)
</td>

<td width="40%">
  <a href="https://devsync.work" target="_blank" rel="noopener noreferrer">
    <picture>
      <img alt="Devsync" src="https://github.com/jannael/devsync/raw/main/apps/web/public/og.png" width="100%"/>
    </picture>
  </a>
</td>
      </tr>
      <tr>
        <td>
          <h3>Glinter</h3>

[![Glinter](https://glinter.jannael.com/badge.svg)](https://github.com/jannael/glinter)[![Demo](https://img.shields.io/badge/Demo-22c55e)](https://glinter.jannael.com)
<p>Tool to improve the development experience using git.</p>
Features
<ul>
<li><strong>Transparent proxy</strong> Uses Bun.spawn with stdio: 'inherit' to connect Git streams directly to the terminal, preserving colors, interactive prompts, and the full native UX.</li><li><strong>Hexagonal architecture</strong> Each command (add, commit, switch, setup) is organized into independent domain/app/infra layers, with interfaces as ports and Bun as the adapter.</li><li><strong>Interactive staging</strong> g add without arguments opens a multiselect with @clack/prompts showing only modified files, automatically filtering .env and node_modules.</li><li><strong>Porcelain parsing</strong> Parses git status --porcelain -z with NUL splitting for 100% reliable file detection across Git versions, system languages, and special characters.</li><li><strong>Interactive switch</strong> g switch lists local and remote branches in a navigable selector, running checkout without needing to remember the exact branch name.</li><li><strong>Cross-platform alias</strong> The setup command configures the g alias on Unix and Windows automatically, with separate infrastructure implementations per OS.</li>
</ul>
</br>

![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?logo=typescript&logoColor=fff)![Bun](https://img.shields.io/badge/Bun-fbf0df?logo=bun&logoColor=000)![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=fff)![Vitest](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=fff)![Cloudflare Pages](https://img.shields.io/badge/Cloudflare%20Pages-F38020?logo=cloudflare&logoColor=fff)
</td>

<td width="40%">
  <a href="https://glinter.jannael.com" target="_blank" rel="noopener noreferrer">
    <picture>
      <img alt="Glinter" src="https://github.com/Jannael/glinter/raw/main/apps/web/public/og.png" width="100%"/>
    </picture>
  </a>
</td>
      </tr></table>
