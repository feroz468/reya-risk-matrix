# 🐙 Reya Risk Matrix

A lightweight, open-source risk analytics matrix and read-only wallet position inspector for **Reya Network** (L2 Chain ID 1729). Powered by Reya's public v2 L2 REST node endpoints.

🚀 **Live App**: [https://feroz468.github.io/reya-risk-matrix/](https://feroz468.github.io/reya-risk-matrix/)

---

## ✨ Key Features

- 📊 **Perpetual Market Intelligence**: Live mark prices, funding rates, and max leverage limits across 34 active perpetual markets.
- 🧮 **Interactive Margin Simulator**: Calculate notional values, initial margin requirements, and estimated liquidation thresholds without connecting a wallet.
- 🔍 **Read-Only Wallet Audit**: Inspect open positions, average entry prices, and accrued funding for any public Ethereum address.
- ⚡ **Resilient Fallback Routing**: Integrated client-side CORS proxy fallbacks to ensure uninterrupted data streaming across browser environments.

---

## 🛠️ Architecture & Tech Stack

- **Frontend**: HTML5, Tailwind CSS (Custom Reya dark aesthetic & glassmorphism)
- **APIs**: Reya v2 REST API (`api.reya.xyz/v2`)
- **Deployment**: GitHub Pages

---

## ⚠️ Risk Disclaimer

Liquidations on Reya Network are triggered based on mark prices and may occur as partial liquidations according to protocol margin requirements. Calculations provided by this tool are approximate estimates intended for educational and simulation purposes only.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.