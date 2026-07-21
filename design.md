# Design — LonelyAgent Tools Directory

Locked design system for lonelyagent.github.io. Every page redesign reads this file first.

## Genre
modern-minimal

## Macrostructure family
- Marketing / home: Workbench (product captures first)
- Project notes: Workbench + long caption prose
- Index pages: Index-First list with one featured capture
- Content guides: Long Document within the same tokens

## Theme · Cobalt
- `--color-paper`   oklch(99% 0.004 250)
- `--color-paper-2` oklch(97% 0.008 250)
- `--color-ink`     oklch(22% 0.02 255)
- `--color-ink-2`   oklch(42% 0.02 255)
- `--color-rule`    oklch(90% 0.01 250)
- `--color-accent`  oklch(48% 0.16 255)
- `--color-accent-ink` oklch(99% 0.005 250)
- `--color-focus`   oklch(55% 0.18 255)
- `--color-good`    oklch(55% 0.14 155)

## Typography
- Display: Space Grotesk 600–700, roman only
- Body: Inter 400–500
- Mono: JetBrains Mono 400
- Display tracking: -0.03em

## Spacing
4-point named scale in `assets/tokens.css`.

## Motion
- Quiet only: opacity + transform
- Reduced-motion: opacity ≤ 150ms
- No scroll-jacking, no bouncy easings

## Microinteractions stance
- Silent success
- Hover delay not used on primary CTAs
- Focus rings instant

## CTA voice
- Primary: filled cobalt pill
- Secondary: outlined cool border pill

## What pages MUST share
- Wordmark LonelyAgent
- Cobalt accent + Space Grotesk / Inter pairing
- Root-absolute nav (`/tools/`, `/games/`, `/guides/`)
- Real product screenshots only (no fake chrome)
- Honest copy — no invented metrics

## What pages MAY differ on
- Which product screenshot leads
- Index vs detail depth
