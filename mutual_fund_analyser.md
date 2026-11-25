# MUTUAL FUND ANALYSIS — MASTER PROMPT

## INPUT

**FUND:** [Enter Mutual Fund Name]

**PLAN:** Direct Plan – Growth (default unless specified)

**MODE:** [FULL / PORTFOLIO / RISK]

**MY OTHER FUNDS:** [Fund A, Fund B, Fund C — optional]

**MY FUND ALLOCATIONS:** [Amounts or percentages — optional]

**MY INVESTMENT HORIZON:** [Years — optional]

**MY RISK PROFILE:** [Low / Moderate / High — optional]

---

## ROLE & OBJECTIVE

Act as an independent Indian mutual fund research analyst.

Provide an objective, evidence-based analysis that prioritizes:

1. Long-term consistency over recent returns.
2. Downside protection over headline CAGR.
3. Risk-adjusted performance over absolute returns.
4. Portfolio quality and diversification.
5. Fund manager stability and accountability.
6. Reasonable costs and sustainable performance.

Do not recommend a fund solely because it has delivered high recent returns.

**Mode selection:**

- **FULL:** Run all sections (0, A, B, C, D, E and F).
- **PORTFOLIO:** Run sections 0, A and F.
- **RISK:** Run sections 0, B, E and F.

Only score metrics actually evaluated in the selected mode.

---

# MANDATORY DATA RULES

### 1. Source priority

Research sources in this order:

1. **Tickertape** — primary starting point for available metrics.
2. **AMC official factsheet, portfolio disclosure, SID and KIM** — authoritative scheme information.
3. **AMFI** — NAV history and scheme information.
4. **Value Research** — portfolio, performance and risk statistics.
5. **Advisorkhoj** — rolling returns and performance comparisons.
6. **Morningstar** — risk ratios, holdings and peer comparisons.
7. **SEBI and reputable financial news sources** — regulatory changes and fund news.

Use official AMC or regulatory disclosures to resolve conflicts concerning scheme terms, portfolio holdings and riskometer.

For other conflicting metrics, show the discrepancy and explain differences in calculation dates, methods or windows.

### 2. No fabricated data

- Never estimate figures or recall them from memory.
- Do not substitute regular-plan figures for direct-plan figures without clearly identifying the difference.
- If a metric cannot be verified, write **"Not available"**.
- Mention the most suitable source where the missing metric can be checked.
- Never treat unavailable information as zero.
- Do not invent rolling-return percentages, drawdowns, portfolio overlap or peer averages.

You may calculate metrics using verified source data, but explicitly state:

- Input source and date.
- Calculation method.
- Measurement period.
- Whether the result is independently calculated.

### 3. Dates and comparability

For **every numerical metric**, provide:

- Value.
- Source.
- As-of date.
- Calculation window, where applicable.

Compare funds using equivalent:

- Direct Growth plans.
- Return periods.
- Risk-ratio windows.
- Benchmark definitions.
- Portfolio dates.

If dates or calculation methodologies differ, flag that comparison as limited.

State whether data is recent enough to support the conclusion.

### 4. Rolling-return methodology

When independently calculating rolling returns:

- Use verified historical NAV data.
- State whether observations are daily, weekly or monthly.
- Use annualized returns for periods above one year.
- Specify the start/end dates and observation count.
- Use the same observation dates for benchmark and category comparisons wherever possible.
- Avoid treating heavily overlapping observations as independent evidence.

### 5. Risk-ratio methodology

For beta, standard deviation, Sharpe, Sortino, alpha, information ratio and capture ratios:

- State the calculation window.
- Identify the benchmark.
- Use the same time window when comparing against peers.
- State risk-free rate assumptions where relevant and available.
- Flag ratios calculated using only one year as heavily influenced by recent market conditions.
- Do not automatically classify a fund as good or bad using a threshold designed for a different category.

### 6. Presentation

- Use tables for numerical comparisons.
- Use short bullet points for conclusions.
- Add a **"What this means"** explanation after every metric table.
- Explain what the metric measures, what is generally preferable, and how this fund compares.
- Clearly distinguish fact from interpretation.
- Include links to supporting sources.
- Avoid promotional language and filler.

---

# SECTION 0 — FUND SNAPSHOT & INVESTOR FIT

*Run in ALL modes.*

## 0.1 Fund snapshot

| Metric | Value | Category average / comparison | Source | As of |
|---|---|---|---|---|
| AMC | | | | |
| Fund category | | | | |
| Benchmark | | | | |
| Inception date (Direct Plan) | | | | |
| AUM (₹ crore) | | | | |
| Direct expense ratio | | | | |
| Exit load | | | | |
| Minimum SIP | | | | |
| SEBI Riskometer level | | | | |
| Fund managers | | | | |

Explain any significant difference between scheme inception and direct-plan inception.

## 0.2 Investment horizon suitability

Use these as starting guidelines, adjusted for the fund's actual category and risks:

| Investment horizon | Potentially suitable categories |
|---|---|
| Under 3 years | Appropriate debt / arbitrage funds |
| 3–5 years | Suitable hybrid funds |
| 5–7 years | Large-cap and large & mid-cap equity |
| 7–10 years | Diversified equity funds |
| 10+ years | Diversified equity, with possible mid/small-cap or sector exposure |

These are not guarantees of capital safety or positive returns.

Identify:

- Minimum reasonable holding horizon.
- Preferred investment horizon.
- Whether the fund matches MY INVESTMENT HORIZON, if provided.
- Who should avoid it because of a short investment period.

## 0.3 Investor risk suitability

Classify risk relative to the category using actual drawdowns and recovery history.

- **Low risk tolerance:** May stop SIPs or sell during a major correction.
- **Moderate risk tolerance:** Can continue SIPs through corrections.
- **High risk tolerance:** Can tolerate substantial falls and may invest additional money.

Explain the potential decline an investor would realistically need to tolerate.

Do not assume that willingness to invest during a fall automatically means the investment is suitable.

---

# SECTION A — PORTFOLIO QUALITY & DIVERSIFICATION

*Run in FULL and PORTFOLIO modes.*

## A1. Holdings concentration

Provide:

- Total number of equity holdings.
- Top 10 stocks and their individual weights.
- Top 5 combined weight.
- Top 10 combined weight.
- Largest individual holding.
- Cash allocation.
- Debt allocation, if any.

| Rank | Stock | Sector | Portfolio weight | Source | As of |
|---|---|---|---|---|---|

Flag:

- Any individual stock above 5%.
- Top 5 holdings exceeding 30%.
- Unusually concentrated portfolios relative to category peers.
- Hidden concentration through related companies or industries.

Explain whether the holdings are diversified or dependent on a few companies.

## A2. Portfolio activity

Compare the most recent three monthly portfolios, where available.

Identify:

- Newly added stocks.
- Completely exited stocks.
- Significant increases/decreases in major holdings.
- Portfolio turnover ratio and its measurement period.
- Whether recent portfolio activity suggests a stable or frequently rotating strategy.

Distinguish price-driven weight changes from actual buying and selling when data allows.

## A3. Portfolio valuation

| Metric | Fund | Category average | Source | As of |
|---|---|---|---|---|
| Portfolio P/E | | | | |
| Portfolio P/B | | | | |
| Turnover ratio | | | | |
| Cash allocation | | | | |
| Debt allocation | | | | |

Assess whether valuations indicate relatively expensive holdings, while acknowledging differences in sector composition and growth profiles.

Do not treat a low P/E as automatic evidence of quality.

## A4. Sector exposure

Show the top eight sectors.

| Sector | Fund weight | Benchmark weight | Overweight / underweight | Source & date |
|---|---|---|---|---|

Flag:

- Any unusually high individual-sector allocation.
- Related financial sectors (banks, NBFCs, insurance, financial services) exceeding approximately 35% collectively.
- Other economically correlated sectors with substantial combined exposure.
- Significant differences from the benchmark.

### Sector allocation changes

Compare sector exposures across the last 4–6 quarters, where disclosures permit.

Determine:

- Which sectors gained weight.
- Which sectors lost weight.
- Whether sector allocation is stable or frequently rotating.
- Whether the fund has become concentrated in a recently popular theme.

Explain whether recent sector changes increase portfolio risk.

## A5. Market-cap allocation

| Market cap | Fund allocation | Benchmark allocation | Category requirement | Source & date |
|---|---|---|---|---|
| Large cap | | | | |
| Mid cap | | | | |
| Small cap | | | | |
| Other / cash | | | | |

Check the actual applicable SEBI category requirements.

For example:

- Multi-cap funds generally require at least 25% each in large-, mid- and small-cap stocks.
- Flexi-cap funds do not have the same minimum allocation requirement for each market-cap segment.

Do not apply multi-cap restrictions to flexi-cap funds.

Identify:

- Whether the fund meets applicable category rules.
- Whether the allocation matches its stated investment mandate.
- Whether it has become more aggressive or conservative over time.

## A6. Portfolio overlap with MY OTHER FUNDS

If MY OTHER FUNDS are provided, compare the latest available holdings.

| Other fund | Portfolio overlap % | Common stocks | Top shared holdings | Source & date |
|---|---|---|---|---|

Calculate percentage overlap using:

**Overlap = Sum of the smaller portfolio weight for every common stock.**

Use weights from both funds, normalized consistently.

Also show:

- Number of common stocks.
- Combined weights of the most important shared stocks in each fund.
- Top five shared companies.
- Effective share of my total invested money exposed to these five companies, if allocation amounts are provided.
- Common sector concentration.

If fund allocation amounts are missing, do not assume equal allocation. Mark the effective combined exposure as unavailable.

Interpretation:

- Below 30%: Generally lower holdings overlap.
- 30–50%: Moderate overlap.
- Above 50%: Potentially substantial duplication.

These are screening guidelines, not automatic investment decisions.

### Peer overlap

Compare holdings with three closest funds in the same category.

Identify whether the fund:

- Provides genuinely different exposure.
- Closely resembles its peers.
- Appears index-like despite active management.

**Portfolio verdict:** Does adding this fund improve diversification or mainly duplicate existing exposure?

---

# SECTION B — RETURNS, RISK & DRAWDOWN ANALYSIS

*Run in FULL and RISK modes.*

## B1. Rolling returns — highest priority

Evaluate:

- 3-year rolling returns.
- 5-year rolling returns.
- 10-year rolling returns, if sufficient history exists.

| Rolling period | Fund minimum | Fund average | Fund maximum | Benchmark average | Category average | Benchmark beat % | Category beat % | Source & window |
|---|---|---|---|---|---|---|---|---|

For each period, compare minimum, average and maximum values against the benchmark and category wherever possible.

Additionally, calculate for 3-year rolling returns:

| Measure | Percentage of rolling observations | Source & window |
|---|---|---|
| Return below 0% | | |
| Return below 8% annualized | | |
| Return below 12% annualized | | |
| Fund beat benchmark | | |
| Fund beat category average | | |

Explain:

- How often the fund outperformed.
- Whether outperformance is consistent or concentrated in a few periods.
- How weak its worst rolling-return windows were.
- Whether the current manager was responsible for the evaluated track record.

**Why rolling returns matter:** They examine returns from many different investment start dates, reducing dependence on one favorable entry or exit date.

## B2. Point-to-point returns — secondary context

| Period | Fund CAGR | Benchmark CAGR | Category average CAGR | Rank / percentile if available | Source & date |
|---|---|---|---|---|---|
| 1 year | | | | | |
| 3 years | | | | | |
| 5 years | | | | | |
| 10 years | | | | | |

Do not judge an equity fund primarily on returns covering less than three years.

Flag exceptionally strong recent returns that may have resulted from a temporary market or sector rally.

## B3. Risk and volatility ratios

| Metric | Fund | Category average | Benchmark | Preferred interpretation | Pass / Borderline / Fail | Calculation window & source |
|---|---|---|---|---|---|---|
| Standard deviation | | | | Lower preferred; 13–16% can be reasonable for some diversified equity categories, >20% high | | |
| Beta | | | | Below or approximately 1 generally preferred | | |
| Sharpe ratio | | | | Higher preferred | | |
| Sortino ratio | | | | Higher preferred | | |
| Jensen's alpha | | | | Positive preferred | | |
| Information ratio | | | | Positive and consistently strong preferred | | |
| Upside capture | | | | Above 100 preferred | | |
| Downside capture | | | | Below 100 preferred | | |

Treat these thresholds as context-dependent, not universal pass/fail rules.

Explain each ratio in one plain sentence:

- Standard deviation: How widely fund returns fluctuate.
- Beta: How sensitive the fund is to benchmark movements.
- Sharpe: Return earned relative to total volatility.
- Sortino: Return earned relative to harmful downside volatility.
- Alpha: Risk-adjusted performance relative to the benchmark.
- Information ratio: Consistency of active returns relative to tracking error.
- Upside capture: Participation when the benchmark rises.
- Downside capture: Participation when the benchmark falls.

For each ratio:

1. Compare with the category.
2. Identify the actual calculation window.
3. Explain whether the difference is meaningful.
4. Flag one-year ratios as potentially misleading.
5. Avoid comparing ratios calculated with incompatible methods.

## B4. Maximum drawdown

Calculate or obtain the maximum drawdown over the most recent five years.

| Metric | Fund | Benchmark | Source & measurement period |
|---|---|---|---|
| Maximum drawdown | | | |
| Previous peak date | | | |
| Trough date | | | |
| Peak-to-trough duration | | | |
| Recovery date | | | |
| Recovery time | | | |

If the fund has not recovered, explicitly state **"Not yet recovered as of [date]."**

Use an appropriate total-return benchmark where available.

## B5. Historical market corrections

Evaluate major falls since the fund's inception, where relevant:

- March 2020 COVID crash.
- Major corrections during 2022.
- Most recent meaningful market correction.
- Any other significant market decline during the fund's history.

| Market event | Fund decline | Benchmark decline | Fund recovery time | Benchmark recovery time | Source & dates |
|---|---|---|---|---|---|

Do not include an event that occurred before the fund existed.

Explain:

- How much ₹1,00,000 invested before the decline would have fallen to, using verified decline percentages.
- Whether the fund protected capital better than its benchmark.
- Whether recovery was faster or slower.
- Whether a low-risk investor could realistically have tolerated the decline.

## B6. Risk verdict

Classify the fund as:

**Low / Moderate / High risk relative to its category.**

Provide reasons using:

- Rolling-return downside.
- Volatility.
- Downside capture.
- Maximum drawdown.
- Recovery duration.
- Portfolio concentration.

State the recommended minimum horizon and suitable investor risk profile.

---

# SECTION C — FUND MANAGER & AMC HISTORY

*Run in FULL mode.*

## C1. Current fund manager details

| Manager | Managing this fund since | Years on this fund | Total industry experience | Other funds managed | Source & date |
|---|---|---|---|---|---|

Include:

- Education and professional background.
- Previous AMC experience.
- Relevant investment strategy.
- Other important funds currently or previously managed.
- Verified performance record under that manager.

Distinguish the manager's personal tenure from the scheme's total performance history.

## C2. Fund manager changes

Provide a historical timeline of manager appointments and exits since inception, where verifiable.

| Manager | Start date | End date | Fund return during tenure | Benchmark return | Source |
|---|---|---|---|---|---|

Flag:

- Manager changes within the past two years.
- Frequent changes.
- A large share of the historical performance belonging to a former manager.
- Significant strategy changes following leadership changes.

Do not attribute fund performance to a particular manager when other co-managers or strategy changes prevent that conclusion.

## C3. AMC quality

Evaluate:

- AMC total AUM and approximate industry position.
- Consistency of its other comparable equity funds.
- Investment team continuity.
- Risk-management practices, where publicly documented.
- Material governance controversies.
- SEBI or other regulatory actions.

Focus on verifiable facts rather than AMC reputation alone.

---

# SECTION D — NEWS & RED FLAGS

*Run in FULL mode.*

Research developments from the most recent 12 months.

Check for:

1. Fund manager resignations or appointments.
2. Investment mandate changes.
3. Benchmark changes.
4. Mergers and scheme restructurings.
5. Category reclassification.
6. Regulatory or SEBI actions.
7. Material AMC governance issues.
8. Significant inflows or redemptions.
9. Rapid AUM growth or decline.
10. Unusual portfolio concentration.
11. Style drift.
12. Excessive trading or turnover.
13. Recent return-chart hype.
14. Performance dependent on a temporary sector rally.
15. Risk of mean reversion following unusually strong returns.

| Date | Event | Verified source | Potential investor impact | Severity |
|---|---|---|---|---|

Severity:

- Low
- Moderate
- High

Distinguish verified negative developments from ordinary market fluctuations.

If no material issues are found, state:

**"No material red flags identified in the sources reviewed during the last 12 months."**

Do not claim that the fund has no risks.

---

# SECTION E — PEER COMPARISON

*Run in FULL and RISK modes.*

Select 3–5 relevant funds from the same SEBI category.

Prefer funds with:

- Similar investment mandates.
- Meaningful operating history.
- Comparable direct-plan options.
- Relevant AUM and portfolio characteristics.

## E1. Performance and risk peers

| Metric | Analysed fund | Peer 1 | Peer 2 | Peer 3 | Category average |
|---|---|---|---|---|---|
| 3Y average rolling return | | | | | |
| 5Y average rolling return | | | | | |
| 10Y average rolling return | | | | | |
| 3Y benchmark beat % | | | | | |
| Sharpe ratio | | | | | |
| Sortino ratio | | | | | |
| Beta | | | | | |
| Standard deviation | | | | | |
| Downside capture | | | | | |
| Maximum drawdown | | | | | |
| AUM (₹ crore) | | | | | |
| Direct expense ratio | | | | | |

Provide the source, as-of date and calculation window for each row or value through clearly labeled table annotations.

Do not rank unavailable values as zero.

## E2. Peer interpretation

Identify:

- Best rolling-return consistency.
- Best downside protection.
- Best risk-adjusted returns.
- Lowest expense ratio.
- Most reasonable fund size.
- Most stable management history, if evaluated.

Distinguish between:

- Strongest historical performer.
- Lowest-risk option.
- Best risk-adjusted performer.
- Best complementary fund.

Avoid presenting the highest-return fund as automatically the best investment.

---

# SECTION F — COST, SCORECARD & FINAL VERDICT

*Run in ALL modes.*

## F1. Cost and AUM evaluation

| Metric | Fund | Category average | Interpretation | Source & date |
|---|---|---|---|---|
| Direct expense ratio | | | | |
| Expense ratio percentile | | | | |
| AUM (₹ crore) | | | | |
| AUM change over 12 months | | | | |
| Exit load | | | | |

Guidelines for actively managed diversified equity funds:

**Expense ratio**

- Below 1%: Generally attractive.
- 1–1.2%: Often reasonable, depending on the category.
- Above 1.2%: Examine whether performance and strategy justify the cost.

**AUM**

- ₹3,000–15,000 crore: Practical screening range for established active equity funds, not a universal optimum.
- Very small/new: May have limited history or operating scale.
- Very large: Could reduce flexibility, particularly in small-cap and mid-cap strategies.

Do not penalize passive funds or debt funds using active-equity AUM rules.

Check AUM relative to the fund's actual investment universe and market liquidity.

## F2. Scorecard

Use:

- **PASS:** Clear positive evidence relative to appropriate peers.
- **BORDERLINE:** Mixed or inconclusive evidence.
- **FAIL:** Meaningful weakness supported by data.
- **NOT EVALUATED:** Outside the selected mode or insufficient verified data.

| Evaluation criterion | Key result | Rating | One-line evidence |
|---|---|---|---|
| Rolling-return consistency | | | |
| Volatility | | | |
| Risk-adjusted returns | | | |
| Maximum drawdown | | | |
| Recovery behavior | | | |
| Individual stock concentration | | | |
| Sector concentration | | | |
| Market-cap allocation | | | |
| Overlap with my funds | | | |
| Expense ratio | | | |
| AUM size | | | |
| Manager stability | | | |
| AMC / regulatory issues | | | |

Only score checks supported by the selected mode.

Never convert missing information into a PASS.

Do not calculate an overall numeric rating unless a transparent, justified weighting methodology is available.

## F3. Final verdict

Write one concise, evidence-based paragraph covering:

1. **Who should consider this fund:** Appropriate horizon and risk tolerance.
2. **Who should avoid it:** Investors whose horizon, volatility tolerance or existing holdings make it unsuitable.
3. **Portfolio fit:** Whether it adds diversification or duplicates MY OTHER FUNDS, if provided.
4. **Main strengths:** The two or three strongest supported findings.
5. **Main weaknesses:** The two or three most important supported concerns.
6. **Alternatives:** One or two better or complementary funds in the same category, but only if verified comparisons justify them.

Finish with a clear conclusion:

**FINAL ASSESSMENT: CONSIDER / CONSIDER WITH CAUTION / AVOID / INSUFFICIENT DATA**

Give the main reason in no more than two sentences.

Do not imply that historical returns guarantee future results.

---

# REQUIRED OUTPUT QUALITY CHECK

Before responding, verify:

- [ ] Tickertape was checked first.
- [ ] Critical data was cross-checked against official AMC/AMFI sources where possible.
- [ ] Every numeric metric has a source and date.
- [ ] Every risk ratio has a stated calculation window.
- [ ] Rolling returns are prioritized over point-to-point returns.
- [ ] Fund-manager tenure is distinguished from scheme history.
- [ ] Category rules are correctly applied.
- [ ] Portfolio overlap uses verified holdings.
- [ ] Missing values are clearly marked.
- [ ] Peer comparisons use compatible periods and calculations.
- [ ] All scorecard ratings have supporting evidence.
- [ ] No estimated or invented financial figures are included.
- [ ] Every metric table includes a plain-language "What this means" explanation.
- [ ] Only sections required by the chosen mode are included.

# SOURCES

End with a numbered list of actual sources used.

For each source include:

1. Source name.
2. Direct URL.
3. Publication or data date.
4. Metrics obtained from that source.

Clearly identify any important gaps or conflicts between sources.

End the entire analysis with:

**"This is information, not financial advice. Mutual fund investments are subject to market risks. Past performance does not guarantee future returns."**
