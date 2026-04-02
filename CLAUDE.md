# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal recipe book stored as Markdown files, organized into category folders. There are no build tools, scripts, or dependencies — all content is plain `.md` files.

## Structure

Recipes are organized by category folder:

| Folder | Number Series | Description |
|---|---|---|
| `breakfasts/` | 100s | Breakfast recipes |
| `dinners/` | 200s | Main dinner dishes |
| `soups/` | 300s | Soups and stews |
| `slowcooker/` | 400s | Slow cooker recipes |
| `sides/` | 500s | Side dishes |
| `snacks/` | 600s | Snacks and dips |
| `desserts/` | 700s | Desserts |

`TOC.md` is the Table of Contents listing every recipe by number and name.

## Recipe File Format

Each recipe file should follow this structure:

```markdown
**Category  |  Tag1  |  Tag2**

## Recipe Title
*Source Name*

Servings: X | Prep: X min | Cook: X min | Total: ~X min

### Ingredients

**Section Name** (if multiple ingredient groups)
- ingredient

### Instructions
1. Step one...

### Notes / Tips
- Note...
```

## Naming Convention

Recipe files use the format `NNN-kebab-case-title.md` where `NNN` is the recipe number. The numbers in each category are sequential but not necessarily contiguous (gaps exist for removed recipes). When adding a new recipe, check the existing highest number in that category and increment.

## Updating TOC.md

When adding, removing, or renaming a recipe, update `TOC.md` to keep it in sync. The TOC lists recipes in number order within each category section.
