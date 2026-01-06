# DR_GRIEZEL

**Kwantitatieve finance** · **simulaties** · **risico** · **minimalistische engineering**

- 🧠 Interests: risk models, backtesting, Monte Carlo, execution rules, “what breaks first?”
- 🧰 Praktisch: Python-first, Linux/homelab, GitHub Actions, statische frontends met live data
- 🔐 Security-stance: 100% third-party auth (Google/GitHub) boven custom login

---

## Nu bezig
- **Bitvavo API → GitHub Pages dashboard** (publieke frontend, private server)
- **Discord bot UI** voor marktdata/portfolio/alerts
- **CI & security checks**: use-case–fit workflows, incl. CodeQL waar zinvol

## Project status

| Project | Wat het is | Status | Notes |
|---|---|---:|---|
| **Bitvavo trading engine** | OHLCV → strategy → virtuele portfolio tracking | 🟡 | Drawdown, risk caps, testbaarheid |
| **Auto-optimizer** | grid/random search over strategy params | 🟡 | Export naar dashboard |
| **Monte Carlo robustness** | randomization voor stress tests | 🟠 | MDD, ruin-risk, tail events |
| **Discord ‘Financieel Adviseur’ bot** | RSI/ATR, tickers, embeds | 🟡 | UX-first: minder spam |
| **GitHub Pages dashboard** | statische frontend met live updates | 🟠 | No secrets in client |
| **Homelab (RPi)** | self-hosted services, hardening | 🟢 | Backups, rollback |

Legenda: 🟢 stabiel · 🟡 actief · 🟠 in opbouw · 🔴 gepauzeerd

---

## Tech stack
- **Python**
- **Linux / Debian (RPi OS)**
- **GitHub Actions**
- **TradingView Pine Script**
- **Discord**
- **Frontend**: statisch (GitHub Pages) + API proxy/tunnel

## Engineering regels
- Geen framework-rituelen zonder payoff.
- Transparante logs + reproduceerbare runs boven fancy dashboards.
- Secrets blijven server-side; client is untrusted; auth extern.
- Idempotente setup + rollback-opties.

## Contact / samenwerking
- Issues/PR’s: concreet (repro steps, logs, expected vs actual).
- Ik hou van: minimal fixes, duidelijke tradeoffs, geen buzzword-bingo.

> Pinned repos hierboven zijn de actuele kern van waar ik aan bouw.
