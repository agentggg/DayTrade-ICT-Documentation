---
layout: default
title: Chapter 3 — Liquidity Zones
permalink: /ICT-Book/chapter3/
---

# Institutional Liquidity Zones

## What is Institutional Liquidity Zones
### What are Liquidity Zones
    - Areas on a chart where most of the stop orders are resting, and Smart Money tries to sweep this liquidity zone. 
### What are Stop Orders
    - **Stop Orders:** Consist of two well known ICT terms. *Buy stops and sell stops*
        - Buy stops: This is usually placed above swing highs.
            - It references retail traders that short the market and this is also known as either of the following names:
                - buy-side liquidity 
                - run-buy stops 
                - buy to sell
                - buy stops
        - Sell stops: This is usually placed below swings lows
            - It references retail traders that went in long into the market and this is also known as either of the following names:
                - sell-side liquidity 
                - run-sell stops 
                - sell to buy
                - sell stops
        - Having a buy stop right above a swing high is very common
        - Having a sell stop right below a swing low is very common
        - When a stop order is hit, smart money does not win money from your loss. Funds from your account is not transfered over to their account, however, smart money indeed WINS big by taking out liquidity 
        - When a buy-side liquidity is swept the broker must send a market sell order into the market to sell the order that you just lost, because you closed, so now they are FORCED to sell your order into the back into market, as holding the order for long will not benefit them, as it is money that they owe
        - When sell-orders are forced unto the market, you can get it at a cheaper entry cost as a discount before price moves higher. Liquidity sweep usually happens before the BIG move. It allows smart money to fill as much order as possible, as the big moves requires massive volume (vice-versa).
### Sweeping Liquidity
    - Sweeps are not the move, sweep sets the move-up 
    - If they buy without sweeping liquidity then price jumps to the next avail purchase number. It causes an imbalance and price must return BACK so they balance their numbers.
### Sweeps and FVG's
    - An imbalance in price is what causes an FVG
    - FVG is proof of bad price and limited order available as the orderbooks cannot meet the demands. 
        - **ORDERBOOKS:** 
            - ICT orderbook orders already placed + liquidity behavior + inefficiency + future stop orders that will activate.
                *visible + invisible
            - Retail orderbook = just the limit orders that are sitting and waiting for price.
                *visible*
                ```
                SELL LIMITS:
                8010 — 1200 contracts
                8009 — 900 contracts
                8008 — 300 contracts
                8007 — 100 contracts
                --------------------
                Current Price: 8006
                --------------------
                BUY LIMITS:
                8005 — 500 contracts
                8004 — 900 contracts
                8003 — 2000 contracts
                8002 — 1500 contracts
                ```
    - FVG is not a good thing for institutions. So that’s why price must return to FVG because it’s an imbalance. 
        *However, it also is NOT a mistake on the institution part, its just that the order books couldn't meet orders as quick as it came in.*
    - Smart money cannot buy $100M of contracts at ONE price, if $100M worth of contract is not available at the $8000 price in the order books, then price must keep jumping to where order can be filled. 
        1. 8005 might have 20m
        2. 8012 might have another 20m
        3. etc. etc. etc. so price must continue to jump till the order is filled
        - A move like this without liquidity will move the market massively
            - Smart money will pay WAY worse prices than intended
        - If smart money buy $15M and price jumps, but they planned $100M:
            - They’re not in their full position
            - Now they must buy at higher, worse prices
                - They may want to buy:
                    - $50M today
                    - $50M tomorrow
                    - $75M next week
    - FVG is an inefficiency in the orderbooks due to POOR institutional fills. 
        *Institutional orders are made by 1 or 100's of organization pushing orders at the same time.*
    - Because smart money bought almost NOTHING in the skipped area. So when price returns to an FVG smart money finally get to purchase the orders that they didn’t get a chance to buy and now they get to grab liquidity and then slowly accumulate towards their BIG move. 
        *It gives them the chance to rebalance their books.*            
        - FVG’s are not good for Smart Money. 
            *The 3 candles forming is a visual representation of the inbalance.*
        - The retrace back to the FVG rebalances the books slowly for multiple reason. 
            1. It gives smart money time to build liquidity on both side that they can eventually sweep
### Resting Orders
    - When price moves to fast and skip the resting order:
        - Resting order is ordered placed on the market that is waiting for price to meet in order to be executed. It is resting because it is sitting in the orderbooks.
            - ICT refers to resting order as orders that are already in the market and is tangable, not orders that hasnt't entered the market yet
            - The market only cares about resting orders, because these are guranteed and reachable, me as a retail trader who's playing it at a play-by-play does not matter to retail as they cannot predict it 
            - Smart money relies on resting order and stop orders: resting orders for accumulation and stop orders for big moves and for extra liquidity when needed. These both are liquidity
### Buy and Sell Limit Order and Market Orders      
    - **Buy limit orders:** traders that waiting for price to go lower to enter the market, as it is currently at a premimum 
    - Sell limit orders: traders that waiting for price to go higher to enter the market, as it is currently at a discount
    - Market order: execute now, at the current price
        - Smart Money knows where resting orders are, but retail cannot. It's an access thing, also Institutions literally wrote the books that retail studies.
            - So smart money knows:
                - where stops are
                - where resting orders are
                - where imbalance is
                - where orderflow shifts
                - where FVGs formed
                - where inefficiencies exist
                    - 4000 contracts selling at 4020
                    - 1200 contracts buying at 3970
### ICT Terminology Table

| **Term**              | **Meaning (ICT Definition)**                                        |
|-----------------------|----------------------------------------------------------------------|
| **Orderbook**         | The full institutional liquidity landscape (resting orders, stops, inefficiencies, algorithmic targets). Not the retail DOM. |
| **Resting Orders**    | Institutional limit orders already in the book, waiting to be filled. |
| **FVG / Inefficiency**| A gap created when price moves too fast and *skips liquidity*; an imbalance that must be rebalanced. |
| **Liquidity**         | Combined pool of retail stop orders *and* institutional limit orders that Smart Money uses to fill positions. |
| **Displacement**      | Aggressive algorithmic move where price consumes liquidity and creates imbalance (FVG). |
| **Rebalancing**       | Price returning to inefficiencies (FVG) to fill unfilled orders and restore fair value. |
| **Stop Hunt**         | When price purposely runs retail stop-losses, turning them into *market orders* that Smart Money uses as liquidity. |
| **Orderflow Shift**   | Algorithmic change in directional bias, usually confirmed by MSS (Market Structure Shift). |
### Enhanced ICT Definitions

#### 📘 **Orderbook**
The *institutional* orderbook: total liquidity landscape including  
resting limit orders, inefficiencies, stop clusters, and algorithmic delivery targets.

#### 📥 **Resting Orders**
Unfilled *limit orders* already sitting in the book.  
These are the true “resting liquidity” Smart Money uses.

#### ⚡ **FVG (Fair Value Gap) / Inefficiency**
A gap formed when price displaces too fast and skips levels where orders should have been matched.  
Represents *unfinished business* that price later returns to rebalance.

#### 💧 **Liquidity**
All available orders the algorithm uses, including:  
- Retail stop-loss clusters  
- Institutional limit orders  
- Implied liquidity zones  

#### 🚀 **Displacement**
A strong directional move that consumes liquidity aggressively and creates FVGs.  
This shows *intention* of Smart Money.

#### 🔄 **Rebalancing**
Price returning to fill inefficiencies (FVGs) and complete unfilled institutional orders.

#### 🎯 **Stop Hunt**
When the algorithm targets retail stop orders, converting retail SLs into *market orders* for Smart Money to absorb.

#### 🔀 **Orderflow Shift**
A structural change in the algorithm, often confirmed by MSS:  
old direction loses control → new direction takes over.