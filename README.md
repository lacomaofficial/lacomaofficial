# 👋 Hey! New here? I’m Jay

I'm a future computational neuroscientist focused on predicting and optimizing treatments for mental health conditions using advanced data analysis techniques. My work lies at the intersection of neuroscience, data science, and machine learning, and I'm driven by the potential of these fields to unlock new insights into brain function and health.

![pexels-caleb-oquendo-7388486-2368x1050](https://github.com/user-attachments/assets/729cdb51-c877-4042-b10e-127bbf706e98)

🔬 **Transformer-Based fMRI Analysis for Autism Prediction** 🧠  

I’ve been working on an app that applies a **Transformer-based fMRI encoder model** to predict autism from resting-state fMRI data. The model is trained on datasets like **ABIDE** and integrates **brain connectivity features with demographic data (age, gender)** for classification.  

### **How it works:**  
📡 **Input:** Preprocessed fMRI data (CPAC or similar), age, and gender.  
🔗 **Feature Extraction:** Computes functional connectivity matrices using Nilearn.  
🧠 **Model:** A transformer-based architecture processes the extracted features, leveraging **multi-head attention** and **learned embeddings** for age and gender.  
📊 **Output:** A probability score indicating the likelihood of autism, along with a visualization.  

The model was trained with:  
✔ **BCEWithLogitsLoss** (handling class imbalance)  
✔ **Ranger optimizer** (RAdam + Lookahead)  
✔ **Cosine Annealing LR scheduling**  
✔ **Pooling strategies** (mean, max, attention)  

🔗 **Try it out here:** [https://huggingface.co/spaces/JayLacoma/fMRI-ASD-Classifier](https://huggingface.co/spaces/JayLacoma/fMRI-ASD-Classifier)  









