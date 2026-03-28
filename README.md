# 📊 Trader Behavior vs Market Sentiment Analysis

## 👩‍💻 Author
Payal Tamboli

---

## 📌 Project Overview
This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance using historical trading data from Hyperliquid.

The goal is to identify patterns in trading activity and generate actionable insights that can help improve trading strategies under different market conditions.

---

## 📂 Dataset

Due to file size limitations, datasets are not included directly in this repository.

You can download them from the links below:

- 📥 Fear & Greed Index Dataset:  
  https://drive.google.com/file/d/1PgQC0tO8XN-wqkNyghWc_-mnrYv_nhSf/view?usp=sharing  

- 📥 Historical Trader Data (Hyperliquid):  
  https://drive.google.com/file/d/1IAfLZwu6rJzyWKgBToqwSmmVYU6VbjVs/view?usp=sharing  

After downloading, place both files inside the `data/` folder before running the notebook.

---

## ⚙️ Methodology
- Data cleaning and preprocessing  
- Standardizing column names and handling missing values  
- Merging datasets on a daily level  
- Feature engineering (PnL, win rate, trade frequency, position size)  
- Behavioral segmentation of traders  

---

## 📊 Analysis & Visualizations
The notebook includes:
- PnL distribution across Fear vs Greed  
- Win rate comparison  
- Trade frequency analysis  
- Position size trends  
- Behavioral segmentation insights  

*(Run the notebook to view all visualizations)*

---

## 📈 Key Insights
- Trader performance (PnL & win rate) is lower during Fear periods  
- Trading activity and position sizes increase during periods of Greed  
- Frequent traders exhibit more stable performance across sentiment conditions  
- Market sentiment strongly influences trading behavior and outcomes  

---

## 💡 Strategy Recommendations
- Reduce leverage and exposure during Fear periods  
- Avoid overtrading and cap risk during Greed  
- Prefer systematic, rule-based trading strategies  
- Use sentiment as an input for dynamic risk adjustment  

---
## 📁 Project Structure
├── data/
├── notebooks/
│ └── analysis.ipynb
├── outputs/
├── README.md


---
📦 Requirements
Python 3.x
pandas
numpy
matplotlib
seaborn

📌 Conclusion

Market sentiment plays a significant role in shaping trader behavior and performance. Fear leads to cautious but often less profitable trading, while Greed encourages aggressive strategies with higher volatility.

Incorporating sentiment-aware strategies can help traders improve consistency, manage risk effectively, and make more informed decisions.

## ▶️ How to Run

### 1. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
notebooks/analysis.ipynb

