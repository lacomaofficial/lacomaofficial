# Research Portfolio

I develop machine learning systems for **high-dimensional dynamical data**, with primary applications in **computational neuroscience** and secondary validation in **quantitative finance**. My work emphasizes **architectural integrity**, **reproducible pipelines**, and **clinically interpretable outputs**.

All code is maintained as open scientific infrastructure. Repositories are organized by domain, methodology, and pedagogical utility.

---

## Core Research Areas

### 1. **Multivariate Time Series Modeling**  
Design and evaluation of deep architectures for non-stationary, multichannel temporal sequences.  
- Patch-based Transformers with **channel-independent** or **multi-scale embeddings**  
- Architectural primitives: **RoPE**, **Grouped-Query Attention (GQA)**, **SwiGLU**, **RMSNorm**  
- **Temporal attention pooling** and **overlapping patch extraction** (stride < patch size)  
- Validation via **walk-forward splits**, **subject-wise partitioning**, and **permutation testing**  

**Key repository**:  
- [`Transformer-Time-Series-Model`](https://github.com/lacomaofficial/Transformer-Time-Series-Model)

---

### 2. **Computational Neuroscience & Clinical Biomarkers**  
Machine learning applied to multimodal neural data for diagnostic stratification and mechanistic insight.

#### fMRI-Based Classification  
- Resting-state fMRI analysis using **414-region parcellations** (HCP-MMP + Tian subcortical)  
- Transformer and classical ML models for **Parkinson’s**, **ASD**, and **ADHD**  
- Feature importance via **permutation ranking**, not attention maps  

**Repositories**:  
- [`BB-Toolbox`](https://github.com/lacomaofficial/BB-Toolbox) — Parkinson’s classification (95.2% accuracy, AUC = 0.958)  
- [`ASD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ASD-Prediction-rsfMRI) — Transformer model identifying Callosomarginal Sulcus–Lingual Gyrus dysconnectivity  
- [`ADHD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ADHD-Prediction-rsfMRI) — SVM-based connectivity classifier on ADHD-200  

#### Electrophysiology (EEG/iEEG)  
- **Source-localized analysis** via LCMV beamforming  
- **Behavior-anchored epoching** using video pose estimation  
- **Debiased wPLI** for frequency-specific connectivity (beta band: 13–30 Hz)  
- Classification using **CSP**, **XGBoost**, and **MLPs**  

**Repositories**:  
- [`EEG-Neuro-Toolbox`](https://github.com/lacomaofficial/EEG-Neuro-Toolbox) — End-to-end EEG preprocessing, feature extraction, and ML  
- [`iEEG-MLP-Classifier`](https://github.com/lacomaofficial/iEEG-MLP-Classifier) — Epileptic event detection from intracranial EEG  

#### Network Neuroscience  
- Construction of **functional brain graphs** from fMRI connectivity matrices  
- Visualization of group-level differences (e.g., adult vs. child) using **Yeo-17 networks**  
- Integration with **Graph Neural Networks (GNNs)** for predictive modeling  

**Repositories**:  
- [`Graph-Neural-Networks`](https://github.com/lacomaofficial/Graph-Neural-Networks)  
- [`Pink_Crystal_Model`](https://github.com/lacomaofficial/Pink_Crystal_Model)  

---

### 3. **Open Educational Infrastructure**  
Graduate-level teaching materials for reproducible computational neuroscience. Designed for rapid adoption and pipeline extension.

- **DWI**: Tract-based feature engineering and ML-ready extraction  
- **EEG**: Source reconstruction tutorials and wPLI connectivity framework  
- **fMRI**: Classical (SVM, MLP) and deep learning (Transformer) examples  

**Repository**:  
- [`cimt-unia/neuro_ai`](https://github.com/cimt-unia/neuro_ai)

---

### 4. **Cross-Domain Validation**  
Testing neuro-inspired architectures in non-biological domains to assess robustness and generalization.

- **Equity regime detection** using 27 dimensionless macro features (debt cycles, inequality, market structure)—**no raw prices**  
- **Personality modeling** via the Five-Factor framework as a behavioral proxy  
- Shared backbone (>90%) between **BBTransformer** and **FinancialTransformer**

**Repositories**:  
- [`Hedge-Fund-Apps`](https://github.com/lacomaofficial/Hedge-Fund-Apps) 
- [`Five-Factor-Model-Test`](https://github.com/lacomaofficial/Five-Factor-Model-Test)

---

## Methodological Principles

| Principle | Rationale |
|---------|----------|
| **No dropout in embedding layers** | Preserves signal fidelity in low-SNR, high-dimensional regimes |
| **Per-series normalization** | Prevents data leakage; respects subject- or ticker-specific baselines |
| **Overlapping patch embeddings** (stride < patch size) | Captures local dynamics without temporal aliasing |
| **RMSNorm + SwiGLU + RoPE** | Enables stable training and strong empirical performance across modalities |
| **Permutation-based feature importance** | Provides reliable biomarker ranking; avoids attention map misinterpretation |
| **Cohort-stratified or walk-forward validation** | Eliminates optimistic bias in clinical and financial time series |

---

## Selected Technical Outputs

- **BBTransformer**: Six-layer dual-stream Transformer for Parkinson’s classification from rs-fMRI (414 regions, 150 timepoints). Achieved **95.2% accuracy**, **F1 = 95.2%**, **AUC = 0.958** on UK Biobank test set (n = 63).  
- **Behavior-Anchored EEG Pipeline**: Integrated video pose estimation, LCMV beamforming, and debiased wPLI to detect phase-dependent beta-band connectivity shifts in PUT-DP, NAc-shell, and aGP during motor transitions (|Cohen’s d| ≥ 0.8, *p* < 0.01).  
- **FinancialTransformer**: Equity regime predictor using theory-grounded macro features; validated via multi-window voting, walk-forward backtesting, and permutation importance—demonstrating cross-domain transfer of neuro-AI architecture.

---

## Availability

- **Code**: All repositories are public under permissive licenses.  
- **Models & Demos**: Shared via [Hugging Face](https://huggingface.co/lacomaofficial).  
- **Reproducibility**: Each project includes Jupyter notebooks, environment specs, and detailed READMEs.  
- **Collaboration**: Open to research partnerships in **computational psychiatry**, **digital biomarkers**, **robust time series foundations**, and **causal representation learning**.

[Personal Site](https://lacomaofficial.github.io) | [Hugging Face](https://huggingface.co/lacomaofficial)


