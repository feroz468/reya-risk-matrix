# Reya Risk & Market Analytics Matrix

An open-source, lightweight analytics tool and position risk simulator designed for traders on **Reya Network L2**.

## 📌 Purpose
The Reya Risk Matrix provides immediate transparency into active perpetual markets, funding rate fees, and position leverage health without requiring users to connect a Web3 wallet or sign private key authorizations.

## ✨ Key Features
- **Live Market Data:** Queries real-time mark prices, funding rates, and max leverage specs from Reya's public v2 REST API (`api.reya.xyz/v2/`).
- **Interactive Risk Simulator:** Calculates notional position sizes and estimated liquidation thresholds based on user-defined margin deposits.
- **Read-Only Wallet Audit:** Inspects open positions for any public EVM wallet address on Reya L2 without wallet permissions.
- **Zero-Cost Architecture:** Pure HTML5, Tailwind CSS, and standard JavaScript with zero external backend dependencies.

## 🚀 Quick Start (Local Run)
1. Clone this repository:
   ```bash
   git clone [https://github.com/feroz468/reya-risk-matrix.git](https://github.com/feroz468/reya-risk-matrix.git)