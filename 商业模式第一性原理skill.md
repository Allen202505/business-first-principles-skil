---
name: business-first-principles
description: Analyze any industry or business using first-principles thinking to uncover the core logic, key variables, and monetization structure. Use this skill whenever the user asks to analyze a business model, understand how an industry works, evaluate a company for investment, or find the fundamental drivers of any commercial activity. Trigger on phrases like "第一性原理", "商业模式分析", "这个行业怎么赚钱", "first principles", "business model", "how does X make money", "analyze this industry", "what drives this business", or any request to deeply understand a company or sector.
---

# Business First-Principles Analysis

A framework for cutting through surface complexity to find the core logic of any business or industry — inspired by value investing methodology: don't stare blindly at financial statements, find the minimum set of key variables that drive everything else.

---

## The 4-Step Framework

### Step 1: Physical-Layer Description (物理层描述)

Describe what the business does in one sentence a child could understand. Strip away all business jargon, brand language, and industry terminology.

**Prompt to use:** "If I had to explain this business to a 10-year-old, what would I say it does?"

**Examples:**
- Coal-to-oil company → "turns coal into oil"
- Recruitment platform → "connects people who want jobs with companies that need workers"
- Gig payroll platform → "helps companies legally pay workers they don't officially employ"

> ⚠️ If you can't do this in one sentence, you don't understand the business yet.

---

### Step 2: Input → Conversion → Output (转化机器模型)

Map the business as a conversion machine:

| Component | Question to ask |
|-----------|----------------|
| **Input** | What raw material/resource/attention does it consume? |
| **Conversion** | What transformation does it perform? What's the efficiency? |
| **Output** | What does it produce that people will pay for? |

**Examples:**
- Coal-to-oil: Input = coal + capital → Conversion = chemical process → Output = oil
- Job platform: Input = job seekers + job listings → Conversion = matching algorithm → Output = successful hires
- Content platform: Input = creator attention → Conversion = distribution → Output = user attention sold to advertisers

---

### Step 3: Find the Minimum Key Variables (最少关键变量)

Ask: **"If I could only track 3–5 numbers, which ones would tell me if this business will thrive or die?"**

These variables must meet two criteria:
1. **Causal** — they cause profits/losses, not just correlate with them
2. **Minimal** — all other financial metrics can be derived from them

**Coal-to-oil example:** Coal price × Conversion ratio × Volume × Oil price = Profit

**Templates by business type:**

| Business Type | Typical Key Variables |
|--------------|----------------------|
| Commodity processor | Input price, conversion ratio, output price, volume |
| Marketplace / platform | Supply density, demand density, match rate, take rate |
| SaaS / subscription | CAC, LTV, churn rate, expansion revenue |
| Retail / consumer | Traffic, conversion rate, basket size, repeat rate |
| Financial / lending | Spread, default rate, leverage, funding cost |
| Media / content | Audience size, engagement rate, CPM/RPM |
| Gig / labor platform | Worker supply, job density, fill rate, margin per placement |

---

### Step 4: Verify by Derivation (推导验证)

**Test:** Can you derive all major financial metrics from your key variables?

- Revenue = ?
- Gross margin = ?
- Unit economics = ?
- Growth ceiling = ?

If yes → you've found the first principles.
If no → you're missing a variable. Go back to Step 3.

---

## The Core Insight (底层洞察)

After completing the 4 steps, state the single sentence that captures *why this business exists and captures value*:

> **"[This business] exists because [fundamental friction/inefficiency]. It captures value by [mechanism]. It wins when [key variable] is optimized."**

**Examples:**
- Recruitment: "Exists because information asymmetry between employers and workers. Captures value by reducing search cost. Wins when match quality and speed are maximized."
- Gig payroll: "Exists because regulatory friction between enterprises and flexible workers. Captures value by providing compliance infrastructure. Wins when transaction volume and compliance moat are maximized."

---

## Common Pitfalls to Avoid

1. **Confusing features with fundamentals** — A product feature (e.g., "direct chat") is not a first principle; it's a solution to a first-principles problem (match efficiency).

2. **Stopping at the revenue model** — "They charge per hire" is not a first principle. Ask *why* someone pays and *what they're really buying*.

3. **Ignoring the supply side** — Most marketplace analyses focus on demand. Always ask: what keeps supply on the platform? What are their alternatives?

4. **Assuming current form is permanent** — First principles analysis should reveal *what the business needs to be true*, not just what it currently is. This exposes disruption risk.

---

## Output Format

When completing a first-principles analysis, structure the output as:

```
## [Industry/Company] — First Principles Analysis

**In one sentence:** [physical-layer description]

**The conversion machine:**
- Input: [what goes in]
- Conversion: [what transformation happens]
- Output: [what value is produced]

**Key variables (3–5):**
1. [Variable] — [why it matters]
2. [Variable] — [why it matters]
3. [Variable] — [why it matters]

**Derivation check:** [show how revenue/profit flows from variables]

**Core insight:** [one sentence — why this business exists and wins]

**Strategic implication:** [what this means for competition, investment, or product]
```

---

## Quick Reference: Questions That Unlock First Principles

- "If this business disappeared tomorrow, what problem would go unsolved?"
- "Who is the real customer — who actually pays and why?"
- "What is the one thing this business must do better than anyone else to survive?"
- "If you rebuilt this industry from scratch, what's the minimum viable version?"
- "What's the most profitable company in this space, and why — structurally, not operationally?"
