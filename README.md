# Hey, I'm Sbusiso 👋

**I'd rather show you the model than tell you about it.**

I'm an actuarial science graduate from the University of the Free State, finishing my BSc Honours in Risk Analysis and taking MSc Financial Engineering modules at WorldQuant University. I build the things I talk about:
- Pricing and risk models
- Forecasting systems with live data behind them
- The software and pipelines that keep them running

---

### How I got here

I started in actuarial science because I liked the idea of putting an honest number on uncertainty. Somewhere along the way, "how much should this cost" turned into "why do people price risk the way they actually do," and that question is what keeps me building. My honours research, recovering how investors trade off risk and return across JSE sectors, was me trying to answer it with data instead of intuition.

I care more about finishing the whole pipeline
<p align="center">data &#8594; model &#8594; decision &#8594; something a non-technical person can actually use </p>
than about a clever result stuck in a notebook. If it can't survive contact with a real user or a real out-of-sample period, it doesn't count yet.

---

### What I've built

**🏥 Sequrin Technologies**
My startup. Claims-integrity software for South African medical schemes: claims analytics, explainable risk signals and investigator workflows, running on AWS with Docker services and infrastructure as code. Private, but the story is on [mdingi.co.za](https://mdingi.co.za/work/sequrin-healthcare-claims).

**📈 [Copula-GARCH Pairs Trading](https://github.com/Sbusiso-Mdingi/jse-statistical-arbitrage)**
Standard Bank against its peers, with ARMA-GARCH margins and a Student t copula. The honours version of this looked great: 6.2% CAGR and a 0.90 Sharpe. Then I rebuilt it properly, with rules fixed on 2010 to 2019, one validation run on 2020 to 2026, and costs on every trade, and it came out at 0.3% and 0.08. That second number is the one I trust, and it's [scored live](https://mdingi-jse-pairs.azurewebsites.net) on days the model has never seen.

**📉 [JSE Portfolio Risk](https://github.com/Sbusiso-Mdingi/jse-risk-management)**
An old Shiny app that picked weights from random draws by in-sample Sharpe, rebuilt in Python and tested out of sample. Six weight rules, four VaR models, stress scenarios. Only one of the four VaR models passed its coverage backtests, which is exactly the kind of thing worth knowing. [Live dashboard](https://mdingi-jse-risk.azurewebsites.net).

**✈️ [Pickup Alerts for FlySafair](https://mdingi.co.za/work/flysafair-pickup-alerts)**
My mom never knows when to leave to fetch my aunt from the airport, so I built the fix. A scheduled pipeline follows each aircraft through its day, predicts the landing, adds the walk to the kerb and live Google traffic, and tells the person fetching when to leave. Replayed on 474 arrivals: passengers waiting outside for over 5 minutes went from 5.5% to 0.2%. [Try it](https://d1h9ep1q89rjmr.cloudfront.net).

**🌍 [Spatial Statistics of SADC Development](https://mdingi.co.za/work/spatial-statistics-sadc)**
Global and local Moran's I over seven World Bank indicators for the 16 SADC countries, with a linked map and parallel-coordinates plot. Urbanisation clusters regionally (Moran's I = +0.425, p = 0.0001). Plus a kriging study in R. [Explore it](https://d37ee3ifn0tf9r.cloudfront.net).

**🔐 [Secure Steganographic Messaging](https://github.com/Sbusiso-Mdingi/stego-messenger)**
The odd one out: AES-256-GCM encryption hidden in image pixels, then attacked with the statistical tests used to catch it. Invisible to the eye, visible to RS steganalysis. Turns out "quant" and "security" scratch the same itch: both are about finding what's hidden in the noise.

**Also:** a [health insurance pricing model](https://github.com/Sbusiso-Mdingi/health-insurance-pricing-model) in R with a Shiny dashboard, and [cross-line tail risk](https://github.com/Sbusiso-Mdingi/Copula-Cross-Line-Insurance-Risk) between life and property catastrophe losses with copulas.

---

### Right now

- 🎓 Wrapping up my BSc Honours in Risk Analysis (dissertation submitted)
- 📚 MSc Financial Engineering modules at WorldQuant University
- 🏗️ Building Sequrin
- 🗺️ Learning a lot of spatial statistics, mostly by pointing it at real data

---

### Toolbox

`R` · `Python` · `SQL` · `JavaScript` · `VBA` · `LaTeX` · `Git`
`GARCH` · `Copulas` · `GLMs` · `Spatial statistics & kriging` · `Discrete choice modelling` · `Monte Carlo simulation` · `Forecasting`
`AWS` · `Azure` · `Google Cloud` · `Docker` · `Linux` · `FastAPI` · `Shiny` · `React`

---

### Find me

🌐 [mdingi.co.za](https://mdingi.co.za)

💼 [linkedin.com/in/ssmdingi](https://linkedin.com/in/ssmdingi)
