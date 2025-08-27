# 12-Week SWE/Trading Prep Roadmap

This roadmap balances **DS&A practice (LeetCode)**, **systems design exercises ("systems bites")**, and **mini coding projects ("projects")**.  
You’ll spend about **4 hrs per week** (≈2 hrs DS&A, ≈1 hr systems bite, ≈1 hr project).

---

## 📝 How to Use This Roadmap

- **Systems Bite 🧩** = a **tiny design exercise**, like a system design interview question.  
  - Output: diagram, notes, or a quick prototype (30–40 lines).  
  - Purpose: practice thinking about scalability, trade-offs, concurrency.  
  - Not necessarily portfolio code — more about *conceptual fluency*.  

- **Project 💻** = a **small coding mini-project** (50–150 lines).  
  - Output: runnable program/script you can commit to GitHub.  
  - Purpose: demonstrate end-to-end implementation skills.  
  - These are *portfolio-worthy* and can build toward your capstone.  

By the end you’ll have:  
- ~12 **systems bites** (conceptual + sketches).  
- ~12 **mini-projects** (portfolio-ready code).  
- 1 **capstone project** (Weeks 11–12).  

---

## Phase 1 – Java (Weeks 1–4)
🎯 **Goal:** DS&A speed + probability/stats basics

### Week 1 – Sorting/Searching + Probability
**LeetCode Set:** 
- Binary search: https://leetcode.com/problems/binary-search/
- rotated arrays
- Kth largest

🧩 Systems bite: **In-memory cache (like Redis)**  
- Implement `get`/`put` with HashMap.  
- Add eviction policy if >N entries.
  
💻 Project: **Coin-flip betting simulator**  
- Simulate 10,000 flips, track bankroll.  
- Print average profit/loss.

### Week 2 – Core Data Structures + Combinatorics
**LeetCode Set:** Stacks, queues, LRU cache, linked list.  
🧩 Systems bite: **URL Shortener**  
- Encode integer counter to base62.  
- Map short → long URL.  
💻 Project: **Random Order-Book Simulator**  
- Maintain bids/asks in heaps.  
- Print best bid/ask.  

### Week 3 – Dynamic Programming + Stats
**LeetCode Set:** Coin change, LIS, knapsack.  
🧩 Systems bite: **Rate Limiter**  
- Implement token bucket.  
- Allow N requests/sec.  
💻 Project: **Monte Carlo Option Pricer**  
- Simulate European call option payoff.  
- Average discounted result.

### Week 4 – Graphs + Probability Distributions
**LeetCode Set:** Islands, clone graph, course schedule.  
🧩 Systems bite: **Leaderboard System**  
- Maintain top-K scores in real time.  
- Functions: `updateScore`, `getTopK(k)`.  
💻 Project: **Random Walk Simulation**  
- Run 1000 walks of 1000 steps.  
- Show histogram convergence to normal.

---

## Phase 2 – Python (Weeks 5–8)
🎯 **Goal:** Trading sims + concurrency/networking

### Week 5 – Bitwise/Math + Pub/Sub
**LeetCode Set:** Bit ops, power of two, sqrt.  
🧩 Systems bite: **Pub/Sub Feed**  
- Dict of `{topic: [subscribers]}`.  
- Support `subscribe`, `publish`.  
💻 Project: **Prime Sieve Benchmark**  
- Sieve of Eratosthenes up to 1e6.  
- Compare vs naive prime check.

### Week 6 – Concurrency & Networking
**LeetCode Set:** Circular queue, sliding window, hit counter.  
🧩 Systems bite: **Chat System**  
- Server accepts multiple clients.  
- Broadcast messages.  
💻 Project: **Async Chat Server**  
- Use `asyncio` streams.  
- Log latency per message.

### Week 7 – Market Microstructure
**LeetCode Set:** Median finder, top-K, task scheduler.  
🧩 Systems bite: **Trading Engine**  
- Extend order book to match trades.  
- Execute if bid ≥ ask.  
💻 Project: **Limit Order Book Simulator**  
- `add_order`, `cancel_order`.  
- Print trades + updated book.

### Week 8 – Risk & Portfolio
**LeetCode Set:** Intervals, meeting rooms, gas station.  
🧩 Systems bite: **Pre-Trade Risk Check**  
- Block trades > $1m notional.  
- Integrate into order book flow.  
💻 Project: **Markowitz Optimizer**  
- Compute optimal weights for 3 assets.  
- Use covariance + returns.

---

## Phase 3 – TypeScript + Mixed (Weeks 9–12)
🎯 **Goal:** Full-stack capstone + mock assessments

### Week 9 – Mock Contest + Pairs Trading
**LeetCode Contest Warmups:** Two Sum, Anagrams, String Compression.  
🧩 Systems bite: **Scaling Backtests**  
- Sketch sharding by ticker, worker pool.  
💻 Project: **Pairs Trading Backtest**  
- Use 2 stock CSVs.  
- Trade when z-score diverges.  
- Plot PnL in React/TS.

### Week 10 – Probability Puzzles + Kelly Criterion
**LeetCode Set:** Random pick, shuffle, randomized set.  
🧩 Systems bite: **Job Scheduler**  
- Master assigns tasks, workers execute.  
💻 Project: **Kelly Criterion Simulator**  
- Python: bankroll growth curve.  
- TS: slider adjusts bet fraction.

### Week 11 – Capstone Build
**LeetCode Design Problems:** Twitter, Underground, Logger limiter.  
🧩 Systems bite: **Architecture Tradeoffs**  
- Document caching/scaling/fault-tolerance.  
💻 Project Options:  
- Option A: **Real-time stock dashboard** (Next.js + WebSockets).  
- Option B: **Distributed backtester** (Ray/Dask + TS frontend).

### Week 12 – Mock Interviews + Polish
**Optional Review Problems:** Serialize/deserialize tree, consistent hashing (DIY).  
🧩 Systems bite: **Failover Design**  
- Sketch redundant servers + retries.  
💻 Project: **Capstone Polish**  
- Write README, diagrams, screenshots.  
- Push final project to GitHub.

---

## ✅ Outcome
By the end, you’ll have:
- Java DS&A repo (Weeks 1–4).  
- Python quant + systems repo (Weeks 5–8).  
- TypeScript full-stack project repo (Weeks 9–12).  
- A polished **capstone project** ready for GitHub portfolio.
