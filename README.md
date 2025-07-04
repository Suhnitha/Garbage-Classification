# Garbage Classification using Transfer Learning

This project uses deep learning and transfer learning techniques to classify waste images into categories such as plastic, paper, glass, metal, cardboard, and trash. The solution is built using EfficientNetV2B2 and deployed with an interactive Gradio interface for real-time predictions.

---

## 📁 Files in this Repository

- `Garbage_Classifier.ipynb` — Main notebook with code for training, evaluation, and Gradio deployment.
- `dataset/` — Sample training and validation dataset organized by class folders.
- `README.md` — This file, containing project details and instructions.

---

## 🧠 Technologies Used

- Python
- TensorFlow & Keras
- EfficientNetV2B2
- ImageDataGenerator
- Scikit-learn
- Matplotlib & Seaborn
- Gradio
- Google Colab

---

## 🚀 How to Run

1. Open the notebook `Garbage_Classifier.ipynb` in Google Colab or Jupyter Notebook.
2. Make sure the dataset is structured in the format:
cardboard/
glass/
metal/
paper/
plastic/
trash/
3. Run the cells to train the model.
4. Launch the Gradio interface to test real-time predictions.

---

## 📷 Sample Output

- Training accuracy/loss curves
 ![loss_curve](https://github.com/user-attachments/assets/21353aa6-e274-44c3-9748-6050e1cca2fc)

- Confusion matrix for evaluation
 ![confusion_matrix](https://github.com/user-attachments/assets/5378d01a-a406-4b83-ae9b-54d9d68aedb9)

- Live predictions via Gradio
 ![trash_pred](https://github.com/user-attachments/assets/ad8d57b7-2c8e-45d9-9a26-a0c65971b0c3)
 ![cardboard_pred](https://github.com/user-attachments/assets/aabe4d80-0691-4908-a94b-e1304dcdc331)

---

