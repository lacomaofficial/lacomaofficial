# Summary

I am a **computational neuroscientist** and **machine learning researcher** developing interpretable AI systems for **medical** and **complex dynamical systems**. My work bridges **clinical neuroscience**, **time series modeling**, and **quantitative decision science**, with a commitment to open, reproducible, and theory-grounded methods.

I lead independent research, teach university-level neuroscience, and maintain a public portfolio of tools and models spanning **fMRI, EEG, iEEG, DWI, behavioral phenotyping, and financial time series**.

---

## 🔬 Research Pillars

### 1. **Neuro-AI for Clinical Translation**  
*Predicting and stratifying neurological & psychiatric conditions using multimodal brain data.*  
- **[BB-Toolbox](https://github.com/lacomaofficial/BB-Toolbox)**: Transformer-based Parkinson’s classifier (95.2% AUC) on UK Biobank fMRI (414 regions).  
- **[ASD-Prediction-rsfMRI](https://github.com/lacomaofficial/ASD-Prediction-rsfMRI)**: Autism spectrum disorder detection via resting-state fMRI Transformers.  
- **[ADHD-Prediction-rsfMRI](https://github.com/lacomaofficial/ADHD-Prediction-rsfMRI)**: Connectivity-based ADHD classification.  
- **[iEEG-MLP-Classifier](https://github.com/lacomaofficial/iEEG-MLP-Classifier)**: Epileptic event detection from intracranial EEG.  
- **[Pink_Crystal_Model](https://github.com/lacomaofficial/Pink_Crystal_Model)**: 3D interactive visualization of brain feature importance.  

### 2. **Foundations of Time Series Modeling**  
*Architecture design for multivariate, non-stationary, high-dimensional sequences.*  
- **[Transformer-Time-Series-Model](https://github.com/lacomaofficial/Transformer-Time-Series-Model)**: Unified framework for univariate/multivariate forecasting with patch embeddings, RoPE, and temporal pooling.  
- **[Comp-Neuro-Toolbox](https://github.com/lacomaofficial/Comp-Neuro-Toolbox)**: Classical + deep learning pipelines for neuroimaging.  
- **[Graph-Neural-Networks](https://github.com/lacomaofficial/Graph-Neural-Networks)**: Brain graph construction from fMRI for GNN-based decoding.  

### 3. **Quantitative Systems Beyond Neuroscience**  
*Validating neuro-inspired models in finance and behavioral science.*  
- **[Hedge-Fund-Apps](https://github.com/lacomaofficial/Hedge-Fund-Apps)**: Regime detection, signal generation, and risk-aware trading interfaces.  
- **[FinancialTransformer]**: Equity move prediction using macro features (no raw prices), sharing >90% backbone with BBTransformer.  
- **[Five-Factor-Model-Test](https://github.com/lacomaofficial/Five-Factor-Model-Test)**: Personality trait modeling as a proxy for behavioral phenotyping.  

### 4. **Open Educational Infrastructure**  
*Teaching reproducible computational neuroscience at scale.*  
- **[Neuro AI Toolbox (`cimt-unia/neuro_ai`)](https://github.com/cimt-unia/neuro_ai)**: University-grade modules for **DWI, EEG, fMRI**—featuring source imaging, connectivity (wPLI), tractography, and Transformer tutorials.  
- Used in graduate instruction to train students in end-to-end pipeline development.  

---

## 🧪 Methodological Signature

Across all domains, I adhere to consistent principles:
- **No dropout in embedding layers** — preserve signal integrity in low-SNR regimes.  
- **Per-subject or per-series normalization** — avoid data leakage.  
- **Patch-based temporal modeling** with stride < patch size for overlapping context.  
- **RMSNorm + SwiGLU + RoPE** as default architectural primitives.  
- **Validation via walk-forward, cohort stratification, or subject-wise splits** — never random shuffle.  
- **Interpretability via permutation importance**, not post-hoc attention maps.  

---

## 🌐 Connect & Collaborate

- **Personal Site**: [lacomaofficial.github.io](https://lacomaofficial.github.io)  
- **Hugging Face**: [lacomaofficial](https://huggingface.co/lacomaofficial) — model cards, demos, Spaces  
- **GitHub Stats**:  
  ![Metrics](https://github-readme-stats.vercel.app/api?username=lacomaofficial&show_icons=true&theme=radical)  
  ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lacomaofficial&layout=compact&theme=radical)

---

> “The most powerful models are not those that merely predict—but those that **reveal mechanism**.”  
> — Jay

*I welcome research collaborations in computational psychiatry, digital biomarkers, causal representation learning, and robust time series foundations.*
