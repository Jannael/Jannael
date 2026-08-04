# Taste (Continuously Learned by [CommandCode][cmd])

- When tailoring DEVSYNC.json to a job offer, injects the offer's exact keywords (job title, tools, frameworks) into `jobTitle`, `description`, and `coreSkills`. Confidence: 1.0
- Reorients the descriptions of experience, projects, and certifications to align with the job offer's keywords and requirements. Confidence: 1.0
- Always keeps the `en` and `es` locale sections symmetric when updating DEVSYNC.json. Confidence: 1.0
- After editing DEVSYNC.json for an offer, validates the JSON, runs `bunx @jannael/devsync build` to regenerate all artifacts (cv-en.txt, cv-es.txt, linkedin-en.md, linkedin-es.md, README.md, academics/README.md, PDFs), and verifies the result in cv-en.txt. Confidence: 1.0
- Closes each offer pivot with a structured recap in Spanish: what changed per section (jobTitle/description/coreSkills/experience/projects/certifications), validation status, and an honest note on aspirational keywords. Confidence: 0.95
- Warns honestly when job-offer keywords are aspirational relative to the user's real experience (e.g., 10+ years SFCC, OpenAI API/agentic workflows, C#/.NET, SQL), flagging which ones are defensible, noting that injected keywords get past ATS filters but the real risk is the technical interview, and recommending a quick crash course for missing "working knowledge" skills. Confidence: 0.95
- Plans each offer pivot with a todo list in a fixed order: update `coreSkills` first, then the `en` section, then the mirrored `es` section, then validate/regenerate artifacts. Confidence: 0.8
- New skills in DEVSYNC.json follow the pattern: `name` + `mdBadge` (shields.io badge in the existing black style) + `icon` (https://cdn.simpleicons.org/<name>). Confidence: 0.8
  keywords), and flagging "plus"-only requirements (e.g., health-data domain) as non-blocking. Confidence: 0.8
- New skills in DEVSYNC.json follow the pattern: `name` + `mdBadge` (shields.io badge in the existing black style) + `icon` (https://cdn.simpleicons.org/<name>). Confidence: 0.8
