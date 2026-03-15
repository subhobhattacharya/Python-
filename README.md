# 🐍 Python for Product Management
### Technical Scoping | Prototyping | Data-Driven Decisions

This repository contains Python utilities and prototypes I’ve developed to bridge the gap between product requirements and technical implementation. As a PM, I use Python to validate hypotheses, test APIs, and prototype AI logic before moving to full-scale engineering production.

---

## 📂 Featured Modules

### 1. Agentic AI & RAG Logic (`/ai-prototypes`)
- **Objective:** Testing retrieval accuracy for the Aviation Research Agent.
- **Tech:** OpenAI API, Pinecone, LangChain.
- **Outcome:** Validated that a multi-LLM approach reduced hallucination by 30% before the dev team started the build.

### 2. Fintech API Validator (`/api-testing`)
- **Objective:** Automated smoke tests for B2B API endpoints to ensure RBI compliance in response headers.
- **Tech:** `requests`, `pytest`.

### 3. Funnel Analysis Tool (`/data-analysis`)
- **Objective:** Processing 1M+ rows of transaction data to identify drop-off points in the onboarding flow.
- **Tech:** Pandas, Matplotlib.

---

## 🛠️ How I Use This
I don't just write code; I use these scripts to:
1. **Reduce Engineering Overhead:** By prototyping logic myself, I provide clearer PRDs.
2. **Data Sovereignty:** Writing my own SQL/Python queries to get insights without waiting for a Data Analyst.
3. **API Due Diligence:** Testing third-party integrations (like Cirium or IATA) early in the discovery phase.
