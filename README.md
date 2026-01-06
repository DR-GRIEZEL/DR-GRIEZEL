# DR_GRIEZEL

**Quantitative finance** · **simulations** · **risk** · **minimalist engineering**

- 🧠 Interests: risk models, backtesting, Monte Carlo, execution rules, “what breaks first?”
- 🧰 Practical: Python-first, Linux/homelab, GitHub Actions, static frontends with live data
- 🔐 Security stance: 100% third-party auth (Google/GitHub) over custom login

---

## Currently working on
- **Bot API → GitHub Pages dashboard** (public frontend, private server)
- **Discord bot UI** for market data / portfolio / alerts
- **CI & security checks**: use-case-fit workflows, incl. CodeQL where it makes sense

## Project status

| Project | What it is | Status | Notes |
|---|---|---:|---|
| **Trading engine** | OHLCV → strategy → virtual portfolio tracking | 🟡 | Drawdown, risk caps, testability |
| **Auto-optimizer** | grid/random search over strategy params | 🟡 | Export to dashboard |
| **Monte Carlo robustness** | randomization for stress tests | 🟠 | MDD, ruin risk, tail events |
| **Discord API** | RSI/ATR, tickers, embeds | 🟡 | UX-first: less spam |
| **GitHub Pages** | static frontend with live updates | 🟠 | No secrets in the client |
| **Server** | self-hosted services, hardening | 🟢 | Backups, rollback |

Legend: 🟢 stable · 🟡 active · 🟠 in progress · 🔴 paused

---

## Tech stack
- **Python**
- **Linux (Debian)**
- **GitHub Actions**
- **PineScript**
- **API**
- **Web**

## Engineering rules
- Modular, minimalistic frameworks.
- Excessive debug logs over fancy dashboards.
- Secrets stay server-side; auth is external.
- low-overhead server setup + rollback options.

## Contact / collaboration
- Issues/PRs: be concrete (repro steps, logs, expected vs actual).
- likes (👍): minimal fixes, clear tradeoffs, no word salads.
