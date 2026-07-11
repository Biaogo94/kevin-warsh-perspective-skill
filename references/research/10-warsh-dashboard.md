# Warsh dashboard for policy analysis

Research cutoff: 2026-06-02.

Purpose: turn the skill's "market dashboard" instinct into a repeatable checklist. Use this file for live policy questions, backtests, scenario tests, FOMC statement analysis, and financial-stability judgments.

This is not a mechanical rule or trading system. It is an evidence map for forming a Warsh-style judgment.

## State classification

Start by classifying the environment:

| State | Signal | Policy posture |
|---|---|---|
| Normal adjustment | Markets reprice risk but continue to trade; inflation and employment data are interpretable | Use ordinary rate policy and communication discipline |
| Macro deterioration | Real activity slows or inflation persistence changes, but market plumbing works | Separate monetary response from fiscal/regulatory responsibilities |
| Market dysfunction | Price discovery, liquidity, or funding channels break down | Consider liquidity tools, but attach boundaries and exit |
| Systemic failure | Markets stop distinguishing strong from weak institutions; counterparty trust collapses | Act decisively to restore function, then design retreat |

## Inflation and price-stability panel

Use when judging rate policy, credibility, or cut pressure.

Core measures:

- Core PCE and headline PCE.
- CPI and core CPI.
- Trimmed mean or median inflation measures where available.
- Wage growth and unit labor cost pressure.
- Market and survey inflation expectations.
- Dollar, commodities, import prices, and breakevens as forward-looking cross-checks.

Warsh-style read:

- A one-off relative-price shock is not automatically a monetary-policy failure.
- Persistent, broadening inflation is a direct credibility problem.
- If inflation is above target and expectations are drifting, the burden of proof is against early easing.
- If inflation is falling but only because of one volatile category, keep humility.

Failure signals:

- Excusing persistent inflation by naming a cause rather than explaining why it will not propagate.
- Treating a soft CPI print as victory before expectations, wages, and breadth confirm it.

## Real-economy panel

Use when balancing dual-mandate risks.

Indicators:

- Payroll growth, unemployment, participation, hours, and job openings.
- Real income, consumption, savings, and household balance-sheet stress.
- Productivity, capex, business confidence, and small-business credit access.
- Manufacturing/services surveys and regional Fed reports.
- Housing activity and mortgage-credit conditions.

Warsh-style read:

- Monetary policy can affect demand, but cannot solve every supply, productivity, fiscal, or regulatory problem.
- Weak growth is not by itself a mandate to use every Fed instrument.
- If low growth is structural, overusing monetary policy can hide the real problem and reduce pressure on responsible authorities.

Failure signals:

- Treating a weak labor market as automatically validating balance-sheet expansion.
- Treating pro-growth reform as a substitute for price stability.

## Market-functioning panel

Use when deciding whether stress is discomfort or dysfunction.

Price indicators:

- Treasury curve, term premium, TIPS breakevens.
- Credit spreads: investment grade, high yield, bank CDS, commercial paper, interbank/funding spreads.
- Equity risk premiums, volatility, and cross-asset correlation.
- Dollar funding pressure and safe-haven flows.

Plumbing indicators:

- Treasury bid-ask spreads, market depth, auction tails, fails, and repo conditions.
- Commercial paper issuance, corporate issuance windows, and money-market fund behavior.
- Dealer balance-sheet capacity and willingness to intermediate.
- Settlement, collateral, margin, and counterparty behavior.

Backstop design:

- Protected parties: depositors, counterparties, shareholders, debtholders, management.
- Pricing: penalty, market, subsidized, or hidden subsidy.
- Collateral valuation: market value, par, haircut, or discretionary.
- Loss allocation: bank, Deposit Insurance Fund, special assessment, Treasury, taxpayer.
- Exit: sunset, repayment, unwind path, and conditions for ending the facility.

Warsh-style read:

- The central question is whether markets are discriminating among firms or losing trust in the architecture.
- Spreads widening can be healthy market discipline; frozen issuance and indiscriminate funding pressure can signal dysfunction.
- Liquidity facilities should target functioning, not the level of asset prices.
- A backstop can be justified in crisis and still badly designed if it subsidizes avoidable risk-taking or lacks an exit.

Failure signals:

- Calling every selloff "financial instability."
- Ignoring plumbing because macro aggregates still look tolerable.

## Balance-sheet panel

Use for QE, QT, reinvestment, reserve abundance, and Treasury-market questions.

Indicators:

- Fed asset holdings by maturity and security type.
- Reserve levels, ON RRP usage, bank reserve demand, and money-market rates.
- QT pace, reinvestment policy, and maturity composition.
- Security composition: Treasury bills/notes/bonds versus agency debt/MBS, and the destination of principal reinvestment.
- Treasury issuance size, maturity mix, auction performance, and dealer capacity.
- Term premium and market functioning around supply shocks.
- Fed remittances and fiscal optics.

Warsh-style read:

- The balance sheet is policy, not background plumbing.
- Composition is policy: changing agency exposure or duration can alter market footprint and institutional risk without changing the target rate.
- Passive runoff can be policy tightening if it changes expected financial conditions.
- QE may repair dysfunction in crisis, but repeated QE as growth policy risks dependency and blurred fiscal boundaries.
- QT should be explained as policy normalization, not treated as an accounting footnote.

Failure signals:

- Treating reserves or asset holdings as irrelevant because the policy rate is the "main" tool.
- Treating balance-sheet expansion and rate cuts as perfect substitutes.

## Institutional and political panel

Use for Fed independence, White House pressure, congressional oversight, and mandate creep.

Indicators:

- FOMC statement, minutes, SEP, press conference language, and dissents.
- Speeches by governors and presidents.
- Congressional hearings and statutory-remit debate.
- White House commentary on rates or balance sheet.
- Treasury-Fed coordination, debt-management context, and emergency-facility design.

Warsh-style read:

- Independence is strongest when the Fed stays in its lane and delivers price stability.
- Oversight is not the enemy of independence; fiscal commandeering is.
- Communication should clarify the reaction function, not multiply ambiguous signals.

Failure signals:

- Treating all political criticism as illegitimate.
- Letting the Fed solve elected officials' problems through quasi-fiscal tools.

## Communication panel

Use for statement drafting, forward guidance, and market reaction.

Audit exact words:

- Words that imply patience, vigilance, transience, review, conditionality, close monitoring, or balance of risks.
- Omissions that markets will read as signals.
- Differences between statement, press conference, minutes, and speeches.

Warsh-style read:

- Words are market operations when markets infer the reaction function from them.
- More transparency is not always more clarity.
- The best communication protects optionality while stating principles.

Failure signals:

- Adding language that sounds precise but pre-commits unintentionally.
- Letting communication celebrate asset-price gains before real data validate them.

## Decision template

For a live prompt, produce:

1. State classification: normal, macro deterioration, dysfunction, or systemic failure.
2. Mandate and instrument: what the Fed owns, and which tool is legitimate.
3. Dashboard facts: inflation, real economy, market functioning, balance sheet, institutional setting.
4. Risk ledger: credibility, employment, financial stability, fiscal boundary, market discipline.
5. Communication audit: what markets will hear.
6. Judgment: clear, provisional, and conditional on named facts.
