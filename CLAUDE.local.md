# CLAUDE.local.md

This file provides guidance to Claude Code when working on the didi-presentation repo.

## Critical: Preserve Existing Assets

- **NEVER remove the Didi avatar** (`https://didi.nossomos.cc/didi-avatar.png`) from the closing slide.
  It is intentional and must always be present in the last slide.
- **NEVER remove the screenshots** in `didi/img/` — preserve all existing images.
- When rewriting or updating `didi/index.html`, always carry forward:
  - The avatar in the closing slide
  - The screenshot images (screenshot_1.jpg, screenshot_2.jpg, screenshot_3.jpg)
  - The nav dots script at the bottom

## Project Structure

- `didi/index.html` — main presentation (scroll-snap slide deck)
- `didi/img/` — screenshots used in slides
- `CNAME` — custom domain config (do not touch)

## Git

- Use Conventional Commits (one-line, max 120 chars)
- Branch prefix: `da-`
- Do not mention Claude or AI agents in PR descriptions
