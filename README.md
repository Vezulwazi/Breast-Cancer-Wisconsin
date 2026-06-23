# 🧬 Breast Cancer Wisconsin (Diagnostic) Classification

A beginner-level machine learning classification project that predicts whether a breast tumor is **malignant or benign** using cell nucleus measurements from fine-needle aspirate (FNA) samples.

---

## 📌 Problem Statement

Given 30 numerical features describing the size, shape, and texture of cell nuclei in an FNA sample, predict the diagnosis:

- **M = Malignant (1)**
- **B = Benign (0)**

---

## 📊 Dataset

- **Source:** UCI Breast Cancer Wisconsin (Diagnostic) Dataset  
- **Samples:** 569 patients  
  - 357 Benign  
  - 212 Malignant  
- **Features:** 30 numeric features + 1 target column  

### 🔬 Feature Groups

Each measurement includes:
- mean  
- standard error  
- worst (largest value)

Base features:
- radius  
- texture  
- perimeter  
- area  
- smoothness  
- compactness  
- concavity  
- concave points  
- symmetry  
- fractal dimension  

> The `id` column is dropped during preprocessing.  
> Target `diagnosis` is encoded as: **M → 1, B → 0**

---

## ⚙️ Project Structure
