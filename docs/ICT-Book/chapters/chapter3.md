---
layout: default
title: Chapter 3 — Liquidity Zones
permalink: /ICT-Book/chapter3/
---

# 📘 Chapter 3 — Institutional Liquidity Zones
Institutional Liquidity Zones are engineered price areas where Smart Money seeks liquidity, fills large positions, and begins significant directional moves. Understanding these zones is essential for interpreting price delivery in the ICT framework.

---
## What Are Liquidity Zones
Liquidity means convertible to cash, if an assest is easily convertable to cash it is known marked as high - However, in trading, liquidity means availability of willing of buyers and sellers at market price
Liquidity Zones are areas on the chart where **large clusters of stop orders** rest.  
Smart Money targets these zones to unlock liquidity and accumulate positions efficiently.

Retail consistently places stop orders in predictable places:

- Above swing highs  
- Below swing lows  
- At equal highs/lows  
- At trendlines  
- At “support” and “resistance”  

These zones become **buy-side** or **sell-side** liquidity pools.

---
## What Are Stop Orders
Stop orders consist of two ICT-recognized forms of liquidity:
### 🟦 **Buy Stops (Buy-Side Liquidity, BSL)**
Placed *above swing highs*, typically by traders shorting the market.

Names you’ll hear:
- Buy-side liquidity  
- Run buy stops  
- Buy to sell  
- Buy stop pool  
  - ![alt text](images/image-18.png)

### 🟥 **Sell Stops (Sell-Side Liquidity, SSL)**
Placed *below swing lows*, typically by traders going long.

Names you’ll hear:
- Sell-side liquidity  
- Run sell stops  
- Sell to buy  
- Sell stop pool  
  - ![alt text](image-1.png)
### 🧠 Key Notes
- Smart Money **does NOT take your money** when your stop-loss hits.  
- When your stop is triggered, your broker must convert it into a **forced market order**.  
- Those forced orders are used by institutions to fill their own positions.  
- Liquidity sweeps almost always occur **before** the real move begins.

---
## Sweeping Liquidity
Sweeps are **not** the actual move — they **set up** the move.
  - ![alt text](images/image-25.png)
### Why sweeps occur:
- They unlock forced market orders (extra liquidity)  
- They allow institutions to accumulate positions at discount/premium  
- They create displacement  
- They produce inefficiencies (FVGs)  
- They prevent price from jumping too far too fast  

If Smart Money buys *before* sweeping liquidity, price:

- Jumps to the next available sell limit  
- Creates a large imbalance  
- Forms an FVG  
- Must return later to rebalance  

---
## Sweeps And Fair Value Gaps
### What Causes an FVG?

FVGs form when price moves so aggressively that it **skips resting orders** in the orderbook.

Example:
#### Why did this happen?
- Not enough resting **sell limit orders**  
- Buying pressure overwhelmed available liquidity  
- Only partial institutional orders were filled  

This creates a **displacement candle** and the **Fair Value Gap**.

---
#### 🟩 Why FVGs Matter to Smart Money

- FVGs are NOT “mistakes.”  
- They represent **poor fills** and **skipped liquidity**.  
- Price must return to rebalance and complete institutional fills.

#### Why can't institutions buy $100M at one price?

Because the orderbook might look like:

- 8000 → only $2M available  
- 8005 → $20M  
- 8012 → $20M  
- 8020 → $30M  

Price must jump until enough liquidity is found.  
This creates displacement and FVGs.

Institutions then return to:

- Complete unfilled buy/sell orders  
- Rebalance pricing  
- Build positions  
- Prepare the large directional move  

---

## Orderbooks (ICT vs Retail)

### 📘 ICT Orderbook (Advanced)
Includes:

- Resting limit orders (visible)
- Hidden/iceberg liquidity  
- Stop-loss clusters (future market orders)
- Algorithmic delivery targets  
- Inefficiencies (FVGs)  
- Rebalancing zones  
- External/internal liquidity  
- Implied liquidity  

This is the *true liquidity environment* algorithms use.

### 🧾 Retail Orderbook (Shallow View)
Only shows **visible limit orders**:
```
SELL LIMITS:
8010 — 1200 contracts
8009 — 900 contracts
8008 — 300 contracts
8017 — 100 contracts

Current Price: 8006

BUY LIMITS:
8005 — 500 contracts
8004 — 900 contracts
8003 — 2000 contracts
8002 — 1500 contracts
```
Retail sees only a tiny fraction of actual liquidity.

---


## Resting Orders

A **resting order** is a LIMIT ORDER already present in the market.

- **Buy limit** → below price (want cheaper entry)  
- **Sell limit** → above price (want higher entry)  
- **Market orders** → execute immediately (not resting)  

#### ICT Key Points:
- Only *resting orders* matter to the algorithm.
- Future retail orders (your next click) do not exist yet → irrelevant.  
- Institutions rely on:
  - Resting orders → accumulation  
  - Stop orders → forced liquidity  

Both are liquidity sources.

---
## Order Types Summary

#### 🔵 Buy Limit  
Buy at discount.

#### 🔴 Sell Limit  
Sell at premium.

#### ⚫ Market Order  
Takes liquidity immediately.

#### ✔ Institutions Know:
- Where resting orders are  
- Where imbalance exists  
- Where FVGs formed  
- Where inefficiencies are  
- Where orderflow shifts  
- Where algorithmic targets lie  

Retail does NOT see this.

---

## ICT Terminology Table

| **Term**              | **Meaning (ICT Definition)**                                        |
|-----------------------|----------------------------------------------------------------------|
| **Orderbook**         | The full institutional liquidity landscape (resting orders, stops, inefficiencies, algorithmic targets). Not the retail DOM. |
| **Resting Orders**    | Institutional limit orders already in the book, waiting to be filled. |
| **FVG / Inefficiency**| A gap created when price skips liquidity during fast displacement. Must be rebalanced. |
| **Liquidity**         | Combined pool of retail stop orders *and* institutional limit orders. |
| **Displacement**      | Aggressive algorithmic move consuming liquidity and creating FVGs. |
| **Rebalancing**       | Price returning to inefficiencies (FVGs) to complete institutional orders. |
| **Stop Hunt**         | When price deliberately targets retail stops, converting them into market orders for institutional entry. |
| **Orderflow Shift**   | Algorithmic change in directional bias, often confirmed by MSS. |

---

## Enhanced ICT Definitions

#### 📘 **Orderbook**
The institutional liquidity map containing visible, hidden, and implied liquidity zones, used by the algorithm to deliver price.

#### 📥 **Resting Orders**
Limit orders already active in the market.  
These are the “guaranteed” liquidity levels Smart Money can use.

#### ⚡ **Fair Value Gap (FVG)**
A displacement-driven gap where price skipped liquidity.  
Represents unfinished business and must be rebalanced.

#### 💧 **Liquidity**
The total pool of orders:
- Retail stops  
- Institutional limits  
- Hidden liquidity  
- Implied liquidity  

#### 🚀 **Displacement**
A strong algorithmic move that removes opposing liquidity and creates an imbalance.

#### 🔄 **Rebalancing**
Price revisiting inefficiencies to restore balance and fill unfilled institutional orders.

#### 🎯 **Stop Hunt**
Engineered pushes into stop clusters to generate forced market orders for institutional entries.

#### 🔀 **Orderflow Shift**
A structural transition where the algorithm moves from one direction of delivery to another.

---

This chapter is now fully structured, formatted, and ready for your ICT Book.


## ICT Liquidity Zones
### High and Low Resistance Liquidities
  - An old high having many swing highs defending it and the old low having many swing lows defending it, is known as a High and Low Resistance Liquidities. 
  - A **High Resistance Liquidity Run** occurs when the price struggles to sweep out liquidity and takes a long time to reach an old high or swing low. This happens because liquidity is defended by multiple resistance levels.
  - *Low Resistance Liquidity* are the multiple short term swing highs and lows forming between an old high and low 
    - *With HRLR, it will be difficult for a MSS to take place, because price would have to take out a collection of old highs and old lows before finally causing a MSS, so it is encouraged to avoid going opposite direciton of the market, and remain in the current trend of the market*
      - ![alt text](images/image-19.png)
        -  *for price to reverse and trend down, it would have to sweep multiple liquidity and then take out the swing low. That is very uncommon, and not recommended to trade in this manner, opposite of the currect market structure, especailly if the HTF is not aligned*
    - *Low Liqudity Resistance Run - LRLR* Is the same exact concept, however, opposite of the HRLR (High Resistance Liquidity Run)
      - ![alt text](images/image-20.png)
### Internal and External Range Liquidities
  #### ICT Dealing Range
    - Anything between an established swing high (*which has taken the liquidity of an old high), and an established swing low (which has taken the liquidity of an old low)
      - ![alt text](images/image-21.png)
  #### Internal Range Liquidity
    - Price within the range of the established swings (ICT Dealing Range), are known as *internal range liquidity*, but only the **FVG** is marked as the ICT Internal Range Liqudity
  #### External Range Liquidity
    - The swing high and the swing low of the dealing range is known as the *External Range Liquidity*
      - The high is known as buy-side liquidity
      - The low is known as the sell-side liquidity
        - ![alt text](images/image-22.png)
### Liquidity Pool
  - Retail traders usually buy/sell above/below old highs/lows. 
  - Retail traders would buy above an old high or put a stop loss there, smart money would leverage that. Don't think like a retail trader, think like smart money.
    - ![alt text](images/image-23.png)
### Liquidity Void
  - When prices moves aggressively after a consilidation in a direction, with a LONG and strong FVG. Only smart money has the power to do that, 
    - *Liquidity Voids are inefficiencies that must eventually be repriced*
    - There was no liquidity available
    - Price will usually return to rebalnce
      - ![alt text](images/image-24.png)
### Liquidity Run
  -  When price targets a liquidity sweep, and instead of reversing, price continues in the direction of the sweep, with momemtum
    - ![alt text](images/image-26.png)