# Scenario stress tests: 2020 COVID QE, 2022 inflation, 2023 SVB, fiscal-pressure cuts

Research cutoff: 2026-06-02.

Purpose: run out-of-sample stress tests against large historical events and near-current institutional-pressure cases. These are not statistical forecasts. They test whether the Kevin Warsh perspective skill produces the right pattern of reasoning, boundaries, and policy instincts.

Scoring:

- Strong match: predicts both stance and reasoning.
- Partial match: predicts stance but misses a design constraint, or predicts reasoning but not public/institutional behavior.
- Miss: materially wrong.

## Summary

| Case | Score | What the skill got right | Calibration needed |
|---|---|---|---|
| 2020 COVID QE | Strong match | Treats true market dysfunction as emergency; supports liquidity/QE for market functioning; demands exit and fiscal boundary | None material |
| 2022 inflation | Strong match | Rejects "transitory" excuse once inflation broadens; emphasizes price-stability credibility and faster normalization | None material |
| 2023 SVB | Strong-to-partial match | Supports depositor/liquidity backstop if contagion risk is real while imposing losses on shareholders/management and strengthening supervision | Add explicit backstop-design audit: pricing, collateral valuation, loss allocation, sunset |
| Fiscal-pressure rate cuts | Strong match | Distinguishes public political speech from actual loss of monetary independence; cuts only if mandate/data justify them | None material |

Overall: 3 strong matches, 1 strong-to-partial match, 0 misses.

## Test 1: 2020 COVID QE and emergency facilities

### Facts available at the time

- COVID created a sudden stop in real activity and market stress.
- The Fed moved the funds-rate target to 0 to 1/4 percent and directed purchases of Treasury securities and agency MBS in amounts needed to support smooth market functioning.
- The Fed's June 2020 Monetary Policy Report said the balance sheet increased from $4.2 trillion at the start of 2020 to $7.2 trillion in June 2020.
- Warsh publicly argued in March/April 2020 that central banks are born as crisis fighters and should provide liquidity against good collateral to solvent borrowers. He distinguished this from peacetime fine-tuning and warned against the Fed picking winners and losers.
- By 2025, Warsh's Hoover discussion treated the post-pandemic policy mix as a source of later inflation and fiscal-monetary irresponsibility, while preserving the idea that crisis action can be legitimate.

Primary/high-value sources:

- Federal Reserve, FOMC statement, 2020-03-23: https://www.federalreserve.gov/newsevents/pressreleases/monetary20200323a.htm
- Federal Reserve, Monetary Policy Report, June 2020 balance-sheet discussion: https://www.federalreserve.gov/monetarypolicy/2020-06-mpr-part2.htm
- Hoover Institution, "Kevin Warsh And The Long Road Back To Economic Recovery", 2020: https://www.hoover.org/research/kevin-warsh-and-long-road-back-economic-recovery-0
- Hoover Institution, "Inflation Is A Choice", 2025: https://www.hoover.org/research/inflation-choice-kevin-warsh-fixing-federal-reserve

### Skill prediction

A Warsh-style read should:

- Classify the episode as market dysfunction/systemic-risk conditions, not ordinary weakness.
- Support aggressive liquidity and balance-sheet action to preserve Treasury, MBS, repo, dollar-funding, and credit channels.
- Prefer liquidity through banks or broad facilities for solvent borrowers over central-bank selection of individual winners.
- Keep the fiscal backstop visible when credit risk is fiscal-adjacent.
- Warn that the emergency label must expire when market functioning returns.
- Avoid judging the success of the intervention by asset-price gains alone.

### Comparison with later Warsh behavior

Strong match.

Warsh's 2020 Hoover conversation matches the skill almost exactly: emergency action is legitimate; monetary policy should be aggressive in war/crisis, humble in peacetime; liquidity should go to solvent comers against good collateral; the Fed should not pick winners and losers. His later critique of pandemic-era policy focuses less on the initial firebreak and more on treating emergency policy as normal policy, helping fiscal profligacy, and fueling later inflation.

### Calibration

No core change. This confirms the current distinction: anti-normalized-QE is not anti-crisis-QE.

## Test 2: 2022 inflation surge

### Facts available at the time

- In June 2022, CPI rose 1.3 percent month-over-month and 9.1 percent year-over-year, the largest 12-month increase since November 1981.
- Core CPI rose 5.9 percent year-over-year, and the BLS described the increase as broad-based.
- The FOMC raised the funds-rate target range by 75 basis points on 2022-06-15 to 1.50-1.75 percent, continued balance-sheet reduction, and said it was strongly committed to returning inflation to 2 percent.
- Warsh later argued that inflation is a choice, that price stability was Congress's assignment to the Fed, and that supply shocks are relative-price changes unless they become self-reinforcing inflation.

Primary/high-value sources:

- BLS CPI release, June 2022: https://www.bls.gov/news.release/archives/cpi_07132022.htm
- Federal Reserve, FOMC statement, 2022-06-15: https://www.federalreserve.gov/newsevents/pressreleases/monetary20220615a.htm
- Hoover Institution, "Inflation Is A Choice", 2025: https://www.hoover.org/research/inflation-choice-kevin-warsh-fixing-federal-reserve
- Truth in Accounting summary of Warsh WSJ op-ed, "The Fed is the main inflation culprit", 2021-12-13: https://www.truthinaccounting.org/news/detail/the-fed-is-the-main-inflation-culprit

### Skill prediction

A Warsh-style read should:

- Treat inflation as a credibility crisis once it is broad, persistent, and self-reinforcing.
- Reject the move of blaming persistent inflation only on supply chains, energy, Putin, or bad luck.
- Support decisive rate hikes and balance-sheet normalization.
- Say the Fed should have moved earlier once the market and inflation dashboard no longer supported "transitory."
- Distinguish pain from policy error: tightening can hurt growth, but credibility loss hurts the monetary system.
- Communicate in institutional terms rather than partisan terms.

### Comparison with later Warsh behavior

Strong match.

The skill's predicted diagnosis matches Warsh's later public framework: supply shocks can explain relative-price moves, but inflation becomes the Fed's responsibility when higher prices beget higher prices. His 2025 framing that "inflation is a choice" and his criticism of fiscal-monetary profligacy are exactly the skill's price-stability/institutional-capital model.

### Calibration

No change. The test confirms that the skill should become less patient once inflation breadth and persistence are visible. It should not let the existence of supply shocks become an all-purpose excuse.

## Test 3: 2023 Silicon Valley Bank and BTFP

### Facts available at the time

- SVB was closed on 2023-03-10 after rapid deposit outflows.
- On 2023-03-12, Treasury, the Fed, and FDIC invoked actions that fully protected SVB depositors, while shareholders and certain unsecured debtholders were not protected and senior management was removed.
- The Fed created the Bank Term Funding Program (BTFP), offering one-year loans against Treasuries, agency debt, agency MBS, and other qualifying assets valued at par.
- The Fed's April 2023 review found SVB management failed to manage risks; supervisors failed to fully appreciate vulnerabilities; supervisors did not force fixes quickly enough; and regulatory tailoring/supervisory stance weakened effective supervision.

Primary/high-value sources:

- Joint Treasury/Fed/FDIC statement, 2023-03-12: https://www.federalreserve.gov/newsevents/pressreleases/monetary20230312b.htm
- Federal Reserve BTFP announcement, 2023-03-12: https://www.federalreserve.gov/newsevents/pressreleases/monetary20230312a.htm
- Federal Reserve SVB review key takeaways, April 2023: https://www.federalreserve.gov/publications/2023-April-SVB-Key-Takeaways.htm
- Federal Reserve SVB review press release, 2023-04-28: https://www.federalreserve.gov/newsevents/pressreleases/bcreg20230428a.htm

### Skill prediction

A Warsh-style read should:

- Run the discrimination test first: is this a weak-firm failure or a system-wide confidence failure?
- Support rapid action to prevent depositor panic if markets are starting to stop distinguishing strong from weak institutions.
- Protect the payment/credit system, not equity holders, unsecured creditors, or failed managers.
- Use liquidity tools for market functioning while preserving the monetary-policy fight against inflation.
- Demand a postmortem on supervision, liquidity, interest-rate risk management, uninsured deposits, and resolution credibility.
- Avoid turning every regional bank into a permanent state client.

### Comparison with later institutional behavior

Strong-to-partial match.

The official response matches the skill's main policy architecture: depositors protected, shareholders and certain unsecured debtholders not protected, management removed, system-wide liquidity facility created, and later supervisory review focused on management failure plus supervisory/regulatory failure. The partial element is design detail: BTFP's par valuation of collateral is a more generous backstop than a strict Bagehot-style penalty-rate/haircut design. A Warsh-style skill should explicitly audit whether a backstop's terms preserve market discipline or subsidize duration-risk mistakes.

### Calibration

Add a backstop-design audit:

- Who is protected: depositors, counterparties, shareholders, debtholders, management?
- What is the pricing: penalty, market, subsidized, or hidden subsidy?
- How is collateral valued: market value, par, haircut, or discretionary?
- Who bears losses: bank, Deposit Insurance Fund, special assessment, Treasury, taxpayer?
- What is the sunset/exit plan?

This strengthens the crisis-tools model without changing its core stance.

## Test 4: Fiscal pressure and demands for rate cuts

### Facts available at the time

- In 2019, the Fed cut rates while President Trump publicly pushed for more aggressive easing. The FOMC cited global developments and muted inflation pressures when it lowered the target range on 2019-07-31.
- In 2026, Warsh's Senate nomination hearing occurred amid concerns about White House pressure on rates. His prepared testimony committed to strictly independent monetary policy, while making the more nuanced point that elected officials stating their views does not itself destroy operational independence.
- Warsh's broader public record links Fed independence to staying in lane, price stability, and accountability.

Primary/high-value sources:

- Federal Reserve, FOMC statement, 2019-07-31: https://www.federalreserve.gov/newsevents/pressreleases/monetary20190731a.htm
- Senate Banking hearing page for Kevin Warsh nomination, 2026-04-21: https://www.banking.senate.gov/hearings/04/14/2026/nomination-hearing
- Warsh testimony PDF, 2026-04-21: https://www.banking.senate.gov/imo/media/doc/warsh_testimony_4-21-26.pdf
- Axios summary of Warsh testimony and White House pressure context, 2026-04-21: https://www.axios.com/2026/04/21/fed-trump-warsh-senate

### Skill prediction

A Warsh-style read should:

- Start with the mandate, not the President's or Treasury's preference.
- Say elected officials can state views on rates; the Fed must make the decision.
- Cut only if inflation, employment, financial conditions, and risk balance justify a cut.
- Treat fiscal debt-service pressure as a danger signal, not a reason to subordinate monetary policy.
- Communicate without personal combat: the best answer to pressure is performance.
- If data justify cuts, make clear that the policy is data-driven, not a concession.

### Comparison with later Warsh behavior

Strong match.

The 2019 Fed example shows how a central bank can cut while refusing to frame the cut as obedience to political pressure. Warsh's 2026 testimony matches the skill's pressure model: monetary-policy independence is essential, but elected officials expressing views on interest rates is not itself the breach. The breach would be letting those views override the mandate and the evidence.

### Calibration

No core change. The existing chair-constraint model is sound. The skill should keep separating:

- political noise,
- legitimate democratic oversight,
- fiscal dominance,
- and actual loss of operational monetary independence.

## Net update to the skill

Only one calibration is required:

**Backstop-design audit.** When the skill evaluates emergency facilities, depositor guarantees, swap lines, BTFP-style lending, or market backstops, it should not stop at "act or do not act." It must inspect terms: protected parties, pricing, collateral valuation, loss allocation, and exit plan.

This is especially important because Warsh can support a crisis backstop and still object to a poorly designed or normalized backstop.
