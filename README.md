<img src="https://capsule-render.vercel.app/api?type=waving&color=6366f1&height=200&section=header&text=Hyeonju%20Cho&fontColor=ffffff&fontSize=52&fontAlignY=38&desc=AI-Native%20Builder%20%7C%20Production%20AI%20Systems&descSize=20&descAlignY=60&descColor=e0e7ff" width="100%"/>

## 💡 About Me

> I build production AI systems end to end. I own the architecture, specs, and verification, and use AI coding agents to ship faster without lowering the quality bar.

- **Now**: Enterprise AI in production at Eugene Group (AI CoE, Apr–Aug 2026) — LLM deliberation & hybrid retrieval systems
- **How I work**: requirements → unambiguous specs → golden-test / HITL verification → ship → iterate on field feedback
- **What I own**: the decisions, the quality bar, the outcome — agents speed up the build; I'm accountable for every line that ships

---

## 🛠 What I Ship With

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white)
![Claude](https://img.shields.io/badge/Claude%20Agent-D97757?style=for-the-badge&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG%20%C2%B7%20BM25-0EA5E9?style=for-the-badge&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL%20%2B%20pgvector-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

## 🚀 Featured Projects

### 🏢 In Production — Enterprise AI @ Eugene Group

> Both systems are deployed and in live use at Eugene Group. Repos are private mirrors of the corporate GitLab (🔒) — the verification patterns from both are open-sourced in **[CiteGuard](https://github.com/SarahCho0/citeguard)** below.

<table>
<tr>
<td width="50%" valign="top">

#### [투자심의 AI — Investment Deliberation Engine](https://github.com/SarahCho0/-Project-Eugene-Investment-Decision) 🔒
**Deal documents in → committee-grade deliberation report out**

`Python engine (8.5k lines) + Next.js (22k+ lines)`

- Ingest (pptx/docx/PDF → Claude-agent visual canonicalization) → per-axis scoring against anchor rubrics, **every score backed by cited evidence**
- **Zero-LLM-call citation verification** + a readiness-diagnosis **HITL gate** before full review; **449 golden pytest tests** pin behavior (team)

`Python` `Next.js` `TypeScript` `Claude Agent`

</td>
<td width="50%" valign="top">

#### [매칭 AI — Field-Language Product Search](https://github.com/SarahCho0/project-eugene_homecenter) 🔒
**Slang/typo-riddled field queries → exact product codes**

`Hit@10 88% · 600+ tests`

- Dual-channel retrieval (field-term thesaurus ∥ char n-gram BM25) → LLM re-ranking constrained to the candidate pool (hallucination guard)
- Built the taxonomy from scratch — **1.9K groups · 7.8K field aliases** over a 24K-SKU catalog; live for field workers, **4.9/5.0 satisfaction** (team result)

`Python` `FastAPI` `BM25` `SQLite` `Docker`

</td>
</tr>
</table>

### 🛡️ Open Source

#### [CiteGuard — Verification Toolkit for LLM Applications](https://github.com/SarahCho0/citeguard) · [Live demo ↗](https://sarahcho0.github.io/citeguard/)
**The verification patterns above, generalized into a public, reusable library — no company code or data.**

`430 tests · zero dependencies · zero LLM calls in verification`

- **Citation Gate**: deterministic string-match verification of citations against a corpus — six verdicts, from `verified` to `quote_not_found`
- **Eval Harness**: Hit@K/MRR + stage-level diagnosis (recall problem vs. ranking problem) — plus **math-grounded design**: metric axioms and branch-and-bound pruning verified by property tests ([MATH.md](https://github.com/SarahCho0/citeguard/blob/main/MATH.md))

`Python` `JavaScript` `pytest` `BM25` `GitHub Actions CI`

### 🔬 Other Highlights

<table>
<tr>
<td width="50%" valign="top">

#### Partial-Symmetric Tensor Toolbox (MATLAB)
**Independent study under Prof. João M. Pereira, UGA (MATH 4950) · Aug 2026 – Present**

Extending Pereira's `tensor_toolbox` with a from-scratch partial-symmetric tensor OOP class — 5 constructor modes, a unary/binary/N-ary operation dispatcher, 23 operators + 7 core/utility methods.

**57/57 tests passing** across 44 commits, merged into the professor's shared research fork.

`MATLAB`

</td>
<td width="50%" valign="top">

#### [YOLOE3R](https://github.com/SarahCho0/team6_yoloe3r) · [LLM Module ↗](https://github.com/SarahCho0/yoloe3r_llm)
**Multi-angle 3D reconstruction + LLM interior simulation**

Full pipeline (YOLOE → SAM2 → SigLIP → DUSt3R/MASt3R → PE3R) chained end-to-end from room photos; independently extended with a Gemini 2.5 Flash module for interior simulation reports — unprompted by the course.

**Winner, NIA President's Award** (National Information Society Agency) · published, KCI 39(2) 2026

`PyTorch` `SAM2` `DUSt3R/MASt3R` `Gemini 2.5 Flash`

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### [SketchGPT — QuickDraw Generation](https://github.com/SarahCho0/QuickDraw_Generation)
**Paper reimplementation — no public reference implementation existed**

Decoder-only Transformer (8L·8H·d=512) generating sketches as stroke sequences. Fixed **category bleed** (cars → planes) with per-class fine-tuning on a shared backbone.

`PyTorch` `CUDA`

</td>
<td width="50%" valign="top">

#### [ANN Lending Club](https://github.com/SarahCho0/ANN_Lendingclub)
**Credit risk scoring & portfolio optimization on 1.2M records**

ANN with cost-sensitive class weighting → Top-K portfolio selection by weighted Sharpe Ratio, bootstrap-validated (N=1000). **~25% improvement over benchmark.**

`Python` `TensorFlow` `Polars`

</td>
</tr>
</table>

---

## 📬 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-SarahCho0-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SarahCho0)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hyeonju--cho-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hyeonju-cho-b9b441312)
&nbsp;
[![Email](https://img.shields.io/badge/Email-chohjeonju5640@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chohjeonju5640@gmail.com)

</div>
