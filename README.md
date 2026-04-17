# EMOTION CLASSIFICATION USING MOBILE-NET_V3

---

## Dataset
RAF-DB DATASET: https://www.kaggle.com/datasets/shuvoalok/raf-db-dataset

---

## Device Specification
| Component | Specification |
| :--- | :--- |
| **Processor** | AMD Ryzen 5 5600XT |
| **GPU** | NVIDIA GeForce RTX 5060 8GB |
| **RAM** | 16 GB |
| **OS** | Windows 11 |
| **Python** | 3.13.13 |
| **CUDA Driver** | 13.2 (Runtime: 12.8) | 

---

## Installation

### 1. Clone repository
```bash
git clone https://github.com/achmadrzm/emotion_classification.git
```

```bash
cd emotion_classification
```

### 2. Create virtual environment
```bash
python -m venv emotion
```

### 3. Activate virtual environment
#### Windows:
```bash
emotion\Scripts\activate
```

#### Linux/MacOS:
```bash
source emotion/bin/activate
```

### 4. Install library
```bash
pip install -r requirements.txt
```

---

## Result

### Confusion Matrix
![Confusion Matrix](training_mobilenet\results\confusion_matrix.png)

### Training Plot
![Training Plot](training_mobilenet\results\training_plot.png)