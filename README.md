# 🧠 Your Medical Report Companion

An AI-powered assistant that reads your medical PDF reports, summarizes them in simple language, and offers personalized health advice using Generative AI (LLMs + RAG).

## 🚀 Usage Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/your-medical-report-companion.git
cd your-medical-report-companion
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Set Your OpenAI API Key
Create a `.env` file in the root directory:
```
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```

### 4. Run the App
```bash
uvicorn app:app --reload
```

Open your browser at: [http://127.0.0.1:8000](http://127.0.0.1:8000)
