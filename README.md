# 📚 Hybrid and Semi-Supervised Sentiment Analysis Techniques: Colab Implementations

## Overview

This repository contains the Colab-compatible implementations of three prominent papers in the field of sentiment analysis and semi-supervised text classification. Each notebook demonstrates a cutting-edge methodology using deep learning or hybrid models on movie review sentiment datasets (primarily IMDB). The implementations are fully executable in Google Colab and provide an educational and practical foundation for researchers and practitioners interested in text classification, NLP, and explainable AI.

## 📄 Papers & Implementations

| Paper Title                                                                                         | accurancy                                                  | Link |
|-----------------------------------------------------------------------------------------------------|---------------------------------------------------------------|---|
| **1. Adversarial Training Methods for Semi-Supervised Text Classification**                         |86%     | [Colab](https://colab.research.google.com/drive/1eZLPjSda1ujVfYsVTyo2uxR4AymdyAzv?usp=sharing) |
| **2. Revisiting LSTM Networks for Semi-Supervised Text Classification via Mixed Objective Function**| 84% | [Colab](https://colab.research.google.com/drive/1lAiESaxF4siCpikVXu2RAnXxAK6-TVoh?usp=sharing) |
| **3. Advancing Sentiment Analysis of IMDB Movie Reviews with a Hybrid Naive Bayes and LSTM Approach**| 84%  | [Colab](https://colab.research.google.com/drive/1t-7nc1XRNp57iZHrcIkIwVn0MUrqdjWq?usp=sharing) |
| **4. Towards a Seamless Integration of Word Senses into Downstream NLP Applications**| 52% | [Colab](https://colab.research.google.com/drive/1WJ1phfe0OrivlGI1DEKfPMOyxyec1hAR?usp=sharing) |
| **5. Recurrent Residual Learning for Sequence Classification**| 84%  | [Colab](https://colab.research.google.com/drive/1lV5D07UYc4JoBM8QBUjMaApP4xT1oYvh?usp=sharing) |
| **6. Semi-supervised Sequence Learning**| 85%  | [Colab](https://colab.research.google.com/drive/1En1T4jZ74Iz6ssKrQbUVfYymIGolZ8Wf?usp=sharing) |
| **7. Long-Short Transformer: Effficient Transformers for Language and Vision**| 83.9%  | [Colab](https://colab.research.google.com/drive/1LadMVPuWnBz3-suXomUmTiTc4GoPBaeQ?usp=sharing) |
| **8. Certified Robustness to Programmable Transformations in LSTMs**| 80%  | [Colab](https://colab.research.google.com/drive/1M_OeFti28bQsEdpqueXUfmENJpu0Xkvy?usp=sharing) |
| **9. Sparse Sinkhorn Attention**| 79%  | [Colab](https://colab.research.google.com/drive/1eONh7SISwNoY18V1HihPYZ5jDDE6Qm4S?usp=sharing) |

## 🔧 How to Run

These notebooks are designed for **Google Colab** with minimal setup required. Simply follow these steps for each notebook:

1. **Open in Colab**  
   Click on the notebook link or upload it to your Google Drive and open with Colab.

2. **Set Runtime**  
   - Navigate to `Runtime` > `Change runtime type`.
   - Set **Hardware Accelerator** to `GPU` and ensure `T4 GPU` is selected if available.

3. **Run All**  
   - Go to `Runtime` > `Run all`.
   - No additional installation or configuration is required unless prompted.

> 📝 All notebooks are self-contained and include code cells for data loading (IMDB or similar datasets), preprocessing, model definition, training, and evaluation.

## 📁 Dataset

### The Benchmark dataset cheosen to test the models is the [IMDB Movie Reviews Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).
The IMDb Movie Reviews dataset is a binary sentiment analysis dataset consisting of 50,000 reviews from the Internet Movie Database (IMDb) labeled as positive or negative. The dataset contains an even number of positive and negative reviews. Only highly polarizing reviews are considered. A negative review has a score ≤ 4 out of 10, and a positive review has a score ≥ 7 out of 10. No more than 30 reviews are included per movie. The dataset contains additional unlabeled data.

## 🧠 Topics Covered

- Semi-supervised Learning with Adversarial Regularization
- Cross-Entropy + Entropy Minimization Objectives
- Naive Bayes and LSTM Hybrid Architectures
- Sentiment Classification
- NLP Preprocessing Techniques
- Recurrent and Convolutional Neural Networks in Text

## 📜 License

This repository is intended for educational and academic use. For usage aligned with the original authors' rights and publication terms, refer to the official papers and citations provided in the notebooks.
