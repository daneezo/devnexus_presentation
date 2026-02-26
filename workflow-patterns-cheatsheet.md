# 4 AI Workflow Patterns — Cheat Sheet

These patterns work regardless of which AI tool you use (ChatGPT, Claude, Gemini, Copilot, etc.).

## Pattern 1: Translate → Synthesize → Act

**When to use:** You have raw data or information that needs to become decisions or deliverables.

| Step | What Happens | Example |
|------|-------------|---------|
| Translate | Convert raw input into structured format | Monthly metrics → organized summary |
| Synthesize | Identify patterns, trends, insights | "Revenue up 12% but churn accelerated" |
| Act | Generate deliverable or recommendation | Executive report with action items |

**Prompt structure:** "Here is [raw data]. Summarize the key trends, then create a [deliverable] with specific recommendations."

---

## Pattern 2: Build → Test → Iterate

**When to use:** You need working code, scripts, or automation.

| Step | What Happens | Example |
|------|-------------|---------|
| Build | Generate initial code/script | Google Apps Script for CSV cleaning |
| Test | Run it, find failures | Date parsing breaks on "March 5 2024" |
| Iterate | Feed error back to AI, refine | "This date format fails. Add support for..." |

**Prompt structure:** "Write a [language] script that [specific steps]. When I paste an error, fix the code and explain what changed."

---

## Pattern 3: Research → Evaluate → Decide

**When to use:** You need to analyze options or assess against criteria.

| Step | What Happens | Example |
|------|-------------|---------|
| Research | Gather relevant information | IRS 4-part test criteria |
| Evaluate | Score against framework | Project meets 3 of 4 criteria |
| Decide | Make recommendation with evidence | "Strong candidate — document uncertainty better" |

**Prompt structure:** "Evaluate [subject] against [framework/criteria]. For each criterion, assess pass/fail and cite specific evidence."

---

## Pattern 4: Draft → Fact-Check → Refine

**When to use:** You're creating content that needs accuracy and polish.

| Step | What Happens | Example |
|------|-------------|---------|
| Draft | Generate initial content | Presentation outline |
| Fact-Check | Verify claims, check for gaps | Persona analyzer reviews for 3 audiences |
| Refine | Incorporate feedback, polish | Update slides based on specific suggestions |

**Prompt structure:** "Review this [content] for [specific audience]. Flag inaccuracies, gaps, and tone issues. Suggest specific improvements."

---

## Quick Start

1. **Pick your boring task** — the one you dread every week
2. **Match it to a pattern** — which workflow fits?
3. **Write a specific prompt** — role + context + procedure + constraints + output format
4. **Iterate** — paste errors back, refine, repeat
5. **Graduate to a system** — build a Custom GPT with your best prompts baked in
