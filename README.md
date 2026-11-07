# Pablo Encalada

**AI/ML Engineer** · Quito, Ecuador

I build GenAI and NLP systems that run in production — multi-agent pipelines, RAG
architectures, and the evaluation frameworks that keep them honest. Currently at
Actuaria Consultores, automating actuarial work that used to take days. Finishing
an MSc in Artificial Intelligence at USFQ.

Most of what I care about is the unglamorous half: whether the retrieval actually
grounds the answer, whether the eval measures what it claims to measure, and whether
the thing survives contact with real data.

---

## Selected work

**[SQLens](https://github.com/PabloAndresE/SQLens)** · [`pip install sqlens`](https://pypi.org/project/sqlens/)
Schema intelligence layer for LLMs. Introspects a database, enriches it with
descriptions and statistics, and retrieves only the relevant tables per query — so the
model sees context instead of a 200-table dump. Published on PyPI.

**[sam2-supertuxkart-segmentation](https://github.com/PabloAndresE/sam2-supertuxkart-segmentation)**
Frozen SAM 2 encoder with a 2.1M-parameter decoder (7% trainable). 38 runs, and the
interesting result wasn't the score — it was finding out what the evaluation protocol
was actually reporting.

**[dungeon-master-agentic](https://github.com/PabloAndresE/dungeon-master-agentic)**
Direct LLM vs. single-agent vs. multi-agent LangGraph on the same narrative task,
scored by an LLM judge with held-out sets and component ablations. Does the
orchestration earn its complexity? Sometimes.

**[simulst-es-en](https://github.com/PabloAndresE/simulst-es-en)**
Simultaneous ES→EN speech translation: fine-tuned offline model plus the emission
policy from the paper. The latency/quality tradeoff is the whole problem.

**[traductor-voz-lstm](https://github.com/PabloAndresE/traductor-voz-lstm)**
Whisper for ASR into a from-scratch 2-layer bidirectional LSTM encoder-decoder with
Luong attention and BPE, in PyTorch. Built before reaching for a transformer, on
purpose.

**[salary-benchmarking](https://github.com/PabloAndresE/salary-benchmarking)**
MSc thesis. Payroll job titles are unreliable — in real data, 1% of labels contaminated
40% of the population. Rebuilds the grouping from the text itself with multilingual
embeddings, UMAP and HDBSCAN. PII anonymization under Ecuador's LOPDP runs first.

**[Dactil](https://github.com/PabloAndresE/Dactil)**
Real-time Ecuadorian Sign Language (LSEC) interpreter with MediaPipe. There is no
usable LSEC dataset, which turns out to be most of the work.

**[quack.sh](https://github.com/PabloAndresE/quack.sh)**
The AI that only asks questions and never answers. Rubber duck debugging, but the duck
talks back.

---

## Stack

**ML / NLP** — PyTorch · Hugging Face (transformers, peft, trl) · scikit-learn · sentence-transformers · LoRA/QLoRA · DPO

**GenAI** — LangChain · LangGraph · Vertex AI · Milvus · RAGAS · OPIK · LLM-as-judge

**Backend** — Python · FastAPI · Flask · Pydantic · PostgreSQL · BigQuery

**Infra** — Docker · Terraform · GitHub Actions · Google Cloud (Cloud Run, Agent Engine)

---

## Currently

Finishing the MSc thesis. Open to remote AI/ML roles.

Also reverse-engineering guitar amps into neural networks, which has nothing to do with
any of the above and that's rather the point.

---

**dev@pabloencalada.com** · [LinkedIn](https://linkedin.com/in/pablo-encalada) · [pabloencalada.com](https://pabloencalada.com)
