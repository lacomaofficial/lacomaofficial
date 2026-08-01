## About Me
[Personal Site](https://www.linkedin.com/in/jlacoma/) |  [Academia](https://github.com/cimt-unia) |  [Sound Cloud](https://soundcloud.com/jaylacoma)
- **Computational Neuroscience & Deep Learning Research**

<img width="356" height="446" alt="607856404-fa657070-b406-4795-aa80-fde4137c1be1" src="https://github.com/user-attachments/assets/915769d9-9b18-42ca-a2a5-01d9fb5c1014" />


<br>

My work lies at the intersection of neuroscience, data science, and machine learning, driven by the potential of these fields to unlock new insights into **complex nonlinear stochastic systems**.




<br>

# Research Portfolio



### 1. Academic Infrastructure  
Graduate-level teaching materials for reproducible computational neuroscience. Covers DWI, EEG, fMRI, LFP, and BCI.


**Repository**:  [`cimt-unia/neuro_ai`](https://github.com/cimt-unia/neuro_ai)


<br>

### 2. Packages/Libraries

#### Electrophysiology (EEG/iEEG)  
- **Preprocessing** · [`xeeg_kit`](https://github.com/cimt-unia/xeeg_kit)
> Multi-stage artifact removal for 280-channel EEG. Integrates MEEGKit (ASR + STAR + SNS) with ICLabel deep-learning component classification. Built for BEL EEG System One; compatible with any MNE-supported format. Includes parallel batch processing with per-subject logging.

- **Source Reconstruction** · [`lcmv_xtra`](https://github.com/cimt-unia/lcmv_xtra)
> LCMV beamforming pipeline on `fsaverage` space with automated BEL 280 coregistration. Extracts time courses from DiFuMo (512), Glasser+Tian (414), and CIMT Unified (448) atlases. Computes debiased WPLI connectivity across eight frequency bands. Fully self-contained, no manual downloads required.

- **Statistical Inference** · [`lcmv_stats`](https://github.com/cimt-unia/lcmv_stats)
> Statistical analysis companion to `lcmv_xtra`, optimized for the CIMT Unified Atlas (448 ROIs). Provides robust tools for group-level permutation tests, Generalized Partial Directed Coherence (GPDC) for directional connectivity, cluster-based time-frequency correction, and automated reporting.


#### Brain Imaging (fMRI)
- **Glasser-Tian Atlas** · [`gt_map`](https://github.com/cimt-unia/gt_map)
> TR-flexible Glasser+Tian parcellator combining 360 cortical and 54 subcortical regions. Resamples before standardizing to preserve signal integrity; no temporal filtering avoids `padlen` errors on short scans. Designed for multi-site studies (ABIDE, UK Biobank, ADHD-200). Atlases bundled, zero external downloads required.

- **CIMT Atlas** · [`cimt_atlas`](https://cimt-atlas-app.onrender.com/)
> Interactive 3D visualization of the CIMT 448-ROI Atlas. This application enables researchers to explore functional brain systems through a hierarchical cascade filter (System, Hemisphere, Sub-system), select regions of interest, and render them as interactive 3D meshes in the browser.


<br>

### 3. **Toolboxes**

- **Neuro-Toolbox** · [`Neuro-Toolbox`](https://github.com/lacomaofficial/Neuro-Toolbox)
> Curated tutorials, templates, and reusable frameworks for EEG signal processing, fMRI machine learning, and psychometric assessment. Includes preprocessing pipelines, SVM and transformer-based classification, PyTorch tutorials, and graph neural networks for brain connectivity.

- **Quant-Toolbox** · [`Quant-Toolbox`](https://github.com/lacomaofficial/Quant-Toolbox)
> Quantitative finance tools for market screening, technical analysis, and macro regime detection. Gradio apps for fundamental analysis, sentiment analysis, and economic cycle frameworks. Built with Yahoo Finance and Hugging Face models.

<br>



### 4. **Ongoing Research**
*Currently under embargo / in preparation for publication.*

- **Parkinson's Disease EEG:** Three complementary experiments (bimanual motor task, resting-state, intracranial LFP) validating LCMV source-localized EEG against gold-standard LFP STN recordings. Frequency-specific connectivity changes characterized across theta through high-gamma bands in motor-basal-executive networks.
- **BBT: Multivariate Time Series Transformer:** A foundation model for fMRI-based biomarker discovery trained on Glasser+Tian (414 ROI) parcellated time series. Uses rotary embeddings and grouped-query attention for diagnostic classification across ADHD, ASD, and UK Biobank cohorts. Features transfer learning, permutation-based interpretability, and single-subject diagnosis.

<br>

### 5. **Time Series Models**  
- [`Transformer-Time-Series-Model`](https://github.com/lacomaofficial/Transformer-Time-Series-Model) — Multivariate and univariate deep learning for time series forecasting.




<br>

## YC Hedge Fund
Independent quantitative research group applying AI to financial analysis and investing. Conducts macroeconomic, sectoral, and machine-learning–based market studies to identify inefficiencies and optimize portfolio strategies.

[Homepage](https://lacomaofficial.github.io) | [Data Analysis](https://huggingface.co/JayLacoma) | [Systems Theory](https://www.linkedin.com/pulse/chaos-markets-why-linear-thinking-fails-stochastic-system-fdnrf)

#### **Proprietary Models** *(private)*
- **Multivariate Time Series Classifier:** Binary classification of asset price movements using cross-asset relative value metrics and macro regime detectors. Paired with a structured analyst agent protocol for regime-aware signal interpretation.
- **Multivariate Time Series Regressor:** Probabilistic forecasting engine with quantile outputs and integrated geo/macro-economic regime detection.

