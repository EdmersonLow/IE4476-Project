# 🌟 IE4476 Project: Dimensionality Reduction & Classification 🌟

Welcome to the **IE4476 Project**! This repository showcases the power of **Principal Component Analysis (PCA)**, **Linear Discriminant Analysis (LDA)**, and their combination (**PCA+LDA**) for dimensionality reduction and classification. We also implement **three classifiers** to evaluate the performance on image datasets.

---

## 🚀 Features of This Project
✨ **Dimensionality Reduction Techniques**  
- **PCA**: Captures maximum variance in the dataset.  
- **LDA**: Enhances class separability for supervised classification.  
- **PCA+LDA**: Combines PCA’s variance maximization and LDA’s class focus for optimal results.

🎯 **Classifiers**  
- **KNN**: A straightforward yet effective nearest-neighbor classifier.  
- **Mahalanobis Distance**: Excels in structured data with its sensitivity to data distribution.  
- **Linear SVM**: Robust linear boundary classification for high accuracy.

📈 **Performance Metrics & Visualizations**  
- Scree plots and cumulative variance to explain PCA dimensions.  
- Reconstructed images for visualizing the effect of dimensionality reduction.  
- Performance metrics for all techniques and classifiers.

---

## 🔧 How to Run the Project

### 📥 Step 1: Clone the Repository  
Clone the project repository:  
```bash
git clone https://github.com/EdmersonLow/IE4476-Project/
cd IE4476-Project
```

---

### 📂 Step 2: Set Up the Dataset  
This project uses the **Fashion-MNIST** dataset.  

1️⃣ **Use the Preloaded Dataset**  
   The dataset is included in the repository. Just run the project!  

2️⃣ **Switch to TensorFlow Keras Dataset**  
   Modify the dataset loading section in the script to:  
   ```python
   from tensorflow.keras.datasets import fashion_mnist
   (X_train, y_train), (X_test, y_test) = fashion_mnist.load_data()
   ```

3️⃣ **Bring Your Own Dataset**  
   Update the file paths to use any image dataset you prefer.  

---

### ▶️ Step 3: Run the Script  
Run the project in your Python environment (e.g., Jupyter Notebook, Google Colab).  

---

## 🎨 Cool Visualizations
✨ **Dimensionality Reduction Insights**  
- PCA variance analysis with scree and cumulative plots.  
- LDA component analysis for class-based separability.  

🖼 **Reconstructed Images**  
- Compare original and PCA-reconstructed images to understand the reduction's effect.  

📊 **Performance Comparisons**  
- Accuracy trends for PCA, LDA, and PCA+LDA across all classifiers.  

---

## 🔥 Highlights
🚀 **Flexible**: Modify paths to use any dataset with ease.  
📚 **Comprehensive**: Combines cutting-edge dimensionality reduction techniques with practical classifier evaluations.  
🎓 **Educational**: Perfect for learning and understanding PCA, LDA, and their real-world applications.

---

## ✨ Author  
👨‍💻 **Edmerson Low Soon Xiang**  
Feel free to explore, learn, and enjoy dimensionality reduction and classification with this project! 🌟  

💬 Reach out for feedback or collaboration opportunities. 😊  

Let’s classify smarter together! 🚀✨
