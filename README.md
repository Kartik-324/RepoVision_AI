# 🚀 GitHub Mermaid Diagram Generator

GitHub Mermaid Diagram Generator is an AI-powered tool that transforms any GitHub repository into **clear, interactive, and visually rich Mermaid diagrams**.  
It helps developers quickly understand complex codebases, visualize system architecture, and explore project structure without manually reading every file.

Using advanced LLMs, the tool analyzes repositories and generates accurate diagrams that can be viewed, customized, and downloaded in real time.

---

## ✨ Features

### 🎨 Supported Diagram Types

Generate multiple diagram formats from a single repository:

- **Sequence Diagrams** – Visualize request flows and interactions
- **Component Diagrams** – Understand system-level architecture
- **ER / Database Diagrams** – See tables, relationships, and schemas
- **Flowcharts** – Follow execution logic and workflows
- **Class Diagrams** – Analyze OOP structure and inheritance
- **State Diagrams** – Track application states and transitions
- **User Journey Maps** – Understand user flows
- **Gantt Charts** – Project timelines and task dependencies
- **Mindmaps** – High-level project overview

---

## 💬 Intelligent Chat Interface

- Ask **natural language questions** about any GitHub repository  
- Generate diagrams on demand from chat prompts  
- Get **visual explanations** of architecture and workflows  
- Ideal for learning, onboarding, and documentation

---

## 🎯 Smart Capabilities

- Deep and recursive GitHub repository scanning  
- Accurate diagram generation using **GPT-4o**  
- Real-time Mermaid rendering  
- Dark & Light theme support  
- Diagram history tracking  
- Export diagrams as images or Mermaid code  

---

## 📋 Prerequisites

Before running the project, ensure you have:

- Python **3.8 or higher**
- OpenAI API Key
- GitHub Personal Access Token *(optional but recommended to avoid rate limits)*

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Kartik-324/RepoVision-AI.git
cd github-mermaid-generator
2️⃣ Backend Setup
bash
Copy code
cd backend
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
Create a .env file in the backend directory:

env
Copy code
OPENAI_API_KEY=your_openai_key
GITHUB_TOKEN=your_github_token
3️⃣ Frontend Setup
bash
Copy code
cd ../frontend
pip install -r requirements.txt
4️⃣ Run the System
Backend
bash
Copy code
uvicorn main:app --reload --host 0.0.0.0 --port 8000
Frontend
bash
Copy code
streamlit run app.py
Access the application:

Frontend: http://localhost:8501

Backend API: http://localhost:8000

API Docs: http://localhost:8000/docs

📁 Project Structure
bash
Copy code
github-mermaid-generator/
│
├── backend/
│   ├── main.py            # FastAPI entry point
│   ├── models.py          # Pydantic models
│   ├── routes/            # API routes
│   ├── services/          # Repo analysis & diagram logic
│
├── frontend/
│   ├── app.py             # Streamlit main app
│   ├── components/        # UI components
│   ├── pages/             # App pages
│   ├── utils/             # Helper utilities
│
└── README.md
🎯 Usage Examples
Quick Diagram Mode
Enter a GitHub repository URL

Select the desired diagram type

Generate → View → Download

Chat Mode Examples
Ask questions like:

"Show authentication flow"

"Visualize database schema"

"Generate class hierarchy diagram"

"Explain backend architecture"

🔧 Environment Variables
env
Copy code
OPENAI_API_KEY=your_openai_key
GITHUB_TOKEN=your_github_token
🐛 Troubleshooting
Backend not starting → Check .env and dependencies

Frontend shows no data → Verify backend URL

Mermaid diagram blank → Mermaid syntax error

GitHub API limit exceeded → Add GitHub token

🤝 Contributing
Contributions are welcome 🚀

Fork the repository

Create a new branch

Commit your changes

Push and create a Pull Request

