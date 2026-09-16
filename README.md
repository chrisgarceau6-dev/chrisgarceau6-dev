## Chris Garceau

Finance student at UMass Isenberg. I build systems that have to survive contact with
a live market, and I'm heading toward product roles where that instinct transfers —
deciding what to build, measuring whether it worked, and killing it when it didn't.

Most of what I've learned came from being wrong in public and writing down why.

---

### What I'm building

**[kalshi-trading-audit](https://github.com/chrisgarceau6-dev/kalshi-trading-audit)** — I run an automated
trading system on Kalshi's 15-minute crypto markets. Rather than publish the strategy, I published
the audit: two AI agents reviewing my code independently, four measurement bugs that
already had live decisions built on them, and two safety limits that could never have fired.

**[VRP-Harvester](https://github.com/chrisgarceau6-dev/VRP-Harvester)** — Options volatility engine that sells
defined-risk spreads when forecast IV exceeds expected RV. 7k lines of Python, GARCH/HAR
forecasting, a central risk chokepoint, and a backtest that models unfilled orders and
replays Volmageddon, COVID, and 2022. Ships with a document listing everywhere the model
diverges from reality.

**[stronger](https://github.com/chrisgarceau6-dev/stronger)** — Progressive overload tracker. React + Express +
Postgres, AI weight suggestions, push notifications, social feed. [Live here](https://stronger-client.vercel.app).

**[polymarket-monitor](https://github.com/chrisgarceau6-dev/polymarket-monitor)** — Copy-trade watcher for
Polymarket wallets. Runs entirely on GitHub Actions — no server, no hosting bill.

---

### How I work

I pre-register what would count as failure before running a test, and honor it afterward.
On one momentum strategy I killed ten ideas that way — leverage, 52-week-high proximity,
short-term reversal, and seven others — and kept the one that survived out-of-sample.

Being able to say "this didn't work" quickly is most of the value I bring.

---

### Toolkit

Python · JavaScript/React · Node/Express · PostgreSQL · pandas/NumPy · GitHub Actions · Supabase · Vercel

Backtesting · options pricing · risk sizing · statistical validation · A/B and OOS testing

---

*Amherst, MA · chrisgarceau6@gmail.com*
