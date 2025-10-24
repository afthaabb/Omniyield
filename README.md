# Avail Nexus Hackathon Ideas

Use the Avail Nexus SDK to act on unified liquidity across chains using `bridgeAndExecute`.
Move funds, execute smart contracts, and interact across chains — all in one transaction.

---

## 1. One-Click Yield Optimizer (DeFi)

**Problem:**
Moving USDC from Ethereum to Base for better yield takes multiple steps and gas fees.

**Solution:**
A dashboard showing unified USDC deposits and top APYs across chains.
Click **"Move to Highest APY"** → uses `bridgeAndExecute` to:
- Withdraw from Ethereum pool
- Bridge to Base
- Deposit into new pool
All in one click.

---

## 2. Universal NFT Bidder (NFTs)

**Problem:**
An NFT is on Polygon, but your ETH is on Ethereum — manual bridging loses time.

**Solution:**
An NFT aggregator with **"Buy Now with Unified ETH"**.
`bridgeAndExecute`:
- Pulls ETH from Ethereum
- Bridges to Polygon
- Executes marketplace `buyItem()`

---

## 3. Cross-Chain Gas Top-Up (Tooling)

**Problem:**
You’re stuck on Arbitrum with 0 ETH for gas but funds elsewhere.

**Solution:**
A tool **"Nexus Gas"** with inputs: target chain + token to use.
`bridgeAndExecute`:
- Takes USDC from Polygon
- Bridges to Arbitrum
- Swaps for ETH and sends to your address

---

## 4. Multichain Game Store (Gaming)

**Problem:**
User wants to buy an NFT item on Base using funds on TRON.

**Solution:**
A game store with **"Buy Now"** using `bridgeAndExecute`:
- Takes USDT from TRON
- Bridges/swaps to USDC on Base
- Calls `mintItem("Legendary Sword")`

---

These projects highlight what makes **Avail Nexus** powerful — not viewing balances, but **acting across chains seamlessly.**
