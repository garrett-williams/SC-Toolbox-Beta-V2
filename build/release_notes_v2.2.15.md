# SC Toolbox v2.2.15

A feature release: two new database tools, the PlayTime Calculator, an updated
launcher, and continued Mining Signals refinements.

## New — PlayTime Calculator (Shift+T)

Reads your Star Citizen `Game.log` + log backups (across LIVE / PTU / HOTFIX) to
reconstruct your play history — no extra tracking, just your existing logs.

- **Total playtime** headline with an optional AFK-trim cap (so a session you
  left running overnight doesn't count as 47 hours).
- **Overview / Trends / Calendar** — per-day bar charts and a GitHub-style year
  heatmap.
- **Fun Stats** — most-flown ships, favourite weapon/loadout, and other trivia
  pulled from your logs.
- **Career** — mission completion and commodity-sell activity **counts** by type
  and employer (payouts/aUEC live server-side and aren't in the logs, so this
  tracks activity, never earnings).
- **Cost / hour** — enter your lifetime spend + currency to see real money per
  hour played.

The launcher main menu now shows a **PLAY TIME** link and a live total-played
badge.

## New — Mission Database (Shift+3)

Browse Star Citizen missions with data sourced from scmdb.net — searchable and
filterable, in the same MobiGlas style as the rest of the toolbox.

## New — Craft Database (Shift+7)

Crafting recipes and component lookup for the crafting system.

## Updated — Main launcher

Refreshed main menu with the new tool tiles and the PlayTime badge.

## Updated — Mining Signals

Continued accuracy and stability improvements to the OCR scanning pipeline
(HUD digit reader + signature scanner) on top of the v2.2.14 auto-heal capture
work.

---

🤖 Generated with [Claude Code](https://claude.com/claude-code)
