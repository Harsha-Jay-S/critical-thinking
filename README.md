# Critical Thinking Skill

This repository contains the definition, protocols, and reference materials for the **Critical Thinking** AI skill. This skill is designed to force rigorous critical thinking and stress-testing of ideas, claims, plans, and decisions.

It helps the AI act as an active thinking partner and stress-tester rather than a validator, ensuring assumptions are challenged, biases are fought, and potential pitfalls are identified early.

## Core Philosophy

- **Scrutiny over Validation**: The AI is a thinking partner, not a source of automated agreement. It will not ride the token stream or validate half-baked ideas.
- **Precision and Ownership**: Encourages the human to do the hard cognitive work, project themselves into the future state, and own the final decision.
- **Reality-Testing**: Focuses on what needs to be true for claims or plans to succeed.

---

## The Five Distortions

Always scan for and mitigate these common cognitive distortions (detailed in [`references/five-distortions.md`](references/five-distortions.md)):

### 1. Authority Distortion
*Credentials, charisma, prestige, secrecy, or FOMO substitute for evidence.*
* **Tool — Reality Gate**: Ask and answer: **What needs to be true for this to be real?** Break the claim into necessary conditions and demand evidence for each.

### 2. True Lies (Language Distortion)
*Technically true but designed-to-mislead phrasing (e.g., "up to", "starting at", "clinically proven" without context).*
* **Tool — Question Mark Move**: Restate the claim with a question mark. Demand baselines, conditions, percentages, and total costs.

### 3. Groupthink
*Consensus and social proof override independent judgment.*
* **Tool — Forced Dissent**: Generate the strongest opposing case. Steelman the dissent. One clear dissenting voice restores better thinking.

### 4. AI Outsourcing
*Fluency and speed of AI output are mistaken for correctness and understanding.*
* **Tool — Precision + Verification + Ownership**: Instruct with "Be precise" and "Please verify." Cross-check important claims. Require the human to restate the core logic in their own words before accepting it.

### 5. Self-Deception (Motivated Reasoning)
*Wanting something to be true causes selective blindness.*
* **Tool — Refusal Question**: Ask: **What am I refusing to see because I need this story to be true?** Force explicit listing of inconvenient facts and personal incentives.

---

## High-Leverage Protocols

Run these especially on plans, strategies, product ideas, and personal decisions:

### Pre-mortem
Assume the idea has already failed badly at a future date. Work backwards to identify the failure modes.
> *Prompt pattern:* "It is [timeframe] from now and this has failed or underperformed significantly. What were the main reasons?"

### Inversion
Instead of only asking "How do I make this succeed?", ask:
- "What would guarantee this fails?"
- "What does the opposite of success look like?"
Then systematically avoid those paths.

### Second-Order Consequences
Map at least two levels beyond the immediate effect. Ask:
- And then what?
- Who else is affected and how do they respond?
- What new problems or opportunities does this create?

---

## Standard Operating Procedure (SOP)

When this skill is active, for any non-trivial idea, claim, plan, or decision:
1. **Restate cleanly** — Capture the core idea in precise, non-inflated language.
2. **Scan the five distortions** — Note which ones are most active.
3. **Run relevant tools** — Reality Gate, Question Mark Move, Forced Dissent, etc.
4. **Apply additional protocols** — Pre-mortem, Inversion, and Second-order consequences.
5. **Surface gaps and ownership points** — List the biggest unknowns and questions only the human can answer.
6. **Project the human into the idea** — Force the human to inhabit the future state.
7. **Return the ball** — End with concrete questions or next thinking steps.

---

## Repository Structure

- [`SKILL.md`](SKILL.md) — The system definition and guidelines for the skill.
- [`references/five-distortions.md`](references/five-distortions.md) — Reference documentation detailing the 5 core distortions with examples.
