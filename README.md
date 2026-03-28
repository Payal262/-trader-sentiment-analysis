# 📊 Trader Behavior vs Market Sentiment Analysis

## 👩‍💻 Author
Payal Tamboli

## 📌 Objective
Analyze how Bitcoin market sentiment (Fear/Greed) impacts trader behavior and performance using Hyperliquid trading data.

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

## 📈 Key Insights
- Trader performance (PnL & win rate) is lower during Fear periods  
- Trading activity and position sizes increase during Greed  
- Frequent traders exhibit more stable performance across sentiment conditions  
- Market sentiment strongly influences trading decisions and outcomes  

---

## 💡 Strategy Recommendations
- Reduce leverage and exposure during Fear periods  
- Avoid overtrading and cap risk during Greed  
- Prefer systematic, rule-based trading strategies  
- Use sentiment as a signal for risk adjustment  

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook
