# Copilot Instructions for natalierharris/natalierharris

## Repository Overview
This is a GitHub profile repository. The `README.md` file is the centerpiece — it is displayed directly on the GitHub profile page at https://github.com/natalierharris. Keep it polished and reflective of the owner's personal brand.

## Purpose
- Showcase the owner's skills, interests, and personality to visitors
- Serve as a living document that gets updated as the owner grows
- Link out to projects, social profiles, and contact information

## Tech Stack
- **Markdown** (`README.md`): GitHub Flavored Markdown (GFM) rendered on the profile page
- **HTML5** (`index.html`): Simple standalone web page
- **GitHub Actions / Agents** (`.github/`): Automation and Copilot agent definitions

## File Structure
- `README.md` — Profile README shown on GitHub profile
- `index.html` — Standalone HTML page
- `summary.md` — Summary document
- `TASK.md` — Task tracking document
- `.github/copilot-instructions.md` — This file; Copilot coding guidelines
- `.github/agents/` — Custom Copilot agent definitions

## Coding Guidelines

### General Principles
- Make the smallest change necessary to accomplish the task
- Keep content simple, clean, and easy to maintain
- Ensure all content is appropriate for a public-facing profile
- Do not commit secrets, credentials, or private information

### README.md
- Keep the tone friendly, professional, and authentic
- Use emojis sparingly and purposefully
- Prefer short, scannable sections over long paragraphs
- Use GitHub Flavored Markdown: headers, lists, bold/italic, links, badges
- Badges (e.g., shields.io) are welcome but should not clutter the page
- All external links must use HTTPS

### HTML Files
- Use semantic HTML5 elements (`<header>`, `<main>`, `<footer>`, etc.)
- Always include `<meta charset="UTF-8">` and `<meta name="viewport" ...>`
- Maintain accessibility: use `alt` attributes on images, meaningful link text
- Indentation: 4 spaces
- Keep inline styles minimal; move to `<style>` block or external CSS if styling grows

### Markdown Files
- Follow GitHub Flavored Markdown syntax
- Use clear, concise language
- Maintain consistent heading hierarchy (H1 → H2 → H3)
- Lists use 2-space indentation
- Blank line between sections for readability

### Links
- Always use HTTPS for external links
- Verify links are valid before committing
- Use relative paths for internal repository links

## Conventions
- File names: lowercase with hyphens (`kebab-case`)
- Line endings: LF (Unix-style)
- No trailing whitespace

## Common Tasks
- **Update profile info**: Edit `README.md`
- **Modify the HTML page**: Edit `index.html`
- **Add/update Copilot agents**: Edit files in `.github/agents/`
- **Update these instructions**: Edit `.github/copilot-instructions.md`

## Quality Standards
- All HTML must be valid HTML5
- All Markdown must render correctly on GitHub (preview before committing)
- Content should be professional, accurate, and up to date
- No sensitive information or credentials should ever be committed
- Changes to `README.md` should reflect the owner's actual skills and experience
