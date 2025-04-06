# Fish Species Detection Under Low Light

## 📌 Summary
An advanced computer vision project developed as part of my Master's thesis, focused on detecting and classifying fish species in low-light underwater environments. The project combines traditional image processing, deep learning, and a **custom hybrid technique using Template Matching + CNNs**.

## 🛠 Tools Used
- Python
- OpenCV
- Keras / TensorFlow
- Scikit-learn
- NumPy, Matplotlib

## 📈 Approach
- Enhanced low-light underwater images using:
  - Histogram Equalization
  - CLAHE (Contrast Limited Adaptive Histogram Equalization)
  - Noise reduction and edge enhancement
- Developed and compared multiple models:
  - Classical ML: SVM, Logistic Regression, Random Forest
  - Deep Learning: CNNs with custom architectures
- **Invented and implemented a hybrid Template Matching + CNN pipeline**
  - Template Matching used for initial localization
  - CNN used for robust species classification
- Addressed data imbalance via augmentation (flip, rotation, brightness shift)

## ✅ Results
- Classification accuracy exceeded **90%** under various light/distortion conditions
- Hybrid method improved classification precision compared to baseline CNN
- Demonstrated robustness on real-world underwater datasets

## 🚀 Key Innovations
- **Custom-designed technique combining Template Matching with CNN confidence scores**
- Tuned for scenarios with low visibility, noise, and poor contrast
- Balanced performance between detection speed and classification accuracy

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
- Cross-validation and test set generalization performance

## 🧠 Skills Demonstrated
- End-to-end CV pipeline design
- Deep learning model design and training
- Image preprocessing under real-world conditions
- Inventing and validating novel methods

