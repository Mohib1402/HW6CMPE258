# 🧠 Deep Learning Assignment 6: Training Neural Networks with Keras (Advanced)

This repository contains the implementation of Assignment 6 for **CMPE-258: Deep Learning** at San Jose State University. The assignment explores advanced training strategies in Keras/TensorFlow, including data augmentation, regularization, hyperparameter tuning, and custom training loop components.

---

## 🔗 Notebooks

- 📘 [Part 1: Data Augmentation & Generalization](https://colab.research.google.com/drive/179yLwYnrpCyi6SdJ_rTiSuwfHYntQvnC?usp=sharing)
- 📙 [Part 2: Advanced Keras Constructs](https://colab.research.google.com/drive/1K2VJGdH19fwk3c4R_U40hndzGV76dZ9q?usp=sharing)
- 🎥 Video Walkthrough: [Demo](https://drive.google.com/file/d/1vZ7TY6_bU-eAk1z01y4BL25XuWoZ5s1p/view?usp=sharing)

---

## 📦 Part 1: Data Augmentation & Generalization

This notebook demonstrates various techniques to improve generalization and model robustness through regularization and data augmentation.

### ✅ Topics Covered:
- **Regularization**:
  - L1, L2 Regularization
  - Dropout and Monte Carlo Dropout
  - Batch Normalization
  - EarlyStopping
- **Hyperparameter Tuning**:
  - `Keras Tuner` with Hyperband
- **TensorBoard**:
  - Integrated for training visualization
- **Initializations**:
  - Glorot, He, Random
- **Custom Regularization**:
  - LoggingDropout and custom L1

### 🧪 Multi-Modality Augmentation (Section k):
- 📷 **Image**: `keras_cv`, `imgaug`, `albumentations`
- 📝 **Text**: `nlpaug` with WordNet and BERT-based augmentation
- 📼 **Video**: `moviepy` used to apply effects on video
- 📊 **Tabular**: SMOTE balancing and Gaussian noise injection
- 📈 **Time Series**: Jittering and scaling applied to synthetic sine wave
- 🎤 **Speech**: Pitch shift and time stretch using `librosa`
- 📄 **Document Images**: Blurring, rotation, noise with `albumentations`

### 🔁 fastai Augmentations (Section l):
- `aug_transforms()` on MNIST sample
- `learn.tta()` for test-time augmentation
- Accuracy evaluation on augmented predictions

---

## ⚙️ Part 2: Advanced Keras Constructs

This notebook demonstrates advanced model training customization using low-level APIs and custom class implementations.

### ✅ Key Features:
- **Custom Learning Rate Scheduler** (Cosine Decay Callback)
- **Custom Dropout**: `MCAlphaDropout`
- **Custom Normalization**: `MaxNormDense`
- **Custom Loss**: `HuberLoss`
- **Custom Metric**: `HuberMetric`
- **Custom Layers**:
  - `MyDense` with max norm
  - `AddGaussianNoise`
- **Custom Model**:
  - `ResidualBlock` and `ResidualRegressor`
- **Custom Initializer, Activation, Regularizer, Constraint**:
  - `my_glorot_initializer`, `leaky_relu`, `MyL1Regularizer`, `MyPositiveWeights`
- **Manual Optimizer Logic**:
  - Momentum updates without subclassing
- **Custom Training Loop**:
  - Using `GradientTape` on Fashion MNIST with manual updates

---

## 📝 How to Run

1. Open each Colab notebook via the links above
2. Follow the cells top-to-bottom
3. Upload media files (e.g., audio, video, documents) when prompted
4. View visualizations and results in each section
5. Add your walkthrough video to YouTube and update the link

---

