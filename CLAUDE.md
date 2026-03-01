# Project Configuration

This project uses the **frontend-landings** Claude Code skill for generating production-ready, animated single-file HTML landing pages.

## Skills

The `frontend-landings` skill is installed at `.claude/skills/frontend-landings-claude-skill/`. It provides:

- **From Scratch mode**: Generate complete landing pages from product descriptions
- **Improve/Convert mode**: Enhance existing HTML with better design, animations, and responsiveness
- **10 curated visual presets**: Clean SaaS, Glassmorphic, Brutalist, Cyberpunk, Elegant Serif, Playful Gradients, Dark Mode First, Vintage Retro, Organic Nature, Corporate Professional
- **Tech stack**: Tailwind CSS (CDN), Anime.js, Google Fonts, inline SVGs, vanilla JS
- **Output**: Single self-contained HTML files with responsive design, dark/light mode, scroll animations, and SEO meta tags

## Usage

Ask Claude to create or improve a landing page. Examples:
- "Make a landing page for my SaaS product called X"
- "Generate a landing page with the Cyberpunk Neon style"
- "Improve this existing HTML to look more modern"

Generated HTML files should be saved in the project root or an `output/` directory.
