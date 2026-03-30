# 🐱 vs 🐶 Cats vs. Dogs Image Classification

A deep learning project that classifies images of cats and dogs using convolutional neural networks (CNNs) with TensorFlow/Keras. Built and trained on Google Colab with GPU acceleration.

---

## 📊 Dataset

The model is trained on the **Cats and Dogs Dataset** from Kaggle.

- 🔗 [Dogs vs. Cats Dataset – Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)
- ~25,000 labeled images (cats and dogs)
- Split into training and validation sets for model evaluation

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed (or use Google Colab):

```bash
pip install tensorflow keras matplotlib opencv-python
```

### How to Run

1. **Open the notebook** – Load `cats_v_dogs_classification.ipynb` in [Google Colab](https://colab.research.google.com/).
2. **Download the dataset** – Get it from the [Kaggle link](https://www.kaggle.com/c/dogs-vs-cats/data) above.
3. **Upload the dataset** – Upload it to your Colab session storage or mount Google Drive.
4. **Run all cells** – Execute cells sequentially to:
   - Preprocess and augment the data
   - Build and compile the CNN model
   - Train the model
   - Evaluate and visualize results

---

## 🧬 Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Core programming language |
| **TensorFlow / Keras** | Model building and training |
| **Matplotlib** | Plotting training curves and predictions |
| **OpenCV** | Image loading and preprocessing |
| **Google Colab** | Cloud GPU environment for training |

---

## 🗂️ Project Structure

```
cats-vs-dogs-classification/
│
├── cats_v_dogs_classification.ipynb   # Main notebook
├── README.md                          # Project documentation
└── sample_predictions/                # (Optional) Sample output images
```

---

## 🧠 Model Overview

- **Architecture**: Convolutional Neural Network (CNN)
- **Input**: RGB images resized to a fixed dimension (e.g., 150×150)
- **Output**: Binary classification — Cat (0) or Dog (1)
- **Training**: Includes data augmentation to reduce overfitting
- **Evaluation**: Accuracy and loss curves plotted via Matplotlib

---

## 📈 Results

> Training and validation metrics are visualized within the notebook after model training completes.

---

## 🌐 Development Platform

This project was developed using **Google Colab** to leverage free GPU acceleration. All data handling was done directly within the Colab environment.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Kaggle – Dogs vs. Cats Competition](https://www.kaggle.com/c/dogs-vs-cats)
- TensorFlow and Keras documentation
- Google Colab for providing free GPU resources
