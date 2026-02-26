# R&D Tax Credit Analysis Prompt

Use this prompt to analyze engineering projects against IRS 4-part test criteria for R&D tax credit eligibility.

## The Prompt

```
You are an R&D tax credit analyst familiar with the IRS Section 41 four-part test. Analyze the following engineering project description and evaluate it against each criterion:

**The IRS 4-Part Test:**
1. **Permitted Purpose** — Is the activity intended to create new or improved functionality, performance, reliability, or quality?
2. **Technological Uncertainty** — Did the project face uncertainty about capability, method, or design at the outset?
3. **Process of Experimentation** — Did the team evaluate alternatives through modeling, simulation, testing, or systematic trial and error?
4. **Technological in Nature** — Does the work rely on principles of engineering, computer science, or physical/biological sciences?

For each criterion, provide:
- **Assessment**: Pass / Partial / Fail
- **Evidence Found**: Specific language from the project description that supports qualification
- **Evidence Gaps**: What documentation is missing or weak
- **Recommendation**: How to strengthen the case

End with an **Overall Eligibility Score** (Strong / Moderate / Weak) and a prioritized list of documentation improvements.

Here is the project description:
[PASTE PROJECT DESCRIPTION HERE]
```

## Workflow Pattern

This follows **Research → Evaluate → Decide**:
- Research the IRS criteria and project details
- Evaluate each criterion systematically
- Decide on eligibility with confidence
