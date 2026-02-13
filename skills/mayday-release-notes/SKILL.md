---
name: mayday-release-notes
description: >
  Generate Mayday product release notes in the exact format used on documentation.mayday.fr.
  Trigger when the user asks to write, draft, or create a release note, changelog, or "nouveautés"
  for Mayday. Also trigger when the user mentions "release notes", "notes de version", "nouveautés",
  or references the Mayday documentation update cycle. The output is a structured French-language
  document ready to publish on the Mayday help center.
---

# Mayday Release Notes Generator

## Overview

Generate release notes matching the exact structure, tone, emojis, and formatting conventions used by Mayday on their documentation portal. The output is always in **French**, customer-facing, and organized by product area.

## Workflow

1. **Gather inputs** from the user: release date, list of features/improvements/fixes per product area
2. **Read the template reference** at [references/template.md](references/template.md) for the full structure and examples
3. **Draft the release note** following the template strictly
4. **Review** for consistent emoji usage, tone, and section ordering

## Quick Reference — Document Skeleton

Every release note follows this fixed section order:

```
Title: 💫 DD/MM/YYYY | Catchy descriptive headline !

## 👋 Introduction
  - Warm greeting
  - Context paragraph
  - "Au programme ⭐ :" bullet list (emoji + bold feature + short description)
  - Transition line

## 🤩 Les nouveautés globales
  - Major cross-platform features (one subsection each)
  - For each: description, benefits, callout boxes, screenshots

## 📚 Mayday Knowledge
  ### ✍ Administrateurs sur Mayday
    - New features (emoji + title + description + doc links)
    - 😄 Améliorations notables (collapsible)
    - 🐞 Correctifs (collapsible)
  ### 👥 Conseillers sur Mayday
    - Same sub-structure as Administrateurs

## 🎓 Mayday Academy
  - Training/education features
  - 😄 Améliorations / 🐞 Correctifs

## 🌐 Mayday Selfcare
  - Public-facing / self-service features
  - 😄 Améliorations / 🐞 Correctifs
```

Sections with no content for a given release should be **omitted entirely** (do not include empty sections).

## Key Rules

- **Language**: Always French. Use "vous" (formal-friendly). Never "tu".
- **Tone**: Warm, enthusiastic, customer-benefit-oriented. Celebratory without being excessive.
- **Emojis**: Use them consistently for section headers and feature markers. See the template reference for the exact emoji mapping.
- **Bold text**: Highlight key feature names and important terms in bold within descriptions.
- **Callout boxes**: Use two types:
  - ℹ️ Blue info box: "Consultez la documentation dédiée pour découvrir cette nouveauté :" + links
  - ⚠️ Yellow warning box: "Petit point de vigilance" for caveats or activation requirements
- **Screenshots/GIFs**: Note where they should be inserted with `[Screenshot: description]` placeholders.
- **Collapsible sections**: Improvements (😄) and bug fixes (🐞) are presented in collapsible/expandable blocks using `▶` markers.
- **Documentation links**: Each major feature should link to its dedicated doc article.
- **"Au programme" list**: Always present in the Introduction. Each item has an emoji + **bold key term** + short phrase.

## Detailed Template & Examples

For the complete template with inline examples and all formatting conventions, read:
- [references/template.md](references/template.md) — Full annotated template with real examples
