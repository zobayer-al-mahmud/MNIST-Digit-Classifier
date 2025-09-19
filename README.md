# 🖥️ MNIST Digit Classifier

This project implements a deep learning model to classify handwritten digits (0–9) from the **MNIST dataset** using TensorFlow/Keras.  
The model is trained on 60,000 images and tested on 10,000 images to achieve high accuracy in recognizing digits.

---

## 📌 Project Overview
- **Dataset:** MNIST (28x28 grayscale images of digits 0–9)  
- **Model:** Deep Neural Network with multiple hidden layers  
- **Techniques Used:**  
  - Data normalization  
  - Flattening images for Dense layers  
  - Batch Normalization  
  - Dropout (to reduce overfitting)  
- **Evaluation:** Accuracy and loss tracked over training/validation sets  
- **Visualization:** Training/validation accuracy and loss plotted over epochs  

---

## ⚙️ Technologies Used
- Python 🐍  
- TensorFlow / Keras 🤖  
- NumPy  
- Matplotlib  

---

## 📂 Project Structure
```

MNIST\_Digit\_Classifier/
│── MNIST\_Digit\_Classifier.ipynb   # Main Jupyter Notebook
│── README.md                      # Project documentation
│── requirements.txt               # Dependencies (optional)

````

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/username/repo-name.git
   cd repo-name
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

   *(or manually install TensorFlow, NumPy, Matplotlib)*
3. Open Jupyter Notebook and run:

   ```bash
   jupyter notebook MNIST_Digit_Classifier.ipynb
   ```

---

## 📊 Results

* Achieved **\~98% accuracy** on the test set
* Training and validation graphs show stable learning with reduced overfitting

*(Insert accuracy/loss plots here if available)*

---

## ✨ Future Improvements

* Use Convolutional Neural Networks (CNN) for higher accuracy
* Try data augmentation to make the model more robust
* Deploy the model using Flask/Streamlit

---

## 👨‍💻 Author

**Zobayer Al Mahmud**


