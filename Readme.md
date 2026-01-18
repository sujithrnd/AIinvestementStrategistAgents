# ⚖️ AI Stock Market Analysis & Trading Agent 

## 🚀 Overview
**AI-powered Agentic Stock Market Analysis** System designed to enable data-driven **investment decisions** through intelligent, **autonomous financial agents**.
The platform combines real-time market data, financial indicators, and news sentiment with LLM-driven reasoning to deliver explainable and actionable stock insights.

🔹 Analyze and compare multiple stocks in parallel using specialized AI agents
🔹 Leverage LLMs for explainable market insights, predictions, and investment rationale
🔹 Integrate real-time stock prices, financial metrics, and market news for holistic evaluation
🔹 Built using Agentic AI design patterns and the AGNO framework for scalability and modularity 

---
**User Flow**
<img width="1217" height="558" alt="legal_flow" src="https://github.com/user-attachments/assets/019953d6-3b7b-4e8b-b8a6-0f9798c4c169" />

**User Interface**
<img width="1907" height="936" alt="invest2" src="https://github.com/user-attachments/assets/4c47d687-e024-4989-b9a5-b3dae81a0cc9" />
<img width="1918" height="980" alt="invest1" src="https://github.com/user-attachments/assets/6aa3792b-7ece-4742-a415-3f3d46dc2663" />


## 🛠️ Installation Guide

### **1️⃣ Clone the Repository**

```bash
git clone https://github.com/your-repo/legal-ai-agents.git
cd legal-ai-agents

pip install -r requirements.txt

uv venv fitness --python 3.12

streamlit run investment.py

# remove all instaalrtion
pip freeze > to_remove.txt && pip uninstall -r to_remove.txt -y


####install uv
# Open Windows Power Shell and Run the below command
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"

# Using winget
winget install --id=astral-sh.uv  -e

# Using scoop
scoop install main/uv


