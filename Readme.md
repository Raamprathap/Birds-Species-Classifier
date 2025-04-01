# 🐦 Bird Species Classifier

## 🌐 Live Demo
🔗 [Bird Species Classifier](https://birds-species-classifier.onrender.com)

## 📜 About the Project
The **Bird Species Classifier** is a deep learning-based web application that identifies bird species from images. The model is trained using Convolutional Neural Networks (CNNs) and deployed on a web platform for easy access.

## 📂 Model Details
The classification model is a **sequential CNN** with multiple convolutional and pooling layers to extract features from bird images.

### 📥 Download the Model
🔗 [Bird Species Classifier Model](https://drive.google.com/uc?id=18ovFu6gIvn3mOyR83THrBlU_8YXFEaaq)

### 📊 Model Architecture

| Layer (Type)                 | Output Shape          | Param #      |
|------------------------------|----------------------|-------------|
| conv2d (Conv2D)              | (None, 222, 222, 32) | 896         |
| max_pooling2d (MaxPooling2D)  | (None, 111, 111, 32) | 0           |
| conv2d_1 (Conv2D)            | (None, 109, 109, 64) | 18,496      |
| max_pooling2d_1 (MaxPooling2D) | (None, 54, 54, 64)  | 0           |
| conv2d_2 (Conv2D)            | (None, 52, 52, 128) | 73,856      |
| max_pooling2d_2 (MaxPooling2D) | (None, 26, 26, 128) | 0           |
| flatten (Flatten)            | (None, 86528)       | 0           |
| dense (Dense)                | (None, 128)         | 11,075,712  |
| dense_1 (Dense)              | (None, 525)         | 67,725      |

**Total Parameters:** 11,236,687 (42.86 MB)

## 🛠️ Installation & Setup
1. **Clone the repository:**
   ```sh
   git clone https://github.com/Raamprathap/birds-species-classifier.git
   cd birds-species-classifier
   ```
2. **Install dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
3. **Run the application:**
   ```sh
   python app.py
   ```
4. **Access the application:** Open `http://localhost:5000` in your browser.

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
