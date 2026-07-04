<h1 align="center">Hi, I'm Aisha 👋</h1>
<p align="center"><b>AI Engineer</b> — LLM Applications · RAG · Agents · Backend Systems</p>
<p align="center">
  📍 Dubai, UAE &nbsp;·&nbsp; 📧 aishasurve2007@gmail.com &nbsp;·&nbsp;
  <a href="https://huggingface.co/AishaSurve">🤗 Hugging Face</a>
</p>

---

### About

Computer Science (AI) undergraduate at Heriot-Watt University building **production-ready AI systems** — RAG pipelines, tool-calling agents, and the backend services that run them. I care more about *measuring* a system honestly than making it look good on paper: I benchmark against baselines, audit for data leakage, and report real failure rates instead of best-case numbers.

---

### 🚀 Projects

**[VisionCut AI](https://github.com/aishasurve2007/VisionCut_AI)** — Agentic video-highlight pipeline
FastAPI async backend → faster-whisper transcription → GPT tool-calling agent → FFmpeg cutting, exposed via an MCP server for external orchestration. Grounds every highlight to a real transcript segment so the agent can't point at an invented timestamp. 18 automated tests, CI passing.
`Python` `FastAPI` `SQLAlchemy` `OpenAI` `MCP` `FFmpeg` — [Demo video](https://github.com/user-attachments/assets/adce1370-f3e5-4249-af8b-d718cbbd6ba7)

**[StudyMate AI](https://github.com/aishasurve2007/StudyMate-AI)** — RAG document Q&A with an evaluation harness
Hybrid retrieval (FAISS + BM25 + reranker) with NLI-based hallucination detection. Tuned against a 30-question eval set: 73% faithfulness, 4% hallucination rate, 94% answer recall.
`Python` `FAISS` `BM25` `Streamlit` — [Live on Hugging Face](https://huggingface.co/spaces/AishaSurve/studymate-ai)

**[UAC Care Capacity](https://github.com/aishasurve2007/UAC-Care-Capacity-AI)** — Honest demand nowcaster
Caught target leakage that had inflated an initial model to R² = 0.996, then rebuilt it as an honest nowcaster with walk-forward validation and a documented post-mortem. Benchmarked against a persistence baseline (MAE 10.27) with a leakage-free model (MAE 9.34).
`Python` `scikit-learn` `Streamlit` — [Live demo](https://uac-care-capacity-ai.streamlit.app/)

**[Codebase Intelligence Agent](https://github.com/aishasurve2007/codebase-agent)** — Code-aware retrieval + test generation
Tree-sitter AST parsing + hybrid BM25/vector search feeding an LLM tool-calling agent that generates repository-specific pytest tests. Evaluated on a 20-question harness: 90% file accuracy, 75% citation accuracy.
`Python` — [Live on Hugging Face](https://huggingface.co/spaces/AishaSurve/codebase-agent)

---

### 🛠️ Skills

**AI/ML:** RAG pipelines · LLM tool-calling agents · FAISS · BM25 · rerankers · NLI hallucination detection · evaluation harnesses · tree-sitter
**Backend:** FastAPI · SQLAlchemy 2.0 · REST APIs · async jobs · Django · Streamlit
**Tools:** Python · Git · GitHub Actions (CI) · pytest · Docker · MCP · FFmpeg
