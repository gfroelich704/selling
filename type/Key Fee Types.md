
### Key Fee Types:
1. **Trading Fees**:  
   Minimum calculation based on the above formula or a percentage of the option premium.  
2. **Exercise Fees**:  
   Only applied to exercised options, with day options exempt.  
3. **Forced Liquidation Fees**:  
   Determined by the user’s tier level.  
4. **Liquidation Penalty**:  
   Based on the MMR (Maintenance Margin Ratio).  
5. **Options Combo Discounts**:  
   Options combos traded via RFQ (Request for Quote) receive up to **50% fee discounts**.

---

## Trading Fee Examples

### Example 1: BTCUSD Options
- **Multiplier**: 0.01  
- **Contract Size**: 1 BTC  
- **Option Premium**: 0.05 BTC  

#### Trader A:
- **Maker Fee**: 0.02%  
- **Taker Fee**: 0.03%  

1. **As a taker**:  
   `Trading Fee = Min(0.03% × 0.01 × 1 × 100, 12.5% × 0.05 × 0.01 × 1 × 100) = 0.0003 BTC`  
2. **As a maker**:  
   `Trading Fee = Min(0.02% × 0.01 × 1 × 100, 12.5% × 0.05 × 0.01 × 1 × 100) = 0.0002 BTC`

---

## Options Combo Fee Examples

| **Combo Trades**                         | **Fees**                                      |
|------------------------------------------|-----------------------------------------------|
| Buy 3 BTC call, sell 2 BTC put           | Fees charged only on the **buy 3 BTC call** leg. |
| Buy 3 BTC call, sell 2 ETH put           | Fees charged on both legs and total gross notional. |
| Buy BTC options + BTC perpetual hedge    | Fees charged only for the options.            |

---

## Fee Tier for Main and Sub-Accounts

The **fee tier** of a user’s main account applies to all sub-accounts and is determined daily at **4:00 PM UTC**. Key considerations include:
1. **30-day Trading Volume**:  
   Based on the BTC equivalent of all trades, converted to TRY.  
2. **Asset Balance**:  
   Daily snapshots at 4:00 PM UTC, converted to TRY.

---

## 24-Hour Crypto Withdrawal Limits

Your withdrawal limit is updated daily at **4:00 PM UTC** and depends on your identity verification level and tier. All assets are converted to USD, and their total value must not exceed the allowed limit.

### Example:
- **Limit**: 300 USD  
- Withdrawals:  
  - 250 USDT  
  - 25 USD (OMG)  
  - 15 USD (XRP)  

**Remaining Limit**: 10 USD  

If you exceed this limit, contact OKX support to request a temporary increase.

---

## Makers and Takers

- **Maker Orders**: Placed into the order book and wait to be matched.  
- **Taker Orders**: Filled immediately at the market price.  

### Example:
- Current BTC price = 1,000 USDT.  
- Maker places a bid at 999 USDT (maker fee applied).  
- Taker matches the order at 1,000 USDT (taker fee applied).

---

## Spot Trading Fee Example

**Trading Pair**: USDT/TRY  
- Maker Fee: 0.04%  
- Taker Fee: 0.10%  

1. **As a Taker**:  
   `Fee = 0.1% × 1 USDT = 0.001 USDT`  

2. **As a Maker**:  
   `Fee = 0.04% × 10 TRY = 0.004 TRY`

---

## Important Updates and Notes

- **Fee Updates**:  
  Updated daily between 8:00 - 10:00 PM UTC.  
- **Region-Specific Fees**:  
  Trading fees may vary by region. Check the latest fees [here](https://bit.ly/OKXe).

---

💡 **Maximize Your Savings!**  
Use the OKX invitation code **8265080** during registration or click the link below to unlock exclusive fee discounts and bonuses:  

👉 Click to view ☞ [OKX Welcome Limited-Time Offer, Claim Up to 100 USDT Reward](https://bit.ly/OKXe)
