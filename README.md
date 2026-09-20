# 🧠 metalslime-perspective — Investment Thinking Lens

> 基于雪球大V"药神"(metalslime) 2019–2026 全周期公开内容（2 万帖＋91 万字碎碎念深读）蒸馏的投资思维分身：周期判断、估值纪律、比价方法论、产业链穿透与传播链定价。
>
> An educational analysis lens distilled from 5 years of public posts by metalslime (药神), a Chinese cross-market investor — covering cycle timing, valuation discipline, cross-asset comparison, supply-chain penetration, and propagation-chain pricing.

---

## 📖 What Is This?

This is an AI agent skill that applies a **metalslime-style investment thinking framework** as an analytical perspective. Instead of generic market commentary, it helps you reason through the lens of a cross-market research style that:

- 🔄 Rotates across industries at speed (baijiu → gaming → wind power → oil shipping → semiconductors)
- 📊 Uses **IRR** as the ultimate decision yardstick
- 🎯 Hunts value at **cycle bottoms** with extreme selectivity
- 🔗 **Perp-leaf method**: compares across assets horizontally, then penetrates the supply chain vertically to find the irreplaceable bottleneck
- 📡 Prices the **propagation chain** — earning from "what others will be forced to believe," not from "what is right"
- 🛡️ Treats **position discipline as prior to opinions** — surviving to catch the rare high-certainty moment

**Important:** This is a *thinking framework*, not financial advice and not the real metalslime account. See [`docs/core-boundary.md`](docs/core-boundary.md) for the stable boundary, and [`references/honest-boundary.md`](references/honest-boundary.md) for the performance-claim falsification ("100x in 3 years" is a survivorship headline; realistic scale ~10x in 5 years, unverified).

---

## 🧰 10 Core Mental Models

| # | Model | One-Liner |
|---|-------|-----------|
| 1 | **Cycle-Bottom Value Hunting** | Find the best companies when an industry is universally despised — bottoms separate wheat from chaff. |
| 2 | **Price as Core High-Freq Data** | All analysis must converge on price signals. |
| 3 | **Animal Spirits & Consensus** | Trading releases market animal spirits; all research serves to identify consensus formation. |
| 4 | **Endgame Projection** | Project the industry's final-state landscape, then assess current pricing. |
| 5 | **Rapid Learning = Edge** | Learning a new industry in 1–2 weeks is the #1 competitive advantage. |
| 6 | **Cash Flow Thinking** | IRR is the ultimate yardstick for every decision. |
| 7 | **De-financialization Framework** | Physical assets and upstream resources outperform in China's de-financialization. |
| 8 | **Perp-Leaf / Cross-Asset Comparison** | Compare horizontally to pick the asset, penetrate vertically to find the chain's "perilla leaf" — the unremarkable but irreplaceable link held by 1–2 global players. |
| 9 | **Propagation-Chain Pricing** ★new | Stand upstream in the information chain and predict how consensus will spread — info-layer self-check, volume-concentration top signals, "explained clearly = the top". |
| 10 | **Position Discipline over Opinions** ★new | Staying alive with small positions is the precondition of every multi-year return, not its side effect. |

---

## ⚡ 18 Decision Heuristics

1. 🚨 **"Time for space" in a report? → Exit immediately.** Space is created by falling, never by waiting.
2. 📊 **Skip earnings season** — too much uncertainty, not enough upside.
3. 🎭 **Big-name investors start flexing? → Risk rising.**
4. 🎯 **At the bottom, be ruthless** — only buy the absolute best in the sector.
5. 📚 **Never read investing books** — read industry reports and raw research.
6. 📐 **Match valuation method to industry** — PEG for cyclicals is wrong; DCF-with-perpetuity for momentum stocks is also wrong.
7. 👥 **Demographics is the ultimate constraint.**
8. 🛢️ **Non-China-priced resource inflation → bearish for A-shares.**
9. 🏛️ **A-share 3000-point ceiling is a social problem**, not an economic one.
10. ⏳ **Don't waste A-share crises — there's always another one coming.**
11. 🔁 **Compare across asset classes first, then penetrate the chain** (perp-leaf method).
12. 🍣 **Everyone stares at the tuna belly; the perilla leaf is the lifeline** — excess returns hide in unremarkable, irreplaceable links.
13. 🏭 **Only 1–2 global players in a link → pricing power.**
14. 📉 **Assets that stop rising must fall** — opportunity cost gets transferred.
15. 📡 **First ask which propagation layer you're on** ★new — layer-3+ information only matters when layer-1/2 positions already reflect it.
16. 📊 **A sector dominating the volume board = the top** ★new — volume concentration as a quantified proxy for propagation.
17. 🗣️ **When the market can explain the story clearly, it's the top** ★new — tops come from consensus completion, not valuation.
18. 🧪 **Use domain expertise to filter scams, not to pick winners** ★new — "expert stock-picking loses to expert scam-detection".

---

## 🗺️ Investment Decision Flow (simplified)

```
Discover → ① Price signal → ② Supply-demand → ③ IRR gate
        → ④ Endgame projection → ⑤ Chain penetration (find the perilla-leaf link)
        → ⑥ Horizontal comparison (cross-asset / cross-market / in-sector)
        → ⑦ Cross-validate ⑤×⑥ → ⑧ Sentiment position
        → ⑨ Risk constraints (never position instructions for the user)
        → ⑩ Track → ⑪ Exit signals ("time for space" / consensus overheat / IRR gone / better asset)
```

Full version with stage-by-stage details in [`SKILL.md`](SKILL.md); full 2019–2026 five-stage evolution in [`references/evolution-2019-2026.md`](references/evolution-2019-2026.md).

---

## 💬 Signature Quotes

> *"Any industry report that mentions 'exchanging time for space' — exit immediately. A-shares have never had time-for-space. Space is always created by falling."* — 3,600 likes

> *"The essence of trading is releasing market animal spirits. Value, profit, valuation, industry research — all are tools to identify consensus."* — 261 likes

> *"You trade chips, not reasons."* — 2023

> *"At any moment, assess which layer of the propagation chain you are receiving information at."* — 2021

> *(30+ classic quotes with dates and like-counts in SKILL.md Appendix B/C)*

---

## 🚀 Installation

```bash
# Works with Claude Code / Codex / OpenClaw and any agent that loads SKILL.md-style skills
git clone https://github.com/xiaogege6697/metalslime-perspective-skill.git
cp -R metalslime-perspective-skill ~/.agents/skills/metalslime-perspective
# or ~/.claude/skills/ / ~/.codex/skills/ / your OpenClaw shared-skills directory
```

### Usage

Once installed, activate the skill by saying things like:
- "Use metalslime's perspective to analyze XX" / "用药神的视角分析一下XX行业"
- "What would the metalslime framework say about this cycle bottom?"
- "Analyze this stock through the propagation-chain lens"

---

## 📁 Repository Structure

```
metalslime-perspective-skill/
├── SKILL.md                    # 10 models · 18 heuristics · expression DNA · timeline
├── references/                 # ★ v0.3.0
│   ├── evolution-2019-2026.md  # five-stage system evolution, incl. 2019-2020 prehistory
│   ├── propagation-chain.md    # propagation-chain pricing system + context warnings
│   └── honest-boundary.md      # performance falsification + what to learn / avoid
├── docs/core-boundary.md       # stable boundary contract
├── evals/evals.json            # 8 behavior evals
├── VERSION · CHANGELOG.md · LICENSE
```

> **Note:** Raw data (20,787 posts + 910k-word journal) is NOT included. This repo contains only the distilled framework. v0.3.0 (2026-09-20) retrained on the full 2019–2026 corpus.

---

## ⚠️ Disclaimer

This skill is a **thinking framework** for educational purposes. It is NOT financial advice, does not represent metalslime, and must not be used as a buy/sell instruction. Market views change over time; verify current data and always do your own research.

---

## 📄 License

MIT — see [LICENSE](LICENSE).

---

### ⭐ If you find this useful, please give it a star!

More distilled thinking-lens and workflow skills: [github.com/xiaogege6697](https://github.com/xiaogege6697) 🙏

<!-- AI/Friendly Search Metadata -->
**keywords: metalslime, investment lens, cycle, IRR, cross-asset comparison, supply chain, propagation chain, position discipline, Xueqiu, knowledge distillation, persona skill, 药神, 投资, 周期, 比价, 产业链, 传播链, 仓位纪律, 雪球, 分身**

