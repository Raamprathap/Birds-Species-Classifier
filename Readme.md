# 🦜 Bird Species Classifier

## 📌 Overview
The Bird Species Classifier is a deep learning-based web application that accurately identifies bird species from uploaded images using a custom-trained convolutional neural network (CNN). Simply upload a bird image, and the model will predict its species with high precision.

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

## 🔗 Pretrained Model Access
The pretrained model is available upon request for research and educational purposes. Please contact me via email for access:
- 📧 **Email:** [raamprathap17242@gmail.com](mailto:raamprathap17242@gmail.com)

## 📊 Model Performance
The model achieves:
- **Accuracy:** 94.8% on the validation dataset
- **Support:** 525 distinct bird species
- **Inference Time:** ~0.5 seconds per image

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
  🔗 LinkedIn: [Raam Prathap](https://linkedin.com/in/raam-prathap)

---

💡 *Built with passion by Raamp* 🚀
