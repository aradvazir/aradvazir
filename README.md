<div align="center">

# Arad Vazirpanah

**M.Sc. Data Science & AI @ Universität Hamburg**
Medical image analysis · biomedical deep learning · time-series & generative models

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aradvazir)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:aradvazir@gmail.com)
![Location](https://img.shields.io/badge/Hamburg,%20Germany-555?style=flat&logo=googlemaps&logoColor=white)

</div>

---

I'm a Data Science & AI master's student working on **reliable, clinically meaningful deep learning** — from semantic segmentation and biomedical signals (EEG/ECG) to generative models. Previously ranked **8th/51** in Computer Science at the University of Tehran (GPA 18.07/20).

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat&logo=keras&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)

---

### 🔬 Research Interests

- Medical Image Analysis
- Deep Learning for Healthcare
- Biomedical Signal Processing
- Self-Supervised & Representation Learning
- Generative Modeling
- Trustworthy, Clinically Meaningful AI

---
### 🧠 Bachelor's Thesis

[Moment_EEG — Deep Learning-based Emotion Detection from EEG](https://github.com/aradvazir/Moment_EEG)

Explores using **MOMENT**, a time-series
foundation model, as a feature extractor for **EEG emotion recognition** on the
**SEED-V** dataset (5 emotions), benchmarked against classical PSD/DE pipelines and
the PGCN reference model.

- **Best result:** ~48% accuracy (PSD + MLP), subject-dependent on SEED-V
- **Stack:** Python · PyTorch · momentfm · scikit-learn · MNE
- 📄 Includes the full thesis report
---

### 🌟 Featured Projects

**[Joint β-VAE + Latent-Space Energy-Based Models](https://github.com/aradvazir/VAE-EBM)** · *research, Universität Hamburg*
A hybrid generative model that trains a β-VAE and an EBM **jointly** in a shared 256-D latent space, with bidirectional coupling instead of the usual sequential setup. Short-run SGLD sampling, spectral-normalized energy net, stable training with no posterior collapse. Includes a paper and slides.
`PyTorch`

**[Kvasir Polyp Segmentation (U-Net)](https://github.com/aradvazir/ArtificialIntelligence/tree/main/UNet-KavirSeg)**
Semantic segmentation of gastrointestinal polyps on Kvasir-SEG, comparing a from-scratch U-Net against a stacked two-stage U-Net. **Dice 89.5%**, outperforming Stack U-Net.
`TensorFlow / Keras`

**[Persian Author Identification with BERT](https://github.com/aradvazir/InformationRetrieval/tree/main/AuthorClassification)**
10-class authorship classification over a Persian literary corpus via a full HuggingFace pipeline (BERT / XLM-RoBERTa / DistilBERT). **93% accuracy**, with Naive Bayes / SVM baselines and cross-class error analysis.
`Hugging Face · hazm`

**[Neural Networks & Deep Learning — 7 End-to-End Projects](https://github.com/aradvazir/NeuralNetworksDeepLearning)**
From raw-NumPy classical nets (McCulloch–Pitts, Adaline/Madaline) to Vision Transformers, VQ-VAEs, cGANs and pix2pix. Highlights: a hand-built two-stage object detector (RPN, RoIAlign, NMS), brain-tumour MRI U-Net, Alzheimer's (ADNI) CNN classification, CNN-LSTM for turbofan RUL, and adversarial attacks — each with a written report.
`PyTorch · TensorFlow · Transformers`

<details>
<summary><b>More projects</b> — IR search engine, audio classification, intrusion detection, metaheuristics, and more</summary>

<br>

- **[Information Retrieval — a search engine from scratch](https://github.com/aradvazir/InformationRetrieval):** positional inverted indexes, BSBI with γ-compressed postings, permuterm-trie wildcard queries, edit-distance spell correction, and VSM / BM25 / LM ranking on Cranfield — almost all hand-rolled.
- **[Speaker & Gender Classification from Audio](https://github.com/aradvazir/MachineLearning):** feature extraction + PCA (95% variance) feeding clustering and classification. Up to **99%** gender accuracy and **100%** on 10-class speaker authentication.
- **[Network Intrusion Detection](https://github.com/aradvazir/DataMiningProject/tree/main/Network-Intrusion-Detection):** PCA with Random Forest, KNN and MLP classifiers; **76.6%** accuracy with MLP.
- **[Bio-Inspired Computing & Metaheuristics](https://github.com/aradvazir/BioInspiredComputing):** GA, SA, PSO, Gravitational Search and Ant Colony on TSP, N-Queens, Set Covering and portfolio optimization — plus Hill Climbing vs. SA vs. GA on Cutting Stock and Q-learning Pac-Man in my [AI repo](https://github.com/aradvazir/ArtificialIntelligence).
- **[Variational Autoencoders](https://github.com/aradvazir/NeuralNetworksDeepLearning/tree/main/Generative-Models/VAE):** full training/inference for VAEs, CVAEs and VQ-VAEs across two image datasets.
- **Other:** [MNIST / Fashion-MNIST](https://github.com/aradvazir/DataMiningProject) with tree ensembles · a [React front-end](https://github.com/aradvazir/polymer_proj) for product management · C++ systems work ([data structures](https://github.com/aradvazir/DSproject), [client–server matrix service](https://github.com/aradvazir/APproject)).

</details>

---

### 💼 Experience

**Research Assistant** — University of Tehran · *Sep 2024 – Feb 2025*
Designed reproducible end-to-end PyTorch pipelines for multivariate biomedical time-series with robust cross-dataset evaluation, and benchmarked transformer architectures for a six-member team.
For my **B.Sc. thesis** (supervised by Dr. Bagher BabaAli), I built a five-class EEG emotion-recognition study on **SEED-V** — extracting PSD and Differential-Entropy features and comparing SVM, MLP and Transformer models against the **MOMENT** time-series foundation model (used as a feature extractor) under both subject-dependent and subject-independent protocols.

**Teaching Assistant** — University of Tehran · *Sep 2020 – Feb 2025*
TA'd Neural Networks & Deep Learning (graduate-level), Nonlinear Programming, Probability, and Principles of Computer Systems across four years — designing projects, grading, and leading review sessions.

---

### 🔧 Skills

- **Languages:** Python, SQL, C/C++, R, JavaScript/TypeScript
- **ML/DL:** PyTorch, TensorFlow, Keras, Scikit-learn, Hugging Face Transformers, Pandas, NumPy, Matplotlib
- **Areas:** Deep Learning, NLP, Computer Vision, Generative Models (VAE, EBM, Diffusion), Signal Processing, Biomedical Time-Series, Optimisation, Statistical Modelling
- **Tools & Workflow:** Git, LaTeX, Jupyter, Weights & Biases, Linux/Bash, pytest, GitHub Actions (CI/CD), Claude & GPT-4 APIs, LangChain

---

### 🏅 Honors

- **Top Graduate**, Computer Science Class of 2024 — ranked 8th of 51, University of Tehran
- **Nationwide University Entrance Exam (2020):** 445th of 135,000+ (Top 0.3%), Math-Physics
