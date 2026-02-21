# 🇮🇳 BharatSpatialNet
### Multi-Modal Spatial Intelligence for Smart Urban Monitoring in India

![PyTorch](https://img.shields.io/badge/PyTorch-DeepLearning-red)
![Multi-Modal](https://img.shields.io/badge/Multi--Modal-Fusion-blue)
![Smart Cities](https://img.shields.io/badge/Smart-Cities-green)

---

## 🚀 Overview

BharatSpatialNet is a multi-modal deep learning framework that integrates:

- 🗺 Spatial grid representations (simulated satellite urban layout)
- 📡 IoT sensor signals (Traffic Density, AQI, Humidity, Temperature)

The model predicts **urban congestion risk** using attention-based feature fusion.

Inspired by real-world challenges in Indian metropolitan regions such as:
- Bengaluru (traffic congestion)
- Delhi (AQI variability)
- Mumbai (high-density planning)

---

## 🧠 Architecture

The system consists of:

1. CNN-based Spatial Encoder  
2. Sensor Feature Encoder (MLP)  
3. Attention-Based Fusion Layer  
4. Binary Risk Classification Head  

Multi-modal fusion allows adaptive weighting of heterogeneous data sources.

---

## 📊 Experimental Setup

- Optimizer: Adam
- Loss: CrossEntropyLoss
- Epochs: 8
- Evaluation Metric: Accuracy

Training demonstrates stable convergence and effective fusion learning.

---

## 🔬 Ablation Study

| Model Variant        | Description                     |
|----------------------|---------------------------------|
| Full Multi-Modal     | Spatial + Sensor Fusion         |
| Spatial Only         | CNN without sensor features     |
| Sensor Only          | MLP without spatial features    |

Results show improved performance when both modalities are fused.

---

## 🛠 Tech Stack

- Python 3.x
- PyTorch
- NumPy
- Matplotlib
- Google Colab

---

## 📁 Project Structure

```
BharatSpatialNet/
│
├── BharatSpatialNet_Colab.ipynb
├── bharat_spatial_model.pth
└── README.md
```

---

## 🔮 Future Improvements

- Real satellite imagery integration
- Temporal modeling (LSTM)
- REST API deployment
- Edge-device optimization
- Smart City API integration

---

## 👨‍💻 Author

AI/ML Engineer | India  
Specializing in Spatial Intelligence & Multi-Modal Learning
