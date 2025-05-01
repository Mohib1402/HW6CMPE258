# 🧠 Deep Learning Assignment 6: Training Neural Networks with Keras (Advanced)

This repository contains the implementation of Assignment 6 for CMPE-258: Deep Learning — focused on advanced training strategies using Keras, TensorFlow, and complementary libraries. The assignment was completed in two parts, across two Google Colab notebooks.

---

## 🔗 Notebooks

- 📘 [Part 1: Data Augmentation & Generalization](https://colab.research.google.com/drive/179yLwYnrpCyi6SdJ_rTiSuwfHYntQvnC?usp=sharing)
- 📙 [Part 2: Advanced Keras Constructs](https://colab.research.google.com/drive/1K2VJGdH19fwk3c4R_U40hndzGV76dZ9q?usp=sharing)
- 🎥 Video Walkthrough: [YouTube Link Placeholder](https://www.youtube.com/watch?v=XXXXXXXXXXX)

---

## 📦 Part 1: Data Augmentation and Generalization

This notebook demonstrates regularization and generalization strategies using Keras/TensorFlow and complementary tools.

### ✅ Techniques Covered:
- L1 and L2 Regularization
- Dropout, Monte Carlo Dropout
- EarlyStopping and TensorBoard Logging
- Initializer Comparison (Glorot, He, Random)
- Batch Normalization
- Custom Dropout and Regularizer
- Hyperparameter Tuning using Keras Tuner
- Image Augmentation using KerasCV
- **Multi-Modality Augmentation**:
  - 📷 Image: `keras_cv`, `imgaug`, `albumentations`
  - 📝 Text: `nlpaug` (WordNet, BERT-based)
  - 📼 Video: `moviepy`
  - 📊 Tabular: SMOTE, Noise Injection
  - 📈 Time Series: Jitter + Scale
  - 🎤 Audio: `librosa` pitch/time stretch
  - 📄 Document Images: Blur, Perspective via `albumentations`
- `fastai` Test-Time Augmentation (TTA)

---

## ⚙️ Part 2: Advanced Keras Constructs

This notebook explores low-level Keras functionality including custom training loops, layers, optimizers, and more.

### ✅ Features Demonstrated:
- Custom Learning Rate Scheduler (Cosine Decay)
- `MCAlphaDropout` Layer
- Custom Normalization: `MaxNormDense`
- Custom Regularizer, Constraint, Initializer, Activation
- TensorBoard Logging
- Custom Loss: Huber Loss
- Custom Metric: HuberMetric
- Custom Layers: `AddGaussianNoise`, `MyDense`
- Residual Model: `ResidualBlock` + `ResidualRegressor`
- Manual Momentum Optimizer
- Full Custom Training Loop using `GradientTape`

---

## 📁 Folder Structure Suggestion

