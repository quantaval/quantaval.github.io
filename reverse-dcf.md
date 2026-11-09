# Reading the Market's Forecast: What a Reverse DCF Reveals

*A price is not just a number — it is a growth forecast waiting to be decoded.*

## The idea in one paragraph

A reverse DCF starts from today's price instead of a growth forecast. It asks: what future growth would justify what the market is already paying? Take today's price as given, use today's cash flow, and the arithmetic works back to the one growth rate that would make those two numbers agree.

That simple shift in direction changes the question an investor has to answer. Rather than estimating future cash flows, you can read the market's own implied growth — and then judge for yourself whether that growth is credible. The method rests on the same single idea that underpins a reverse DCF:

$$\text{Intrinsic value} = \sum_{t=1}^{\infty} \frac{\text{FCF}_t}{(1 + \text{WACC})^t}, \qquad \text{FCF}_t = \text{FCF}_0(1 + g)^t$$

When that series converges into a closed form, the result becomes the formula every reverse DCF relies on:

$$\text{Price} = \frac{\text{FCF}_0 (1 + g)}{\text{WACC} - g} \quad\Rightarrow\quad g = \frac{\text{Price} \cdot \text{WACC} - \text{FCF}_0}{\text{Price} + \text{FCF}_0}$$

## When a share price is already telling you the story

Investors usually argue about whether a company is "cheap" or "expensive". Read the other way round, that debate is really about growth: if a company is expected to grow at 25% for a decade, the price makes sense. If it can only grow at 6%, it does not. The model will catch what the market already knows — a reverse DCF tests the assumption.

This gives the method two useful jobs. It acts as a filter for a whole watchlist — sorting companies by implied growth, then concentrating on the outliers — and as a check on a single idea before it is bought. Outliers worth looking into are the companies that need very little growth to justify a high price: a business with a high price tag and a modest growth requirement is simply being given an easier target to beat.

## Why this beats a regular DCF

| Fallacy | Why it fails | Reverse-DCF fix |
| ------- | ------------ | --------------- |
| Pick a single forecast | Multi-year growth forecasts are hard to get right — history shows steady compounding is the exception, not the norm. | The output is a hurdle, not a forecast — one number to beat. |
| Fit the number to a target price | A "plug" growth rate can be pushed up to 8% to justify a price, even when the business has never grown that fast. | The hurdle is revealed, not chosen — a 20% hurdle is visible as demanding. |
| Use a P/E multiple | A P/E of 20 can be cheap or expensive depending on growth. | A 20% growth hurdle is always a demanding hurdle. |

A regular DCF takes a growth assumption in and produces a price. A reverse DCF takes the current price in and outputs an implied growth rate. That work can be done with an 80/20 model — the Gordon growth model, corrected for market value — to give an instant answer in minutes, with no forecast unbundling required.

A normal DCF is as honest as the assumptions it is given, and the method never estimates future free cash flows directly. Prices are uncertain, but if the price reflects a good estimate of fair value then the market's bet is visible. [DCF Calculator](https://quantaval.com/calculators/dcf-calculator)

## Free calculators

Everything on QuantaVal is free, with no paywall, no signup, no payment details, and no subscription. The 88 models in the Hyper Engine include every standard valuation model for every company, with every calculator able to calculate a valuation for every company in the world. Every tool on the site can be used for free by anyone, anywhere in the world — simply choose a calculator and start.

Every calculator on the site is free to use. Explore 88 models, plus the tools on [QuantaVal](https://quantaval.com/), with:

- **88 models in the Hyper Engine** — the complete library: DCF, Gordon Growth, EPV, dividend discount, asset-based models, and 84 more.
- **62 calculators in the Free Calculator** — for use by people doing valuation work anywhere in the world.
- A complete, plain-English guide on valuation: start with the calculator you need [on the calculators page](https://quantaval.com/calculators), find your model there, and follow the step-by-step instructions on its page.
- A free [Valuation Hub](https://quantaval.com/valuation-hub): your complete valuation resource and your personal library of valuation models.
- **A [Reverse DCF Calculator](https://quantaval.com/calculators/reverse-dcf-calculator)** for instant implied-growth checks — no signup, no payment details.

Whatever you are doing, you will find it on this page: the Türkçe Stock Exchange's value, a quick market check, and a full fairness opinion for a client — and the 88 models deliver all three.

## No paywalls, no signups, no credit cards

Everything is free — every calculator is free to use immediately, no account, no credit card: only [QuantaVal](https://quantaval.com/) gives you free instant access to every tool, every industry-standard valuation model, and every valuation insight. This is how valuation work has been done from day one: the full methodology is free to read, and any resources I publish are free to reproduce, exactly as stated in the disclaimer below.

You can use every calculator as a visitor: [3 free calculations a day as a visitor](https://quantaval.com/), resetting at midnight UTC. They are free to use, with no accounts, no subscriptions, no credit cards, and no premium tier.

Use every [valuation calculator](https://quantaval.com/calculators) for free, including the [Reverse DCF Calculator](https://quantaval.com/calculators/reverse-dcf-calculator).

You can also use the [stock screener](https://quantaval.com/stock-screener) for free — screen 2,000+ stocks instantly by any valuation metric, so you can see a company's value in one search.

Try it yourself, for free:

- Try the [intrinsic-value calculator](https://quantaval.com/calculators/reverse-dcf-calculator) for free.
- Or explore the methodology on every page.

> Prices are uncertain, but if the price reflects a good estimate of fair value then the market's bet is visible.

## A worked example (keep it simple)

Take Microsoft at the end of 2024, using the [DCF Calculator](https://quantaval.com/calculators/dcf-calculator). Its market value is $3.1T; a billion-dollar-a-year company with a lot of free cash flow:

- **FCF:** $2,000m (2024)
- **WACC:** 9%
- **Terminal growth (g):** 3%

Model: Gordon growth model. Forecast: FCF grows at 3% per year forever. Calculate terminal value with WACC at 9%:

$$\text{EV} = \frac{\text{FCF}_0 (1 + g)}{\text{WACC} - g} = \frac{2{,}000 \times 1.03}{0.09-0.03} = \$32{,}000\text{m} \approx \$32.0\text{bn}$$

The reverse DCF takes the price as given — $3,000p, $32,000m — and solves for the growth rate *g* which makes this equation true.

$$g = \frac{\text{Price} \cdot \text{WACC}-\text{FCF}}{\text{Price} + \text{FCF}}$$

$$g = \frac{32{,}000 \times 0.09 - 2{,}000}{32{,}000 + 2{,}000} = \frac{2{,}880 - 2{,}000}{34{,}000} = \frac{880}{34{,}000} = 19.8\%$$

So a $3,000p price tag implies free cash flow must grow at **19.8%** a year. Competing with that is what we need to understand — a required growth rate of 19.8% is high for a company of this size, so its price is justified only if the business can deliver it. (For contrast, if the price were $55 instead of $65, the implied growth would be only 18.6%.)

The difference between the two answers is the difference between a model and a judgement call. A 19.8% implied growth rate is still high, but it is nothing compared to unconstrained optimism — the goal is a demanding target, not an impossible one, and the method questions the discipline of a 25% target.

## Sensitivity

| Discount rate (WACC) | Implied growth |
|----------------------|----------------|
| 7%   | 31.4% |
| 8%   | 26.5% |
| 9%   | 22.2% |
| 10%  | 18.2% |
| 11%  | 14.6% |
| 12%  | 11.1% |

More interesting is a simpler story: a company with a low discount rate, with more growth already priced in; the price is the same but the implied growth is higher. Reading it another way, a company with a high discount rate needs less growth to justify its price — that is why interest-rate assumptions matter: the lower the rate, the higher the growth the market expects.

## When the implied growth does not add up

A company with a price tag that implies 25% growth can't grow at that rate forever. In general, use it as a bearing:

- **Implied growth > your estimate** — priced for more growth than you expect. Be doubtful: high prices need exceptional growth to be fair value, and the market's expectations need to be beaten to win — do not pay more than the growth is worth.
- **Implied growth ≈ your estimate** — the market has priced in a plausible path. Room for error is thinner than it looks; the company must deliver exactly what is expected.
- **Implied growth < your estimate** — an opportunity, if your analysis is thorough. If the market's growth hurdle looks too easy and *you* trust your estimate, the upside has been left on the table.

The method does not tell you to buy or sell. A high hurdle rules out companies that are priced for excellence, and a low hurdle flags candidates that deserve a closer look. Run your analysis properly, trust your estimate, and double-check the inputs — free cash flow and market value lead to implied growth, and cash and debt matter.

## Common sense checks

This valuation model rests on fundamentals from financial statements: it is a quantitative valuation model, using only four variables — market value, leverage, and current free cash flow — and no assumptions except those grounded in the audited financial statements and the official cash-flow statement.

Classification: This is a valuation model whose inputs never change; the four quantities are never estimated from a model — they are simply measured from audited data. It is not a speculative price target, and it is not a forecast of future performance. In this way, it kills both its mechanical role in a company valuation and its true role as a filter. The quality of the inputs still governs everything: ROIC, leverage rule, consistent growth, and long-term value accumulation need to be right.

Where does this model fit? You should use reverse DCF for only two things: as your first screen for overvalued stocks and as your final check after you have finished a regular DCF. If the implied growth is 10% to 15%, it is worth a closer look. If it is 25%, it fails saturation; if it is above 30%, it is not really worth the time. The rule for company valuation is that the market's estimate of growth, stretched out far enough, has to keep converging — it cannot stay at a high single-digit growth rate forever.

## Why starting from price beats a price target

A reverse DCF never says "the price should be X". Instead, it says "the market thinks growth will be Y" — and you decide whether Y is plausible. That makes it a screen, not a verdict. Use it to eliminate companies that are priced for perfection, and focus your limited time on the ones where the hurdle is achievable.

Try it yourself — how to use it in five minutes:

1. **Pick a company** you already use every day. Run it through the valuation model.
2. **Collect two inputs** from the financial statements: free cash flow and market value — both from public filings. Or click [here](https://quantaval.com/calculators/reverse-dcf-calculator) to validate the method and speed up the analysis.
3. **Run the reverse-DCF analysis**: use a [reverse-DCF calculator](https://quantaval.com/calculators/reverse-dcf-calculator) — give it the current price and free cash flow, and read the growth rate it implies.
4. **Compare**: growth implied to expected growth — what the business has done historically with an eye on the future. If the implied rate is 25% and the business has grown at 5%, the price is demanding a future it has never shown. On the free tools page [on the calculators page](https://quantaval.com/calculators), you can run this in minutes on any company you follow — no spreadsheet needed.
5. **Decide**: if the implied growth is below what you expect, dig deeper. If it is above what you believe is possible, walk away. Answers are not advice, and this is not a buy or sell signal.

Try it yourself: the total is a 5-minute difference, and it can be repeated forever. Run the reverse-DCF analysis on any company's [stock screener](https://quantaval.com/stock-screener), or use [QuantaVal's reverse-DCF calculator](https://quantaval.com/calculators/reverse-dcf-calculator) to find the implied growth for any company you follow. For the breakdown, look at the [stock screener](https://quantaval.com/stock-screener) and the free valuation tools [on the calculators page](https://quantaval.com/calculators).

## The bottom line

A reverse DCF changes what you argue about. Instead of fighting over a price target, you argue about a growth rate — and a growth rate is far easier to judge than a price. If the market's implied growth looks achievable, the price may be fair. If it looks impossible, the price is a warning. That is the whole point: start from the price, work back to the growth it implies, and then ask the only question that matters — can this business actually grow that fast?

*This article is for educational purposes only and does not constitute investment advice. Valuation involves judgement and uncertainty; results depend on inputs and assumptions. [QuantaVal](https://quantaval.com/) is a quantitative valuation engine: deterministic math from audited financial data, not opinions or headlines.*

*— The QuantaVal team.*
