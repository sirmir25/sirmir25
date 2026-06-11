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
  programmer / DevOps engineer) built from GitHub-renderable Markdown/HTML and
  external image services: capsule-render header/footer waves, a
  readme-typing-svg tagline, shields.io badges for the stack, repo pin cards
  and stats/streak/top-langs cards from github-readme-stats and
  streak-stats.demolab.com, github-profile-trophy, an activity graph, a
  komarev profile-views counter, a fake terminal as a fenced `console` code
  block, and contact links (Telegram `@linuxexex`, GitHub `sirmir25`).

## Key constraints and conventions

- **GitHub strips `<style>` tags and `class`/`style`-based CSS** when
  rendering README files. That's why the README uses image services and
  allowed HTML (`<img>`, `<div align>`, tables, blockquotes) instead of CSS —
  keep new additions within those techniques.
- Badge style is uniform: `style=for-the-badge`, background `0d1520`,
  `logoColor=4ade80`; stat-card services are themed with the same palette via
  URL parameters (`bg_color=0d1520`, `title_color=4ade80`,
  `border_color=1e2a3a`, `text_color=e2e8f0`/`94a3b8`).
- Pinned repo cards reference real repositories under the `sirmir25` account
  (`Rach`, `DevTools`, `vpnlaunch`, `JakeLinux`) — verify a repo exists before
  adding a new pin card, otherwise the card renders an error.
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
