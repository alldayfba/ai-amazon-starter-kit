---
name: doe
description: Route any task through the Directive → Orchestration → Execution framework
trigger: when user says "doe", "run the workflow", "follow the SOP", or gives any repeatable business task
---

# DOE — Directive → Orchestration → Execution

You (Claude) operate a 3-layer system. Your job is Layer 2: intelligent routing.
Never do everything yourself in one giant response — that's the 59% failure path
(90% accuracy per step × 5 steps = 59% success). Separate judgment from mechanics.

## The 3 Layers

**Layer 1 — Directives (`directives/`)**
Plain-English SOPs. What to do, written like a brief to a competent employee.
Each directive has: Goal · Inputs · Tools to use · Output ("done" looks like this) · Edge cases.

**Layer 2 — Orchestration (YOU)**
Read the directive, make the judgment calls, run the tools in the right order,
handle errors, ask when genuinely blocked. You are the glue — not the labor.

**Layer 3 — Execution (`execution/`)**
Deterministic scripts that do the mechanical work: pull data, compute profitability,
format reports. Reliable, testable, same result every time. No guessing inside a script.

## Rules (always)

1. **Check `directives/` first.** If an SOP exists for this task, follow it. Don't freelance.
2. **Check `execution/` before writing a script.** The fastest build is the one that exists.
3. **No directive exists?** Draft one WITH the user (Goal/Inputs/Tools/Output/Edge cases),
   save it to `directives/<task-name>-sop.md`, then execute it.
4. **Repeatable mechanical step with no script?** Write one in `execution/`, test it on real
   input, then use it. The AI decides; the script does.
5. **Define "good."** Never accept vague criteria. "Good product" = ROI ≥ X%, price band,
   demand proof, not gated. Make the user state their numbers, then encode them in the directive.
6. **Amazon result standard:** any product presented as a BUY must have all five fields —
   Amazon link, ASIN, verified buy link, ROI, profit. Anything missing = RESEARCH, never a buy.
7. **Human approval gate:** never auto-send anything to a real person (customer, supplier,
   Amazon) without explicit approval on that specific send.

## Self-Annealing (when anything breaks)

1. Read the actual error — don't guess.
2. Fix the script in `execution/` and test it again.
3. Update the directive's **Known Issues** section with what you learned.
4. If the mistake came from a wrong assumption, add a one-line rule to the
   **Learned Rules** section of `CLAUDE.md` so it can never happen again.
5. The system is now stronger than before the error. That's the point.
