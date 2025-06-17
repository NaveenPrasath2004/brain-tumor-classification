# Brain Tumor MRI Classification

This project uses a Convolutional Neural Network (CNN) to classify grayscale brain MRI images into four classes:
- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

It uses TensorFlow and Keras to train and evaluate the model, achieving high accuracy on the dataset.

---

## 📂 Dataset

**Source:** [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

- Total images: 7023
- Image type: Grayscale MRI scans
- Classes:
  - `glioma`
  - `meningioma`
  - `pituitary`
  - `no` (no tumor)

More details about the dataset can be found in `data/about_data.txt`.

---

## 🧠 Model Overview

- **Type:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow / Keras
- **Input Size:** 150×150 grayscale image
- **Output:** Softmax (4-class classification)
- **Accuracy Achieved:** ~88%

---

## 📁 Project Structure

<pre>
brain-tumor-classification/
├── README.md                  ← Project overview
├── requirements.txt           ← Required packages
├── notebook/
│   └── brain_tumor_cnn.ipynb  ← Your main Colab notebook
├── model/
│   └── brain_tumor_model.h5   ← Saved Keras model
├── data/
│   ├── sample_images/         ← (Optional) few sample MRI images
│   └── about_data.txt         ← Notes about dataset source and structure
</pre>

---

## 🧪 Predict Single Image

You can test individual MRI images using the trained model.  
Example prediction logic is included in the notebook (`brain_tumor_cnn.ipynb`) and can be ported to a script if needed.

---

## 🙏 Credits

- Dataset: Masoud Nickparvar on Kaggle  
- Project: Naveen Prasath K
