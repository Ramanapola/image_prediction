# 🐶🐱 Cat vs Dog Image Classification using SVM

This project classifies images of **cats** and **dogs** using a **Support Vector Machine (SVM)** classifier in Python.  
Images are resized to 32x32, flattened into feature vectors, and then passed to the SVM model.

---

## 📂 Dataset Structure

Place your dataset like this:

```
dog and cat/
 ├── cats_set/
 │     ├── cat1.jpg
 │     ├── cat2.jpg
 │     └── ...
 └── dogs_set/
       ├── dog1.jpg
       ├── dog2.jpg
       └── ...
```

---

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 🚀 Steps Performed
1. Loaded cat & dog images from folders
2. Resized each image to **32×32**
3. Converted images to arrays and flattened
4. Assigned labels  
   - `0 = Cat`
   - `1 = Dog`
5. Split dataset into **Train** and **Test**
6. Trained **SVM Classifier**
7. Predicted results
8. Calculated accuracy
9. Plotted confusion matrix

---

## 📌 Model Performance
- ✔️ Accuracy Achieved: **~56%**
- ✔️ Confusion Matrix implemented

> Note: Accuracy is low because raw pixel flattening + SVM is not ideal. CNN will perform much better.

---

## 📷 Output Example
- Predicted Labels printed
- Confusion Matrix plotted

---

## ▶️ How to Run
```
pip install numpy opencv-python matplotlib scikit-learn
```

Run the script:
```
python your_file_name.py
```

---

## 📈 Possible Improvements
- Convert to grayscale / normalization
- Use Feature extraction (HOG, SIFT)
- Increase image size
- Train **CNN (Convolutional Neural Network)** for better accuracy

---

## 👨‍💻 Author
Ramana – Data Science Student  
📚 Learning ML & Projects

---

⭐ If you like this project, give it a star on GitHub!
