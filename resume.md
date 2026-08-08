# MD AMIR KHAN

mkhan37@stevens.edu · Stamford, CT · [GitHub](https://github.com/Mkhan2317) · [LinkedIn](https://www.linkedin.com/in/amirkhan2317/) · [Portfolio](https://mkhan2317.github.io/)

---

## PROFESSIONAL SUMMARY

AI engineer and quantitative analyst at DXT Commodities, building production LLM systems, forecasting models, and full-stack analytics platforms used daily by the trading desk across U.S. natural gas and power markets. Sole architect on nine live systems shipped since March 2026.

---

## EXPERIENCE

### DXT Commodities North America — Stamford, CT
**Applied AI Engineer & Quantitative Analyst — Market Fundamentals (LNG & Power)** | March 2026 – Present

- **Pipeline Transparency Platform (LLM extraction).** Live production web application monitoring 19 U.S. interstate natural-gas pipelines across 8 operator portal architectures. Built 15+ format-specific scrapers (HTML, PDF via pdfplumber, Excel, ASP.NET WebForms, WAF-protected portals via TLS impersonation) and a structured-output extraction layer over the Anthropic Claude API that normalizes free-form maintenance and capacity-restriction notices into typed capacity-impact records. Content-hash caching cut LLM calls from ~40/run to 0 on unchanged notices with no freshness loss. Stack: FastAPI + SQL Server. Tracks 40+ active and 198+ upcoming restrictions on a peak day, aggregating 17.5 M Dth/d capacity offline.
- **WattsApp — PJM Fleet Analytics Platform.** Full-stack production web application covering the PJM generation fleet: 4,305 units / 232.5 GW nameplate capacity across 2,262 plants in 13 states + DC. Overview / Thermal / Non-Thermal / Plants / Insights / Ask (natural-language query) / My Units / Exports views used daily by the power desk. Stack: Next.js + React + TypeScript + Leaflet · FastAPI + SQLAlchemy · SQL Server · containerized with Docker.
- **Wattson — Multi-ISO Wholesale Power Price Analytics Platform.** Live production platform for U.S. wholesale power analysis across the five major FERC-regulated RTOs (PJM, ERCOT, NYISO, MISO, ISO-NE). Historical daily and hourly LMPs (energy, congestion, marginal-loss components), monthly and daily forward-contract settlement histories, contract-strip aggregation (Summer, Winter, Spring, Q1–Q4), and an integrated Price ⇄ Heat-Rate toggle bridging power ($/MWh) and gas ($/MMBtu) markets via Platts / Henry Hub LD1 / ICE GDD FUT.
- **U.S. Natural Gas Demand Forecast Platform.** Production codebase producing daily 30-day demand forecasts for the U.S. Lower 48, disaggregated into 12 geographic regions × 4 end-use sectors (48 specialized models) — XGBoost for weather-sensitive sectors, Ridge regression for slower-moving sectors. Driven by NWS temperature forecasts, NOAA NCEI Global Historical Climatology Network — Daily observations, and the Federal Reserve Board's Industrial Production Index (G.17), trained on EIA state-level consumption data (Form EIA-857). Each model validated by walk-forward cross-validation (per-fold MAE / RMSE / MAPE) with physical-bounds sanity checks.
- **U.S. LNG Feed-Gas Forecasting Pipeline.** End-to-end demand forecasting pipeline covering the U.S. LNG export terminal fleet — 126 export trains across 13 terminals (~22,600 MMcf/d nameplate). Three-model validation framework achieving < 3% MAPE on an 8-month out-of-sample holdout.
- **Real-Time U.S. Natural Gas Production Model.** OLS / Ridge scaling framework combining licensed daily pipeline-nominations data with EIA-914 official monthly statistics, validated by R² and MAE. Produces a current-month U.S. production estimate that operates within the two-month EIA reporting-lag interval.
- **Permian Basin Market Intelligence System.** Daily codebase modeling Permian production (~22–25 Bcf/d), integrating egress capacity across the four major egress pipelines to construct a supply-demand balance and predict Waha basis pricing for the trading desk.
- **Pipeline Force Majeure Alert Service.** Real-time alerting service polling electronic bulletin boards across **32 U.S. interstate natural-gas pipelines** every five minutes, deduplicating events against persistent state, and pushing Force Majeure and maintenance notices to the DXT trading team via Microsoft Teams webhook — reducing trading-team response time from hours to minutes.
- **PEPCO Nodal Basis Screen.** Phase-1 quantitative screen of PJM bidding nodes in the PEPCO zone for downstream FTR bidding analysis. ~8.77 M hourly observations across 61 PEPCO nodes and the zone aggregate, 8+ years of PJM day-ahead settlement data (Jan 2018 – mid-2026). Deliverables: print-ready 11-page PDF stakeholder report + markdown companion + per-node per-component CSV + 8.77M-row parquet panel.

### Stevens Institute of Technology — Hoboken, NJ
**Quantitative Research Assistant — School of Business** | April 2025 – February 2026

- Implemented the **ε-subdivision Robust PCA framework for dynamic factor portfolios** in Python with Prof. Papa Momar Ndiaye — block decomposition of the eigenspectrum against a tolerance ε, Gram–Schmidt construction of the closest orthonormal basis to the prior period's factors, and rupture-detection that resets factor tracking when block-mean eigenvalues shift beyond a threshold δ. Added K-Means clustering on eigenvector features as an independent signal of factor-structure change.
- Validated on ~6.5 years of daily returns across the 11 S&P 500 GICS sector ETFs, spanning the COVID-19 shock and the post-pandemic inflation cycle. Fed the robust and standard covariance estimates into a mean-variance optimizer and compared cumulative returns, 126-day rolling annualized volatility, and cluster-transition timing — the robust approach stabilized factors at portfolio volatility essentially identical to standard PCA.

---

## EDUCATION

**Stevens Institute of Technology** — Hoboken, NJ
Master of Science in Financial Engineering & Analytics (STEM-designated)
*Graduate coursework:* Stochastic Calculus for Financial Engineers · Probability Theory · Statistical Learning · Advanced Financial Risk Analytics & Derivatives · Machine & Deep Learning in Finance · Foundation of Financial Data Science & Modeling · Pricing & Hedging · Computational Methods in Finance · Portfolio Optimisation · Algorithmic Trading Strategies · Market Microstructure · C++ for Derivatives · Optimization in Finance

**North South University** — Dhaka, Bangladesh
Bachelor of Business Administration — Major: Finance · Minor: Mathematics

---

## RESEARCH

**Master's Thesis** — *LLM-Generated Views in a Black–Litterman Portfolio*

Fed repeated LLM forecasts into the Bayesian update as probabilistic views — sample mean as the view, sample variance as view uncertainty. Tested on the 50 largest S&P 500 names over Feb 2024 – Jan 2025 with biweekly rebalancing. Beat the mean-variance benchmark on risk-adjusted return with steadier allocations.

---

## TECHNICAL SKILLS

- **Languages & Tools:** Python, SQL, TypeScript, JavaScript · React, Next.js, FastAPI · SQL Server, Docker, AWS · Git, GitHub, GitLab
- **AI / LLM:** LangChain · LangGraph · LangSmith · RAG · Vector Databases · LLM Agents · Prompt Engineering · Anthropic Claude & OpenAI APIs
- **Machine Learning:** PyTorch · Scikit-learn · XGBoost · LightGBM · Pandas · NumPy · Time-Series Forecasting
- **Energy Markets:** Natural Gas & Power · LNG Forecasting · Pipeline Capacity Analysis · ISOs / RTOs (PJM, ERCOT, NYISO, MISO, ISO-NE) · FTR Markets

---

## CERTIFICATIONS

- **Advanced Retrieval-Augmented Generation** — full RAG stack: embeddings, vector stores, HyDE, CRAG, Self-RAG, Graph RAG, Agentic RAG with LangGraph, RAGAS evaluation
- **Akuna Capital Options 101** — options fundamentals from a leading market maker (Greeks, volatility, payoff diagrams)
- **Probability — The Science of Uncertainty and Data** — MIT / edX
- **Python and Statistics for Financial Analysis** — Coursera
- **FastAPI — The Complete Course** · **Complete Data Science, ML, DL, NLP Bootcamp** · **Algorithmic Trading with Python, ChatGPT, ML** — Udemy

---

## PROFESSIONAL AFFILIATIONS & AWARDS

- Student Member, **CFA Society New York**
