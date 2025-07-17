
# 🦁 LionVest AI – Intelligent Investment Recommendation System

# [Demo](https://github.com/Pathaan/Finance_Advisor_AI/blob/main/Demo.mp4)

LionVest AI is a next-generation investment analytics platform that leverages the power of Google Gemini and Streamlit to deliver intelligent, data-driven insights for the Indian stock market. Designed for investors and analysts alike, it seamlessly integrates real-time stock performance, fundamental metrics, and market sentiment to generate informed and personalised investment recommendations.

By combining advanced AI agents through the Agno framework with a sleek, interactive UI, LionVest AI transforms complex financial data into actionable strategies—enabling users to make confident, research-backed decisions in a dynamic market environment.

# Agno + Gemini Agents in the Financial Domain: Redefining Intelligent Finance
In today’s fast-evolving financial ecosystem, where data complexity, market volatility, and decision speed converge, the integration of intelligent agent-based systems is revolutionising the way institutions approach analysis, forecasting, and investment strategy. Two key innovations leading this transformation are Agno, a multi-agent orchestration framework, and Gemini, Google’s advanced large language model (LLM). When combined, they enable powerful, specialized AI agents tailored to meet the unique challenges of the finance domain.

# What is Agno?
Agno is a modular, developer-friendly framework for creating, orchestrating, and managing multi-agent AI systems. Unlike traditional monolithic models, Agno allows you to build task-specific agents that can reason, collaborate, and use tools to solve complex problems. Agents in Agno are modular — each one with a defined role (like a researcher, summarizer, analyst, or strategist), and can communicate with other agents or external tools like APIs, databases, or LLMs.

 In the finance domain, Agno facilitates workflows that require structured reasoning, data interpretation, and multi-step decision-making — such as portfolio optimization, risk assessment, credit analysis, or investment research. It acts as the orchestration layer where each agent contributes to a holistic financial analysis pipeline.

# What is Gemini?
Gemini is Google’s multimodal, next-generation LLM that excels in understanding and generating text, analyzing structured and unstructured data, and performing high-level reasoning. With support for tool usage and API calls, Gemini is ideal for building intelligent agents that not only understand financial queries but can also generate insights, summarize news, interpret charts, and adapt to real-time data feeds.

When paired with Agno, Gemini acts as the reasoning engine behind each financial agent — enabling natural language understanding, data summarization, and communication across agents.

## Real-World Use Case in Finance
Imagine a financial application powered by Gemini + Agno agents analyzing the Indian stock market:

## Market Analyst Agent
Uses Gemini to evaluate stock price movements, calculate returns, detect volatility, and rank companies based on recent performance.

## Company Researcher Agent
Retrieves business summaries, news headlines, sector performance, and financial ratios, then uses Gemini to summarize them for investors.

## Stock Strategist Agent
Compares risk-reward profiles, evaluates macroeconomic trends, and recommends buy/hold/avoid actions tailored to different investor types.

## Team Lead Agent
Aggregates insights from all other agents to create a final investment report — complete with justifications, rankings, and visual analysis.

This multi-agent architecture ensures modular intelligence, allowing independent validation, scalability, and high interpretability — critical for compliance-heavy and data-sensitive industries like finance.


# Agentic AI 
Agentic AI refers to a class of artificial intelligence systems designed to operate as autonomous agents capable of making decisions, pursuing goals, and interacting proactively with their environment and users. Unlike traditional AI models that passively respond to prompts, Agentic AI exhibits initiative, planning, reasoning, and adaptability—mimicking human-like agency in both thought and action.

At the heart of Agentic AI lies the concept of agency—the capacity to act independently in pursuit of objectives. These systems can break down high-level goals into subtasks, reason about them, execute actions, evaluate outcomes, and adjust their strategies accordingly. This makes them particularly valuable in complex, dynamic environments where predefined instructions are insufficient.

Key Components of Agentic AI
Goal-Oriented Behavior: Agentic AIs are driven by defined objectives. For instance, if tasked with researching a topic, an agent might autonomously search the web, extract relevant information, summarize findings, and report results—without constant human intervention.

Planning and Reasoning: These systems use cognitive architectures or AI planning algorithms (like PDDL-based planners or neural-symbolic hybrids) to devise step-by-step plans to achieve their goals. They can adapt plans based on new data or failed attempts, much like how humans revise strategies.

Memory and Context Awareness: Agentic AI can utilize short-term and long-term memory to maintain context over time. This allows agents to remember user preferences, past decisions, or ongoing tasks, making interactions more coherent and productive.

Autonomy and Decision-Making: Such systems can make choices based on preferences, ethical constraints, or learned behavior. For example, an AI personal assistant may choose the best flight for a user based on past travel habits and current schedule.

Tool Use and Environment Interaction: Agentic AI agents often leverage external tools such as APIs, web browsers, or file systems. Frameworks like LangChain, OpenAI’s Function Calling, or Auto-GPT are examples where agents use modular tools to perform complex workflows like data analysis or task automation.

Applications
Agentic AI has wide-ranging applications:

Productivity Agents: Automating workflows (e.g., summarizing emails, scheduling meetings, preparing reports).

Customer Service: Handling dynamic conversations with memory and goal-driven follow-up actions.

Research and Knowledge Work: Assisting in literature reviews, legal analysis, or data exploration.

Robotics and Autonomous Systems: Guiding physical agents like drones or self-driving cars to perform complex missions.

Challenges and Ethical Considerations
While promising, Agentic AI raises several challenges:

Reliability: Ensuring consistent performance across tasks and edge cases.

Alignment: Aligning agent goals with human values to prevent unintended behaviors.

Transparency: Understanding the reasoning and decision-making of autonomous agents.

Security: Preventing misuse or unintended consequences when agents have access to tools or sensitive information.


# Benefits in the Financial Sector
📊 Enhanced decision quality with AI-driven analytics

⏱️ Faster time-to-insight from raw market data

🔍 Contextual intelligence that understands financial jargon

🧩 Composable agents that can adapt to new financial products or markets

🔐 Explainability in AI-generated financial recommendations

## 🚀 Features

- 📈 Compare stock performance over 3 months using Yahoo Finance data.
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







<<img width="1600" height="803" alt="image" src="https://github.com/user-attachments/assets/2e60ae9f-b0f3-47c0-82f9-57830aa8cca4" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/45536378-aa02-4f0b-9ca0-13ce982d56bf" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bf1a71fc-b849-4c17-bc87-4989c0e4c631" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/bfd677a3-bcb1-4057-b605-f5e95bda0acf" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c448194c-1dd0-4aa9-8478-c826c04bcebe" />






---




### 📄 License

MIT License. Free to use, modify, and build upon — attribution appreciated.

---

### 📬 Contact

Built with ❤️ by **[Md Shahrukh](https://github.com/Pathaan)**
     
[Email](mdshahrukhbme.com)

---
