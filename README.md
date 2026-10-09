<div align="center">

# Hi, I'm Yashwanth K 👋

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=7C3AED&center=true&vCenter=true&width=700&lines=Python+Full+Stack+Developer;Generative+AI+%26+RAG+Engineer;LLM+Apps+%7C+LangChain+%7C+FAISS+%7C+Django;Turning+documents+and+data+into+intelligent+products" alt="Typing SVG" />

I build **database-driven web apps** and **AI-powered products**, from Django backends to RAG chatbots that ground LLM answers in real documents instead of guessing.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yashwanthk2004)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:yashwanthk2004k@gmail.com)
![Profile Views](https://komarev.com/ghpvc/?username=Yashwanth-12-yash&label=Profile%20Views&color=7C3AED&style=for-the-badge)

</div>

---

## 👨‍💻 About Me

| | |
|---|---|
| 🎓 **Education** | B.E. Information Science & Engineering, Ghousia College of Engineering (VTU), 2022 – 2026 |
| 💼 **Experience** | Python Full Stack Trainee @ Palle Technologies · Data Science Intern @ Palle Consulting Services |
| 🧠 **Focus** | LLMs, Retrieval-Augmented Generation, NLP, Machine Learning |
| 🌐 **Full Stack** | Django · Flask · REST APIs · MySQL · HTML/CSS/JavaScript |
| 📍 **Location** | Karnataka, India |
| 🔎 **Status** | **Open to work**: Python Full Stack, Software Engineering, AI/ML roles |

---

## 🤖 AI Engineering Focus

I work at the intersection of **backend engineering and applied AI**. My goal is not just to call an LLM API, but to build the full system around it: data ingestion, retrieval, grounding, serving, and evaluation.

```mermaid
flowchart LR
    A[📄 Documents / Data] --> B[✂️ Chunking]
    B --> C[🔢 Embeddings]
    C --> D[(FAISS Vector Store)]
    E[❓ User Query] --> F[🔍 Semantic Search]
    D --> F
    F --> G[🧩 Prompt + Retrieved Context]
    G --> H[🤖 LLM]
    H --> I[✅ Grounded Answer]
```

### What I Work With

| Layer | Tools & Techniques |
|---|---|
| **LLMs & APIs** | OpenAI GPT, Gemini Flash, prompt engineering |
| **Orchestration** | LangChain (loaders, splitters, retrievers, chains) |
| **Embeddings** | Hugging Face `all-MiniLM-L6-v2`, sentence embeddings |
| **Vector Search** | FAISS with persistent index storage, semantic search |
| **Classical ML** | Scikit-learn: supervised and unsupervised learning, feature engineering, model evaluation |
| **Deep Learning** | TensorFlow, Keras |
| **Data Science** | NumPy, Pandas, Matplotlib, EDA |
| **Serving** | Django / Flask backends, REST APIs |

---

## 📂 Featured Projects

### 🤖 TCS Chatbot: RAG-Based Generative AI Chatbot

A document-aware chatbot that answers questions **using only your uploaded files as the source of truth**, which reduces hallucination and keeps responses verifiable.

**How it works**

1. **Ingest:** PDFs are loaded with `PyPDFLoader`
2. **Chunk:** `RecursiveCharacterTextSplitter` splits text into retrieval-friendly passages
3. **Embed:** `all-MiniLM-L6-v2` (Hugging Face) converts chunks to vectors
4. **Store:** vectors are saved in a **persistent FAISS index** (no re-embedding on every restart)
5. **Retrieve:** the user's question is embedded and matched against the index by semantic similarity
6. **Generate:** OpenAI GPT answers using the retrieved passages as context

**Stack:** `Python` `LangChain` `OpenAI GPT` `RAG` `Hugging Face` `FAISS`

---

### 🛒 NexTrade: AI-Powered E-Commerce Platform

A full-stack e-commerce platform with separate **customer** and **admin** modules and an **AI product recommendation** feature.

```mermaid
flowchart TB
    U[👤 Customer] --> UI[Responsive UI: HTML · CSS · JS]
    AD[🛠️ Admin] --> UI
    UI --> DJ[Django Backend]
    DJ --> DB[(SQL Database)]
    DJ --> REC[🤖 AI Recommendation Engine]
    DB --> REC
    REC --> DJ
```

- **Customer module:** browsing, cart, wishlist, orders, saved addresses
- **Admin module:** product and inventory management, order handling
- **Backend:** Django models and SQL integration for users, products, inventory, addresses, and orders
- **AI layer:** product recommendations surfaced directly in the storefront

**Stack:** `Python` `Django` `SQL` `HTML` `CSS` `JavaScript`

---

### 🩺 Diabetes Prediction Using Machine Learning

A supervised classification pipeline that predicts diabetes from patient health data, built to compare algorithms rather than assume one.

| Step | What I did |
|---|---|
| **EDA** | Explored distributions, correlations, and data quality with Pandas and Matplotlib |
| **Feature engineering** | Prepared and transformed features for training |
| **Modeling** | Logistic Regression · K-Nearest Neighbors · Naive Bayes · Random Forest |
| **Evaluation** | Compared models side by side to select the best performer |

**Stack:** `Python` `Pandas` `NumPy` `Scikit-learn` `Matplotlib`

> 🔗 **Repo links:** replace this line with `[View Code](https://github.com/Yashwanth-12-yash/<repo-name>)` for each project.

---

## 💼 Experience

### Python Full Stack Trainee: Palle Technologies, Bengaluru
*Dec 2025 – Jun 2026*
- Built full-stack web applications with Python, Django, SQL, HTML, CSS, and JavaScript
- Connected backend logic and database-driven features to user-facing interfaces
- Strengthened application architecture, database design, and debugging through hands-on projects

### Data Science Intern: Palle Consulting Services Pvt. Ltd., Bengaluru
*2026*
- Preprocessed datasets and ran exploratory analysis with Python, NumPy, Pandas, and Matplotlib
- Applied supervised and unsupervised ML to real-world datasets for predictive analysis
- Built end-to-end ML workflows: feature engineering, training, model comparison, and result interpretation

---

## 🛠️ Tech Stack

**Languages & Backend**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-02569B?style=flat-square&logo=fastapi&logoColor=white)

**Frontend**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Database**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Generative AI & LLMs**
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white)

**Machine Learning & Data Science**
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)

**Tools**
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![PyCharm](https://img.shields.io/badge/PyCharm-000000?style=flat-square&logo=pycharm&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## 🧭 How I Build AI Features

1. **Start from the data problem**: what does the model need to know, and where does it live?
2. **Ground before you generate**: retrieval first, so answers trace back to a source
3. **Compare, don't assume**: benchmark several approaches before committing (as in my diabetes project)
4. **Persist and reuse**: cache embeddings and indexes so apps start fast and cost less
5. **Wrap it in a real product**: AI behind clean APIs and usable interfaces, not just notebooks

---

## 🌱 Currently Exploring

- 🔭 More advanced RAG: better chunking, re-ranking, and answer evaluation
- 🧠 Deep learning with TensorFlow and Keras
- ⚙️ Production-ready Django REST APIs for serving ML and LLM features
- ☁️ Deploying AI apps end to end

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=Yashwanth-12-yash&show_icons=true&theme=radical&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats"/>
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Yashwanth-12-yash&layout=donut-vertical&theme=radical&hide_border=true&langs_count=6" alt="Top languages"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Yashwanth-12-yash&theme=radical&hide_border=true" alt="GitHub streak"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Yashwanth-12-yash&theme=react-dark&hide_border=true&area=true&custom_title=Contribution%20Activity" alt="Contribution graph"/>

<img src="https://github-profile-trophy.vercel.app/?username=Yashwanth-12-yash&theme=radical&no-frame=true&no-bg=true&row=1&column=7&margin-w=8" alt="GitHub trophies"/>

</div>

---

## 📫 Let's Connect

Interested in **Python, Django, GenAI, or RAG systems**? Let's talk.

📧 **yashwanthk2004k@gmail.com** · 💼 [LinkedIn](https://linkedin.com/in/yashwanthk2004) · 🐙 [GitHub](https://github.com/Yashwanth-12-yash)

<p align="center">⭐ If you like my work, drop a star on my repos!</p>
