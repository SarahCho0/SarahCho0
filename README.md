<h1 align="center">Hi, I'm Hyeonju Cho 👋</h1>

<p align="center">
  Python · AI/ML · Computer Vision · Generative Models · FinTech
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=SarahCho0&style=flat-square&color=grey" alt=""/>
</p>

---

I build end-to-end AI systems — from 3D perception pipelines and generative models to RAG-based applications and quantitative finance tools.
My work focuses on applying research-level models to real, usable products — with attention to both the math and the interface.
Currently interested in multimodal AI, LLM integration, and financial ML.

---

## 🛠 Skills

**Languages** &emsp; Python · JavaScript · HTML/CSS  
**AI / ML** &emsp; PyTorch · Scikit-learn · TensorFlow · Transformers · SHAP  
**Vision** &emsp; YOLO · SAM / SAM2 · SigLIP · DUSt3R / MASt3R · PE3R  
**LLM / API** &emsp; OpenAI GPT-4o / GPT-4o-mini · Gemini 2.5 Flash · TF-IDF RAG  
**App / UI** &emsp; Streamlit · Gradio · Vanilla JS (no-framework browser apps)  
**Data** &emsp; Pandas · Polars · Numpy · Jupyter Notebook  
**Tools** &emsp; Git · Conda · VS Code · CUDA (RTX 3090)

---

## 🔖 Projects

### [YOLOE3R](https://github.com/SarahCho0/team6_yoloe3r) · [LLM Module](https://github.com/SarahCho0/yoloe3r_llm) &nbsp;`Team · Individual`
> Multi-angle 3D reconstruction + LLM-powered interior simulation

`PyTorch` `SAM2` `SigLIP` `DUSt3R/MASt3R` `PE3R` `Gemini 2.5 Flash` `Gradio`

Object detection, segmentation, and perception-efficient 3D reconstruction from multi-angle inputs — deployed as a Gradio demo. Extended independently with a Gemini-powered LLM module that analyzes room images, generates structured reports, and produces multi-angle furniture simulation outputs (add / remove / change). 175+ commits.

---

### [5지는 카페 AI 키오스크](https://github.com/SarahCho0/cafe_kiosk_prj) &nbsp;`Individual`
> Full-stack AI kiosk with natural language ordering in 4 languages

`Python` `Streamlit` `GPT-4o-mini` `TF-IDF RAG` `BeautifulSoup4`

AI chatbot **Oji** takes natural language orders, manages a cart, and guides a 7-step checkout flow — across Korean, English, Chinese, and Japanese. Built on real Paik's Coffee menu data (332 items, 100% parsed with nutrition/allergy info). RAG pipeline uses TF-IDF char n-gram cosine similarity; includes abuse detection, staff-call triggers, coupon/point handling, and 9 payment methods.

---

### [QuickDraw Generation (SketchGPT)](https://github.com/SarahCho0/QuickDraw_Generation) &nbsp;`Individual`
> Transformer-based sketch generation model — paper implementation from scratch

`PyTorch` `CUDA (RTX 3090)` `Scikit-learn` `Google QuickDraw`

Implements §3.4 of the SketchGPT paper: a decoder-only Transformer (8L · 8H · d=512) pre-trained on 10 vehicle classes from QuickDraw, then fine-tuned per class to eliminate category bleed. Full pipeline — stroke-3 preprocessing, primitive tokenization, AMP training with cosine LR, class-conditional generation with top-k sampling.

---

### [ANN Lending Club](https://github.com/SarahCho0/ANN_Lendingclub) &nbsp;`Team`
> ANN-based credit risk scoring and portfolio optimization on 1.2M loan records

`Python` `Keras/TensorFlow` `Polars` `Jupyter Notebook`

End-to-end pipeline: feature engineering on 1.2M+ LendingClub records, ANN with BatchNorm + Dropout, cost-sensitive sample weights for class imbalance, and Top-K portfolio selection optimized by weighted Sharpe Ratio. Bootstrap validation (N=1000) with 95% CI. Benchmark improvement of 25–45%. SNU Statistical Data Science course project.

---

### [Historical Figures Chatbot](https://github.com/SarahCho0/historical-figure-chatbot) &nbsp;`Individual`
> Browser-based chatbot to converse with historical figures — per-figure themes and modes

`Vanilla JS` `HTML/CSS` `GPT-4o` `OpenAI API`

Zero-install single-file app featuring 10+ historical figures (Einstein, Gandhi, Sejong, da Vinci…), each with a unique visual theme, font, and color palette. Four conversation modes per figure: Normal · Deep Reflection · Historical Context · Teaching + a figure-specific specialty mode (Thought Experiments, Strategic Analysis, etc.). EN/KR bilingual UI.

---

### [AI Story Generator (Picture Story)](https://github.com/SarahCho0/ai-story-generator) &nbsp;`Individual`
> Upload images, pick an emotion, get a story — GPT-4o Vision, no install required

`Vanilla JS` `HTML/CSS` `GPT-4o Vision` `OpenAI API`

Single-file browser app with 18+ dynamic emotion themes that transform the page palette and typography on selection. Multi-image upload (drag & drop) with order-preserving story sequencing. GPT-4o analyzes all images and generates a cohesive narrative. EN/KR toggle. SNU AI Application Lab Exercise.

---

### [Samsung Audit RAG](https://github.com/njungyeon/samsung-audit-rag) &nbsp;`Team`
> RAG-based document Q&A system for Samsung audit reports

`Python` `RAG` `LLM`

Retrieval-Augmented Generation pipeline for querying internal audit documents. Contributed as a team member.

---

## 📊 Stats

<p align="center">
  <img height="155" src="https://github-readme-stats.vercel.app/api?username=SarahCho0&show_icons=true&hide_border=true&theme=default" />
  <img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SarahCho0&layout=compact&hide_border=true&theme=default" />
</p>

---

## 📬 Contact

GitHub &nbsp;→&nbsp; [github.com/SarahCho0](https://github.com/SarahCho0)
