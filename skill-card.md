## Description: <br>
Query a brand's DESIGN.md (a plain-text design-system format) and present the spec — color palette, typography, components, layout principles, do's and don'ts — back to the user or to another AI agent. <br>

This skill is ready for commercial/non-commercial use. <br>

## Publisher: <br>
[mebusw](https://clawhub.ai/user/mebusw) <br>

### License/Terms of Use: <br>
MIT <br>


## Use Case: <br>
Designers, front-end engineers, and product teams use this skill when they need a real product's design system in seconds — copy a brand's DESIGN.md, then prompt an AI agent to build a page, dashboard, or component that matches the brand's visual language. <br>

### Deployment Geography for Use: <br>
Global <br>

## Known Risks and Mitigations: <br>
Risk: The agent may pick the wrong brand slug when the user's input is ambiguous (e.g., "linear" vs "Linear app" vs "LinearB"). <br>
Mitigation: The skill defines a slug-mapping table and falls back to `ls docs/ | grep -i` fuzzy search before failing. <br>
Risk: The skill ships with 58 brand folders; the bundle may exceed ClawHub's 50 MB cap if too many preview HTMLs are added. <br>
Mitigation: Preview HTMLs are plain text; current bundle size is 7 MB, well under the limit. Re-validate with `du -sh` before each release. <br>
Risk: Brand design systems drift over time; the bundled DESIGN.md files may become stale. <br>
Mitigation: Treat the bundled files as a snapshot; users should refresh from the brand's own design system when precision matters. <br>


## Reference(s): <br>
- [ClawHub Skill Page](https://clawhub.ai/mebusw/skills/awesome-design-of-great-product-company-skill) <br>
- [skills.sh Listing](https://skills.sh/mebusw/awesome-design-of-great-product-company-skill) <br>
- [GitHub Repository](https://github.com/mebusw/awesome-design-of-great-product-company-skill) <br>
- [DESIGN.md format overview (Google Stitch)](https://stitch.withgoogle.com/docs/design-md/overview/) <br>
- [Agent Skills Specification](https://agentskills.io/specification) <br>


## Skill Output: <br>
**Output Type(s):** [text, markdown, shell commands, configuration, guidance] <br>
**Output Format:** [Structured Markdown report covering brand summary, color palette, typography, components, layout, do's and don'ts, plus an Agent Prompt snippet] <br>
**Output Parameters:** [1D] <br>
**Other Properties Related to Output:** [Read-only; the skill only reads `docs/<slug>/DESIGN.md` and related preview files. No network calls, no file mutations.] <br>

## Skill Version(s): <br>
1.0.0 (source: git tag v1.0.0) <br>

## Ethical Considerations: <br>
Users should review the generated design summary before applying it commercially; brand design systems are the intellectual property of their respective owners, and the bundled DESIGN.md files are derivative works for educational and prototyping use. Organizations should apply their own legal review before using these design systems in production. <br>
