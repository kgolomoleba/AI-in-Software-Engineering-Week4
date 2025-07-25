# AI Tools Assignment Report  
## Mastering the AI Toolkit  

---

## Part 1: Theoretical Understanding  

### Q1: Primary Differences between TensorFlow and PyTorch  
- TensorFlow: Best for production deployment with static computational graphs; integrates well with mobile/edge devices (TensorFlow Lite).  
- PyTorch: More intuitive and Pythonic; uses dynamic graphs; preferred for research and experimentation.  
- **When to choose:** TensorFlow for scalable production systems; PyTorch for prototyping and academic research.

### Q2: Use Cases for Jupyter Notebooks  
- Interactive prototyping: Testing and visualizing ML models step-by-step.  
- Documentation and code: Combining explanations, code, and visualizations in a shareable format.

### Q3: How spaCy Enhances NLP  
- Provides pre-trained models for tokenization, POS tagging, Named Entity Recognition (NER), etc.  
- More advanced than basic Python string operations which are limited to simple text manipulations.

### Comparative Analysis: Scikit-learn vs TensorFlow  

| Feature            | Scikit-learn                             | TensorFlow                      |
|--------------------|----------------------------------------|--------------------------------|
| Target Applications | Classical ML (Decision Trees, SVM, etc.) | Deep Learning (CNNs, RNNs)       |
| Ease of Use        | Beginner-friendly                        | Steeper learning curve          |
| Community Support  | Large and well-documented                | Huge, especially in deep learning |

---

## Part 2: Practical Implementation  

### Task 1: Iris Classification with Decision Tree  
- **Goal:** Classify iris flowers into Setosa, Versicolor, Virginica.  
- **Process:** Loaded dataset, visualized features, trained decision tree, evaluated metrics.  
- **Result:** Achieved 100% accuracy, precision, and recall.  
- **Code & outputs:** Available in [Task 1 Notebook](YOUR_COLAB_LINK_HERE).

### Task 2: MNIST CNN Classification  
- **Goal:** Classify handwritten digits using a CNN.  
- **Process:** Built CNN architecture, trained for 3 epochs, evaluated accuracy.  
- **Result:** Achieved >95% test accuracy.  
- **Code & outputs:** Available in [Task 2 Notebook](YOUR_COLAB_LINK_HERE).

### Task 3: NLP with spaCy  
- **Goal:** Extract product names & brands, analyze sentiment in product reviews.  
- **Process:** Processed text with spaCy, extracted entities, applied rule-based sentiment scoring.  
- **Result:** Detected entities like Apple iPhone 14 (PRODUCT) and Amazon (ORG); sentiment identified as positive.  
- **Code & outputs:** Available in [Task 3 Notebook](YOUR_COLAB_LINK_HERE).

---

## Part 3: Ethical Reflection & Optimization  

- **Bias in Data:**  
  - MNIST dataset lacks handwriting diversity.  
  - Rule-based sentiment analysis can misinterpret sarcasm or slang.  

- **Mitigation Strategies:**  
  - Use larger, diverse datasets and data augmentation techniques.  
  - Apply TensorFlow Fairness Indicators for bias detection and correction.  
  - Employ advanced NLP models (e.g., BERT) for contextual understanding.  

- **Optimization:**  
  - CNN performance can be improved with hyperparameter tuning and dropout layers.  
  - Sentiment analysis can be enhanced by fine-tuning pre-trained sentiment models.

---

## Summary  

This assignment showcased:  
- Classical ML with decision trees on structured data.  
- Deep learning using CNN for image classification.  
- NLP techniques with spaCy for entity recognition and sentiment analysis.  

All code, outputs, and analyses are documented in linked notebooks. Ethical considerations and optimization suggestions were included.

---

## Author  
Kgololosego Moleba  
kgolomoleba@gmail.com  

---

## Submission Details  
- Notebooks: [Google Colab links for Tasks 1, 2, 3]  
- Report: This document  
- Repository README.md: Project overview and instructions  
