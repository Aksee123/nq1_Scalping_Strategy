
# ⚡️ Enhanced NQ1 Scalping Strategy (v6)

This strategy is tailored for high-speed NQ1 scalping using real-time volume distribution, point-of-control logic, candle confirmation, and filter overlays. Built in Pine Script v6, it adapts dynamically using EMA trends, ATR thresholds, and session-level validations — giving traders scalpel-sharp signals during volatile price action.

---

## 🧠 Highlights

- 🔎 **Volume Profile Engine**: Calculates custom swing zones and auto-identifies support/resistance levels based on low-volume rejections.
- 🧮 **POC Detection**: Visualizes point of control with optional label and dynamic extension.
- 🎯 **TP/SL Framework**:
  - Fixed points or dynamic swing logic
  - Optional 1:1 reward-risk ratio
  - Visual dotted lines + labels per signal
- 📊 **Trade Filters**:
  - Candle color validation
  - Two EMA trend detection
  - ATR volatility gating
  - Session/time-based constraints

---

## 🛠 Parameters

| Feature                | Description                                    |
|------------------------|------------------------------------------------|
| `Invert Signal`        | Reverses logic for contrarian setups          |
| `Strict Entry`         | Requires extra price distance from break zone |
| `EMA Filter`           | Confirms trend before entry                   |
| `ATR Filter`           | Suppresses trades in low-vol environments     |
| `Volume Filter`        | Confirms breakout with aggressive volume      |
| `Take Profit / SL`     | Set in points; fully customizable             |

---

## 📈 Deployment & Backtesting

1. Paste into TradingView Pine Editor.
2. Configure based on asset/session preferences.
3. Toggle visualization tools (POC, resistance/support bands).
4. Launch strategy tester with historical validation.
5. Fine-tune performance via indicator overlay and alert messages.

---

## 🔔 Alerts

Integrated with formatted alerts via:
```pine
{"ticker": "TICKER", "action": "buy/sell", "price": PRICE}
Use these for webhook integrations or automated trading pipelines.

🧑‍💻 Author
Built by Rao Aksee Nasir — software engineer, global mobility strategist, and expert in AI-powered trading systems.

📝 License
Open source under the MIT License. Attribution appreciated for derivatives and forks.

💬 Feedback
Feature requests, bug fixes, and improvement ideas are welcome! Submit an issue or pull request via GitHub.

---

When you're ready, I can help you format a performance dashboard in the README to show backtest stats, maybe even a link to a GitHub Pages portfolio. Want to keep leveling up this repo or create a showcase layout next?


