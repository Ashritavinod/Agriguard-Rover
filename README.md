# 🌾 AgriGuard Rover: Paddy Disease Detection Using Deep Learning

**AgriGuard** is an AI-powered rover system designed to detect diseases in paddy crops using deep learning and a robust rocker-bogie suspension for seamless movement across muddy and uneven field terrain.

---

## 📊 Dataset: Paddy Doctor (Kaggle Competition)

- **Source**: [Paddy Doctor Dataset – Kaggle](https://www.kaggle.com/competitions/paddy-disease-classification/)
- **Description**: A comprehensive dataset of paddy leaf images categorized into multiple disease classes.
- **Classes**:
  - Bacterial leaf blight
  - Brown spot
  - Leaf smut
  - Hispa
  - Dead heart
  - Healthy
- **Size**: ~10,000+ high-resolution images with class labels.

---

## 🧠 Deep Learning Models Used

We trained and evaluated the following models for disease classification:

| Model       | Accuracy | Remarks                      |
|-------------|----------|------------------------------|
| DenseNet121 | **95%**  | ✅ Best-performing model     |
| ResNet50    | 92%      | Robust and reliable          |
| Xception    | 90%      | Lightweight alternative      |

> Final deployed model: **DenseNet121** for highest accuracy and balanced performance.

---

## 🤖 Hardware: Rocker-Bogie Rover

AgriGuard uses a **6-wheel rocker-bogie suspension system** to handle rugged field terrain:
- Smooth motion over bumps and ditches
- Excellent stability in muddy paddy fields
- Camera mounted on the body for real-time image capture

---

## ⚙️ System Architecture

1. **Navigation**: Rover moves autonomously through paddy fields
2. **Image Capture**: Camera collects leaf images from plants
3. **Inference**: DenseNet121 classifies leaf diseases in real-time
4. **Output**: Results displayed or logged for farmer action

---

## 🛠 Technologies Used

- **Dataset**: Paddy Doctor (Kaggle)
- **Deep Learning**: TensorFlow, Keras
- **Models**: DenseNet121, ResNet50, Xception
- **Hardware**: Rocker-bogie rover chassis, Raspberry Pi/Jetson Nano, camera module
- **Frameworks**: OpenCV, NumPy, Flask (for local dashboard)

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/agriguard-rover.git
   cd agriguard-rover
