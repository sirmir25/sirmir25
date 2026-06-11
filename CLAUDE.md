# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is `sirmir25/sirmir25`, a GitHub **profile README repository**. Its only
content is `Readme.md`, which GitHub renders at the top of the
[github.com/sirmir25](https://github.com/sirmir25) profile page. There is no
application code, build system, package manager, or test suite — and none
should be added. Changes here are edits to the profile presentation.

## Structure

- `Readme.md` — the entire repository. A profile card for sirmir25 (systems
  programmer / DevOps engineer) written as raw HTML with an embedded `<style>`
  block: hero header, badge row, about/stack cards, a featured-project section
  (the "Rach" programming language), stats, current-focus list, a fake
  terminal session, contact links (Telegram `@linuxexex`, GitHub `sirmir25`),
  and a footer.

## Key constraints and conventions

- **GitHub strips `<style>` tags and `class`/`style`-based CSS** when
  rendering README files. The current file is written as styled HTML, so most
  of its visual design does not survive GitHub's sanitizer — only the text
  content and links render. Keep this in mind before adding more CSS-dependent
  markup; if asked to make the profile actually look styled on GitHub, the
  reliable techniques are Markdown, allowed HTML tags (`<img>`, `<table>`,
  `<details>`, `align` attributes), shields.io badges, and SVG images.
- The file is named `Readme.md` (not `README.md`). Keep that casing when
  referencing or replacing it.
- Visual theme, if preserving the design intent: dark background (`#080c10`),
  green accent (`#4ade80`), monospace type (IBM Plex Mono) with Anybody for
  headings.
- Content should stay consistent with the owner's profile: Arch Linux, Rust,
  C/C++, Python, Bash, Docker, Kubernetes, eBPF, Prometheus/Grafana,
  AppArmor, CI/CD; located in Billings, Montana.

## Workflow

There are no build, lint, or test commands. Verify changes by previewing the
Markdown/HTML rendering (keeping the GitHub sanitizer limitations above in
mind), then commit and push. Commit messages in the history are terse; a short
descriptive message is fine.
