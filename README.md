# DR_GRIEZEL

**Python** · **Linux** · **Git** · **CI/CD** · **API** · **Web** · **Bots**


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=DR-GRIEZEL&show_icons=true&hide_border=true&border_radius=10&include_all_commits=true&rank_icon=github&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api?username=DR-GRIEZEL&show_icons=true&hide_border=true&border_radius=10&include_all_commits=true&rank_icon=github&theme=default" />
  <img alt="GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=DR-GRIEZEL&show_icons=true&hide_border=true&border_radius=10&include_all_commits=true&rank_icon=github&theme=default" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=DR-GRIEZEL&layout=compact&hide_border=true&border_radius=10&size_weight=0.5&count_weight=0.5&theme=dark" />
  <source media="(prefers-color-scheme: light)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=DR-GRIEZEL&layout=compact&hide_border=true&border_radius=10&size_weight=0.5&count_weight=0.5&theme=default" />
  <img alt="Top Languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DR-GRIEZEL&layout=compact&hide_border=true&border_radius=10&size_weight=0.5&count_weight=0.5&theme=default" />
</picture>

---

## Currently working on
- **Bot API → GitHub Pages dashboard**
- **Discord bot UI** for displaying market data / portfolio / alerts

## Project status

| Project | Description | ✅ | Notes |
|---|---|---:|---|
| **Trading engine** | OHLCV → strategy → virtual portfolio tracking | 🟡 | Drawdown, risk caps, testability |
| **Auto-optimizer** | grid/random search over strategy params | 🟡 | Export to dashboard |
| **Monte Carlo robustness** | randomization for stress tests | 🟠 | MDD, ruin risk, tail events |
| **Discord API** | RSI/ATR, tickers, embeds | 🟡 | UX-first: less spam |
| **GitHub Pages** | static frontend with live updates | 🟠 | No secrets in the client |
| **Server** | self-hosted services, hardening | 🟢 | Backups, rollback |

Legend: 🟢 stable · 🟡 active · 🟠 in progress · 🔴 paused

---

## Engineering rules
- Modular, minimalistic frameworks. Structure before content.
- Excessive debug logs over fancy dashboards. Focus on code first.
- low-overhead, zero down-time server setup + rollback options.

## Contact / collaboration
- Issues/PRs: be concrete (reproduce steps, debug/error logs, expectaction vs actual result).
- 👍 Likes: minimal fixes, clear tradeoffs, no word salads.
