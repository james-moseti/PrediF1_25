# 🏎️ F1 Predictions 2025

Predict Formula 1 race outcomes for the 2025 season using machine learning and FastF1 data.

## 🚀 Overview
Gradient Boosting model trained on:
- FastF1 API data
- 2024 race results
- 2025 qualifying results

## 📊 Data Sources
- FastF1 API (lap times, telemetry, results)
- 2025 qualifying sessions
- Historical race data

## 🏎️ How It Works
1. Collect & preprocess data
2. Engineer features
3. Train model on 2024 results
4. Predict 2025 race times & rank drivers

## 🔧 Usage
```bash
python3 prediction1.py
```
Example output:
```
🏁 Predicted 2025 Australian GP Winner 🏁
Driver: Lando Norris, Predicted Race Time: 81.78s
...
🔍 Model Error (MAE): 3.22 seconds
```

## 📈 Model
- Algorithm: Gradient Boosting Regressor
- Metric: Mean Absolute Error (MAE)

## 📌 Future Plans
- Add weather & pit stop strategy
- Explore deep learning

## 📜 License
MIT License

