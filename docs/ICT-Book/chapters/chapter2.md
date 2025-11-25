---
layout: default
title: Chapter 2 — PD Array
permalink: /ICT-Book/chapter2/
---

# Chapter 2 - PD-Array
PD-Array stands for *Premium Discount Arrangement*

## What is PD-Array
[See this section for more on **<u>Premium and Discount</u>**](/docs/Development-Lesson-2.md#premium-and-discount)

## Different type of PD-Arrays
- ### Order Blocks
    - **Bullish Order Block:** occurs when a *bullish* candle body (not wick) engulfs a *bearish* candle before a displacement (FVG).
    ![alt text](/docs/ICT-Book/images/image.png)
        - * displacement is the confirmation, but the entry point would be a retracel back to the order block. A single displacement candle can be retail FOMO. FVG is institution intentionally pushing price  *
    - **Bearish Order Block:** occurs when a *bearish* candle body (not wick) engulfs a *bullish* candle before a displacement (FVG).
        - ![alt text](/docs/ICT-Book/images/image-1.png)
        - *displacement is the confirmation, but the entry point would be a retracel back to the order block*
        - The order block process is predisposed with the sweep of liquidity. After institutions has swept liquidity, then the reversal is being staged. The start of the reversal is usually an OB, followed by a displacement (FVG). From there you can expect price to retrace back to the OB, as anywhere there is an FVG, a retracal is emminent as there is an inbalance and orders that needs to be filled. 
            - You can validate this with the volumes-range indicator
        - Once price retraces and price is balanced, then go for a long, if it is a bearish order block, vice-versa
- ### Breaker Blocks 
    - Breaker Block: *is a failed order block that happens after liquidity sweep or market structure shift*
    - A **BB** forms after an **OB** is formed. Once an **OB** is formed, price should never revisit that level again within that session. However, if price revisit that level again, then it is a **BB**
        - If price revisits the **OB** again then it violates the **OB** and is an intentional move by SM
            - It lured traders
            - It created liquidity
            - It got invalidated
            - It flipped into a breaker zone
    - You enter at the direction the **BB** was created
- ### Inverse FVG
    - Inverse FVG is when a displacement happens, and when the FVG fails to hold the price, and price revisits the FVG
    - ![alt text](/docs/ICT-Book/images/image-3.png)
- ### Implied FVG
    - Happens when price moves so fast that it skipped levels, but did it all within one candle, it's an invisible area
        - *if you were to take that single displacement candle, and split it in half, you could see an FVG being formed*
    - A typically FVG consist of 3 candles:
        1. impulse candle
        2. inefficiency candle
        3. continuation candle
            *in an inverse fair value gap, it is all one single candle. The chart won't show the inefficiency, but exists inside of that candle
    - Large candles by default are **NEVER** efficient, even when no FVG is present
        - Displacement candle is the middle candle of the FVG
    - In a regular FVG you would get candle A, B, and C, with C being the displacement candle, leaving a gap/inefficiency behind
    - IFVG happens because algo push prices so fast
    - How to mark it
        - Bullish IFVG zone = from open of displacement candle → to its 50% midpoint
        - Bullish IFVG zone = open → midpoint (in bearish direction)
    - Place the FIB at the wicks that overlap, and the 50% mark is the IFVG
    - ![alt text](/docs/ICT-Book/images/image-2.png)
    - ![alt text](/docs/ICT-Book/images/image-4.png)
    - ![alt text](/docs/ICT-Book/images/image-5.png)
- ### Balanced Price Range-BPR
    - This is the same as inversion FVG.
    - IFVG is the method and Balanced Price Range is the result.
        - The price is balanced
        - This also happens when the opposite side of the FVG that is violated is the same wick, and body size, everything the same
    - ![alt text](/docs/ICT-Book/images/image-7.png)
    - ![alt text](/docs/ICT-Book/images/image-8.png)
- ### Rejection Block
    - Rejection block is when price sweeps a liqudity and forms a long rejection wick.
    - The section from the previous liqudity and where the wick ends is the rejection block
        - *ONLY USED IN LIQ SWEEP OF HIGHS and LOWS*
    - Runs liquidity, fills their orders, and then price attempts to breakthrough the liquidity level, however, price gets rejected aggresively and then leaves a candle that represents the algo rejecting the price
    - ![alt text](/docs/ICT-Book/images/image-9.png)
    - ![alt text](/docs/ICT-Book/images/image-10.png)
- ### Vaccume Gap
    - Vaccum Gap is when there is a huge visible gap between the close/open of one candle to another
    - It can be created because of a week, day or session opening. volatility event like FOMC, NFP or a geopolitical event like war.
        - Meaning there was no trading activiy at the time of the gap
    Price tends to revisit gap, to fill orders, and then continue in the direction of the gap
        - Imagine NQ (NASDAQ futures) is at 17,000.
        - A sudden news event hits (like NFP, CPI, FOMC)
        - Price instantly jumps to 17,120.
        - Nobody bought, sold, no trades executed, priced moved FAST, like a **VACCUME BLOCK**
    - ![alt text](/docs/ICT-Book/images/image-11.png)
    - ![alt text](/docs/ICT-Book/images/image-12.png)
- ### Mitigation Block
    - A MSS that failed to make higher highs/lower lows and SM algos needs to return to that area to mitigate those lossess before continuing the original direction
        - Smart Money was caught on the wrong side
        - They later return to that zone
        - They “mitigate” (offset) their losing orders
        - That zone becomes a support/resistance level
        - It acts like an Order Block, but with a different origin
    - This usually happens because price had an OB that failed and/or is violated. When price returns, SMC mitigates their losing positions, then SMC continues with the original MSS.
    - This usually happens right after an OB
    - It was just a way to clean up their mess and grab liq
    - Difference between **Mitigration Block** and **Breaker Block**:
        - Breaker Block grabs liquidity on it's way down, and a reversal happens
        - Mitigration Block does not grab liquidity on it's way down, price simply violated the OB, no reversal happens after it returns, it just continues
    - ![alt text](/docs/ICT-Book/images/image-13.png)
    - ![alt text](/docs/ICT-Book/images/image-14.png)
    - ![alt text](/docs/ICT-Book/images/image-15.png)
    - ![alt text](/docs/ICT-Book/images/image-16.png)
    - ![alt text](/docs/ICT-Book/images/image-17.png)