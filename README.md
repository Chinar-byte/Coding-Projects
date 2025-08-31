# 12-Week Integrated Roadmap: Real-Time Trading Simulator & Dashboard

**Languages:** Java → Python → TypeScript/React  
**Weekly time commitment:** ~4 hours (2 DS&A, 1 system bite, 1 project/capstone work)  

**Capstone:** Full-stack Real-Time Trading Simulator with Market Simulation, Risk Checks, Backtesting, and Dashboard

---

## Phase 1 – Core Mechanics & Data Structures (Weeks 1–4, Java)

### Week 1
- **DS&A (LeetCode):** Binary Search, Search in Rotated Sorted Array, Kth Largest  
- **Systems Bite 🧩:** In-memory cache (track account balances & positions)  
- **Capstone Feature 💻:** Basic simulation engine: “Coin-flip” trades, track balance, simple random orders  

### Week 2
- **DS&A (LeetCode):** Stack, Queue, LRU Cache, Linked List  
- **Systems Bite 🧩:** URL Shortener → map orders to trade IDs  
- **Capstone Feature 💻:** Build **limit order book** using heaps: addOrder(), matchOrders()  

### Week 3
- **DS&A (LeetCode):** Coin Change, Longest Increasing Subsequence, Knapsack  
- **Systems Bite 🧩:** Token Bucket → rate-limit trades  
- **Capstone Feature 💻:** Pre-trade **risk checks**: max order size, margin limits; reject invalid orders  

### Week 4
- **DS&A (LeetCode):** Graphs: Number of Islands, Clone Graph, Course Schedule  
- **Systems Bite 🧩:** Leaderboard → track top traders by PnL  
- **Capstone Feature 💻:** Monte Carlo **market simulation**: random walk prices, simulate order execution against market  

---

## Phase 2 – Concurrency & Analytics (Weeks 5–8, Python)

### Week 5
- **DS&A (LeetCode):** Bitwise ops: Power of Two, Sqrt, Single Number  
- **Systems Bite 🧩:** Pub/Sub → subscribers receive events  
- **Capstone Feature 💻:** Event system: traders subscribe to price feed updates and order confirmations  

### Week 6
- **DS&A (LeetCode):** Circular Queue, Sliding Window, Hit Counter  
- **Systems Bite 🧩:** Async Chat System → multiple clients  
- **Capstone Feature 💻:** Real-time trade logging, broadcast messages, measure latency  

### Week 7
- **DS&A (LeetCode):** Median Finder, Top-K, Task Scheduler  
- **Systems Bite 🧩:** Trading Engine → auto-match trades  
- **Capstone Feature 💻:** Extend order book: auto-execute trades, track volume & bid-ask spread analytics  

### Week 8
- **DS&A (LeetCode):** Intervals: Meeting Rooms, Gas Station, Insert Interval  
- **Systems Bite 🧩:** Pre-Trade Risk Check → block large trades  
- **Capstone Feature 💻:** Portfolio analytics: Markowitz optimization with risk constraints, dynamic position checks  

---

## Phase 3 – Full-Stack & Dashboard (Weeks 9–12, TypeScript/React)

### Week 9
- **DS&A (LeetCode):** Two Sum, Valid Anagram, String Compression  
- **Systems Bite 🧩:** Scaling Backtests → sharding by ticker, worker pool  
- **Capstone Feature 💻:** Backtesting module: pairs trading backtest, trade logs, PnL charts  

### Week 10
- **DS&A (LeetCode):** Random Pick, Shuffle, Randomized Set  
- **Systems Bite 🧩:** Job Scheduler → master assigns tasks to workers  
- **Capstone Feature 💻:** Real-time **dashboard**: live order book, price charts, trader leaderboard  

### Week 11
- **DS&A (LeetCode):** Design Twitter, Underground, Logger Rate Limiter  
- **Systems Bite 🧩:** Architecture Tradeoffs → caching, fault-tolerance  
- **Capstone Feature 💻:** Integrate **backend (Java/Python) with frontend (React/TS)** via WebSockets; full system end-to-end  

### Week 12
- **DS&A (LeetCode):** Serialize/Deserialize Tree, Consistent Hashing  
- **Systems Bite 🧩:** Failover Design → redundant servers, retries  
- **Capstone Feature 💻:** Polish & deploy: README, diagrams, screenshots, unit tests, GitHub portfolio-ready project  

---

## Key Features Integrated
- **DS&A practice:** 36+ LeetCode problems covering arrays, heaps, graphs, dynamic programming, concurrency, and system design-related algorithms.  
- **Systems design practice:** 12 “mini” exercises building up understanding of caching, rate-limiting, pub/sub, leaderboards, scaling, and fault-tolerance.  
- **Portfolio project:** One cohesive system that grows weekly:
  - Java engine → Python real-time & analytics → TypeScript frontend  
  - Features: limit order book, market simulation, risk checks, auto-trading, backtesting, dashboard  
  - Ready for GitHub with documentation, diagrams, and screenshots.  

---

## How to Execute
1. **Weekly structure (~4 hours/week):**  
   - 2 hrs LeetCode problems (focus on speed and problem patterns)  
   - 1 hr systems bite (write notes, draw diagrams, or prototype small module)  
   - 1 hr capstone feature integration (extend the main project)  
2. **Cumulative development:** Each week’s project work builds on prior weeks → by Week 12, a fully functional, deployable trading simulator.  
3. **Portfolio readiness:** Weekly commits to GitHub with meaningful messages; final polish in Week 12.
