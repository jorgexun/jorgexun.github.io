# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static GitHub Pages website for Pencilsmith (pencilsmith.com), a simple landing page showcasing minimalist productivity tools. The entire site is contained in a single `index.html` file with inline CSS.

## Architecture

**Single-file static site**: The entire website consists of one HTML file ([index.html](index.html)) with:
- Embedded CSS styling (no external stylesheets)
- Google Fonts integration (Lustria serif font)
- Simple semantic HTML structure
- No JavaScript or build process

**Design philosophy**: The site follows a minimalist aesthetic matching the "Simplest tools with zero intelligence" tagline - clean typography, centered layout, minimal interactions (hover effects only).

## Development

**Local development**: Simply open [index.html](index.html) in a browser. No build step or local server required.

**Deployment**: This is a GitHub Pages site. Changes pushed to the `main` branch are automatically deployed to pencilsmith.com (configured via CNAME).

**Making changes**:
- All styling is inline in the `<style>` tag within [index.html](index.html)
- The site uses a centered container with max-width of 960px
- Typography: Lustria font at 22px body text, 36px title
- Color scheme: near-black text (#000) on off-white background (#fafafa)

## Key Considerations

When modifying this site, maintain the minimalist aesthetic and single-file architecture. The site intentionally avoids build tools, frameworks, and external dependencies beyond Google Fonts.
