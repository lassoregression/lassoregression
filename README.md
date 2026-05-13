## AI & Analytics Specialist @ SAP
M.S. Quantitative Finance, Fordham University

Building data products, LLM applications, and agents for enterprise and financial workflows.

---

### averroes
[GitHub](https://github.com/lassoregression/averroes) • [Live](https://averroes-llm.vercel.app)

Prompting is the act of translating intent into something a language model can execute. Small differences in phrasing can materially change the quality of an answer, but most systems provide no feedback on this. The model responds, and the user is left guessing whether the issue was the prompt or the model.

Over time, this breaks the feedback loop. Weak outputs are attributed to the model, not the input. Prompt quality becomes dependent on prior experience rather than something users can develop in context.

Averroes addresses this by introducing a second model — the *Commentator* — that observes each exchange as a read-only participant. After every interaction, without any action from the user, it diagnoses the prompt, identifies what was underspecified, and produces a refined version. A structured 0→1 workshop mode inverts this: before any primary model call, the Commentator takes over the interaction, runs a short clarifying dialogue, and returns a precise prompt the user can review and send. Once the workshop completes, the primary model resumes normally.

The separation is strict: the Commentator reads the full conversation but cannot write to it, and the primary model is unaware of its existence. This keeps the feedback honest — an observer with no stake in the response it is evaluating has no incentive to rationalize a weak one.

---

### geist *(in progress)*

Investment research is not limited by access to information. It is limited by the lack of a clean link between what an investor holds, what new information exists, and whether that information changes the original thesis.

General-purpose language models fail here in predictable ways. They operate without knowledge of positions, produce claims without grounding, hallucinate citations, and offer recommendations without accountability. They have no memory of prior commitments or how incoming evidence relates to them.

Geist is a read-only intelligence layer built around these constraints. It connects to an investor's accounts, constructs a unified view of positions across brokerages, exchanges, and self-custody wallets, and indexes relevant public information — filings, transcripts, news, prediction-market state — into a structured, citable corpus. Every output is an evidence card: each claim bound to a primary source, with a mandatory citation, timestamp, and relevance tie-in to the user's holdings. Claims that cannot be cited are dropped before rendering.

Hard boundaries are enforced at the synthesis layer in code, not system-prompt policy: no forecasts, no recommendations, no composite scoring, no ungrounded claims.

Workspaces let users commit investment theses as explicit assumptions and risks. The system continuously evaluates incoming evidence against these commitments and surfaces when the underlying argument shifts. For institutional users, every computed value is traceable to a versioned methodology entry, keeping scenario analyses reproducible and defensible.

---

### earlier work

- [Measuring Distance to Default](https://github.com/lassoregression/dtd) — Merton model implementation with market value proxy and volatility restricted methods
- [Mortgage-Backed Security Valuation](https://github.com/lassoregression/mbs-val) — prepayment modeling via the Vasicek interest rate model
- [Algorithmic Trading System](https://github.com/lassoregression/strat-backtest) — strategy backtesting with GUI
- [U.S. Delinquency Rate Forecasting](https://github.com/lassoregression/us-delinquency-forecast) — time-series forecasting against macroeconomic indicators
