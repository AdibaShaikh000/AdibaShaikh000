# Hi, I'm Adiba Shaikh

**Tech Lead · Data Scientist · GenAI & Agentic AI**

8 years in Python, the last few spent building and shipping production GenAI systems for Fortune 500 banking and financial-services clients. I lead teams of 6–8 engineers and own delivery end-to-end — stakeholder problem framing, solution architecture, model selection and fine-tuning, RAG pipeline design, guardrails and PII redaction, evaluation and observability, and cloud deployment. Systems I've shipped run at **87% RAG accuracy** and have cut analyst workflows by **40–60%**.

📍 Bengaluru, India · 💼 [LinkedIn](https://www.linkedin.com/in/adiba-shaikh-495716163/) · ✉️ adibashaikh000@gmail.com

## Experience highlights

| Where | What I built | Impact |
|---|---|---|
| **Synechron** — Tech Lead | GPT-5.2 audit chatbot on Azure OpenAI that auto-generates compliance test plans from regulatory documents, with PII detection/redaction and OpenTelemetry → Azure App Insights observability | Compliance teams save ~18 hrs/week |
| **Synechron** — Tech Lead | RAG chatbot on Azure OpenAI (GPT-4o) — chunking strategy, hybrid search via Azure AI Search, semantic reranking, multi-turn memory, agentic retrieval | 87% response accuracy · 60% faster document analysis |
| **Brane Enterprises** — Associate Solution Lead | Domain-aware knowledge graph in Neo4j with LaBSE embeddings as native vectors, powering entity-attribute suggestions across 20M nodes | Context-aware attribute surfacing at scale |
| **Brane Enterprises** - Associate Solution Lead | Fine-tuned DistilBERT NER (few-shot synthetic data + BIO tagging), packaged as a versioned REST microservice | 96% macro F1 · 109 languages |
| **TCS** — System Engineer | Enterprise document-processing pipeline on AWS Textract + GCP Document AI for multi-page PDFs, invoices, and IDs | 20K+ documents/month |

## Open-source projects

| Project | What it does |
|---|---|
| [**RegulationQA**](https://github.com/AdibaShaikh000/regulation-qa-agent) | Multi-agent LangGraph system answering US banking-regulation questions with verifiable CFR citations — Graph RAG over a Neo4j citation network, live eCFR fetch backed by a ChromaDB semantic cache, SSE-streamed agent progress, LangSmith tracing, and the full tool suite exposed as an MCP server. 100% open-source, no paid APIs. |
| [**RAG Q&A Assistant**](https://github.com/AdibaShaikh000/conversational-rag) | Production-packaged conversational RAG with two-stage retrieval (FAISS recall → cross-encoder rerank), sliding-window query condensing for multi-turn accuracy, a modular LCEL pipeline, and per-answer source citations — containerized with a multi-stage Docker build. |
| [**House Price Prediction**](https://github.com/AdibaShaikh000/house_price_assessment) | End-to-end regression study — EDA, data-quality investigation, model training and evaluation, and prediction explainability on a multi-modal price distribution. |

## Toolbox

**GenAI & Agentic** — LangGraph · LangChain · LlamaIndex · multi-agent & ReAct systems · Graph RAG · hybrid search · reranking · MCP (FastMCP) · tool calling · SSE streaming · prompt engineering · multi-turn memory

**LLMs & Models** — GPT-4o / GPT-5.2 · Llama 3 · Mistral · BERT / DistilBERT / LaBSE · Transformers · fine-tuning (LoRA, QLoRA)
**ML & NLP** — classification · Random Forest · NER · BIO tagging · dependency parsing · sentence embeddings · semantic reranking
**Safety & Observability** — PII detection & redaction · guardrails · RAGAS · DeepEval · LangSmith · OpenTelemetry · Azure Application Insights
**Engineering** — Python · FastAPI · Flask · Django · microservices · system design · CI/CD · Docker · unit / load / integration testing
**Cloud** — Azure OpenAI · Azure DevOps · AWS Bedrock · GCP
**Data** — Azure SQL · MySQL · Milvus · FAISS · Neo4j · Azure AI Search · MongoDB · Redis

## Education & certifications

**M.S. Artificial Intelligence**, University of Mumbai (86%) 
**B.S. Computer Science**, University of Mumbai (Outstanding)

## Certifications

- AI Engineer — Agentic Track: The Complete Agent & MCP Course (Udemy)
- AI Engineer — Core Track: LLM Engineering, RAG, QLoRA, Agents (Udemy)
- Knowledge Graphs for RAG (DeepLearning.AI)
- ChatGPT Prompt Engineering for Developers (DeepLearning.AI)
- AI-900: Azure AI Fundamentals (Microsoft)

## Awards

🏆 Surpass Innovation Award (Synechron) · Special Initiative Award (TCS)
