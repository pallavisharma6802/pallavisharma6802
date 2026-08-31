# Pallavi Sharma
**Data Scientist & ML Engineer** | MS Data Science @ UW-Madison ('26)
[LinkedIn](https://www.linkedin.com/in/pallavisharma6802/) • [pallavi6802@gmail.com](mailto:pallavi6802@gmail.com)

> *I kept running into the same problem: LLMs that sound completely certain about things they just made up.* I build systems where reliability is the feature, agents that know when to escalate, evaluators that catch fabricated facts, and models that reason about what a user *actually* wants versus what they said in a stressful moment.

🔬 **Graduate research** (Prof. Fred Sala, UW-Madison) : modeling how patient preferences evolve over time for proactive LLM adaptation. Transformer layer probing across 25–29 layers, adversarial red-teaming (cut apparent 94.8% accuracy to 53.3% under directed adversarial search). Targeting publication.

🛡️ **AI safety** : WAISI Technical AI Safety Fundamentals fellow (Feb 2026). The research question maps directly to alignment: when should a system hold firm on what a user said versus treat it as a fear-state artifact?

---

### 🚀 Featured Engineering

| Project | What it does | Stack |
|---------|-------------|-------|
| [Multi-Cloud AI Agent  Ticket Resolution](https://github.com/pallavisharma6802/Multi-Cloud-AI-Agent-for-Ticket-Resolution) | 8-agent cyclic pipeline with CRAG, Self-RAG, Reflexion, per-node LLM-as-judge evaluation | LangGraph, AWS Bedrock, Azure Text Analytics, Pinecone + BM25, LangSmith, Terraform |
| [Travel Desk  Hotel Multi-Agent System](https://github.com/pallavisharma6802/travel_desk) | Multi-agent system for hotel operations  autonomous agents handling guest requests, room assignments, and service coordination | LangGraph, Multi-agent, FastAPI |
| [Trust Under Pressure  LLM Manipulation Resistance](https://github.com/pallavisharma6802/Trust-Under-Pressure-Manipulation-Resistance-in-LLM-Agents) | 8 empirical studies across 4 models. Majority-vote mitigation backfires 33% → 61% once attacker controls peer channels. Translation-bypass hits ~75% compliance | Groq API, Deterministic scoring, Wilson CI |
| [Procedural Intelligence  OR Case Reconstruction](https://github.com/pallavisharma6802/Procedural-Intelligence-prototype) | 9-node LangGraph pipeline reconstructing surgical cases from transcript or audio into operative notes, handoffs, family updates. 4/4 synthetic cases pass evaluation | LangGraph, Groq Whisper, FastAPI |
| [LLM Sentinel  Hallucination Detection](https://github.com/pallavisharma6802/LLM_Sentinel_Hallucination_Detection_Platform) | Precision = 1.0 on fabricated entity detection across 1,044 real inference traces. 10 NLP checks including atomic claim decomposition | Gemini 2.5 Pro, FastAPI, PostgreSQL, Airflow, Next.js |
| [Spending Forecast Platform](https://github.com/pallavisharma6802/Spending-Forecast-Platform) | Per-category forecasting via 10-fold walk-forward backtest across 4 model candidates. Mean WAPE 21.9% across 13 categories, 23K transactions | PySpark, SARIMAX, Kafka, Anthropic SDK, Dash |
| [Critic-Guided Multilingual Continual Learning](https://github.com/sbnikhil/critic-guided-self-adaptation) | LoRA fine-tuning across 15 languages, 3 phases (TyDiQA → XQuAD → MLQA). Representation anchoring cuts catastrophic forgetting by 12.6% (F1 12.66 vs 11.24). Low-resource languages outperform high-resource after Phase 1 | Qwen2.5-7B, LoRA/PEFT, Gemini critic, HuggingFace |
| [LLM Serving Tradeoff Analyzer](https://github.com/pallavisharma6802/LLM-Serving-Tradeoff-Analyzer) | Benchmarks vLLM, SGLang, Ollama, ONNX Runtime across throughput, TTFT, and latency on live GPU hardware | vLLM, SGLang, ONNX Runtime, Grafana |
| [Policy-Aware RAG](https://github.com/pallavisharma6802/Policy-Aware-RAG-System) | RAG for Google Ads policy Q&A  hybrid search, local LLM, citation-backed responses, explicit refusal logic. 90 tests at 100% pass rate | Weaviate, LangChain, Qwen3, FastAPI, Docker |
| [Fraud Detection MLOps](https://github.com/pallavisharma6802/Self-Healing-Fraud-Detection-System) | Drift-aware retraining at 30% threshold across 434 features. ROC-AUC 95.5%, F1 improved from 34.7% to 49.8% | XGBoost, Evidently, MLflow, Docker |
| [DoIT KB Agentic Assistant](https://github.com/pallavisharma6802/DoIT-Help-Desk-Agent) | Agentic IT support  Recall@3 95.4% via LangGraph + graph-augmented BFS retrieval. [Live](https://doit-hd-agentic-assistant.onrender.com/) | LangGraph, ChromaDB, NetworkX, Langfuse, FastAPI, React |
| [High-Efficiency Edge-AI Sentiment Engine](https://github.com/pallavisharma6802/High-Efficiency-Edge-AI-Sentiment-Engine) | DistilBERT fine-tuned and exported to ONNX INT8. 74% size reduction (255 MB → 65.8 MB), 1.8x CPU speedup, PyTorch-free serving | ONNX Runtime, DistilBERT, FastAPI, Docker |

---

## 🛠️ Stack

**LLMs & Agents**
`LangGraph` `LangChain` `AWS Bedrock` `Groq` `Anthropic SDK` `vLLM` `SGLang` `Langfuse` `LangSmith` `MCP` `RAG` `CRAG` `Self-RAG` `Reflexion`

**ML & Deep Learning**
`PyTorch` `HuggingFace Transformers` `LoRA/PEFT` `XGBoost` `Scikit-learn` `DistilBERT` `Mechanistic Interpretability`

**Data & Engineering**
`PySpark` `Kafka` `PostgreSQL` `BigQuery` `SARIMAX` `Prophet` `MLflow` `Evidently`

**Cloud & MLOps**
`AWS (Bedrock, ECS Fargate, S3, RDS)` `GCP` `Azure` `Docker` `Terraform` `GitHub Actions`

<br/>

---
*Actively looking for full-time AI/ML/Data Science roles.*
