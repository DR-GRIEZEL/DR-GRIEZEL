# DR_GRIEZEL

**Quant finance** · **Simulations** · **Minimalism** · **Automations**

Focus: Automated bots, Python data-engineering, Linux & self-hosting, Web development

---

## Currently working on
- **Bot API → GitHub Pages dashboard** (public frontend, private server)
- **Discord bot UI** for displaying market data / portfolio / alerts

## Project status

| Project | Description | Status | Notes |
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
- **API**
- **Web**

## Engineering rules
- Modular, minimalistic frameworks. Structure before content.
- Excessive debug logs over fancy dashboards. Focus on code first.
- low-overhead, zero down-time server setup + rollback options.

## Contact / collaboration
- Issues/PRs: be concrete (reproduce steps, debug/error logs, expectaction vs actual result).
- 👍 Likes: minimal fixes, clear tradeoffs, no word salads.
