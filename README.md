# 🧠 GEN AI Interview Coach

An interactive AI-based **Interview Practice App** built using **Transformers**, **Sentence Transformers**, and **Gradio**.  
It helps users **practice interview answers** by generating:
- A **summary** of their response
- A **relevance score** comparing the answer with the actual question

---

## 🚀 Features
- Domain-based question selection (HR, Tech, Product)
- Automatic summarization using `t5-small`
- Semantic similarity scoring using `SentenceTransformer (all-MiniLM-L6-v2)`
- Simple, interactive Gradio UI

---

## 💻 Run Locally

### 1️⃣ Clone this repo
```bash
git clone https://github.com/your-username/interview-coach.git
cd interview-coach


pip install -r requirements.txt
'
python app.py

