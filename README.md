# 🎵 Semantic Sonifier — Machine Learning Experiments on Audio Semantics

This repository contains **Experiments 5 to 9** based on the *Semantic Sonifier* dataset.  
These experiments explore clustering, dimensionality reduction, sequence modeling, decision trees,  
and ensemble methods to analyze and classify sound semantics such as emotion, tempo, and pitch.

---

## 📊 Dataset

**Source:** Simulated Semantic Sonifier Dataset (or extracted audio features from emotion recordings)  
**File Used:** `semantic_sonifier.csv`

Contains audio-derived semantic attributes:

- `pitch_mean` – Average pitch (Hz)  
- `tempo_bpm` – Tempo in beats per minute  
- `energy` – Relative loudness/intensity  
- `spectral_centroid` – Frequency brightness  
- `zero_crossing_rate` – Signal sharpness  
- `emotion` – Target class (Happy, Sad, Angry, Calm)

---

## 🧪 Experiments Overview

### **Experiment 5 – Clustering (K-Means, Gaussian Mixture, Hierarchical)**
- **Goal:** Group audio samples based on sound features without using emotion labels.  
- **Algorithms:** `KMeans`, `GaussianMixture`, `AgglomerativeClustering`  
- **Visualization:** 2-D PCA cluster comparison.  
- 📎 https://colab.research.google.com/drive/1wl1A5V74_leA1cArg1FkaotJWXxP2A-Z?usp=sharing

---

### **Experiment 6 – Principal Component Analysis (PCA)**
- **Goal:** Reduce dimensionality and visualize the main sound-feature components.  
- **Output:** 2-D PCA scatter plot colored by emotion.  
- 📎https://colab.research.google.com/drive/1wl1A5V74_leA1cArg1FkaotJWXxP2A-Z?usp=sharing

---

### **Experiment 7 – Hidden Markov Model (HMM)**
- **Goal:** Model temporal sound transitions using pitch and energy features.  
- **Tool:** `hmmlearn GaussianHMM` with 4 hidden states.  
- **Output:** Hidden-state predictions and generated semantic-sound samples.  
- 📎 https://colab.research.google.com/drive/1wl1A5V74_leA1cArg1FkaotJWXxP2A-Z?usp=sharing

---

### **Experiment 8 – CART (Decision Tree Classification)**
- **Goal:** Predict emotion labels using a decision-tree classifier.  
- **Output:** Tree visualization and model accuracy score.  
- 📎 https://colab.research.google.com/drive/1wl1A5V74_leA1cArg1FkaotJWXxP2A-Z?usp=sharing

---

### **Experiment 9 – Ensemble Learning (Random Forest & AdaBoost)**
- **Goal:** Improve semantic-emotion classification through ensemble methods.  
- **Metrics:** Accuracy, Precision, Recall, F1-score.  
- 📎 https://colab.research.google.com/drive/1wl1A5V74_leA1cArg1FkaotJWXxP2A-Z?usp=sharing

---

## 🧰 Tools & Libraries Used
- **Python 3.10+**  
- **Google Colab**  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `hmmlearn`

---

## 📈 Expected Outcomes
- Discovering natural clusters of sound semantics.  
- Visualization of feature variance using PCA.  
- Temporal modeling of sound transitions via HMM.  
- Accurate and interpretable emotion classification using CART.  
- Improved generalization through Random Forest and AdaBoost.


---

## 🔗 Reference
Semantic Sonifier Dataset © 2025 (academic simulation or emotion audio features)
