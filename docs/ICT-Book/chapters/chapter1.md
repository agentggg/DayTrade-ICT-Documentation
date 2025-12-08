---
layout: default
title: Chapter 1
permalink: /ICT-Book/chapter1/
---
# Chapter 1 - Introduction
## What is ICT Trading
- Inner Circle Trading Strategy was Developed by *Micheal J. Huddleston*, commonly known as the Inner Circle Trader
- His strategy is based off of the relationship between **time** and **price** 

### Interbank Price Delivery Algorithm *(IPA)*
- Micheal believes that price is controlled and delivered by an **<u>algorithm</u>**
- The algo is designed to target liquidity, and balancing price that is imbalance. 
    - *hence why ICT is teachings is base off of liqudity*
- Modern Markets are ran by multiple algorithms, not just one master algo. However, all the big players leverages algo to enter and exit the market. There is no need for human-interaction and emotional involvement.
    - The algo are programmed with rules
        - These rules include:
            - Filling liquidity
            - Grabbing highs/lows
            - Returning to imbalances
            - Mitigating blocks
            - Maintaining fair value
        - These rules produce:
            - FVGs
            - Liquidity sweeps
            - Breakers
            - Order Blocks
            - BPR (Balanced Price Range)
            - Judas swings
            - Repricing
    - All firms share one principle:
        1. Remove liquidity
        2. Rebalance
        3. Deliver price efficiently
    - *ICT entire concept is based off of understanding the algo, and how the algo fills orders*
    - Few common reasons why the *IPA* works:
        1. Liquidity Grab Must Happen Before a Move:
            - algos push prices down to grab sell stops, vice-versa
            - retails sells and institutions buy cheap
            - institutions then pump price back up, and repeat
                - algo knows where liquidity rest because of the following:
                    - Just above equal highs
                    - Just below equal lows
                    - Below swing lows
                    - Above swing highs
                    - Below trendlines
                    - Above fair value gaps
                    - At moving averages
                    - At indicator signals
                - Institutions have:
                    - 40 years of retail behavior data
                    - Models that predict stop clusters
                    - Order flow heatmaps
                    - Large flow data
                    - Market microstructure models
        2. 8:30a to 10a move
            - 8:30a
                - News happen Major news releases (CPI, NFP, PPI, GDP)
            - 9:30a 
                - NYSE open (reversal or continuation)
            - 10a
                - Manipulation + setup confirmation
        3. Why high/lows are swept before major move, known as the **<u>Judas Swing</u>**
            - Those orders at the high/low are easily access for instant liquidity
                - This is why you always see: *Sweep → Displacement → FVG → Return → Continuation*
        4. Buy and sell orders did not match properly:
            - Every buy order must be matched with a sell order. 
                - If there is no sell order avail the market must jump to the next level for a sell
                    1. At 18,000 NAS100 → all sellers are filled
                    2. At 18,001 → all sellers are filled
                    3. At 18,002 → no sellers exist
                        - This leaves an inbalance/void, and price must fill in the gaps
                            - You can use the Volume Range Volume Profile for dynamic volume range, to see where there was a gap in the orders, esp with FVG's
        5. Price always returns to FVG because of why/how FVG's are formed
            - FVG's are formed because of inbalances
                - FVG's act as support in resistance, until price revists and fill the orders
                - FVG's are formed because orders did not match: 
                    - Not enough buy orders per sale orders, vice-versa
                        - Every buy order must match a sale, vice-versa. So if there is not an available sell at the buy order request, it must go to the next avail sell order.
                            - So if I buy at 1801 but there is no sale till 1810, then there will be a HUGE displacement becaues the next avail order is at 1810
                            - Displacement is the middle candle of the FVG
                - Liqudidty was skipped:
                    - No trades happened inside that price range
                    - Price jumped over because no resting orders were avail
                    - The algo needs to come back afterwards to fill that inbalance
                        - NAS100 moves from 1800 to 1810 in one candle
                    - If there was no trade within a timeframe, or if the volume is low, price will most likely revist this time, because the market needs to rebalance
        6. The stop losses are 90% predicatable for retail traders
            - Just above equal highs
            - Just below equal lows
            - Below swing lows
            - Above swing highs
            - Below trendlines
            - Above fair value gaps
            - At moving averages
            - At indicator signals