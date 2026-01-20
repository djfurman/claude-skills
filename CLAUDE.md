# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a Claude Code skills repository containing custom skills (slash commands) that extend Claude Code's capabilities. Skills are invoked via `/skill-name` commands in Claude Code.

## Structure

Each skill lives in its own directory with a `SKILL.md` file that defines:
- Frontmatter with `name` and `description` fields (YAML format between `---` delimiters)
- Skill instructions in markdown below the frontmatter

## Creating a New Skill

1. Create a directory with the skill name (use kebab-case)
2. Add a `SKILL.md` file with this structure:
   ```markdown
   ---
   name: skill-name
   description: Brief description shown in skill listings
   ---

   # Skill Title

   Instructions for what the skill should do...
   ```

## Current Skills

- `conventional-pr-review` - Reviews PRs with conventional comments and constructive feedback
