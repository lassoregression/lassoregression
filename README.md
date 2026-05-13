# Hello, world

- AI & Analytics Specialist @ SAP

- M.S. Quantitative Finance, Fordham University

Building data products, LLM applications, and agents for enterprise and financial workflows. I'm using claude code now. It's pretty good because it automates a lot of the boring stuff. But you can still use your brain.

---

## On-Going Projects

### Averroes
[GitHub](https://github.com/lassoregression/averroes-public) &nbsp;•&nbsp; [Live](https://averroes-llm.vercel.app)

Prompting is essentially the process of translating the user's intent into something a language model can execute. Minor differences in phrasing can materially change the quality of a response and most systems provide no feedback on this. When a LLM responds, the user is usually left guessing whether the issue was the prompt or the model. Over time, weak outputs get attributed to the model rather than the input, and the feedback loop that would normally build skill never forms.

Averroes introduces a second model, the *Commentator*, that observes each exchange as a read-only participant. After every interaction it diagnoses the prompt, identifies what was underspecified, and produces a refined version without any action from the user. A 0 to 1 workshop mode goes further: before any primary model call, the Commentator runs a short clarifying dialogue and returns a precise prompt the user reviews and sends.

The result is direct prompt feedback that is specific to the exchange in front of you and comes from something with no stake in making the answer look good.

---

### Geist *(In Progress)*

Investment research is not limited by access to information. It is limited by the lack of a clean link between what an investor holds, what new information exists, and whether that information changes the original view or thesis.

General-purpose language models fail here in predictable ways. They operate without knowledge of positions, produce claims without grounding, hallucinate citations, and offer recommendations without accountability.

Geist is a read-only intelligence layer that connects to an investor's accounts across brokerages, exchanges, and self-custody wallets, and indexes relevant public information (filings, transcripts, news, etc.) into a citable corpus. It can surface your concentration by sector, run your current positions through historical stress tests, track whether a thesis you hold is still supported as new filings arrive, or return the market-implied probability on a macro event with the source contract cited. Every claim is bound to a primary source or it is not rendered.

Hard limits at the synthesis layer: no forecasts, no recommendations, no composite scores, no ungrounded claims.

---

## Earlier Work

- [Measuring Distance to Default](https://github.com/lassoregression/dtd): Merton model implementation with market value proxy and volatility restricted methods
- [Mortgage-Backed Security Valuation](https://github.com/lassoregression/mbs-val): prepayment modeling via the Vasicek interest rate model
- [Algorithmic Trading System](https://github.com/lassoregression/strat-backtest): strategy backtesting with GUI
- [U.S. Delinquency Rate Forecasting](https://github.com/lassoregression/us-delinquency-forecast): time-series forecasting against macroeconomic indicators
