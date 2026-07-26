# AI Amazon Starter Kit

The Directive → Orchestration → Execution (DOE) framework, ready to plug into Claude Code.
This is the starter workspace from the Inner Circle Full-Stack AI course.

## What's in here

```
CLAUDE.md               ← tell Claude who you are (fill in the brackets)
.claude/skills/doe.md   ← the DOE framework as a skill — Claude runs it automatically
directives/             ← your SOPs live here (one example included)
execution/              ← Claude saves your scripts here
```

## Install (2 minutes)

1. **Get Claude Code** — https://claude.com/claude-code (course Video 2 walks the full install)
2. **Get this kit** — click the green **Code** button above → **Download ZIP** → unzip it anywhere
   (or `git clone` this repo if you know git)
3. **Fill in `CLAUDE.md`** — open it in any editor and replace every `[bracket]` with YOUR numbers:
   your capital, your ROI floor, your price band, what you're gated in
4. **Open Claude Code in the folder** — in your terminal:
   ```
   cd ai-amazon-starter-kit
   claude
   ```
5. **First command** — paste this:
   ```
   Read CLAUDE.md and .claude/skills/doe.md, then tell me in plain English:
   who am I, what are my buy criteria, and how will you work for me?
   ```
   If it plays back YOUR numbers and the 3-layer framework — you're live.

## How it works

- **Directives** (`directives/`) = your SOPs in plain English. What to do.
- **Orchestration** = Claude. Reads the SOP, makes the judgment calls, runs the tools.
- **Execution** (`execution/`) = deterministic scripts. Same input, same output, every time.

Claude checks `directives/` before acting, checks `execution/` before building,
enforces your buy criteria from `CLAUDE.md`, and never calls anything a BUY
without all five fields: Amazon link, ASIN, verified buy link, ROI, profit.

When something breaks, Claude fixes the tool, updates the SOP, and adds a
Learned Rule — so the same mistake can never happen twice.

## Rules the kit enforces out of the box

1. No BUY without all five fields — anything missing = RESEARCH
2. Nothing is ever sent to a real person without your explicit approval
3. No spending money/credits without asking first
4. Conservative math, all fees included, YOUR thresholds
5. Unknown ≠ guess — Claude checks data or says UNKNOWN
