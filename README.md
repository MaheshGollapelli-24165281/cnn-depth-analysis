# CNN Depth Analysis: How CNN Depth Shapes Feature Learning

**Author:** Mahesh  
**Student ID:** 24165281  
**Module:** Machine Learning Tutorial Assignment  
**GitHub Repository:** https://github.com/MaheshGollapelli-24165281/cnn-depth-analysis  

---

##  Project Overview

This project investigates how the depth of Convolutional Neural Networks (CNNs) affects feature learning and classification performance using the CIFAR-10 dataset.

Three models are compared:

- Shallow CNN (2 layers)  
- Medium CNN (4 layers)  
- Deep CNN (6 layers)  

---

##  Tutorial Focus

> How does CNN depth affect feature learning and classification performance?

- Feature evolution across layers  
- Model performance differences  
- Trade-offs of deeper architectures  

---

##  Dataset

- CIFAR-10 dataset  
- 60,000 images (10 classes)  
- 32×32 resolution  
- Loaded via TensorFlow  

---

##  Results Summary

| Model        | Test Accuracy |
|--------------|--------------|
| Shallow CNN  | 68.7%        |
| Medium CNN   | 73.8%        |
| Deep CNN     | 74.0%        |

---

##  What This Project Demonstrates

- Training & validation curves  
- Accuracy comparison  
- Confusion matrix  
- Classification report  
- Feature map visualisation  

---

##  Repository Structure

- `cnn_depth_analysis_24165281.ipynb`  
- `CNN_Depth_Analysis_24165281.pdf`  
- `README.md`  
- `requirements.txt`  
- `LICENSE.txt`  
- `images/`  

---

##  How to Run

```bash
git clone https://github.com/MaheshGollapelli-24165281/cnn-depth-analysis.git
cd cnn-depth-analysis
pip install -r requirements.txt
jupyter notebook
```

Open:
```text
cnn_depth_analysis_24165281.ipynb
```

---

##  Runtime

- Few minutes training time  
- GPU recommended  

---

##  Accessibility

- Clear headings  
- Labelled plots  
- Explanations for visuals  
- Colour-blind friendly (`viridis`)  
- Simple language  
---

##  Ethical Considerations

- Dataset bias may exist  
- Some classes are harder to classify  
- Deep models use more resources  
- Responsible AI use is important 
---

##  References

- Goodfellow et al. (2016)  
- LeCun et al. (2015)  
- Krizhevsky (2009)  
- Simonyan & Zisserman (2015)  
- https://www.tensorflow.org  

---

##  Requirements

- TensorFlow  
- NumPy  
- Matplotlib  
- scikit-learn  

---

##  License

MIT License (see LICENSE.txt)

---

##  Summary

- CNN depth improves feature learning  
- Deeper models capture complex patterns  
- Gains reduce at higher depth  
