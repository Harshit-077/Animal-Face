# Animal Image Classification using PyTorch

A deep learning project for multi-class dog breed classification built using **PyTorch**.  
This project includes training, validation, testing, and single-image inference.

---

## 🚀 Project Overview

This project implements a complete deep learning pipeline:

- 📦 Dataset loading with `DataLoader`
- 🧠 CNN-based model architecture
- ⚙️ Training using Adam optimizer
- 🛡️ Regularization using Weight Decay
- 📊 Validation monitoring per epoch
- 💾 Best model saving
- 🧪 Test evaluation
- 🔍 Single image inference

---

## 📊 Final Model Performance

| Metric | Value |
|--------|--------|
| Training Accuracy | **100.0%** |
| Validation Accuracy | **97.27%** |
| Generalization Gap | ~2.7% |

The model shows strong convergence and good generalization.

---


## 🧠 Model Architecture

The model consists of:

- Convolutional Layers
- ReLU Activation
- Pooling Layers
- Fully Connected Layers
- Dropout (if used)
- Final Classification Layer

### Training Configuration

- Optimizer: **Adam**
- Learning Rate: `1e-4`
- Weight Decay: Enabled (L2 Regularization)
- Loss Function: `CrossEntropyLoss`
- Proper `model.train()` and `model.eval()` usage

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install torch torchvision matplotlib
```
## 🧠 Key Learnings
#### Importance of model.train() and model.eval()
#### Effect of weight decay on overfitting
#### Proper metric averaging
#### Saving best validation model
#### Handling tensor shapes during inference
#### Adding batch dimension for single image prediction
## 🚀 Future Improvements
Add Learning Rate Scheduler<br>
Add Early Stopping<br>
Apply Data Augmentation<br>
Plot Confusion Matrix<br>
Compute Precision / Recall / F1-score<br>
Deploy using Streamlit or Flask<br>
## 🎯 Conclusion
 This project demonstrates a complete deep learning workflow:<br>
 Data Preparation<br>
 Model Training<br>
 Validation & Regularization<br>
 Testing<br>
 Inference Deployment<br>
Built using PyTorch with strong generalization performance.<br>
