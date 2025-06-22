# Trading-Bot-using-Binance-Python-Library

This is a simplified trading bot built using the `python-binance` library to interact with the Binance USDT-M Futures **Testnet**. The bot allows users to place market and limit orders, handle both buy and sell sides, and provides clear logging and error tracking.

---

## 🔧 Features

- Connects to Binance Futures Testnet  
- Places **Market** and **Limit** orders  
- Supports both **Buy** and **Sell** sides  
- Validates and logs user input  
- Handles API errors gracefully  
- Logs all activity to `trading_bot.log`  
- Designed for CLI interaction and easy testing

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+  
- Binance Testnet account: [https://testnet.binancefuture.com](https://testnet.binancefuture.com)  
- API key & secret created from the Testnet (not the main Binance site)  
- `python-binance` library

---

### 📦 Install Dependencies

```bash
pip install python-binance
```

---

## ⚙️ Usage

### Step 1: Clone the Repository

```bash
git clone https://github.com/IndraKumarNeogi/Trading-Bot-using-Binance-Python-Library.git
cd Trading-Bot-using-Binance-Python-Library
```

---

### Step 2: Add API Credentials

**Option 1:** Enter when prompted via CLI  
**Option 2 (Recommended):** Use `.env` file for security

Create a `.env` file in the root folder:

```env
API_KEY=your_testnet_api_key
API_SECRET=your_testnet_api_secret
```

---

### Step 3: Run the Bot

```bash
python trading_bot.py
```

You’ll be prompted to enter:
- Symbol (e.g. BTCUSDT)  
- Order Side (BUY or SELL)  
- Order Type (MARKET or LIMIT)  
- Quantity  
- Limit price (if applicable)

---

## 📄 Log File

All API interactions, responses, and errors are saved to:

```
trading_bot.log
```

---

## 📸 Example

```plaintext
Enter symbol (e.g., BTCUSDT): BTCUSDT  
Buy or Sell? BUY  
Order type (MARKET / LIMIT): MARKET  
Quantity: 0.002

✅ Order Placed Successfully  
Order ID: 123456789  
Status: FILLED
```

---

## 🧪 Built With

- [python-binance](https://github.com/sammchardy/python-binance)  
- [Binance Futures Testnet](https://testnet.binancefuture.com)

---

## 🧑‍💻 Author

- **Indra Kumar Neogi**  
- GitHub: [github.com/IndraKumarNeogi](https://github.com/IndraKumarNeogi)  
- Email: [indra.kumar.neogi@gmail.com](mailto:indra.kumar.neogi@gmail.com)  
- LinkedIn: [linkedin.com/in/indra-kumar-neogi-bbb34a268](https://www.linkedin.com/in/indra-kumar-neogi-bbb34a268)

---

## 📄 License

This project is licensed for educational and testing purposes only.
