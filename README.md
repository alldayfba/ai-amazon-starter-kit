# AI Starter Kit — Your Personal Claude OS

The Directive → Orchestration → Execution (DOE) framework as a ready-to-run Claude Code
workspace. This is the BASE of your Claude — start here, then customize it around your
whole life: your Amazon business, your content, your day-to-day, everything you run.

From the Inner Circle Full-Stack AI course.

## Install — one paste, that's it

Open Claude Code in your IDE or terminal ([get it here](https://claude.com/claude-code) — course Video 2 walks the install), then paste this:

```
Set up my personal Claude OS from this starter kit:
https://github.com/alldayfba/ai-amazon-starter-kit
Clone it, read the README's "For Claude" section, and follow it.
```

Claude does the rest — it clones the kit, then interviews you to build YOUR context file.
Answer its questions honestly and specifically. Done means: Claude plays back who you are,
your criteria, and how it will work for you.

## What's in the kit

```
CLAUDE.md               ← your personal context file (Claude fills this in WITH you)
.claude/skills/doe.md   ← the DOE framework as a skill — Claude runs it automatically
directives/             ← your SOPs live here (one example included)
execution/              ← Claude saves your scripts here
```

## How it works

- **Directives** (`directives/`) = your SOPs in plain English. What to do.
- **Orchestration** = Claude. Reads the SOP, makes the judgment calls, runs the tools.
- **Execution** (`execution/`) = deterministic scripts. Same input, same output, every time.

This isn't just for Amazon. Any repeatable thing in your life — meal planning, content
batching, budget reviews, workout tracking — becomes a directive, and Claude runs it
your way, every time. The Amazon sections are the starting module; add your own.

## Rules the kit enforces out of the box

1. No BUY without all five fields (Amazon link, ASIN, verified buy link, ROI, profit) — anything missing = RESEARCH
2. Nothing is ever sent to a real person without your explicit approval
3. No spending money/credits without asking first
4. Conservative math, all fees included, YOUR thresholds
5. Unknown ≠ guess — Claude checks data or says UNKNOWN

---

## For Claude (if a user pasted this repo link to you)

You are setting up this kit as the user's personal operating system. Do this, in order:

1. **Clone the kit** into a sensible workspace folder (ask where they keep projects if
   unclear; default `~/claude-os` or similar). If `git` isn't available, download the ZIP
   via the GitHub archive URL and extract it.
2. **Read** `CLAUDE.md` and `.claude/skills/doe.md` so you understand the framework.
3. **Interview the user** to fill in `CLAUDE.md` — a few questions at a time, not a wall.
   Cover: who they are, their schedule and how they like to work, their Amazon business
   (model, account state, gating, niche), their capital and buy criteria (real numbers —
   push back on vague answers like "good ROI"), and anything else they run that you'll
   help with (content, fitness, budgeting, other projects — this OS is for their whole
   life, not just Amazon).
4. **Write their answers into `CLAUDE.md`**, replacing every bracket. Keep the Hard Rules
   and Learned Rules sections intact.
5. **Confirm the setup**: play back, in plain English — who they are, their buy criteria,
   and how you will work for them (the 3-layer system). Ask them to correct anything wrong.
6. **First win**: offer to turn ONE thing they do every week into their first directive
   in `directives/`, using `price-check-sop.md` as the format example.

Rules for the setup itself: don't send anything anywhere, don't spend anything, and
don't skip the interview — a template full of brackets helps nobody.
