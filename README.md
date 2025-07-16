# Finance_Advisor_AI


# 🦁 LionVest AI – Intelligent Investment Recommendation System

LionVest AI is a Streamlit-powered AI dashboard that analyzes Indian stock market data, compares stock performance, summarizes company news, and recommends top stocks based on both technical and fundamental indicators — using Google Gemini AI.



## 🚀 Features

- 📈 Compare stock performance over a 3-month period using Yahoo Finance data.
- 🧠 Get AI-generated insights from multiple intelligent agents:
  - `Market Analyst`: Evaluates stock trends and ranks them by performance.
  - `Company Researcher`: Provides business overview, sector details, and summarizes latest news.
  - `Stock Strategist`: Suggests top-performing stocks for investment.
  - `Team Lead`: Aggregates all analysis into a final investment recommendation report.
- 📊 Interactive Plotly charts for visualizing stock trends.
- 📰 Integrates company-specific news and insights from Yahoo Finance.
- 🦁 Beautiful Streamlit interface with a seagreen theme and lion-themed branding.



## 🏗️ Technologies Used

- `Python 3.10+`
- `Streamlit` – UI Framework
- `yfinance` – Stock data from Yahoo Finance
- `plotly` – For rich data visualizations
- `Google Gemini API` – Powering multi-agent reasoning (via Agno)
- `dotenv` – For secure API key handling



## 🔧 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Pathaan/Finance_Advisor_AI.git
   cd Finance_Advisor_AI
````

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Create a `.env` file**:

   ```
   GOOGLE_API_KEY=your_google_gemini_api_key_here
   ```

4. **Run the app:**

   ```bash
   streamlit run app.py
   ```



## 💡 Example Input

In the sidebar, enter NSE stock symbols like:

```
HDFCBANK.NS, ICICIBANK.NS, SBIN.NS, AXISBANK.NS
```


## 📉 Sample Output

* A complete investment report with AI insights on:

  * Stock performance trends
  * Sector and market cap analysis
  * Latest company-specific news
  * Ranked recommendations for top stock picks


## 🛡️ Security

Make sure your `.env` file is listed in `.gitignore` and never pushed to GitHub. This file contains your private API keys.

## 📬 Contact

Built with ❤️ by [Pathaan](https://github.com/Pathaan)

If you use this project or like the idea, please ⭐️ the repo!

---

## 📄 License

MIT License – Use it freely, with attribution.

```

---

Would you like me to:
- Generate a matching `.gitignore`
- Export this as a `README.md` file you can download
- Add badges (Streamlit, Python version, License, etc.)

Let me know!
```
Here is an updated, **professional and visually descriptive `README.md`** file for your project **LionVest AI**, based on your UI screenshots and the features implemented:

---

## 🦁 LionVest AI

> **Intelligent Indian Stock Market Advisor** powered by Google Gemini, Plotly, yFinance, and Streamlit.

![LionVest Hero](https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg)

---

### 🧠 Overview

**LionVest AI** is an advanced AI-powered stock market analytics dashboard that helps investors make informed decisions by analyzing **Indian stock market data**. It leverages Google Gemini via the Agno framework to evaluate performance trends, provide personalized stock insights, and deliver **investment-ready recommendations** — all in a clean, dark-themed Streamlit UI with interactive visualizations.

---

### 📸 Screenshots



<<img width="1600" height="803" alt="image" src="https://github.com/user-attachments/assets/2e60ae9f-b0f3-47c0-82f9-57830aa8cca4" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/45536378-aa02-4f0b-9ca0-13ce982d56bf" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bf1a71fc-b849-4c17-bc87-4989c0e4c631" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bfd677a3-bcb1-4057-b605-f5e95bda0acf" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c448194c-1dd0-4aa9-8478-c826c04bcebe" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/5caeb8ad-a5fa-4de8-bd7d-83a4fdc7be27" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/054eb09d-ee03-40d7-9094-550f10d783e1" />

---

### ✨ Features

* 🔍 **Compare NSE stocks** over custom date ranges
* 📊 **Visualize performance** over 3–6 months using Plotly
* 📰 **Summarize latest news** and company fundamentals via Yahoo Finance
* 🦾 AI-Powered Agents:

  * **Market Analyst**: Ranks stocks by performance, volatility, and trend
  * **Company Researcher**: Analyzes sector, business model, market cap, news, and risks
  * **Stock Strategist**: Recommends stocks for various risk appetites
  * **Team Lead**: Aggregates insights into an investor-friendly report
* 🧾 Final report includes:

  * Ranked buy/hold/avoid suggestions
  * Rationales with supporting data
  * Risk factors and current news headlines
* 🎨 Beautiful seagreen-themed interface with dark mode and lion branding

---

### ⚙️ Technologies Used

| Stack    | Tools/Libs             |
| -------- | ---------------------- |
| Language | Python 3.10+           |
| UI       | Streamlit              |
| Data     | yfinance, pandas       |
| AI       | Google Gemini via Agno |
| Charts   | Plotly                 |
| Others   | dotenv, datetime, PIL  |

---

### 🚀 Installation

1. **Clone this repo**

   ```bash
   git clone https://github.com/Pathaan/Finance_Advisor_AI.git
   cd Finance_Advisor_AI
   ```

2. **Create and activate a virtual environment** *(optional but recommended)*

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\\Scripts\\activate on Windows
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up `.env` file**
   Create a `.env` file:

   ```env
   GOOGLE_API_KEY=your_gemini_api_key
   ```

5. **Run the app**

   ```bash
   streamlit run app.py
   ```

---

### 🧪 Example Input

```
HDFCBANK.NS, ICICIBANK.NS, SBIN.NS, AXISBANK.NS
```

Choose your custom start and end dates from the sidebar.

---

### 📈 Sample Output

* Ranked recommendation (Buy / Avoid / Hold)
* AI-generated rationale
* Fundamentals & news breakdown
* Performance graph with custom date range
* Company-specific risk flags

---

### 🔐 Security Note

Ensure your `.env` file is included in `.gitignore`:

```
.env
```

If you pushed `.env` to GitHub by mistake, rotate your API keys immediately and remove it from Git history.

---

### 📌 To Do

* [ ] Add sentiment-based color cues to recommendations
* [ ] Enable export of reports as PDF
* [ ] Add auto-refresh on stock data
* [ ] Add support for US and crypto stocks

---

### 📄 License

MIT License. Free to use, modify, and build upon — attribution appreciated.

---

### 📬 Contact

Built with ❤️ by **[Pathaan](https://github.com/Pathaan)**
📧 Email: [you@example.com](mailto:you@example.com)

---

Would you like me to:

* Upload this as `README.md` to your repo?
* Embed your local screenshots into GitHub-compatible links?

Let me know, I can auto-generate it or prep it for publishing.
