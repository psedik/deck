# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What This Is

A tarot deck content repository — 78 cards written in Markdown, intended to become a published "grimoire for the modern creator." No build system, no dependencies. Content is the product.

The vision is documented in `muse-tarot/creator-tarot-concept.md`: a two-page-spread book where each card has an **Anchor** (intellectual grounding) and a **Muse** (creative inspiration).

## Content Structure

```
tarot-card-index.md          # Master index linking all 78 cards
tarot-cards/
  major-arcana/              # 22 cards (00_fool.md … 21_world.md) + index.md
  minor-arcana/
    wands/                   # 14 cards (wands_01_ace.md … wands_king.md) + index.md
    cups/
    swords/
    pentacles/
muse-tarot/
  creator-tarot-concept.md   # Book concept and extraction strategy
  fool-sample-page.md        # Reference template for the two-page spread
```

Each card file contains these sections (not all cards have all sections):

- **Keywords** — short evocative list
- **Mood** — emotional tone descriptors
- **Core Meaning Snapshot** — upright bullet interpretations
- **Artistic Direction** — symbolic composition guide (The Muse's centrepiece)
- **Impression Palette** — Invocation, Haiku, Story Beat
- **Creator Prompt** — interactive reflection question
- **Esoteric Note** — astrological/elemental correspondence
- **Reversed Meanings** (where present)
- **Cross-Card Echoes** (where present)

## Naming Conventions

- Major arcana: `NN_name.md` (e.g. `00_fool.md`, `13_death.md`)
- Minor arcana: `suit_NN.md` for pips, `suit_page/knight/queen/king.md` for courts, `suit_01_ace.md` for aces
- Images: same base name as the card file, `.jpg` extension, in the same directory

## Planned Next Step

Extract `Keywords`, `Core Meanings`, `Artistic Direction`, and `Impression Palette` from each card into a compiled draft for book layout (InDesign / Affinity Publisher). Two-page spread per card: page 1 is The Anchor (image + keywords + core meanings), page 2 is The Muse (artistic direction + impression palette + creator prompt).
