# 📈 BTC Volatility Matrix · Advanced Straddle Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Chart.js & ApexCharts](https://img.shields.io/badge/Library-ApexCharts-orange.svg)](https://apexcharts.com/)
[![Feed Status](https://img.shields.io/badge/Feed-CoinGecko%20%7C%20MT5-green.svg)](#features)

An interactive, responsive financial web dashboard designed to simulate and model **Long and Short Straddle option payoff strategies** on Bitcoin (BTC) using real-time price feeds.

---

## ✨ Features

- **⚡ Real-Time Price Feed**: Auto-refreshes Bitcoin spot prices via CoinGecko API with fallback simulation (MetaTrader 5 / biquote.io standard).
- **📊 Interactive Payoff Charting**: Built with **ApexCharts**, featuring interactive tooltips, strike price annotations, and dynamic breakeven indicators.
- **🔄 Multi-Strategy Support**:
  - **Long Straddle**: Model high-volatility scenarios with profit caps on premium paid.
  - **Short Straddle**: Model low-volatility/range-bound scenarios and time-decay profits.
- **⏱️ Live Local Time & Dynamic Status Bar**: Real-time connection statuses and user clock integration.
- **🎨 Modern UI/UX**: Clean, light-mode interface built with clean CSS variables and SVG iconography.
- **📚 Educational Hub & Legal Suite**: Detailed options academy breakdowns and risk disclosures included out-of-the-box.

---

## 🛠️ Tech Stack

- **HTML5**: Semantic structure & responsive layout.
- **CSS3**: Custom CSS variables, flexbox, CSS grid, and responsive media queries.
- **JavaScript (ES6+)**: Async/Await API fetching, dynamic calculation logic, and event handling.
- **ApexCharts**: Advanced SVG chart rendering and interactive visualization.

---

## 🚀 Quick Start & Installation

No complex build steps or Node packages required! You can test or run this repository locally in seconds.

### 1. Clone the repository
```bash
git clone [https://github.com/your-username/btc-volatility-matrix.git](https://github.com/your-username/btc-volatility-matrix.git)
cd btc-volatility-matrix

btc-volatility-matrix/
├── index.html       # Application markup, top bar, dashboard grid & footer disclosures
├── style.css        # Custom styles, responsive grid, light theme design system
├── script.js        # Straddle calculation logic, ApexCharts rendering & API integration
└── README.md        # Documentation and project overview

⚖️ Disclaimer
Market data provided by  · MetaTrader 5 feed & CoinGecko API.

Risk Warning: This application is provided solely for educational, analytical, and simulation purposes. Trading cryptocurrency options involves substantial risk of loss and is not suitable for every investor. In particular, writing unhedged options (Short Straddle) carries theoretically unlimited downside risk. Always consult a certified financial advisor before trading real capital.

📜 License
Distributed under the MIT License. See LICENSE for more information.
