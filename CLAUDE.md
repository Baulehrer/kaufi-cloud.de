# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Overview

This is a personal knowledge base (Obsidian vault) for Stephan Kaufmann, synced to git via automated vault backups. It contains markdown notes organized by topic. There is no build system, test suite, or application code.

## Repository Structure

Content is organized into numbered category folders:

- `01 Musik/` — Music recommendations and lists
- `02 Bautechnik/` — Civil engineering and construction references

Files within categories use short codes (e.g., `M01`, `B01`) as prefixes.

## Content Conventions

All markdown files use YAML frontmatter:

```yaml
---
Title: [Title]
Autor: Stephan Kaufmann
Date: [MM/YYYY]
Version: [Version string]
tags:
  - [tag]
---
```

## Git Workflow

Commits are made automatically by the Obsidian git plugin with the message format:
```
vault backup: YYYY-MM-DD HH:MM:SS
```

Manual commits should follow conventional content-describing messages. The remote is `github.com/Baulehrer/kaufi-cloud.de.git`.
