
# 🧬 Chaos Game Representation (CGR) for Biological Sequence Comparison

This project focuses on comparing DNA sequences using Chaos Game Representation (CGR) and Frequency CGR (FCGR), enabling alignment-free and visually intuitive comparison of genetic patterns. Machine learning models are applied to classify sequences based on features extracted from CGR images.

---

## 🔬 Project Overview

- Converts DNA sequences into 2D CGR and FCGR images.
- Extracts features using Histogram of Oriented Gradients (HOG).
- Uses ML models to classify sequences into species or families.
- Visualizes similarity through hierarchical clustering (dendrograms).
- Supports sequence analysis for evolutionary insights.

---

## 🚀 Features

- Alignment-free method for sequence comparison
- Image-based representation of DNA structure
- Feature extraction using HOG
- ML classification using SVM, Random Forest, and KNN
- Hierarchical clustering of similar sequences

---

## 🧪 Techniques Used

| Step | Technique | Purpose |
|------|-----------|---------|
| Sequence Encoding | CGR / FCGR | Represent DNA sequences visually |
| Feature Extraction | HOG | Capture texture/patterns from CGR images |
| Classification | SVM, Random Forest, KNN | Classify sequences based on features |
| Clustering | Dendrograms | Group sequences based on similarity |

---

## 🧬 Workflow

1. **Preprocessing**: Clean and normalize DNA sequences.
2. **CGR Generation**: Generate CGR/FCGR plots from sequences.
3. **Feature Extraction**: Use HOG to extract visual patterns.
4. **Model Training**: Train ML classifiers using extracted features.
5. **Evaluation**: Measure accuracy, precision, and recall.
6. **Clustering**: Create dendrograms to visualize sequence relationships.

---

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/cgr-sequence-comparison.git
cd cgr-sequence-comparison
```

2. Create a virtual environment and install dependencies:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

---

## 📊 Results

- CGR and FCGR effectively capture sequence-specific patterns
- HOG features led to accurate classification (>90% in test cases)
- Dendrograms show clear clustering among species or families

---

## 📚 Future Work

- Test on longer genome sequences (whole genomes)
- Integrate deep learning for automated feature learning
- Compare with alignment-based methods like BLAST

---

## 🙌 Acknowledgements

- DNA datasets from NCBI and public repositories
- Inspired by research on image-based genomic analysis
- Guided by academic project requirements

---
⭐ *If this project helped you, consider giving it a star!*
