<!-- ===================== HEADER ===================== -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=210&section=header&text=Yuvraj%20Singh%20Pundir&fontSize=42&fontColor=ffffff&fontAlignY=36&desc=Agentic%20AI%20%C2%B7%20RAG%20%C2%B7%20Backend%20Systems&descSize=18&descAlignY=58" alt="header" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=8B7CF6&center=true&vCenter=true&width=640&lines=Software+engineering+student+in+Berlin+%F0%9F%87%A9%F0%9F%87%AA;I+build+AI+agents+that+stay+grounded;Guardrails+first.+Honest+limits+always.;Currently+learning+LLM+tracing+%26+observability" alt="typing intro" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yuvraj-singh-pundir-908623351)
![Location](https://img.shields.io/badge/Berlin-Germany-1f2937?style=for-the-badge&logo=googlemaps&logoColor=white)
![Focus](https://img.shields.io/badge/Focus-Agentic%20AI-6E56CF?style=for-the-badge)

</div>

<!--
FILL IN OR DELETE before publishing (only add what you can state exactly):
- 🏭 [Your role], Tesla Gigafactory Berlin, [month year to month year]
-->

---

## 👋 About me

I build the retrieval, tool-routing and safety layers around LLMs, and I write down what each system **cannot** do as clearly as what it can.

| | |
|---|---|
| 🎓 **Studying** | B.Sc. Software Engineering, University of Europe for Applied Sciences |
| 🧠 **Fellowship** | IIT Roorkee Agentic AI Systems & Design cohort<br/>🥈 Excellence in Evaluation (Silver) · 🥇 Total Engagement (Gold) |
| 🔭 **Now** | Evaluating agents with real models, learning tracing and observability |
| 🌍 **Based in** | Berlin |

---

## 🧭 How I build

<table>
<tr>
<td align="center" width="33%">
<h3>🎯 Grounded</h3>
Answers come from retrieved documents or real database rows, not from guesses.
</td>
<td align="center" width="33%">
<h3>🛡️ Guarded</h3>
Masking, injection checks and schema-validated output sit around the model.
</td>
<td align="center" width="33%">
<h3>📝 Honest</h3>
Every README says what is synthetic, what is mocked and what is still missing.
</td>
</tr>
</table>

---

## 🚀 Featured project: Cartmind

> **An e-commerce support agent that answers from real policy documents and real order records.**

```mermaid
flowchart LR
    U([👤 Customer message]) --> C{{🧭 Classify intent<br/>+ mask PII<br/>+ check injection}}
    C -->|policy question| R[📚 RAG<br/>ChromaDB]
    C -->|order status| S[🗃️ SQL lookup<br/>SQLite]
    C -->|feedback| F[💬 Feedback]
    C -->|needs a person| H[🙋 Hand off to human]
    R --> G[✍️ Schema-validated reply]
    S --> G
    F --> G
    H --> G
    G --> O([✅ Response])
```

| 🔀 Graph | 📄 Knowledge base | 🗄️ Data | 🧪 Evaluation |
|:---:|:---:|:---:|:---:|
| **6 nodes**<br/>5 routing branches | **38** policy PDFs | **50** synthetic orders | **15** test queries |

- 🔒 Phone and card-number masking, prompt-injection detection, JSON-Schema-checked answers
- ♻️ SQLite checkpoints let an interrupted run resume
- 🔌 FastAPI backend and an MCP server
- 🔑 Runs with **no API key** (`MOCK_LLM=true`). All data is synthetic.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[**👉 View the repository**](https://github.com/YS-Pundir/cartmind-agentic-ecommerce-support)

---

## 🗂️ More projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 [Agentic-Support-System](https://github.com/YS-Pundir/Agentic-Support-System)
A support bot where one orchestrator agent delegates to a **RAG agent**, a **text-to-SQL agent**, and feedback and escalation tools. Prompts and model settings are versioned files.

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square)

</td>
<td width="50%" valign="top">

### 🏛️ [Sindhu-RAG](https://github.com/YS-Pundir/Sindhu-RAG)
A configurable RAG pipeline over a **200+ page** corpus on the Indus Valley Civilization, with config-tracked experiments, versioned prompts and a Streamlit test UI.

![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏠 [Geo-Spatial Valuation Regressor](https://github.com/YS-Pundir/geo-spatial-valuation-regressor)
Linear vs ensemble models for predicting California property values.

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</td>
<td width="50%" valign="top">

### 🩺 [Clinical Tumor Classifier](https://github.com/YS-Pundir/clinical-tumor-classifier)
Threshold tuning for malignant tumor detection, evaluated with a confusion matrix and ROC-AUC.

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 📈 [Stock Market EDA Pipeline](https://github.com/YS-Pundir/EDA-snack-app-stock-market)
Pulls stock data from the Alpha Vantage API, cleans it with Pandas and visualizes it.

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

</td>
</tr>
</table>

---

## 🛠️ Tools I use in these projects

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📊 GitHub snapshot

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YS-Pundir&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
<img height="170" src="https://github-readme-streak-stats.herokuapp.com/?user=YS-Pundir&theme=tokyonight&hide_border=true" alt="Streak" />

</div>

---

## 🎯 What's next

- [ ] Run my agents against real models and publish the scores
- [ ] Replace keyword intent routing with a measured classifier
- [ ] Learn LLM tracing and observability
- [ ] Contribute to open-source AI tooling

---

<div align="center">

**Want to talk agents, RAG or backend design?**

[![Connect on LinkedIn](https://img.shields.io/badge/Say%20hi%20on%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yuvraj-singh-pundir-908623351)

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="footer" />

</div>
