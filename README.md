# Research Portfolio

My work focuses on **complex nonlinear stochastic systems**  designing architectures that uncover latent regime dynamics in high-dimensional, non-stationary time series—whether in fMRI connectivity, intracranial electrophysiology, or macro-driven financial markets.

As founder of **[YC Hedge Fund](https://www.linkedin.com/company/yc-hedge-fund/ )**—an independent quantitative research entity—I develop AI-driven models for financial analysis that prioritize **theoretical grounding**, **robust validation**, and **architectural reuse across domains**. 



## Core Research Areas

### 1. **Multivariate Time Series Modeling**  
Design and evaluation of deep architectures for non-stationary, multichannel temporal sequences.  
- **Patch-based Transformers** with channel-independent or multi-scale embeddings  
- Architectural primitives: **RoPE**, **Grouped-Query Attention (GQA)**, **SwiGLU**, **RMSNorm**  
- **Temporal attention pooling**, overlapping patches (stride < patch size)  
- Validation via **walk-forward splits**, **subject-wise partitioning**, and **permutation testing**  

**Key repositories**:  
- [`Transformer-Time-Series-Model`](https://github.com/lacomaofficial/Transformer-Time-Series-Model) — Univariate and multivariate forecasting with ProbSparse Attention and PatchTST  
- [`Hedge-Fund-Apps`](https://github.com/lacomaofficial/Hedge-Fund-Apps) — Financial regime detection using macro features (no raw prices); shares backbone with neuro-AI models  



### 2. **Computational Neuroscience & Clinical Biomarkers**  
Machine learning applied to multimodal neural data for diagnostic stratification and mechanistic insight.

#### fMRI-Based Classification  
- Resting-state fMRI analysis using **414-region parcellations** (HCP-MMP + Tian subcortical)  
- Transformer and classical ML models for **Parkinson’s**, **ASD**, and **ADHD**  
- Feature importance via **permutation ranking**, not attention maps  

**Repositories**:  
- [`BB-Toolbox`](https://github.com/lacomaofficial/BB-Toolbox) — Parkinson’s classification (95.2% accuracy, AUC = 0.958) on UK Biobank  
- [`ASD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ASD-Prediction-rsfMRI) — Identifies Callosomarginal Sulcus–Lingual Gyrus dysconnectivity  
- [`ADHD-Prediction-rsfMRI`](https://github.com/lacomaofficial/ADHD-Prediction-rsfMRI) — SVM classifier on ADHD-200 connectivity data  
- [`Regression-Model-to-Predict-Age-rsfMRI`](https://github.com/lacomaofficial/Regression-Model-to-Predict-Age-rsfMRI) — Brain-age estimation as a proxy for neural health  

#### Electrophysiology (EEG/iEEG)  
- **Source-localized analysis** via LCMV beamforming  
- **Behavior-anchored epoching** using video pose estimation  
- **Debiased wPLI** for frequency-specific connectivity (beta band: 13–30 Hz)  
- Classification using **CSP**, **XGBoost**, and **MLPs**  

**Repositories**:  
- [`EEG-Neuro-Toolbox`](https://github.com/lacomaofficial/EEG-Neuro-Toolbox) — End-to-end EEG preprocessing, feature extraction, and ML  
- [`iEEG-MLP-Classifier`](https://github.com/lacomaofficial/iEEG-MLP-Classifier) — Epileptic event detection from intracranial EEG  

#### Network Neuroscience & Visualization  
- Construction of **functional brain graphs** from fMRI  
- Interactive 3D visualization of feature importance  

**Repositories**:  
- [`Graph-Neural-Networks`](https://github.com/lacomaofficial/Graph-Neural-Networks) — GNN-ready brain graphs from connectivity matrices  
- [`Pink_Crystal_Model`](https://github.com/lacomaofficial/Pink_Crystal_Model) — Web-based 3D brain visualization  



### 3. **Open Educational Infrastructure**  
Graduate-level teaching materials for reproducible computational neuroscience.

- **DWI**: Tract-based feature engineering  
- **EEG**: Source reconstruction and wPLI connectivity  
- **fMRI**: Classical (SVM, MLP) and deep learning (Transformer) examples  

**Repository**:  
- [`cimt-unia/neuro_ai`](https://github.com/cimt-unia/neuro_ai)

Additional pedagogical projects (e.g., `Data-Science-Toolbox`, `XGBoost-HousePrice-Regressor`) serve as entry points for students but are not central to my research program.



### 4. **Foundational & Exploratory Work**  
Early-stage or methodological experiments that inform core research:
- [`Comp-Neuro-Toolbox`](https://github.com/lacomaofficial/Comp-Neuro-Toolbox) — Baseline neuroimaging pipelines  
- [`Pytorch-Classifier-fMRI`](https://github.com/lacomaofficial/Pytorch-Classifier-fMRI), [`Transformer-fMRI-Model`](https://github.com/lacomaofficial/Transformer-fMRI-Model) — Architecture ablation studies  
- [`timesfm`](https://github.com/lacomaofficial/timesfm) — Evaluation of pretrained time series foundation models  





## Availability

- **Code**: All repositories are public under permissive licenses.  
- **Models & Demos**: Shared via [Hugging Face](https://huggingface.co/JayLacoma).  
- **Reproducibility**: Each project includes Jupyter notebooks, environment specs, and detailed READMEs.  
- **Collaboration**: Open to research partnerships in **computational psychiatry**, **digital biomarkers**, **robust time series foundations**, and **causal representation learning**.

[Personal Site](https://lacomaofficial.github.io) | [Hugging Face](https://huggingface.co/JayLacoma)  

