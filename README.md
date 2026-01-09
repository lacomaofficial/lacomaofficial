# Jay — Research Portfolio

I develop machine learning systems for high-dimensional dynamical data, with primary applications in **computational neuroscience** and secondary validation in **quantitative finance**. My work emphasizes architectural integrity, reproducible pipelines, and clinical interpretability.

All code is maintained as open scientific infrastructure. Repositories are organized by domain, methodology, and educational utility.

---

## Core Research Areas

### 1. Multivariate Time Series Modeling  
Design and evaluation of deep architectures for non-stationary, multichannel temporal data.  
- **Patch-based Transformers** with channel-independent or multi-scale embeddings  
- Temporal attention pooling, rotary positional encoding (RoPE), grouped-query attention (GQA)  
- Strict adherence to walk-forward validation and subject-wise data splits  
- Key repositories:  
  - [`Transformer-Time-Series-Model`](https://github.com/lacomaofficial/Transformer-Time-Series-Model)  
  - [`BB-Toolbox`](https://github.com/lacomaofficial/BB-Toolbox)  
  - [`Fin-Transformer`]([https://github.com/cimt-unia/neuro_ai](https://huggingface.co/spaces/JayLacoma/Trader_Technical_Indicators))

### 2. Computational Neuroscience & Clinical Biomarkers  
Machine learning applied to neuroimaging and electrophysiology for diagnostic and mechanistic insight.  
- Resting-state fMRI classification (Parkinson’s, ASD, ADHD) using region-level time series (414-parcel atlases)  
- Source-localized EEG/iEEG analysis with behavior-anchored epoching and debiased connectivity (wPLI)  
- Graph-based representations of functional networks  
- Key repositories:  
  - [`BB-Toolbox`](https://github.com/lacomaofficial/BB-Toolbox)  
  - [`ASD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ASD-Prediction-rsfMRI)  
  - [`ADHD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ADHD-Prediction-rsfMRI)  
  - [`iEEG-MLP-Classifier`](https://github.com/lacomaofficial/iEEG-MLP-Classifier)  
  - [`Graph-Neural-Networks`](https://github.com/lacomaofficial/Graph-Neural-Networks)  
  - [`Pink_Crystal_Model`](https://github.com/lacomaofficial/Pink_Crystal_Model) (visualization of feature importance)

### 3. Open Educational Infrastructure  
Publicly available teaching materials for graduate-level computational neuroscience.  
- Modular, copy-ready workflows for DWI, EEG, and fMRI  
- End-to-end pipelines: preprocessing → feature extraction → modeling → interpretation  
- Repository: [`cimt-unia/neuro_ai`](https://github.com/cimt-unia/neuro_ai)

### 4. Cross-Domain Validation  
Testing neuro-inspired architectures in non-biological domains to assess generalization.  
- Equity regime detection using macroeconomic and structural features (no raw prices)  
- Personality modeling via the Five-Factor framework as a proxy for behavioral phenotyping  
- Key repositories:  
  - [`Hedge-Fund-Apps`](https://github.com/lacomaofficial/Hedge-Fund-Apps)  
  - [`Five-Factor-Model-Test`](https://github.com/lacomaofficial/Five-Factor-Model-Test)

---

## Methodological Principles

| Principle | Rationale |
|---------|----------|
| **No dropout in embedding layers** | Preserves signal fidelity in low-SNR, high-dimensional settings |
| **Per-series normalization** | Prevents leakage; respects subject- or ticker-specific baselines |
| **Overlapping patch embeddings** (stride < patch size) | Captures local dynamics without temporal aliasing |
| **RMSNorm + SwiGLU + RoPE** | Stable optimization and strong empirical performance across modalities |
| **Permutation-based feature importance** | Preferred over attention weights for biomarker discovery |
| **Cohort-stratified or walk-forward validation** | Avoids optimistic bias in temporal or clinical data |

---

## Selected Technical Outputs

- **BBTransformer**: 6-layer Transformer for Parkinson’s disease classification from rs-fMRI (414 regions, 150 timepoints). Achieved **95.2% accuracy**, AUC = 0.958 on UK Biobank test set.  
- **Behavior-Anchored EEG Pipeline**: Integrated video pose estimation, LCMV beamforming, and debiased wPLI to detect phase-dependent connectivity shifts in basal ganglia during motor transitions.  
- **Fin-Transformer**: Demonstrated transfer of neuro-AI architecture to equity forecasting using 27 theory-grounded macro features; validated via multi-window voting and backtesting.

---

## Availability

- **Code**: All repositories are public under permissive licenses unless otherwise noted.  
- **Models**: Shared via [Hugging Face](https://huggingface.co/lacomaofficial).  
- **Documentation**: Project-specific READMEs and Jupyter notebooks provide full reproducibility.  
- **Collaboration**: Open to research partnerships in computational psychiatry, digital biomarkers, robust time series foundations, and causal representation learning.

[Personal Site](https://lacomaofficial.github.io) | [Hugging Face](https://huggingface.co/lacomaofficial)
