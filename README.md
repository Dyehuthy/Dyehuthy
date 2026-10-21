<h1 align="center" style="color:#00ffff;">
</h1>

<p align="center">
  <a href="https://x.com/DyehuthyTV">
    <img src="https://pbs.twimg.com/profile_banners/1662106155630354432/1750993527/1500x500" alt="Header" width="100%" />
  </a>
</p>

<p align="center">
  <img src="https://hits.sh/github.com/Dyehuthy.svg?style=flat&label=Visits&color=8fbc8f" alt="Profile visits" />
  <a href="https://github.com/Dyehuthy?tab=followers"><img src="https://img.shields.io/github/followers/Dyehuthy?style=social" /></a>
  <a href="https://github.com/Dyehuthy?tab=stars"><img src="https://img.shields.io/badge/Stars-Lists-%23ff00ff?logo=github&style=flat" /></a>
  <a href="https://x.com/DyehuthyTV"><img src="https://img.shields.io/twitter/follow/DyehuthyTV.svg?style=social" /></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00FFFF&center=true&vCenter=true&width=700&lines=Quantitative+Research+%7C+Python+%7C+Data+Science;Alpha+%E2%89%A0+Luck+%E2%80%94+Falsifiable+Hypotheses+Only;Macro+%C3%97+Value+%C3%97+Systematic+Risk;Backtest+without+look-ahead.+Size+with+Kelly." alt="Typing SVG" />
</p>

---

# <h3 align="center">────⋆⋅Σ⋅⋆── QUANT PROFILE ──⋆⋅Σ⋅⋆────</h3>

<div align="center">

| 📐 Research | 📊 Statistics | ⚠️ Risk | 💰 Fundamentals |
|:--|:--|:--|:--|
| Alpha signals & factor models | Hypothesis testing, regression | Position sizing (Kelly, vol-target) | ROIC, FCF, margins, moat |
| Stationarity & cointegration | Confidence intervals, bootstrap | Tail risk & stress testing | Multiples & quality screens |
| Walk-forward backtesting | Cross-validation, no leakage | Max drawdown control | Macro regimes (Dalio / PTJ style) |

</div>

```python
from dataclasses import dataclass

@dataclass(frozen=True)
class QuantCreed:
    hypothesis: str = "falsifiable, measurable, reproducible"
    validation: str = "walk-forward, no look-ahead, no data leakage"
    costs: str = "fees + slippage + liquidity included"
    risk_first: bool = True          # risk > return
    overfitting: bool = False        # simple, robust, replicable

    def edge(self, p_win: float, avg_win: float, avg_loss: float) -> float:
        """Expected value per trade: EV = p*W - (1-p)*L"""
        return p_win * avg_win - (1.0 - p_win) * avg_loss
```

### 🧮 Core Metrics

<div align="center">

| Metric | Formula |
|:--|:--|
| **Sharpe** | `S = E[Rp − Rf] / σp` |
| **Sortino** | `So = E[Rp − Rf] / σd` |
| **Calmar** | `Ca = CAGR / │MaxDD│` |
| **Kelly** | `f* = (p·(b+1) − 1) / b` |
| **Portfolio σ** | `σp = √(wᵀ Σ w)` |
| **Expected Value** | `EV = p·W − (1−p)·L` |

</div>

### 🔬 Research Pipeline

<p align="center">
  <img src="https://img.shields.io/badge/1-Hypothesis-00ffff?style=for-the-badge" />
  <b>→</b>
  <img src="https://img.shields.io/badge/2-Data%20%26%20Cleaning-1f6feb?style=for-the-badge" />
  <b>→</b>
  <img src="https://img.shields.io/badge/3-Signals-8957e5?style=for-the-badge" />
  <b>→</b>
  <img src="https://img.shields.io/badge/4-Walk--Forward%20Backtest-ff00ff?style=for-the-badge" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/5-Costs%20%26%20Slippage-d29922?style=for-the-badge" />
  <b>→</b>
  <img src="https://img.shields.io/badge/6-Risk%20%26%20Sizing-da3633?style=for-the-badge" />
  <b>→</b>
  <img src="https://img.shields.io/badge/7-Live%20%2F%20Paper-2ea043?style=for-the-badge" />
  <b>↺</b>
</p>

---

# <h3 align="center">────⋆⋅☣︎⋅⋆── SOCIAL NETWORKS ──⋆⋅☣︎⋅⋆────</h3>
<p align="center"> <a align="center">
<a href="https://www.reddit.com/user/DyehuthyTV/"><img align="center" src="https://cdn4.iconfinder.com/data/icons/social-messaging-ui-color-shapes-2-free/128/social-reddit-square1-512.png" alt="Reddit" width="42px"/></a>
<a href="https://cryptoquant.com/profile/u/dyehuthy2023?tab=dashboard"><img align="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR7YNNAQwTYO18cv9XRi2X0oPpwMfOEwfdPlA&s" alt="CryptoQuant" width="42px"/></a>
<a href="https://stocktwits.com/Dyehuthy"><img align="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQoD3bQwpPvjaiaYUShIAU0uu220f6BZJ_psQ&s" alt="StockTwits Profile" width="42px"/></a>
<a href="https://replit.com/@Dyehuthy"><img align="center" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSXMkKd78cldC7LqWfHcXPI7MptFGF4WB8adh_oA46HFb7Yx6h91KNqS0LjqLnp7OfTC8k" alt="Replit Profile" width="42px"/></a>
<a href="https://www.kaggle.com/dyehuthy"><img align="center" src="https://www.kaggle.com/static/images/logos/k-logo-opengraph.png" alt="Kaggle Profile" width="42px"/></a>
<a href="https://www.quantconnect.com/u/dyehuthy"><img align="center" src="https://avatars.githubusercontent.com/u/3912814?s=280&v=4" alt="QuantConnect Profile" width="42px"/></a>  
<a href="https://learn.microsoft.com/en-us/users/dyehuthy/"><img align="center" src="https://cdn-icons-png.flaticon.com/256/732/732221.png" alt="Microsoft Learn Profile" width="42px"/></a>
<a href="https://dyehuthy.imgbb.com/albums"><img align="center" src="https://cdn-1.webcatalog.io/catalog/imgbb/imgbb-icon-filled-256.webp?v=1733731311286" alt="ImgBB Profile - Albums" width="42px"/></a>
</a> </p>

# <h3 align="center">────⋆⋅₿⋅⋆── INVESTOR TOOLS ──⋆⋅₿⋅⋆────</h3>
<div align="center">

<table>
  <tr>
    <th>Stock Research</th>
    <th>Portfolio Metrics</th>
    <th>News</th>
  </tr>
  <tr>
    <td><a href="https://stockanalysis.com/"><img src="https://img.shields.io/badge/stock%20analysis-blue.svg?style=for-the-badge" /></a></td>
    <td><a href="https://www.portfoliovisualizer.com"><img src="https://img.shields.io/badge/portfolio%20visualizer-purple.svg?style=for-the-badge" /></a></td>
    <td><a href="https://www.reuters.com/markets/"><img src="https://img.shields.io/badge/reuters-orange.svg?style=for-the-badge&logo=reuters&logoColor=white" /></a></td>
  </tr>
</table>

</div>

# <h3 align="center">────⋆⋅Σ⋅⋆── QUANT DATA & RESEARCH ──⋆⋅Σ⋅⋆────</h3>
<div align="center">

<table>
  <tr>
    <th>Macro</th>
    <th>Fundamentals</th>
    <th>Screening</th>
    <th>Research Papers</th>
  </tr>
  <tr>
    <td><a href="https://fred.stlouisfed.org/"><img src="https://img.shields.io/badge/FRED-macro%20data-004b87.svg?style=for-the-badge" /></a></td>
    <td><a href="https://www.sec.gov/edgar"><img src="https://img.shields.io/badge/SEC-EDGAR-1f4e79.svg?style=for-the-badge" /></a></td>
    <td><a href="https://finviz.com/"><img src="https://img.shields.io/badge/finviz-screener-2e7d32.svg?style=for-the-badge" /></a></td>
    <td><a href="https://arxiv.org/archive/q-fin"><img src="https://img.shields.io/badge/arXiv-q--fin-b31b1b.svg?style=for-the-badge&logo=arxiv&logoColor=white" /></a></td>
  </tr>
</table>

</div>

# <h3 align="center">────⋆⋅☣︎⋅⋆── LANGUAGES & TECHNOLOGIES ──⋆⋅☣︎⋅⋆────</h3>
<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,html,css,js,react,rust,cs,cpp,bash,linux,powershell,windows" />
  </a>
</p>

# <h3 align="center">────⋆⋅Σ⋅⋆── QUANT STACK ──⋆⋅Σ⋅⋆────</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/statsmodels-econometrics-4B8BBE?style=flat" />
  <img src="https://img.shields.io/badge/yfinance-market%20data-6001D2?style=flat&logo=yahoo&logoColor=white" />
  <img src="https://img.shields.io/badge/QuantConnect-backtesting-F7931A?style=flat" />
  <img src="https://img.shields.io/badge/DeFi-on--chain%20analytics-00ffff?style=flat" />
</p>

# <h3 align="center">────⋆⋅☣︎⋅⋆── GITHUB STATS ──⋆⋅☣︎⋅⋆────</h3>
<p align="center">
<a href="https://github.com/dyehuthy">
  <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=dyehuthy&show_icons=true&theme=merko&include_all_commits=true&count_private=true"/>
</a>
</p>

<p align="center"><sub><i>"Risk comes from not knowing what you're doing." — Warren Buffett</i></sub></p>
