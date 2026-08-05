# 🤖 AI Research Agent

An AI-powered **Multi-Agent Research System** that automates web research, analyzes information, and generates structured research reports using collaborative AI agents.

Built with **Python**, **CrewAI**, **Mistral AI**, **Streamlit**, and **Serper API**, this project demonstrates how multiple AI agents can work together to perform research tasks efficiently.

---

## 🚀 Features

- Multi-Agent AI Architecture
- Automated Web Research
- Intelligent Information Analysis
- AI-Generated Research Reports
- Real-Time Web Search Integration
- Interactive Streamlit Interface
- Modular & Scalable Design
- Secure API Key Management

---

## 🏗️ How It Works

```
User Query
     │
     ▼
Research Agent
     │
     ▼
Analysis Agent
     │
     ▼
Content Writer Agent
     │
     ▼
Structured Research Report
```

### AI Agents

### 🔍 Research Specialist
- Searches the web for relevant information
- Collects reliable sources
- Gathers research data

### 📊 Data Analyst
- Processes collected information
- Identifies key insights
- Removes irrelevant data

### ✍️ Content Writer
- Organizes research findings
- Generates structured reports
- Produces clear and readable content

---

## 📁 Project Structure

```
ai-research-agent/
├── agents/
│   ├── research_specialist.py
│   ├── data_analyst.py
│   └── content_writer.py
├── tasks/
│   ├── research_task.py
│   ├── analysis_task.py
│   └── writing_task.py
├── crew.py
├── app.py
├── requirements.txt
├── .env.example
└── README.md
```

---

## 🛠️ Tech Stack

- Python
- CrewAI
- Mistral AI
- Streamlit
- Serper API
- Large Language Models (LLMs)
- Prompt Engineering

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/ai-research-agent.git
cd ai-research-agent
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

**Windows**

```bash
.venv\Scripts\activate
```

**macOS/Linux**

```bash
source .venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
pip install litellm
```

### 4. Configure API Keys

Create a `.env` file and add:

```env
MISTRAL_API_KEY=your_api_key
SERPER_API_KEY=your_api_key
```

### 5. Run the Application

```bash
streamlit run app.py
```

The application will start at:

```
http://localhost:8501
```

---

## 💡 Example Research Queries

- Latest breakthroughs in fusion energy
- How is AI transforming drug discovery?
- Future of Generative AI in healthcare
- Applications of Quantum Computing
- Impact of Artificial Intelligence on Cybersecurity

---

## 📌 Use Cases

- Academic Research
- Business Intelligence
- Market Research
- Competitive Analysis
- Technology Research
- Content Research

---

## ⚠️ Common Issues

### Invalid API Key
Verify that your API keys are correctly added to the `.env` file.

### Slow Response
Research tasks may take 30–60 seconds depending on the complexity of the query.

### CrewAI Telemetry Warning

Add the following to your `.env` file if required:

```env
CREWAI_TELEMETRY_OPT_OUT=true
```

---

## 🔮 Future Improvements

- PDF Report Export
- Citation Generation
- Multi-LLM Support
- Research History
- Cloud Deployment
- Vector Database Integration (RAG)

---

## 👨‍💻 Author

**Lakshay**

If you found this project useful, consider giving it a ⭐ on GitHub.
