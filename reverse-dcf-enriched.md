<!-- Enriched version — source: reverse-dcf-substack.md (Substack adaptation). Distinct quantaval.com links: 16 (incl. homepage). Prepared 2026-11-09. -->

# Reverse DCF: the growth the market has already priced in

*Every stock price contains a forecast. This issue shows you how to read it.*

A [discounted cash flow model](https://quantaval.com/dcf-calculator) starts from your assumptions and estimates what a stock is worth. A reverse DCF starts from today's price and works out the growth the market is already assuming. That single inversion turns a price debate into an operating question you can actually check.

## The idea in one paragraph

A stock's price implies a set of future cash flows. If you take the price as given, fix a discount rate and a terminal growth rate, the only free variable left is the growth rate the market must be expecting. Solve for it. Then compare that implied growth rate with what the company has actually delivered and what its industry can plausibly support. If the market is pricing in 25% annual growth for a decade from a business that has grown 6% a year, you have found the disagreement — and you know exactly what would have to be true for the price to make sense.

## The formula

A reverse DCF solves for the growth rate `g` that makes a discounted cash flow value equal today's price:

> Solve g such that: Σ FCF₀(1+g)ᵗ ÷ (1+WACC)ᵗ + PV(Terminal Value) − Net Debt = Price × Shares
>
> Terminal Value (Gordon growth) = FCF₅ × (1 + g_terminal) ÷ (WACC − g_terminal)

There is no closed-form answer — you test growth rates until the DCF equals the price (a "goal seek").

## Worked example (hypothetical)

Take a hypothetical company, Example Corp — invented for teaching only, not a real company.

- Current share price: $60.00
- Shares outstanding: 500 million
- Net debt: $2,000 million
- Starting free cash flow: $1,000 million
- Discount rate (WACC): 9%
- Terminal growth rate: 2.5%
- Forecast period: 5 years

Enterprise value implied by the price: $60.00 × 500M + $2,000M = **$32,000 million**.

Now solve for the growth rate that makes a five-year DCF with a Gordon terminal value equal $32,000 million. The answer is roughly **19.8% free cash flow growth every year for five straight years**, then a sudden drop to 2.5% forever.

That is the market's assumption, stated plainly. The question is no longer "is $60 cheap?" but "can this business grow free cash flow ~20% a year for five years?" History, capacity, competition and management execution decide that — and the reverse DCF gives you the number to test them against.

### Don't trust one number — read the sensitivity

| WACC \ Price | $40 | $50 | $60 | $70 | $80 |
| --- | --- | --- | --- | --- | --- |
| 8.0% | 6.3% | 11.2% | 15.3% | 19.0% | 22.3% |
| 9.0% | 10.4% | 15.5% | 19.8% | 23.6% | 27.0% |
| 10.0% | 14.1% | 19.4% | 23.9% | 27.8% | 31.4% |

Change the WACC by one point and the implied growth moves several points. A single implied growth number without its range is false precision.

## Why this beats a regular DCF for checking a price

A forward DCF is fragile: small changes to the discount rate or terminal growth move the answer by double digits, and it is easy to tweak inputs until the output feels right. A reverse DCF removes that temptation. The price is fixed, so the output is a growth rate you can compare with history — [trailing 3-year revenue growth](https://quantaval.com/equity-research), the sector median, the company's own [reinvestment capacity](https://quantaval.com/capex-fcf).

It is also the fastest way to find where you disagree with the market. Two analysts can argue forever about whether a stock is worth $55 or $65. They can settle the argument in one line once they see the price implies 20% growth and the business has never grown faster than 8%.

## When reverse DCF fails

- **Negative or unstable cash flows.** If free cash flow is negative, the model has nothing to grow. Use an earnings-based or [asset-based model](https://quantaval.com/liquidation-value) instead.
- **Cyclical businesses at a peak.** A peak-year cash flow extrapolated forward overstates what the cycle can deliver. Normalise the starting cash flow first.
- **The discount rate still matters.** Always show [the sensitivity](https://quantaval.com/rate-sensitivity).
- **It is not a verdict.** An implied growth rate above history does not mean the stock is overvalued; it means the market expects something the past does not show. Sometimes the market is right.

## How to use it in practice

1. Run the reverse DCF on the stock you own or are considering.
2. Write down the implied growth rate and the assumptions behind it (WACC, terminal growth, forecast years).
3. Compare it with the company's trailing growth, the sector median and [the reinvestment rate](https://quantaval.com/sales-to-capital) the balance sheet can support.
4. If the gap is large, decide which side of it you are on — and what evidence would change your mind.
5. Cross-check with other models. A single DCF, however inverted, is one view. QuantaVal runs 88 models in its [Hyper Engine](https://quantaval.com/hybrid-engine) (62 in the free calculator) — [DCF](https://quantaval.com/dcf-calculator), [reverse DCF](https://quantaval.com/reverse-dcf), [multiples](https://quantaval.com/relative-value), [NAV](https://quantaval.com/nav-per-share), [ROIC vs WACC](https://quantaval.com/roic-wacc) — and the disagreement between models is often more informative than any one of them.

If you are still building a shortlist, the [free stock screener](https://quantaval.com/screener) scans 2,000+ stocks on valuation filters — DCF upside included — so you can start from the names that already screen as undervalued.

## Try it yourself

QuantaVal's [free reverse DCF calculator](https://quantaval.com/reverse-dcf) solves the implied growth for any stock from live fundamentals, and the [free DCF calculator](https://quantaval.com/dcf-calculator) runs the forward model the same way. Visitors get 3 shared calculations a day, resetting at midnight UTC, no credit card required, and the full methodology is free to read. Browse all 62 free tools in the [calculators index](https://quantaval.com/calculators).

And when the question is not one stock but the rate environment around it, the [macro-adjusted DCF](https://quantaval.com/macro-adjusted) stress-tests fair value across rate cycles, while the [risk-adjusted calculator](https://quantaval.com/risk-adjusted) blends bull, base and bear cases into one probability-weighted value.

---

*Figures in the worked example are illustrative, not a forecast for any real company, and nothing in this article is investment advice. Do your own research.*

*— The QuantaVal team. [QuantaVal](https://quantaval.com/) is a quantitative valuation engine: deterministic math from audited financial data, not opinions or headlines.*
