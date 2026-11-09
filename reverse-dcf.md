# Reading the Market's Forecast: What a Reverse DCF Reveals

*A price is not just a number — it is a growth forecast waiting to be decoded.*

## The idea in one paragraph

A reverse DCF starts from today's price instead of a growth forecast. It asks: what future growth would justify what the market is already paying? Take today's price as given, use today's cash flow, and the arithmetic works back to the one growth rate that would make those two numbers agree.

That simple shift in direction changes the question an investor has to answer. Rather than estimating future cash flows, you can read the market's own implied growth — and then judge for yourself whether that growth is credible.

## When a share price is already telling you the story

Every stock price contains a forecast. Before you buy a share, the price has already answered — now it is worth asking the right question in return.

Ask the market: if this company is worth $60 a share, how fast must it grow? If the only way the price makes sense is 25% growth a year for a decade, the price is demanding a lot. If it can only grow at 6%, it does not. The model will catch what the market already knows — a reverse DCF tests the assumption.

## The formula

Solve for *g* such that:

$$\sum_{t=1}^{5} \frac{FCF_0 (1 + g)^t}{(1 + WACC)^t} + PV(\text{Terminal Value}) - \text{Net Debt} = \text{Price} \times \text{Shares}$$

$$\text{Terminal Value (Gordon growth)} = \frac{FCF_5 \times (1 + g_{terminal})}{WACC - g_{terminal}}$$

There is no closed-form answer — you test growth rates until the equation balances. A spreadsheet or a calculator does that in seconds, and what matters is the answer, not the algebra.

## A worked example

Take a company with these numbers:

- Current share price: $60.00
- Shares outstanding: 500 million
- Net debt: $2,000 million
- Starting free cash flow: $1,000 million
- Discount rate (WACC): 9%
- Terminal growth rate: 2.5%
- Forecast period: 5 years

First, work out the enterprise value the price implies:

$$\text{Enterprise value} = $60.00 \times 500M + $2,000M = \textbf{$32,000 million}$$

Now solve for the growth rate that makes the DCF equal that value. The answer is roughly **19.8% free cash flow growth every year for five straight years**, then a sudden drop to 2.5% forever.

That is the market's assumption, written out in plain numbers. The question is no longer "is $60 cheap?" but "can this business grow free cash flow ~20% a year for five years?" History, capacity, and competition all have a view on that — and now you know exactly what to check.

## Don't trust one number — read the sensitivity table

| WACC \ Price | $40 | $50 | $60 | $70 | $80 |
| -------------- | --- | --- | --- | --- | --- |
| 8.0% | 6.3% | 11.2% | 15.3% | 19.0% | 22.3% |
| 9.0% | 10.4% | 15.5% | 19.8% | 23.6% | 27.0% |
| 10.0% | 14.1% | 19.4% | 23.9% | 27.8% | 31.4% |

Change the WACC by one point and the implied growth moves by several points. A single implied growth number, without its range, is false precision.

## Why this beats a regular DCF

A forward DCF is fragile: small changes in the forecast compound into large changes in value, and it is easy — consciously or not — to tweak the inputs until the output feels right. A reverse DCF removes that temptation. The price is fixed, so the output is a growth rate you can compare directly with history — [trailing 3-year revenue growth](https://quantaval.com/equity-research), the sector median, and the company's own [reinvestment capacity](https://quantaval.com/capex-fcf).

It is also the fastest way to find where you disagree with the market. Two analysts can argue forever about whether a stock is worth $55 or $65. They can settle the argument in one line once they see the price implies 20% growth and the business has never grown faster than 8%.

## When a reverse DCF fails

- **Negative or unstable cash flows.** If FCF is negative, the model has nothing to grow. Use an earnings-based or [asset-based model](https://quantaval.com/liquidation-value) instead.
- **Cyclical businesses at a peak.** Peak-year cash flow extrapolated forward overstates what the cycle can deliver. Normalise the starting cash flow first.
- **The discount rate still matters.** Always show [sensitivity](https://quantaval.com/rate-sensitivity).
- **It is not a verdict.** Implied growth above history does not mean the stock is overvalued; it means the market expects something the past does not show. Sometimes the market is right.

## How to use it in practice

1. Run a reverse DCF on a stock you own or are considering.
2. Write down the implied growth rate and the assumptions behind it (WACC, terminal growth, forecast years).
3. Compare it with the company's trailing growth, the sector median, and the [reinvestment rate](https://quantaval.com/sales-to-capital) the balance sheet can support.
4. If the gap is large, decide which side of it you are on — and what evidence would change your mind.
5. Cross-check with other models. A single DCF, however inverted, is one view. QuantaVal runs 88 models in its [Hyper Engine](https://quantaval.com/hybrid-engine) (62 in the free calculator) — [DCF](https://quantaval.com/dcf-calculator), [reverse DCF](https://quantaval.com/reverse-dcf), [multiples](https://quantaval.com/relative-value), [NAV](https://quantaval.com/nav-per-share), [ROIC vs WACC](https://quantaval.com/roic-wacc) — and disagreement between models is often more informative than any one of them.

If you are still building a shortlist, the [free stock screener](https://quantaval.com/screener) scans 2,000+ stocks on valuation filters — DCF upside included — so you can start from names that already screen as undervalued.

## Try it yourself

QuantaVal's [free reverse DCF calculator](https://quantaval.com/reverse-dcf) solves the implied growth for any stock from live fundamentals, and its [free DCF calculator](https://quantaval.com/dcf-calculator) runs the forward model the same way. Visitors get 3 shared calculations a day, resetting at midnight UTC, no credit card required, and the full methodology is free to read. Browse all 62 free tools in the [calculators index](https://quantaval.com/calculators).

And when the question is not one stock but the rate environment around it, the [macro-adjusted DCF](https://quantaval.com/macro-adjusted) stress-tests fair value across rate cycles, while the [risk-adjusted calculator](https://quantaval.com/risk-adjusted) blends bull, base and bear cases into one probability-weighted value.

## The bottom line

A reverse DCF changes what you argue about. Instead of fighting over a price target, you argue about a growth rate — and a growth rate is far easier to judge than a price. If the market's implied growth looks achievable, the price may be fair. If it looks impossible, the price is a warning. That is the whole point: start from the price, work back to the growth it implies, and then ask the only question that matters — can this business actually grow that fast?

---

*Figures in the worked example are illustrative, not a forecast for any real company, and nothing in this article is investment advice. Do your own research.*

*— The QuantaVal team. [QuantaVal](https://quantaval.com/) is a quantitative valuation engine: deterministic math from audited financial data, not opinions or headlines.*
