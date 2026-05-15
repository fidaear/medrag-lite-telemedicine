# 🩺 MedRAG-Lite — Medical RAG & Knowledge Distillation Research

MedRAG-Lite is a research-oriented notebook project focused on building an efficient **Medical Retrieval-Augmented Generation (RAG)** system with **Knowledge Distillation**, **Hybrid Retrieval**, and **LLM optimization techniques** for telemedicine applications.

This project explores:
- Medical document retrieval
- Hybrid search (FAISS + BM25)
- Recall evaluation
- Teacher → Student model distillation
- Lightweight medical AI systems
- RAG optimization for healthcare environments

---

# 🚀 Project Objectives

The main goal of this project is to create a lightweight and efficient medical RAG pipeline capable of:

✅ Retrieving relevant medical knowledge  
✅ Reducing LLM inference cost  
✅ Improving retrieval quality  
✅ Distilling large medical models into smaller models  
✅ Benchmarking retrieval and generation performance  

---

# 🧠 Notebook Pipeline

The notebook contains a complete experimental pipeline:

## 1️⃣ Environment Setup
- GPU verification
- Dependencies installation
- HuggingFace authentication

## 2️⃣ Teacher Model Loading
- MedCPT Teacher model initialization

## 3️⃣ Dataset Preparation
- Medical dataset download
- Selection of 500 medical cases

## 4️⃣ Embedding Generation
- Encoding medical cases using the teacher model

## 5️⃣ Hybrid Retrieval System
Implementation of:
- FAISS vector search
- BM25 keyword retrieval
- Hybrid ranking strategy

## 6️⃣ Retrieval Evaluation
- Recall@3 evaluation
- Retrieval latency benchmarking

## 7️⃣ Knowledge Distillation
Distillation pipeline:
- Teacher Model → Student Model
- Soft label generation
- KD training process

## 8️⃣ Benchmarking
Comparison between:
- Distilled Student
- Original Teacher
- Speed & performance analysis

---

# 📂 Repository Structure

```bash
medrag-lite-telemedicine/
│
├── MedRAG_Lite_D8_COMPLET.ipynb   # Main research notebook
├── README.md
└── requirements.txt
```

---

# ⚙️ Technologies Used

## AI / Machine Learning
- Python
- PyTorch
- HuggingFace Transformers
- Sentence Transformers

## Retrieval Systems
- FAISS
- BM25
- Hybrid Retrieval

## Model Optimization
- Knowledge Distillation
- LoRA
- Embedding Compression

---

# 📊 Core Concepts

## 🔍 Retrieval-Augmented Generation (RAG)

The system retrieves relevant medical documents before generating responses.

### Workflow

```text
Medical Query
      ↓
Hybrid Retriever
(FAISS + BM25)
      ↓
Relevant Medical Context
      ↓
LLM Generation
      ↓
Medical Response
```

---

# 🧬 Knowledge Distillation

The project implements model distillation:

```text
Large Teacher Model
        ↓
Soft Labels Generation
        ↓
Student Training
        ↓
Smaller Faster Medical Model
```

Goal:
- Reduce inference time
- Reduce GPU requirements
- Maintain acceptable medical performance

---

# 📈 Evaluation Metrics

The notebook evaluates:

- Recall@K
- Retrieval Latency
- Inference Speed
- Student vs Teacher Performance
- Hybrid Retrieval Quality

---

# ▶️ Running the Notebook

## 1️⃣ Clone Repository

```bash
git clone https://github.com/fidaear/medrag-lite-telemedicine.git

cd medrag-lite-telemedicine
```

---

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
MedRAG_Lite_D8_COMPLET.ipynb
```

---

# 🧪 Research Topics Covered

- Medical AI
- Retrieval-Augmented Generation
- Information Retrieval
- Vector Databases
- Knowledge Distillation
- Hybrid Search
- Efficient LLMs
- Telemedicine AI Systems

---

# 📌 Experimental Features

✅ Hybrid Retrieval (Dense + Sparse)  
✅ Medical Embeddings  
✅ FAISS Indexing  
✅ BM25 Ranking  
✅ Distillation Training  
✅ Recall Benchmarking  
✅ Latency Measurement  
✅ Lightweight Medical AI Research  

---

# ⚠️ Disclaimer

This project is intended for:
- Academic research
- AI experimentation
- Educational purposes

It is NOT a certified medical system and should not replace professional healthcare advice.

---

# 👨‍💻 Author

## Fidaa Ariyan

- Data Science Student
- AI & Machine Learning Enthusiast
- RAG & LLM Researcher

GitHub: https://github.com/fidaear

---

# ⭐ Contributions

Contributions, improvements, and discussions are welcome.

Feel free to:
- Fork the repository
- Open issues
- Submit pull requests

---

# 📄 License

This project is licensed under the MIT License.
