# KIAM_Week_10

# 📊 Brent Oil Price Insights - Flask App

This Flask web application analyzes **Brent crude oil prices (2015-2025)** and provides **investment, policy, and operational insights** based on key global events.

## 🚀 Features
✅ **Visualizes Brent oil price trends**  
✅ **Marks key global events impacting oil prices**  
✅ **Provides API-based investment & policy insights**  
✅ **Simple web interface for easy access**  

---

## 📦 Installation

1️⃣ **Clone the repository**  
```bash
git clone https://github.com/your-repo/brent-oil-flask.git
cd brent-oil-flask
```

2️⃣ **Install dependencies**  
```bash
pip install flask pandas matplotlib
```

3️⃣ **Run the Flask app**  
```bash
python app.py
```

4️⃣ **Open in browser:**  
```
http://127.0.0.1:5000/
```

---

## 📊 API Endpoints

| Endpoint      | Method | Description |
|--------------|--------|-------------|
| `/`          | GET    | Displays oil price trends with event markers |
| `/api/insights` | GET  | Returns investment & policy recommendations in JSON |

Example API response:
```json
{
    "Investment Strategy": "Buy on major price dips caused by geopolitical crises.",
    "Policy Recommendation": "Diversify energy sources to reduce oil price dependency.",
    "Operational Planning": "Increase fuel reserves during low-price periods to mitigate risks."
}
```

---

## 🔍 Key Events Impacting Oil Prices

| Date       | Event |
|------------|-----------------------------|
| 2015-01-01 | OPEC Oversupply Crash |
| 2016-02-11 | Oil Price Bottoms at $27 |
| 2018-10-03 | Iran Sanctions Peak ($86) |
| 2020-04-20 | COVID-19 Oil Price Collapse |
| 2022-02-24 | Russia-Ukraine War |
| 2023-10-07 | Israel-Gaza Conflict |

---

## 🛠 Future Enhancements
- 📈 **Interactive price charts (Plotly/Dash)**
- 📊 **Real-time oil price updates**
- 🚀 **Deployment to AWS/GCP**

---

## 📜 License
This project is licensed under the **MIT License**.

---

### 🚀 Need Help?
Feel free to reach out! PRs and contributions are welcome. 😊
