# Workshop: Machine Learning-Based Trading Strategy

This project showcases a simple trading strategy using machine learning model outputs for an asset's future price movement. We use historical data and model predictions to generate buy/sell signals and simulate trading performance.

**Overview:**
- **Task:** Decide to buy or sell the asset 24 hours before for a certain price, and hope to make a profit 24 hours later.
- **Predictions:** Model outputs are the probability (between 0 and 1) that price will go up:
    - If probability < 0.45: **Sell** (`-1`)
    - If probability > 0.55: **Buy** (`1`)
    - Otherwise: **No trade** (`0`)
- **Goal:** Use data to find profitable patterns and test the strategy.

---

## What to Try

- Try with different models (`model_pred_1`, ..., `model_pred_6`)
- Discover if combining models or adjusting thresholds improves results!
- Share patterns or ideas you find with the group.

---

*Happy trading! 🚀*

