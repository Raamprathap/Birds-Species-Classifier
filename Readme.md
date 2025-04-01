# 🦜 Bird Species Classifier

## 📌 Overview
The Bird Species Classifier is a deep learning-based web application that classifies bird species from images using a trained convolutional neural network (CNN). Users can upload an image of a bird, and the model will predict its species.

## 🌐 Demo
Live Deployment: [Bird Species Classifier](https://birds-species-classifier.onrender.com)

## 📦 Dataset Structure
The dataset is organized into training, validation, and testing directories:

```
Birds/
├── train/
│   ├── ABBOTTS BABBLER/
│   ├── Species_name...
├── test/
│   ├── ABBOTTS BABBLER/
│   ├── Species_name...
├── valid/
│   ├── ABBOTTS BABBLER/
│   ├── Species_name...
```

## 🤖 Model Details
**Model Architecture:**

```
Model: "sequential"
┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┳━━━━━━━━━━━━━━━━━┓
┃ Layer (type)                         ┃ Output Shape                ┃         Param # ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━┩
│ conv2d (Conv2D)                      │ (None, 222, 222, 32)        │             896 │
│ max_pooling2d (MaxPooling2D)         │ (None, 111, 111, 32)        │               0 │
│ conv2d_1 (Conv2D)                    │ (None, 109, 109, 64)        │          18,496 │
│ max_pooling2d_1 (MaxPooling2D)       │ (None, 54, 54, 64)          │               0 │
│ conv2d_2 (Conv2D)                    │ (None, 52, 52, 128)         │          73,856 │
│ max_pooling2d_2 (MaxPooling2D)       │ (None, 26, 26, 128)         │               0 │
│ flatten (Flatten)                    │ (None, 86528)               │               0 │
│ dense (Dense)                        │ (None, 128)                 │      11,075,712 │
│ dense_1 (Dense)                      │ (None, 525)                 │          67,725 │
└──────────────────────────────────────┴─────────────────────────────┴─────────────────┘
 Total params: 11,236,687 (42.86 MB)
 Trainable params: 11,236,685 (42.86 MB)
 Non-trainable params: 0 (0.00 B)
```

## 📂 Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Flask (Python)
- **Machine Learning:** TensorFlow, Keras
- **Storage:** Google Drive (for model storage)
- **Deployment:** Render (for web hosting)

## 🔗 Model Download
[Download Pretrained Model](https://drive.google.com/uc?id=18ovFu6gIvn3mOyR83THrBlU_8YXFEaaq)

## 🚀 Training the Model
You can train the model from scratch or continue training an existing model.

### Train from Scratch
```python
python train_from_scratch.py
```

### Train Existing Model with More Epochs
```python
python train_existing_model.py
```

## ⭐ Contribute & Support
We welcome contributions! If you want to improve the project:
1. Fork the repository 🍴
2. Create a new branch 🔀
3. Make your changes ✏️
4. Submit a pull request 📬

💡 *Your contributions are highly appreciated!* 🚀

---

## 📞 Contact
- 👤 **Raam Prathap**  
  📧 Email: [raamprathap17242@gmail.com](mailto:raamprathap17242@gmail.com)  
  🔗 GitHub: [Raam Prathap](https://github.com/Raamprathap)  

---

💡 *Built with passion by Raamp* 🚀
