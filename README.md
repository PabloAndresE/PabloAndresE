<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=24&duration=3200&pause=900&color=58A6FF&center=true&vCenter=true&width=720&lines=AI%2FML+Engineer+%C2%B7+Quito%2C+Ecuador;GenAI+and+NLP+systems+that+run+in+production;Multi-agent+pipelines%2C+RAG%2C+honest+evaluation;MSc+in+Artificial+Intelligence+%C2%B7+USFQ" alt="AI/ML Engineer - Quito, Ecuador" />

<br/>

[![Email](https://img.shields.io/badge/dev@pabloencalada.com-0D1117?style=for-the-badge&logo=maildotru&logoColor=58A6FF&labelColor=0D1117)](mailto:dev@pabloencalada.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0D1117?style=for-the-badge&logo=linkedin&logoColor=0A66C2&labelColor=0D1117)](https://linkedin.com/in/pablo-encalada)
[![Website](https://img.shields.io/badge/pabloencalada.com-0D1117?style=for-the-badge&logo=googlechrome&logoColor=58A6FF&labelColor=0D1117)](https://pabloencalada.com)
[![PyPI](https://img.shields.io/badge/sqlens-on_PyPI-0D1117?style=for-the-badge&logo=pypi&logoColor=FFD43B&labelColor=0D1117)](https://pypi.org/project/sqlens/)

</div>

---

I build GenAI and NLP systems that run in production — multi-agent pipelines, RAG
architectures, and the evaluation frameworks that keep them honest. Currently at
Actuaria Consultores, automating actuarial work that used to take days.

Most of what I care about is the unglamorous half: whether the retrieval actually
grounds the answer, whether the eval measures what it claims to measure, and whether
the thing survives contact with real data.

---

## Selected work

<table>
<tr>
<td width="50%" valign="top">

### [SQLens](https://github.com/PabloAndresE/SQLens)

Schema intelligence layer for LLMs. Introspects a database, enriches it with
descriptions and statistics, and retrieves only the relevant tables per query — so
the model sees context instead of a 200-table dump.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyPI](https://img.shields.io/badge/pip_install_sqlens-3775A9?style=flat-square&logo=pypi&logoColor=white)

</td>
<td width="50%" valign="top">

### [sam2-supertuxkart](https://github.com/PabloAndresE/sam2-supertuxkart-segmentation)

Frozen SAM 2 encoder with a 2.1M-parameter decoder — 7% trainable. 38 runs, and the
interesting result wasn't the score: it was finding out what the evaluation protocol
was actually reporting.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![SAM2](https://img.shields.io/badge/SAM_2-0467DF?style=flat-square&logo=meta&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [dungeon-master-agentic](https://github.com/PabloAndresE/dungeon-master-agentic)

Direct LLM vs. single-agent vs. multi-agent LangGraph on the same narrative task,
scored by an LLM judge with held-out sets and ablations. Does the orchestration earn
its complexity? Sometimes.

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

</td>
<td width="50%" valign="top">

### [simulst-es-en](https://github.com/PabloAndresE/simulst-es-en)

Simultaneous ES→EN speech translation: fine-tuned offline model plus the emission
policy from the paper. The latency-versus-quality tradeoff is the whole problem.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)

</td>
</tr>
</table>

<details>
<summary><b>&nbsp;More projects</b></summary>

<br/>

**[traductor-voz-lstm](https://github.com/PabloAndresE/traductor-voz-lstm)** — Whisper
for ASR into a from-scratch 2-layer bidirectional LSTM encoder-decoder with Luong
attention and BPE, in PyTorch. Built before reaching for a transformer, on purpose.

**[salary-benchmarking](https://github.com/PabloAndresE/salary-benchmarking)** — MSc
thesis. Payroll job titles are unreliable: in real data, 1% of labels contaminated 40%
of the population. Rebuilds the grouping from the text itself with multilingual
embeddings, UMAP and HDBSCAN. PII anonymization under Ecuador's LOPDP runs first.

**[Dactil](https://github.com/PabloAndresE/Dactil)** — Real-time Ecuadorian Sign
Language (LSEC) interpreter with MediaPipe. There is no usable LSEC dataset, which
turns out to be most of the work.

**[parking-reserves-app](https://github.com/PabloAndresE/parking-reserves-app)** —
OfiPark: parking reservations with role-based access, calendar booking and web push.
React + Firebase, running with real users.

**[quack.sh](https://github.com/PabloAndresE/quack.sh)** — The AI that only asks
questions and never answers. Rubber duck debugging, but the duck talks back.

**[playlist-history](https://github.com/PabloAndresE/playlist-history)** — Snapshots
Spotify playlists and diffs them over time, so you find out which songs a collaborator
quietly removed.

</details>

---

## Stack

<details open>
<summary><b>&nbsp;ML / NLP</b></summary>

<br/>

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

`LoRA/QLoRA` · `DPO` · `sentence-transformers` · `BGE-M3` · `HDBSCAN` · `UMAP` · `BPE`

</details>

<details open>
<summary><b>&nbsp;GenAI & Agents</b></summary>

<br/>

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Milvus](https://img.shields.io/badge/Milvus-00A1EA?style=for-the-badge&logo=milvus&logoColor=white)

`LangGraph` · `agentic RAG` · `RAGAS` · `OPIK` · `LLM-as-judge` · `guardrails`

</details>

<details>
<summary><b>&nbsp;Backend & Infra</b></summary>

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![GCP](https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

`BigQuery` · `Cloud Run` · `Agent Engine` · `GitHub Actions` · `Pydantic` · `Flask`

</details>

---

## Shipping

<div align="center">

[![PyPI version](https://img.shields.io/pypi/v/sqlens?style=for-the-badge&logo=pypi&logoColor=white&label=sqlens&labelColor=0D1117&color=3775A9)](https://pypi.org/project/sqlens/)
[![Python](https://img.shields.io/pypi/pyversions/sqlens?style=for-the-badge&logo=python&logoColor=white&labelColor=0D1117&color=3776AB)](https://pypi.org/project/sqlens/)

<br/>

<img width="96%" src="https://raw.githubusercontent.com/PabloAndresE/PabloAndresE/output/snake.svg" alt="Contribution snake" />

</div>

---

## Currently

Finishing the MSc thesis. **Open to remote AI/ML roles.**

Also reverse-engineering guitar amps into neural networks, which has nothing to do
with any of the above and that's rather the point.

<div align="center">
<br/>

[![Say hi](https://img.shields.io/badge/say_hi-dev@pabloencalada.com-58A6FF?style=for-the-badge&labelColor=0D1117)](mailto:dev@pabloencalada.com)

</div>
