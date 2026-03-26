# CNN Depth Analysis: How CNN Depth Shapes Feature Learning

**Author:** Mahesh  
**Student ID:** 24165281  
**Module:** Machine Learning Tutorial Assignment  
**GitHub Repository:** https://github.com/YOUR-USERNAME/cnn-depth-analysis  

---

## Project Overview

This project investigates how the **depth of Convolutional Neural Networks (CNNs)** affects feature learning and classification performance using the **CIFAR-10 dataset**.

Three models with increasing depth are compared:

- **Shallow CNN** (2 convolutional layers)  
- **Medium CNN** (4 convolutional layers)  
- **Deep CNN** (6 convolutional layers)  

The aim is to understand how deeper networks learn more abstract representations and to explore the trade-offs between accuracy, computational cost, and overfitting.

---

## Tutorial Focus

> **How does CNN depth affect feature learning and classification performance?**

- How feature representations evolve across layers  
- How model performance changes with depth  
- Why deeper models are not always significantly better  

---

##  Dataset

- CIFAR-10 dataset (via TensorFlow)  
- 60,000 colour images  
- 10 classes  
- Image size: 32 × 32 pixels  
- No manual download required  

---

## 📊 Results Summary

| Model         | Test Accuracy |
|--------------|-------------|
| Shallow CNN  | 68.7%        |
| Medium CNN   | 73.8%        |
| Deep CNN     | 74.0%        |

### Key Findings

- Performance improves with depth  
- Largest gain: **shallow → medium**  
- Diminishing returns at higher depth  
- Deeper models learn more abstract features  

**Trade-offs:**

- Higher computation  
- Longer training  
- Overfitting risk  

---

##  What This Project Demonstrates

- Training & validation curves  
- Accuracy comparison  
- Confusion matrix  
- Classification report  
- Predictions  
- Feature maps  

---

## Repository Structure

notebook/        → Jupyter notebook (main code)  
report/          → Final PDF report  
images/          → Figures used in the report  
requirements.txt → Dependencies  
README.md        → Project description  
LICENSE          → Usage permissions  

---
---

##  How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/YOUR-USERNAME/cnn-depth-analysis.git
cd cnn-depth-analysis
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open the notebook
```text
mahesh_24165281.ipynb
```

### 5. Run all cells

- Training & validation curves  
- Accuracy comparison  
- Confusion matrix  
- Classification report  
- Sample predictions  
- Feature maps  

---

## ⏱ Runtime Notes

- Training may take a few minutes  
- GPU recommended  
- Fully reproducible (no manual setup needed)  

---

## Accessibility

- Clear headings  
- Labelled plots  
- Explanations for visuals  
- Colour-blind friendly (`viridis`)  
- Simple language  

---

## Ethical Considerations

- Dataset bias may exist  
- Some classes are harder to classify  
- Deep models use more resources  
- Responsible AI use is important  

---

## References

- Goodfellow et al. (2016) *Deep Learning*  
- LeCun et al. (2015) *Deep learning*  
- Krizhevsky (2009)  
- Simonyan & Zisserman (2015)  
- https://www.tensorflow.org  

---

## Requirements

- TensorFlow  
- NumPy  
- Matplotlib  
- scikit-learn  

---

##  License

MIT License — see `LICENSE.txt`

---

##  Final Summary

- CNN depth improves feature learning  
- Deeper models capture complex patterns  
- Gains reduce at higher depth  
- Balance accuracy vs cost  

---

