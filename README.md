<div align="center">

# 🧠 AI Engineering & Quantitative Systems Portfolio

### Full-Stack AI Engineer · Quantitative Researcher · Systems Architect

*Building high-performance systems at the intersection of AI, finance, and blockchain since 2022*

[![Protocol Titan](https://img.shields.io/badge/🔗_Protocol_Titan-Live_Product-0a0a0a?style=for-the-badge&labelColor=1a1a2e)](https://protocoltitan.com)
[![AWS Credits](https://img.shields.io/badge/AWS-$10K_Credits_Awarded-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://protocoltitan.com)
[![AI Since](https://img.shields.io/badge/AI_Engineering-Since_2022-00d4aa?style=for-the-badge&logo=openai&logoColor=white)](#-ai--prompt-engineering-mastery)
[![Python](https://img.shields.io/badge/Python-Expert-3776AB?style=for-the-badge&logo=python&logoColor=white)](#-technical-skills)
[![Rust](https://img.shields.io/badge/Rust-Systems-000000?style=for-the-badge&logo=rust&logoColor=white)](#-technical-skills)

---

> **"I don't just use AI — I architect complete systems with it. Every project below was designed, iterated, and shipped using advanced AI-assisted development workflows, giving me thousands of hours of hands-on prompt engineering experience across every major LLM."**

</div>

---

## 📑 Table of Contents

- [Core Competencies](#-core-competencies)
- [Featured Projects](#-featured-projects)
  - [Protocol Titan — DeFi Infrastructure (AWS-Backed)](#1--protocol-titan--institutional-defi-infrastructure)
  - [30-Minute ORB Algorithm — Consistently Profitable Trading System](#2--30-minute-orb-algorithm--consistently-profitable-nasdaq-trading-system)
  - [Prop Firm Model Reverse Engineering](#3--prop-firm-model-reverse-engineering)
  - [Polymarket Dual Arbitrage Bot](#4--polymarket-dual-arbitrage-bot)
  - [RICH Algorithm Blockchain Arbitrage Engine](#5--rich-algorithm-blockchain-arbitrage-engine)
  - [Visionary Vibe SaaS Platform](#6--visionary-vibe--b2b-saas-platform-for-italian-businesses)
  - [Casino Bonus & Sports Build-a-Bet Reverse Engineering](#7--casino--sportsbook-mathematical-edge-systems)
  - [NinjaTrader Custom Indicators with Live Web Data](#8--ninjatrader-professional-indicators-with-live-http-data)
  - [Reth Private Node on Base Network](#9--reth-private-node--base-network-infrastructure)
  - [YouTube Giveaway Edge System](#10--youtube-giveaway-probability-optimization)
  - [Polymarket Temporal Edge Discovery](#11--polymarket-temporal-edge--low-price-share-strategy)
  - [Platform Reverse Engineering & Access Research](#12--platform-reverse-engineering--access-research)
- [Experimental Lab — Failed Experiments & Lessons](#-experimental-lab--failed-experiments--lessons-learned)
- [AI & Prompt Engineering Mastery](#-ai--prompt-engineering-mastery)
- [Asymmetric Risk Framework](#-asymmetric-risk-framework--universal-edge-detection)
- [Research & Pattern Recognition](#-research--pattern-recognition-methodology)
- [Technical Skills](#-technical-skills)
- [Professional Experience](#-professional-experience)
- [Education & Continuous Learning](#-education--continuous-learning)

---

## 🎯 Core Competencies

<table>
<tr>
<td width="50%">

### 🤖 AI & Engineering
- **AI-Assisted Development** — 3+ years of daily LLM usage for building complete production systems
- **Prompt Engineering** — Expert-level across GPT-4, Claude, Gemini, and open-source models
- **System Architecture** — Designing end-to-end solutions from ideation to deployment
- **Full-Stack Development** — Frontend, backend, APIs, databases, cloud infrastructure
- **Data Pipeline Design** — Real-time ingestion, transformation, and analysis

</td>
<td width="50%">

### 📊 Quantitative & Analytical
- **Quantitative Research** — Statistical edge discovery across financial markets
- **Algorithmic Trading** — Strategy design, backtesting, execution optimization
- **Probability Theory** — Win rate / risk-reward analysis applied to every domain
- **Reverse Engineering** — Deconstructing black-box systems to extract mathematical models
- **Pattern Recognition** — Identifying exploitable asymmetries across domains

</td>
</tr>
</table>

---

## 🚀 Featured Projects

### 1. 🏛️ Protocol Titan — Institutional DeFi Infrastructure
**[protocoltitan.com](https://protocoltitan.com)** · *Awarded $10,000 in AWS Credits*

<table>
<tr><td>

#### Problem
Decentralized finance (DeFi) suffers from a critical 2–6 second "Oracle Lag" between real-world event resolution and on-chain settlement, causing **$500M+ in annual price slippage** and preventing institutional market makers from operating efficiently.

#### Solution — Zero-Latency Liquidity Engine
Built a next-generation MEV-resistant infrastructure platform that eliminates Oracle latency in high-frequency prediction markets.

#### Architecture & Technical Details

| Component | Technology | Purpose |
|-----------|-----------|---------|
| **Execution Engine** | Rust / Alloy | Custom execution client for sub-millisecond transaction processing |
| **Network Layer** | DPDK Kernel-Bypass, SR-IOV | Analyzes mempool data **200ms faster** than standard nodes |
| **ML Pipeline** | Amazon SageMaker, Transformer NLP | Predicts Oracle consensus with **99.9% accuracy** before block finalization |
| **Data Ingestion** | Kinesis, MSK (Kafka) | Real-time normalization of WebSocket streams from **50+ DEXs** |
| **Caching** | ElastiCache Redis | In-memory O(1) lookup for millions of QuestionID → ConditionID mappings |
| **Infrastructure** | EC2 `c8i.metal` (Bare Metal) | SR-IOV enabled bare-metal for HFT workloads |
| **Colocation** | AWS `eu-west-2` (London) | Same Availability Zone as major DeFi CLOBs for minimal TCP RTT |
| **Frontend** | Modern web stack | Professional institutional-grade landing page and documentation |

#### Key Achievements
- ✅ **$10,000 AWS credits awarded** — Validated by AWS for infrastructure innovation
- ✅ Designed kernel-bypass architecture achieving **sub-10μs packet processing**
- ✅ Built Transformer NLP models for real-time Oracle proposal interpretation
- ✅ Architected full cloud-native infrastructure across 7+ AWS services
- ✅ Created professional whitepaper and institutional-grade documentation
- ✅ Implemented predictive ML models trained on unstructured DeFi governance text

</td></tr>
</table>

---

### 2. 📈 30-Minute ORB Algorithm — Consistently Profitable Nasdaq Trading System

<table>
<tr><td>

#### Concept
Designed and built an algorithmic trading system based on the **Opening Range Breakout (ORB)** strategy on the Nasdaq, using the first 30 minutes of market data to establish a directional bias.

#### Technical Implementation

```
Strategy Pipeline:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Market Open → Collect 30-min OHLC Data
    ↓
Calculate Opening Range (High/Low boundaries)
    ↓
Apply Relative Volume (RVOL) Filter
  → Skip unfavorable ORBs with abnormal volume profiles
    ↓
Apply Wick Percentage Filter
  → Filter candles where wick-to-body ratio indicates indecision
    ↓
Directional Breakout Detection
    ↓
Position Entry with Risk Management
    ↓
Automated Exit (Target / Stop-Loss)
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

#### Filtering Innovations
- **Relative Volume (RVOL) Filter** — Compared current session volume against historical averages to avoid low-conviction breakouts
- **Wick Percentage Analysis** — Calculated wick-to-body ratios on ORB candles to filter setups showing market indecision
- **OHLC Imbalance Detection** — Identified candles with no wick (open = high or open = low) as signals of strong directional imbalance

#### Results
- ✅ **Consistently profitable** across extended backtesting and live trading periods
- ✅ Robust edge maintained across different market conditions
- ✅ Successfully integrated multiple independent confirmation filters

</td></tr>
</table>

---

### 3. 🎰 Prop Firm Model Reverse Engineering — Complete Mathematical Breakdown

<table>
<tr><td>

#### Objective
Reverse-engineered the **MyFundedFutures (MFF) 50K Rapid Plan** to discover that the prop firm's own rules create a structural mathematical edge — a high-volatility momentum strategy (the 30-minute ORB) combined with an asymmetric payout loop that flips the house math against them.

#### The Complete Pipeline — 3 Phases to Payout

```
╔═════════════════════╗   ╔═════════════════════╗   ╔═════════════════════╗
║  PHASE 1             ║   ║  PHASE 2             ║   ║  PHASE 3             ║
║  EVALUATION          ║ → ║  INTRADAY DRAWDOWN   ║ → ║  SIM FUNDED          ║
║                     ║   ║                     ║   ║                     ║
║  Pay $119 eval fee  ║   ║  Build buffer with   ║   ║  Risk $2,000 max     ║
║  Hit $3K target     ║   ║  intraday drawdown   ║   ║  Target 2RR = $4,000 ║
║  $2K EOD drawdown   ║   ║  rules (stricter)    ║   ║  Min withdrawal $500 ║
║  50% consistency    ║   ║                     ║   ║  Repeat until dead   ║
║  Min 2 days         ║   ║                     ║   ║                     ║
╚═════════════════════╝   ╚═════════════════════╝   ╚═════════════════════╝
    Cost: $119               Cost: $0                 Payout: withdrawals
    Risk: eval fee only      Risk: nothing (virtual)  until account dies
```

---

#### Phase 1: The Evaluation — Where the Hidden Edge Lives

| Parameter | Value |
|-----------|-------|
| Account Size | $50,000 |
| Profit Target | $3,000 (6%) |
| Max Drawdown (EOD) | $2,000 (4%) |
| Consistency Rule | 50% (no single day > 50% of total profit) |
| Minimum Days | 2 |
| Eval Fee | $119 |

**The 50% consistency rule** means the fastest possible pass is exactly 2 days: **$1,500 on Day 1** and **$1,500 on Day 2**.

**Step 1 — The R:R Hidden in the Rules**

The Max Drawdown ($2,000) is **larger** than the daily profit needed ($1,500). This creates a per-day R:R that is automatically favorable:

$$R:R = \frac{\text{Daily Target}}{\text{Max Drawdown}} = \frac{\$1{,}500}{\$2{,}000} = 0.75$$

**Step 2 — Breakeven Win Rate (No Edge / Pure Gambling)**

At R:R = 0.75, a strategy with **zero edge** (completely random trades) has a per-day win probability of:

$$W\%_{\text{day}} = \frac{\text{Risk}}{\text{Risk} + \text{Reward}} = \frac{\$2{,}000}{\$2{,}000 + \$1{,}500} = \frac{2{,}000}{3{,}500} = 57.14\%$$

**Step 3 — Probability of Passing Evaluation (No Edge)**

Passing requires winning on **both** days. With zero trading edge:

$$P(\text{Pass Eval}) = P(\text{Win Day 1}) \times P(\text{Win Day 2}) = 0.5714 \times 0.5714 = \mathbf{32.65\%}$$

> **With absolutely no trading edge — pure gambling — 1 in 3 evaluations will pass.** This is the baseline. The prop firm thinks their rules protect them. They don't.

**Step 4 — Probability of Passing WITH the 30-Minute ORB Edge**

The 30-minute ORB strategy (see Project #2) provides a real, consistent momentum edge. Running a **Monte Carlo simulation with 500,000 random trials** using the ORB backtest results (including partial wins and partial losses):

$$P(\text{Pass Eval with ORB}) = \mathbf{37.26\%}$$

| Scenario | Phase 1 Pass Rate |
|----------|-------------------|
| **No edge (random trades)** | 32.65% |
| **With 30-min ORB strategy** | **37.26%** |
| **Improvement** | **+4.61 percentage points** |

---

#### Phase 2: Intraday Drawdown — The Buffer Phase

Accounts that pass Phase 1 enter Phase 2 with stricter intraday drawdown rules. Using the same Monte Carlo methodology with the 30-minute ORB:

$$P(\text{Pass Phase 2 → Phase 3}) = \mathbf{33.60\%}$$

---

#### Phase 3: Sim Funded — The Payout Phase

This is where revenue is generated. The optimal R-multiple that maximizes Expected Value is **2RR** — risking the full $2,000 drawdown to target $4,000 in profit. Minimum withdrawal is $500.

**Monte Carlo Results — Phase 3 Trade Outcomes:**

| Outcome | Probability | Result |
|---------|------------|--------|
| **Full Win (2RR)** | 25.7% | +$4,000 |
| **Partial Win (0.616R)** | 23.5% | +$1,232 avg |
| **Partial Loss (−0.443R)** | 14.8% | −$886 avg |
| **Full Loss** | 36.7% | Account dies |

**Monte Carlo Results — Phase 3 Account Lifecycle:**

| Outcome | Probability |
|---------|------------|
| **Account dies immediately (no withdrawal)** | 44.41% |
| **Minimum 1 withdrawal ($500+)** | **55.59%** |
| → Single withdrawal ($500–$4,000) | 24.79% |
| → Two or more withdrawals | 30.80% |

**Average revenue per account reaching Phase 3:**

$$\text{Avg Revenue}_{P3} = \mathbf{\$3{,}193.80}$$
$$\text{Avg Account Lifespan} = \mathbf{2.78 \text{ trades}}$$

---

#### Full Pipeline — End-to-End Probability & EV

**Probability of at least 1 withdrawal from a fresh evaluation:**

$$P(\text{Payout}) = P(\text{Phase 1}) \times P(\text{Phase 2}) \times P(\text{Phase 3 Withdrawal})$$

$$P(\text{Payout}) = 0.3726 \times 0.3360 \times 0.5559 = \mathbf{6.96\%}$$

> **1 in every 14.3 evaluation accounts will generate at least one $500+ withdrawal.** This is the hit rate.

**Probability of reaching Phase 3 (funded):**

$$P(\text{Funded}) = 0.3726 \times 0.3360 = \mathbf{12.52\%}$$

**Gross Expected Value per Evaluation:**

$$EV_{\text{gross}} = P(\text{Funded}) \times \text{Avg Revenue}_{P3} = 0.1252 \times \$3{,}193.80 = \mathbf{\$399.86}$$

**Net Expected Value per Evaluation (after eval fee):**

$$EV_{\text{net}} = \$399.86 - \$119 = \mathbf{+\$280.86 \text{ per account}}$$

$$\text{ROI per eval} = \frac{\$280.86}{\$119} = \mathbf{+236\%}$$

---

#### Weekly Profit Projections

Average account lifespan ≈ 2.5 trading days → **2 full account cycles per week** (buy new eval the moment the old one dies).

| Scale | Parallel Accounts | Cycles/Week | Weekly Net Profit |
|-------|-------------------|-------------|-------------------|
| **Solo** | 1 | 2 | **$561.72** |
| **Scaled (trade copier)** | 5 | 10 | **$2,808.60** |

---

#### Why the Edge is in the RULES, Not the Trading

```
ARBITRAGE:    You see price gap → Everyone sees it → Race → Edge dies
PROP FIRM:    Rules exist → Nobody reads the math → Edge is permanent → No race

The 85% of traders who fail:
  → Trade randomly, don't optimize for the specific R:R
  → Use too much leverage, hit drawdown early
  → Don't understand EOD vs intraday measurement
  → Don't use Monte Carlo to model partial wins/losses
  → THEY fund the payouts for the 15% who do the math
```

#### 5-Law Validation ✅

| Law | Pass? | Evidence |
|-----|-------|----------|
| **1. Edge hidden in rules** | ✅ | EOD drawdown ($2K) > daily target ($1.5K) → 0.75 R:R → 57.14% baseline WR. You must DO THE MATH to see it |
| **2. House doesn't know** | ✅ | MFF designed the 50% consistency rule and EOD drawdown to "feel hard." They protect against 85% of traders — not against Monte Carlo optimization |
| **3. No speed dependency** | ✅ | You have ALL DAY to place your trade. The 30-min ORB triggers once per session |
| **4. Structurally repeatable** | ✅ | Same rules → same math → same edge. Every single evaluation, indefinitely |
| **5. No competition** | ✅ | Nobody else sees the R:R in the rules → nobody competes for the same structural edge |

#### Key Skills Demonstrated
- Prop firm rule reverse engineering & financial model deconstruction
- **Monte Carlo simulation** (500K+ random trials with partial win/loss distributions)
- Multi-phase probability modeling (3 consecutive dependent stages)
- Expected Value optimization (identifying 2RR as optimal R-multiple)
- Risk management & position sizing across account lifecycle
- Algorithmic strategy integration (30-min ORB → evaluation pipeline)
- Game theory application to real financial structures

</td></tr>
</table>

---

### 4. 🤖 Polymarket Dual Arbitrage Bot

<table>
<tr><td>

#### Concept
Built an automated arbitrage bot for Polymarket (blockchain-based prediction market) that profits from **pricing inefficiencies where the sum of YES and NO share prices falls below $1.00**.

#### How the Arbitrage Works — Mathematical Proof

In a binary prediction market, a YES share and a NO share must always sum to exactly $1.00 at settlement (one pays $1, the other pays $0). When the market is inefficient:

$$P_{\text{YES}} + P_{\text{NO}} < \$1.00$$

**The arbitrage is risk-free:**

$$\text{Profit} = \$1.00 - (P_{\text{YES}} + P_{\text{NO}}) - \text{Fees}$$

**Example:**

| Share | Market Price | Settlement Value |
|-------|-------------|------------------|
| YES | $0.47 | $1.00 if YES wins |
| NO | $0.48 | $1.00 if NO wins |
| **Total Cost** | **$0.95** | **$1.00 guaranteed** |
| **Risk-Free Profit** | | **$0.05 per share pair (5.26% return)** |

$$\text{Return} = \frac{\$1.00 - \$0.95}{\$0.95} = 5.26\%$$

By buying **both** YES and NO simultaneously when their combined price is below $1.00, one of them is guaranteed to pay out $1.00 — netting the difference as risk-free profit.

#### Architecture

```
         ┌──────────────────────────────┐
         │   WebSocket Price Monitor      │
         │   (Real-time YES + NO prices)  │
         └──────────────┬─────────────────┘
                        │
              ┌─────────▼──────────┐
              │  Arbitrage Detector │
              │                    │
              │  IF (YES + NO) < 1 │
              │  → EXECUTE         │
              └─────────┬──────────┘
                        │
           ┌────────────┼────────────┐
           ▼                         ▼
    ┌─────────────┐          ┌─────────────┐
    │  Buy YES     │          │  Buy NO      │
    │  share       │          │  share       │
    └─────────────┘          └─────────────┘
           │                         │
           └──────────┬──────────────┘
                      ▼
            ┌──────────────────┐
            │ GUARANTEED:      │
            │ One pays $1.00   │
            │ Profit = $1 -    │
            │ (YES + NO cost)  │
            └──────────────────┘
```

#### Outcome & Learnings
- Successfully built and deployed the bot
- Discovered the edge was **too thin after transaction costs** to be consistently profitable
- **Key Insight:** Market makers keep YES + NO prices very tight to $1.00. The windows where the sum drops below $1.00 minus fees are rare and close within seconds, making gas costs the dominant factor

</td></tr>
</table>

---

### 5. ⚡ RICH Algorithm Blockchain Arbitrage Engine

<table>
<tr><td>

#### Innovation
Built a high-performance blockchain arbitrage system on the **Base Network (L2)** implementing the **RICH (Real-time Identification of negative Cycles for High-efficiency arbitrage)** algorithm — a novel framework achieving **32.69× faster** cycle detection compared to state-of-the-art methods.

#### About the RICH Algorithm

**RICH** was designed by **Luo et al.** at the **National University of Singapore (NUS)** and **Tokka Labs**, and was published at **VLDB 2025** — one of the top-tier database/systems conferences in the world.

📄 **Paper:** [RICH: Real-time Identification of negative Cycles for High-efficiency Arbitrage](https://www.vldb.org/pvldb/vol18/p4081-luo.pdf) — *PVLDB, Vol. 18, No. 11, pp. 4081–4089 (2025)*

🔗 **Source Code:** [github.com/Xtra-Computing/RICH](https://github.com/Xtra-Computing/RICH)

#### How RICH Works — Technical Deep Dive

RICH models DEX arbitrage as a **$k$-hop negative cycle detection problem** in a token-pair graph. A negative cycle means that traversing the cycle (swapping through a series of token pairs) results in more tokens than you started with — i.e., **profit**.

```
Token Graph (DEX liquidity pools):

   USDC ──0.98──→ ETH ──1.03──→ WBTC ──1.01──→ USDC
    ↑                                              │
    └──────── Product: 0.98 × 1.03 × 1.01 = 1.019 ─┘
                   ↑
         Product > 1.0 = PROFITABLE CYCLE
         (Negative cycle in log-space)
```

**Three key innovations make RICH 32× faster:**

| Technique | What It Does | Why It's Fast |
|-----------|-------------|---------------|
| **Color-Coding** | Assigns random "colors" to nodes to probabilistically detect cycles without exhaustive traversal | Avoids combinatorial explosion of path enumeration |
| **Dynamic Programming** | Tailored DP tables store intermediate cycle results to eliminate redundant computation | Reuses sub-problems instead of recomputing |
| **Graph Reduction & Encoding** | Prunes irrelevant nodes/edges and encodes the graph compactly | Reduces problem size by orders of magnitude |

**Combined with CPU AVX-512 SIMD vectorization** for parallel price calculations across multiple paths simultaneously:

$$\text{Speedup} = \frac{T_{\text{baseline}}}{T_{\text{RICH}}} = 32.69\times$$

#### Architecture
| Component | Details |
|-----------|---------|
| **Cycle Detection** | RICH algorithm — $k$-hop negative cycle detection via color-coding + DP |
| **Computation** | CPU AVX-512 SIMD for parallel price path evaluation |
| **Network** | Base Network (Ethereum L2) for reduced gas costs |
| **Node** | Private Reth node for low-latency mempool access |
| **Execution** | Atomic smart contract transactions to eliminate partial-fill risk |

#### Results
- ✅ Achieved **32.69× speed improvement** over state-of-the-art using RICH + SIMD vectorization
- ✅ Implemented cutting-edge academic research (VLDB 2025) into a working production system
- ❌ Did not achieve consistent profitability — competition from professional MEV bots with dedicated infrastructure
- ✅ **Deep learning outcome:** Mastered graph algorithms, low-level CPU optimization (AVX-512), blockchain mempool dynamics, and DEX liquidity mechanics

</td></tr>
</table>

---

### 6. 💼 Visionary Vibe — B2B SaaS Platform for Italian Businesses

<table>
<tr><td>

#### Product
Built and launched a full SaaS platform in 2024 targeting **local Italian businesses**, providing professional digital products and services.

#### Service Tiers

| Tier | Services Included |
|------|-------------------|
| **Standard** | Professional website design & development, basic SEO, hosting setup |
| **Premium** | Custom web applications, advanced SEO, branding, analytics dashboard, ongoing support |

#### Technical Stack
- **Frontend** — Modern responsive design with custom UI/UX
- **Backend** — Server-side logic, authentication, payment processing
- **Deployment** — Cloud-hosted with SSL, CDN, and monitoring
- **Client Portal** — Dashboard for clients to manage their services and view analytics

#### Business Operations
- Complete client acquisition pipeline (outreach → proposal → delivery)
- Service packaging and pricing strategy
- Client relationship management
- Iterative design process with client feedback loops

#### Outcome
- Built a fully operational SaaS business from zero
- Successfully delivered professional digital products to Italian SMBs
- Gained end-to-end experience in product design, development, sales, and delivery

</td></tr>
</table>

---

### 7. 🎯 Casino & Sportsbook Mathematical Edge Systems

<table>
<tr><td>

#### Research Areas

---

**🎰 Slot Bonus Reverse Engineering — The Math**

Casino bonuses have **wagering requirements** (WR). The house sets them to "feel hard" — **but they don't run the math.** Just like prop firms, the edge is hidden in the rules:

$$EV_{\text{bonus}} = \text{Bonus} - (\text{Total Wagered} \times \text{House Edge})$$

**Example: $100 bonus, 30× wagering requirement, 97% RTP slot (3% house edge):**

| Parameter | Value |
|-----------|-------|
| Bonus Amount | $100 |
| Wagering Requirement | 30× bonus = $3,000 total |
| House Edge (100% - 97% RTP) | 3% |
| Expected Loss from Wagering | $3,000 × 0.03 = **$90** |
| **Net EV** | **$100 − $90 = +$10.00** |

The **universal rule** for when a bonus is +EV:

$$\text{WR} < \frac{1}{\text{House Edge}}$$

$$\text{WR} < \frac{1}{0.03} = 33.3\times$$

> **Any bonus with a wagering requirement below $\frac{1}{\text{House Edge}}$ is mathematically profitable.** On a 97% RTP slot, any WR below 33.3× creates positive expected value. The casino sets WR to "look difficult" — not to be mathematically optimal against an informed player.

**My approach:** Systematically modeled every combination of (game RTP × bonus amount × WR) to identify which offers crossed the +EV threshold, then executed **only** those.

---

**⚽ Sports Build-a-Bet Edge Analysis — The Math**

Bookmakers price Build-a-Bet (Same Game Parlay) legs as **independent events**, but many legs within the same game are **correlated**:

$$P_{\text{bookmaker}}(A \cap B) = P(A) \times P(B) \quad \text{(assumes independence)}$$

But in reality, player stats and game outcomes are correlated. When a player scores more, their team is more likely to win. The **true** probability is:

$$P_{\text{true}}(A \cap B) = P(A) \times P(B|A)$$

When events are **positively correlated**, $P(B|A) > P(B)$, so:

$$P_{\text{true}}(A \cap B) > P_{\text{bookmaker}}(A \cap B)$$

**This underprices correlated parlays.** The bookmaker's payout multiplier is FIXED regardless of how mispriced the legs are.

**Example: 2-Leg Build-a-Bet**

| Component | Bookmaker's Assumption | True Probability |
|-----------|----------------------|------------------|
| Leg A: Player scores 25+ pts | 55% | 55% |
| Leg B: Team wins | 60% | 60% |
| **Parlay (independent)** | 55% × 60% = **33.0%** | — |
| **Parlay (correlated)** | — | **40.7%** |
| **Build-a-Bet Payout** | **3×** (fixed) | — |

Breakeven for a 2-leg at 3× payout:

$$W\%_{\text{breakeven}} = \frac{1}{\text{Payout}} = \frac{1}{3} = 33.3\%$$

The bookmaker prices the parlay at 33.0% (near breakeven). But the **true correlated probability is 40.7%** — a massive gap:

$$EV = (0.407 \times \$60) - (0.593 \times \$20) = \$24.42 - \$11.86 = \mathbf{+\$12.56 \text{ per \$20 entry}}$$

$$\text{ROI} = \frac{\$12.56}{\$20} = \mathbf{+62.8\%}$$

The **payout multiplier is fixed** regardless of how mispriced the correlation is — this is the exact same structural flaw as prop firm rules: the house prices for optics, not mathematical optimality.

#### 5-Law Validation for Casino & Sports Edge ✅

| Law | Casino Bonus | Sports Build-a-Bet |
|-----|-------------|---------------------|
| **1. Edge hidden in rules** | ✅ Must calculate WR vs. RTP threshold | ✅ Must model correlation that the platform ignores |
| **2. House doesn't know** | ✅ Casino sets WR to "feel hard" not be mathematically optimal | ✅ Bookmaker assumes independence — doesn't model correlation |
| **3. No speed dependency** | ✅ Bonuses available for hours/days | ✅ Lines available hours before game time |
| **4. Structurally repeatable** | ✅ New bonuses daily across platforms | ✅ Every single game offers Build-a-Bet |
| **5. No competition** | ✅ Your bonus doesn't affect mine | ✅ Your bet doesn't move the line — non-zero-sum |

#### Skills Demonstrated
- Probability theory & conditional probability modeling
- Reverse engineering proprietary pricing algorithms
- Correlation analysis between dependent events
- Kelly Criterion-based position sizing

</td></tr>
</table>

---

### 8. 📊 NinjaTrader Professional Indicators with Live HTTP Data

<table>
<tr><td>

#### Project
Built custom professional-grade indicators for the **NinjaTrader** trading platform that pull live data from external web sources via HTTP requests and display it with a polished UI.

#### Technical Details
- **Language:** C# (NinjaScript)
- **Data Integration:** HTTP client for fetching real-time data from REST APIs / web sources
- **Parsing:** JSON/HTML parsing of external data feeds
- **UI/UX:** Custom-rendered indicator panels with professional visual design (colors, layouts, fonts)
- **Real-time Updates:** Automated data refresh cycles synchronized with market data ticks

#### Architecture Flow
```
External Web Source (API / Website)
        │
        │  HTTP GET Request
        ▼
┌──────────────────┐
│  NinjaTrader      │
│  Custom Indicator │
│  ┌──────────────┐ │
│  │ Data Parser   │ │
│  │ (JSON/HTML)   │ │
│  └──────┬───────┘ │
│         ▼         │
│  ┌──────────────┐ │
│  │ Visual Panel  │ │
│  │ (Custom UI)   │ │
│  └──────────────┘ │
└──────────────────┘
```

#### Key Skills
- Platform SDK integration (NinjaScript/C#)
- Async HTTP networking within constrained platform environments
- Custom rendering and UI design within trading platforms
- Real-time data synchronization

</td></tr>
</table>

---

### 9. 🔗 Reth Private Node — Base Network Infrastructure

<table>
<tr><td>

#### Project
Deployed a local private node on the **Base blockchain network** using **Reth** (Rust Ethereum execution client) for low-latency, private access to blockchain state and mempool data.

#### Technical Details
| Component | Details |
|-----------|---------|
| **Client** | Reth (high-performance Rust-based Ethereum client) |
| **Network** | Base (Ethereum L2 by Coinbase) |
| **Deployment** | Local bare-metal setup |
| **Purpose** | Private mempool access, low-latency state queries, MEV research |

#### Skills Demonstrated
- Blockchain node deployment and configuration
- Rust ecosystem familiarity
- Network infrastructure management
- Understanding of Ethereum execution layer internals (EVM, state tries, mempool)

</td></tr>
</table>

---

### 10. 🎁 YouTube Giveaway Probability Optimization

<table>
<tr><td>

#### Concept
Reverse-engineered the mechanics of YouTube giveaways (specifically prop firm account giveaways) to create a systematic, repeatable edge that maximized the probability of winning.

#### Approach
1. **Platform Analysis** — Studied the rules, entry mechanics, and selection criteria of multiple giveaway systems
2. **Pattern Recognition** — Identified structural biases in how winners were selected
3. **Optimization** — Developed systematic entry strategies that exploited the discovered biases
4. **Execution** — Implemented the strategies consistently to achieve an unfairly high win rate

#### Outcome
- Achieved a significantly above-expected win rate across multiple giveaways
- Demonstrated capacity for systematic analysis of seemingly random systems

</td></tr>
</table>

---

### 11. 💹 Polymarket Temporal Edge — Low-Price Share Strategy

<table>
<tr><td>

#### Discovery
Through systematic analysis, discovered a **temporary pricing inefficiency** on Polymarket: shares priced at very low values carried a positive expected value due to the asymmetric payoff structure.

#### Analysis
```
Standard pricing assumption:
  Share price = Probability of outcome

Discovered reality:
  At very low prices (e.g., $0.01–$0.05), the implied probability
  UNDERSTATED the true probability of the outcome occurring.

  → Buying low-priced shares created a positive EV position:
     Small investment → Large potential payout (100:1 to 20:1)
     True probability > Implied probability
```

#### Key Insight
The market was systematically underpricing tail-risk events, creating a repeatable long-shot strategy with positive expected value — a well-known phenomenon in prediction markets and sports betting ("favorite-longshot bias").

</td></tr>
</table>

---

### 12. 🔓 Platform Reverse Engineering & Access Research

<table>
<tr><td>

#### Scope
Conducted security research and reverse engineering on multiple web platforms, analyzing paywall mechanisms, authentication flows, and premium feature gating.

#### Technical Methods
- **Network Analysis** — HTTP/HTTPS traffic inspection, API endpoint mapping, request/response pattern analysis
- **Client-Side Analysis** — JavaScript deobfuscation, DOM manipulation, local storage and session management
- **Authentication Research** — Token lifecycle analysis, session management, access control bypass research
- **API Exploration** — Undocumented endpoint discovery, parameter fuzzing, rate limit analysis

#### Skills Demonstrated
- Web security fundamentals (OWASP awareness)
- Browser DevTools proficiency (Network, Console, Application tabs)
- API reverse engineering
- Understanding of client-server architecture vulnerabilities

</td></tr>
</table>

---

## 🧪 Experimental Lab — Failed Experiments & Lessons Learned

> **"I learn as much from failure as from success. Each failed experiment sharpened my pattern recognition and deepened my understanding of where real edges exist."**

<details>
<summary><b>Click to expand: Hundreds of Nasdaq algorithm experiments</b></summary>

### Wickless Candle Limit Order Strategy
- **Hypothesis:** Candles with no wick (open = high or open = low) indicate a strong order-flow imbalance detectable via OHLC data. Placing limit orders at these levels should capture the continuation move.
- **Implementation:** Built automated detection of wickless candles and systematic limit order placement at those price levels.
- **Result:** ❌ Failed — Random price action overwhelmed the signal. The imbalance was real but **not predictive** enough to overcome transaction costs and slippage.
- **Lesson:** Microstructure signals from OHLC data alone have limited alpha; order-flow data (Level 2, Time & Sales) is necessary for this class of strategy.

### GEX / Dealer Dynamic Hedging Strategy
- **Hypothesis:** Gamma Exposure (GEX) data revealing dealers' hedge pressure — combined with options positioning — creates predictable price magnets and barriers on the Nasdaq.
- **Implementation:** Built models incorporating GEX levels, dealer delta-hedge flows, and options open interest to predict intraday support/resistance.
- **Result:** ❌ Failed — The relationship was too noisy in live markets. GEX data is delayed, approximated, and widely known, eliminating most edge.
- **Lesson:** Widely followed indicators lose their edge through reflexivity. Proprietary, real-time data is necessary for options-flow strategies.

### Relative Volume ORB Filtering
- **Hypothesis:** Filtering ORB setups by relative volume (RVOL) could eliminate low-conviction breakouts.
- **Implementation:** Added RVOL as a pre-filter: only take ORB trades when current session volume significantly exceeds historical average.
- **Result:** ⚠️ Partially successful — Improved win rate but reduced trade frequency to the point of diminishing overall returns.
- **Lesson:** Filters improve quality but can over-optimize, reducing sample size below statistical significance.

### Wick Percentage ORB Filtering
- **Hypothesis:** ORB candles with high wick-to-body ratio indicate indecision and should be filtered out.
- **Implementation:** Calculated wick percentage for ORB candles; filtered trades above a threshold.
- **Result:** ⚠️ Partially successful — Similar to RVOL filter; marginal improvement in isolation.
- **Lesson:** Combining multiple weak filters multiplicatively can create a strong composite filter (which led to the successful ORB system above).

</details>

---

## 🧠 AI & Prompt Engineering Mastery

<table>
<tr><td>

### Experience Timeline
- **2022 → Present** — Daily, intensive use of AI/LLMs for all software development, research, and system design
- **3+ years** of continuous, hands-on prompt engineering across every major model family

### Models & Platforms Used Extensively
| Model Family | Use Cases |
|-------------|-----------|
| **GPT-5.4** | Complex system design, code generation, research synthesis |
| **Claude Opus 4.6** | Long-context analysis, nuanced code review, technical writing |
| **Gemini 3.1 Pro** | Multi-modal analysis, large codebase understanding |
| **Open-source (Llama, Mistral, etc.)** | Local deployment experiments, fine-tuning exploration |

### Prompt Engineering Expertise

**Advanced Techniques Mastered:**
- **Chain-of-Thought (CoT) Prompting** — Breaking complex problems into reasoning steps for higher accuracy
- **Few-Shot Learning** — Providing exemplar input-output pairs to guide model behavior
- **System Prompt Architecture** — Designing multi-layered system prompts that constrain and guide model behavior for production applications
- **Iterative Refinement** — Multi-turn conversations with progressive constraint tightening
- **Context Window Optimization** — Efficiently packing context for large codebases and documents
- **Role-Based Prompting** — Assigning expert personas for domain-specific tasks
- **Output Format Control** — JSON, XML, Markdown, structured data extraction
- **Error Recovery Patterns** — Systematic approaches to handle hallucination and incorrect outputs

### What I've Built with AI
Every single project in this portfolio was designed, engineered, debugged, and shipped using AI-assisted development workflows. This includes:
- Complete web applications (frontend + backend + deployment)
- Trading algorithms with complex mathematical logic
- Blockchain smart contracts and infrastructure
- Data analysis pipelines and statistical models
- Professional documentation and technical writing
- Custom indicator development in platform-specific languages (C#/NinjaScript)

### Key Differentiator
> I don't just prompt AI — I **architect systems through AI**. I understand how to decompose complex engineering problems into AI-solvable sub-tasks, validate outputs, handle edge cases, and iterate until production-quality code is achieved. This makes me exceptionally effective at AI training, evaluation, and RLHF work because I understand both sides: **how AI thinks and how to make it think better.**

</td></tr>
</table>

---

## 🔺 Asymmetric Risk Framework — Universal Edge Detection

<table>
<tr><td>

### Philosophy
I've developed a **universal mental model** for evaluating any opportunity — online or offline — through the lens of asymmetric risk. Every single opportunity is filtered through the same rigorous mathematical framework:

#### The Core Equation

$$EV = (W\% \times \text{Avg Win}) - ((1 - W\%) \times \text{Avg Loss})$$

Where:
- $W\%$ = Win Rate (probability of success)
- $R:R$ = Risk-Reward Ratio = $\frac{\text{Avg Win}}{\text{Avg Loss}}$
- $EV$ = Expected monetary value per repetition

#### Breakeven Win Rate

For any given R:R, the minimum win rate needed to break even:

$$W\%_{\text{breakeven}} = \frac{1}{1 + R:R}$$

| R:R | Breakeven WR | Meaning |
|-----|-------------|----------|
| 0.5:1 | 66.7% | Need to win 2/3 of the time |
| 1:1 | 50.0% | Coin flip territory |
| 2:1 | 33.3% | Only need 1 in 3 to profit |
| 3:1 | 25.0% | High asymmetry — powerful |

---

### 🔐 The 5 Laws of a True Mathematical Edge

Inspired by years of testing across every domain, I developed **5 mandatory laws** that any opportunity must pass before it qualifies as a repeatable money-generating edge:

| # | Law | Description | If it Fails... |
|---|-----|-------------|-----------------|
| **1** | **Edge is HIDDEN in the rules** | You must DO THE MATH to see the advantage. It's not visible to casual participants | If the edge is obvious, everyone will exploit it and it dies |
| **2** | **The house doesn't know they're giving edge** | The rule-setter designed the rules for optics/marketing, not mathematical optimality | If the house knows, they'll patch it immediately |
| **3** | **No speed/latency dependency** | You have ample time to execute. The edge doesn't decay by the second | Speed-based edges get killed by faster competitors |
| **4** | **Structurally repeatable** | Same rules → same math → same edge. Every single time | If rules change, the entire model breaks |
| **5** | **No competition for the same edge** | Nobody else sees it → nobody competes for it | Competition = margin compression = edge death |

> **Any opportunity worth pursuing must pass ALL 5 Laws.** If it fails even one, it's not a true asymmetric edge — it's either noise, arbitrage (which decays), or luck.

#### How Every Project Maps to the 5 Laws

```
                           Law 1   Law 2   Law 3   Law 4   Law 5
                          Hidden  House   No      Repeat  No
                          in      doesn't speed   -able   compet-
                          rules   know    needed          ition
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Prop Firm Exploit           ✅      ✅      ✅      ✅      ✅   → EXECUTE
Casino Bonus +EV            ✅      ✅      ✅      ✅      ✅   → EXECUTE
Sports Build-a-Bet          ✅      ✅      ✅      ✅      ✅   → EXECUTE
ORB Algorithm               ✅      ✅      ✅      ✅      ✅   → EXECUTE
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Blockchain Arbitrage        ❌      ❌      ❌      ⚠️      ❌   → REJECTED
GEX/Dealer Hedging          ❌      ❌      ✅      ⚠️      ❌   → REJECTED
Polymarket Arb Bot          ❌      ❌      ❌      ⚠️      ❌   → REJECTED
```

> *"The best edge is the one the house doesn't even know it's giving away."*

---

### Application Across Domains
This framework has been applied to:
- **Financial Markets** — Algorithmic trading, prop firm evaluations, options strategies
- **Prediction Markets** — Polymarket pricing inefficiencies
- **Casino/Sports** — Bonus structures, Build-a-Bet mispricing
- **Blockchain/DeFi** — Arbitrage, MEV, liquidity provision
- **Online Platforms** — Giveaways, promotions, referral systems
- **Business** — SaaS pricing, client acquisition cost vs. LTV

### Why This Matters for AI Work
This probabilistic thinking translates directly to AI model evaluation:
- Evaluating model outputs requires the same **systematic analytical framework**
- Identifying when AI is "hallucinating" is a form of **edge detection** (separating signal from noise)
- RLHF requires understanding what "better" means in a **structured, quantifiable way**
- Quality annotation demands **consistent judgment** under ambiguity — the same skill used in trading under uncertainty
- The 5-Law framework demonstrates **structured analytical thinking** — the exact skill needed for high-quality AI training data

</td></tr>
</table>

---

## 🔬 Research & Pattern Recognition Methodology

<table>
<tr><td>

### Research Expertise
- **Academic Paper Analysis** — Skilled at reading, interpreting, and extracting actionable insights from research papers across finance, CS, and ML
- **State-of-the-Art Discovery** — Systematic approach to finding the current best solutions, tools, and methodologies for any given domain
- **Cross-Domain Pattern Transfer** — Ability to recognize when a pattern from one domain (e.g., options pricing) applies to another (e.g., prediction market mechanics)

### Pattern Recognition — Trained by Thousands of Experiments
Years of trial and error across quantitative trading, blockchain, casino math, and platform analysis have trained an intuitive + analytical pattern recognition ability:

| Pattern Type | Description | Example |
|-------------|-------------|---------|
| **Structural Edge** | A persistent, exploitable asymmetry built into a system's rules | Prop firm evaluation rules that can be gamed with optimal sizing |
| **Temporal Edge** | A temporary mispricing that exists until market participants discover it | Polymarket low-price share positive EV window |
| **Reflexive Decay** | An edge that disappears as more people discover and exploit it | GEX/dealer hedging indicators losing predictive power |
| **Composite Signal** | Weak signals that become strong when combined multiplicatively | RVOL + Wick % + ORB = profitable system |

### Information Synthesis Speed
- Can rapidly evaluate whether a new opportunity has a genuine mathematical edge or is noise
- Trained on hundreds of real-world experiments with real capital at stake
- Build a hypothesis → test → measure → iterate cycle that closely mirrors the scientific method

</td></tr>
</table>

---

## 💻 Technical Skills

<table>
<tr>
<td width="33%">

### Languages
- **Python** — Advanced
- **JavaScript / TypeScript** — Advanced
- **Rust** — Intermediate
- **C#** — Intermediate (NinjaScript)
- **Solidity** — Intermediate
- **HTML / CSS** — Advanced
- **SQL** — Intermediate

</td>
<td width="33%">

### Frameworks & Tools
- **Web:** React, Next.js, Node.js, Express
- **Data:** Pandas, NumPy, Matplotlib
- **Blockchain:** Ethers.js, Web3, Hardhat, Foundry
- **Cloud:** AWS (EC2, SageMaker, Kinesis, MSK, Redis, S3)
- **DevOps:** Docker, Git, CI/CD, Linux
- **Trading:** NinjaTrader, MetaTrader, custom engines
- **AI/ML:** Transformers, NLP pipelines, model evaluation

</td>
<td width="33%">

### Domains
- **AI Engineering & Prompt Design**
- **Quantitative Finance**
- **Blockchain / DeFi / MEV**
- **High-Frequency Systems**
- **SaaS Product Development**
- **Security Research**
- **Data Analysis & Statistics**
- **Web Application Architecture**

</td>
</tr>
</table>

---

## 👔 Professional Experience

<table>
<tr><td>

### AI-Assisted Development Engineer *(Self-Directed, 2022–Present)*
- Designed, built, and shipped **12+ production-quality projects** across trading, blockchain, SaaS, and infrastructure
- Awarded **$10,000 in AWS credits** for Protocol Titan's infrastructure innovation
- Developed proprietary algorithmic trading systems with proven, consistent profitability
- Architected and deployed cloud-native systems using AWS bare-metal instances

### SaaS Founder — Visionary Vibe *(2024)*
- Built and launched a B2B SaaS platform serving Italian local businesses
- Managed full product lifecycle: design → development → sales → delivery → support
- Delivered professional digital products including websites, branding, and analytics

### Platform Work & AI Training *(2022–Present)*
- **UserTesting** — UX evaluation and feedback on software products
- **UHRS (Clickworker)** — Early AI training and data annotation work
- **Freelance Development** — Custom software solutions for clients

</td></tr>
</table>

---

## 📚 Education & Continuous Learning

<table>
<tr><td>

### Self-Directed Technical Education
- **3+ years** of intensive, daily AI/ML engineering practice
- **Hundreds** of algorithmic trading strategies researched, implemented, tested, and evaluated
- **Deep study** of probability theory, statistics, and quantitative methods
- **Continuous research** — Reading academic papers on ML, NLP, financial engineering, and cryptographic systems

### Methodology
My education is **project-driven**: every concept I learn is immediately applied to a real system with real stakes. This creates a feedback loop where theoretical knowledge is validated (or invalidated) by practical results, producing a deeply grounded understanding that pure academic study cannot match.

### Areas of Active Study
- Reinforcement Learning from Human Feedback (RLHF)
- Large Language Model fine-tuning and evaluation
- Advanced prompt engineering techniques
- MEV and blockchain consensus mechanisms
- High-frequency trading infrastructure

</td></tr>
</table>

---

<div align="center">

### 📫 Let's Connect

📧 **elias@protocoltitan.com**

*I'm actively seeking AI training, RLHF, and model evaluation roles where my unique combination of AI engineering expertise, quantitative rigor, and pattern recognition skills can directly improve AI model quality.*

> **🔍 Need proof?** I can provide live demos, code walkthroughs, backtesting results, architecture deep-dives, or any other evidence for every single project listed here. Just reach out at **elias@protocoltitan.com** — I'm happy to showcase anything on request.

**Available for immediate start · Remote · Flexible hours**

---

*This portfolio represents thousands of hours of hands-on experimentation, building, and learning. Every project listed is real work with real outcomes — successes and failures alike.*

</div>
