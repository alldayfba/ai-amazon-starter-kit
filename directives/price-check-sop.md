# Price Check — SOP (starter example)

> This is what a directive looks like. Copy this structure for every process you teach Claude.

## Goal
Given a retailer product URL, report the current price, stock status, and whether it clears my buy criteria (see CLAUDE.md).

## Inputs
- One or more product URLs from a retailer I shop

## Tools
- `execution/check_price.py` — if it doesn't exist yet, build it (one script, one job: URL in → price + stock out)
- My profit criteria from CLAUDE.md — never invent your own thresholds

## Output ("done" looks like this)
A table: URL · product name · price · in stock? · passes my criteria? (yes/no + why)

## Edge Cases
- Page won't load or blocks the request → report it, don't guess the price
- Price shown is a multi-pack → say so, compute per-unit
- Any field unknown → mark UNKNOWN, never fill in a guess

## Known Issues
(Claude: append what you learn here every time something breaks — this is how the SOP gets smarter)
