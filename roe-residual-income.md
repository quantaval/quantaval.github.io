---
layout: post
title: "ROE as a Price Tag: Valuing Book-Value Businesses with Residual Income"
---

# ROE as a Price Tag: Valuing Book-Value Businesses with Residual Income

*Most investors treat return on equity as a quality score. For a bank, it is something more useful: a price tag.*

Imagine a bank with $30 of book value per share, trading at $42. Is $42 cheap? The usual screening answer — "ROE above 15% is good, below 8% is bad" — wastes the number. For a bank, an insurer, or any business whose assets are mostly financial, ROE connects directly to value through one identity: a business is worth more than its book value only if it earns more on that book than its shareholders demand. Earn exactly the required return and the business is worth exactly its book. Earn less, and it is worth less than book — no matter how safe it feels.

## The three cases that explain every bank multiple

Before the formula, look at where it leads:

- **ROE = r (10%):** value = $30.00 — exactly book. A bank earning its cost of equity deserves a [price-to-book](https://quantaval.com/pb-ratio) of 1.0×, neither premium nor discount.
- **ROE above r (15%):** value = $51.43 — a premium to book is earned, not given.
- **ROE below r (8%):** value = $21.43 — below book, and correctly so: every dollar of equity retained destroys two dimes of value over time.

This is why "cheap at 0.8× book" is not an argument. If ROE sits below the cost of equity, 0.8× book can still be too expensive.

## The formula

The residual income method values a share as its book value plus the present value of the "residual" earnings above the required return:

> Value = BVPS + (ROE − r) × BVPS ÷ (r − g)

where BVPS is book value per share, ROE is the sustainable return on equity, r is the cost of equity (the return shareholders require), and g is the long-run growth rate of book value. The term (ROE − r) is the spread that does all the work — the same logic as [ROIC vs WACC](https://quantaval.com/roic-wacc) for industrial companies, applied to equity capital instead of all invested capital.

## Worked example (hypothetical)

Take a hypothetical bank, Example Regional Bancorp — invented for teaching only, not a real company.

- Book value per share: $30.00
- Share price: $42.00
- Sustainable ROE: 15%
- Cost of equity (r): 10%
- Long-run book growth (g): 3%

Value = $30.00 + (0.15 − 0.10) × $30.00 ÷ (0.10 − 0.03) = $30.00 + $21.43 = **$51.43**.

At a 15% sustainable ROE, the bank is worth about $51 a share — the $30 of book plus $21.43 for the excess returns that book can generate. Against the $42 price, that is upside — if, and only if, the 15% ROE is truly sustainable.

### Run it backwards: what ROE is the price already assuming?

Fix the price at $42 and solve for ROE instead. The answer is **12.8%**: the market is paying for a bank that earns 12.8% on equity forever. That is the same inversion a [reverse DCF](https://quantaval.com/reverse-dcf) performs on growth — here it turns "is $42 cheap?" into one checkable question: can this bank hold ROE above ~13% through a full credit cycle? Compare that with its own history in the [equity research terminal](https://quantaval.com/equity-research) before you argue with the price.

### Don't trust one number — read the sensitivity

| Cost of equity (r) | Implied value (ROE 15%, g 3%) |
| --- | --- |
| 9% | $60.00 |
| 10% | $51.43 |
| 11% | $45.00 |

One point on the discount rate moves the answer by roughly $6–9 a share. Show the range, never just the point estimate — the same discipline a [forward DCF](https://quantaval.com/dcf-calculator) demands.

## Where the ROE comes from: DuPont

ROE is not one number; it is three multiplied together: net profit margin × asset turnover × financial leverage. Two banks can both report 15% ROE — one from a wide lending margin, one from thin margins levered twelve times. They do not deserve the same multiple, because the levered one's ROE is the first to collapse when credit costs normalise. QuantaVal's [free ROE calculator](https://quantaval.com/roe-calculator) shows the full DuPont breakdown alongside the residual-income value, so you can see which of the three is doing the lifting before you trust the spread.

## When this method fails

- **Book value you cannot trust.** If loan losses are under-provisioned, book is overstated and every output inherits the error. Cross-check with [tangible book value](https://quantaval.com/tangible-equity), which strips intangibles and goodwill.
- **A peak-cycle ROE.** A bank earning 15% at the top of a credit cycle may earn 7% through it. Normalise ROE across the cycle first, or the premium you calculate is the cycle's, not the bank's.
- **Negative or near-zero book.** The formula has nothing to anchor to; use an earnings or [dividend discount model](https://quantaval.com/ddm) instead.
- **It is not a verdict.** A value above price means the market's implied ROE looks low against your estimate — it does not tell you whose estimate is wrong.

## Cross-checks before you act

No single model should carry a decision. Value the same bank with the [Graham Number](https://quantaval.com/graham) for a conservative floor, [NAV per share](https://quantaval.com/nav-per-share) where assets can be marked to market, and its [dividend yield and payout safety](https://quantaval.com/dividend-yield) if income is part of the thesis. QuantaVal runs 88 models in its [Hyper Engine](https://quantaval.com/hybrid-engine) (62 in the free calculator) and converges them into one fair-value range — the disagreement between models is often more informative than any one of them. If you are building a shortlist rather than valuing one name, the [free stock screener](https://quantaval.com/screener) scans 2,000+ stocks on valuation and profitability filters, and the [dividend-growth stock ideas](https://quantaval.com/stock-ideas/dividend-growth) list applies the same quality logic to income stocks.

## Try it yourself

The [ROE calculator](https://quantaval.com/roe-calculator) runs the residual-income method and the DuPont breakdown from live fundamentals, and the full set of 62 free tools sits in the [calculators index](https://quantaval.com/calculators). Visitors get 3 shared calculations a day, resetting at midnight UTC, no credit card required, and the full methodology is free to read. In the worst case — where the equity story fails entirely — the [liquidation value](https://quantaval.com/liquidation-value) tells you what the assets alone would return, and a [relative-value comparison](https://quantaval.com/relative-value) against peer banks tells you whether the discount is the bank's or the sector's.

---

*Figures in the worked example are illustrative, not a forecast for any real company, and nothing in this article is investment advice. Do your own research.*

*— The QuantaVal team. [QuantaVal](https://quantaval.com/) is a quantitative valuation engine: deterministic math from audited financial data, not opinions or headlines.*
