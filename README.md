# Stock Price Prediction API 🚀

I just built my first **stock price prediction mini project**, and the best part?  
👉 The data shows up instantly—no waiting around for a spinny circular buffer of doom. 💥

---

## What's Cooking

- **Backend:** FastAPI with real-time stock data using `yfinance`  
- **Database:** None! Data comes straight from Yahoo Finance 🤑  
- **Deployment:** API deployed on [Render](https://stock-price-model.onrender.com)  
- **Frontend:** You can hook this API up to anything—Flutter, React, or even Postman  

---

## Lessons Learned

- Real-time stock APIs are fun… until the market crashes 😅  
- Predicting stock prices is easy to try, but hard to make perfect 🧠  
- FastAPI + yfinance = instant gratification for developers  
- Mini projects can teach mega lessons  

---

## Live API

👉 Check it out here: [https://stock-price-model.onrender.com](https://stock-price-model.onrender.com)  

**Endpoints you can try:**

1. **Home:**  
`GET /` → Welcome message  

2. **Predict stock price:**  
`GET /predict/?stock=AAPL` → Returns current price, historical data, and predicted price  
