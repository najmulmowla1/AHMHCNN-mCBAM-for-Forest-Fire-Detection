# AHMHCNN-mCBAM-for-Forest-Fire-Detection

## HMHCNN-mCBAM: Hierarchical Multi-Head CNN with Modified CBAM for Visual Attention

This repository provides the implementation of **HMHCNN-mCBAM**, a novel deep learning architecture combining **Hierarchical Multi-Headed Convolutional Networks** with a **Modified Convolutional Block Attention Module (mCBAM)** for forest fire detection and classification. It is optimized for high-resolution aerial imagery tasks such as **forest fire detection** and **damage assessment**, delivering improved interpretability, accuracy, and computational efficiency.

---

## 🔍 Key Features

- 🧩 **Hierarchical Convolution**: Multi-scale feature encoding via grouped convolutions and resolution-aware pooling.
- 🧠 **Multi-Head CNN Backbone**: Parallel convolutional paths to learn diverse and rich spatial representations.
- 👁️‍🗨️ **Modified CBAM (mCBAM)**: Extended attention mechanism with channel & spatial gating and normalization enhancements.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `mcbam.py` | Implements the **Modified CBAM module** with enhanced spatial and channel attention mechanisms. |
| `ahmh.py` | Defines the **Adaptive Hierarchical Multi-Head Convolution layer** for dynamic feature extraction. |
| `HMHCNN-mCBAM.py` | Main file for assembling and compiling the full HMHCNN-mCBAM model architecture. |

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python ≥ 3.8
- TensorFlow ≥ 2.8
- NumPy

### 📦 Install Dependencies

```bash
pip install tensorflow numpy

## 🗃 Dataset

This model is benchmarked on the **UAVs-FFDB** dataset:

**Citation**:  
Mowla, M. N., Asadi, D., Tekeoglu, K. N., Masum, S., & Rabie, K. (2024).  
*UAVs-FFDB: A high-resolution dataset for advancing forest fire detection and monitoring using unmanned aerial vehicles (UAVs).*  
Data in Brief, 55, 110706.  
[https://doi.org/10.1016/j.dib.2024.110706](https://doi.org/10.1016/j.dib.2024.110706)

---

## 📚 Citation

If you use this code or model in your research, please cite:

> M. N. Mowla, D. Asadi, S. Masum and K. Rabie,  
> "Adaptive Hierarchical Multi-Headed Convolutional Neural Network With Modified Convolutional Block Attention for Aerial Forest Fire Detection,"  
> *IEEE Access*, vol. 13, pp. 3412–3433, 2025.  
> doi: [10.1109/ACCESS.2024.3524320](https://doi.org/10.1109/ACCESS.2024.3524320)

### 📑 BibTeX
```bibtex
@article{mowla2025adaptive,
  title={Adaptive Hierarchical Multi-Headed Convolutional Neural Network With Modified Convolutional Block Attention for Aerial Forest Fire Detection},
  author={Mowla, M. N. and Asadi, D. and Masum, S. and Rabie, K.},
  journal={IEEE Access},
  volume={13},
  pages={3412--3433},
  year={2025},
  doi={10.1109/ACCESS.2024.3524320}
}
