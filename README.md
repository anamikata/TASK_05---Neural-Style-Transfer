# PRODIGY_ML_05 - Neural Style Transfer

## 📌 Task Overview

This project implements **Neural Style Transfer (NST)** using TensorFlow and a pre-trained VGG19 Convolutional Neural Network. Neural Style Transfer is a deep learning technique that combines the content of one image with the artistic style of another image to generate a new stylized image.

**Internship:** ProDigy InfoTech
**Task Number:** 05
**Domain:** Machine Learning

---

## 🎯 Objective

Apply the artistic style of one image (such as a famous painting) to the content of another image while preserving the original structure and details of the content image.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* VGG19 (Pre-trained CNN)
* NumPy
* Matplotlib
* Pillow (PIL)
* Google Colab

---

## 📂 Project Structure

```
PRODIGY_ML_05_Neural_Style_Transfer/
│
├── Neural_Style_Transfer.ipynb
├── README.md
├── requirements.txt
│
└── images/
    ├── content.jpg
    ├── style.jpg
    └── output.jpg
```

---

## ⚙️ How It Works

1. Load a content image and a style image.
2. Use a pre-trained VGG19 model to extract image features.
3. Extract content features from the content image.
4. Extract style features from the style image using Gram Matrices.
5. Optimize a generated image to minimize:

   * Content Loss
   * Style Loss
6. Produce a final image that preserves the content while adopting the artistic style.

---

## 🚀 Installation

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib pillow
```

Or install using:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

1. Open the notebook in Google Colab.
2. Upload:

   * `content.jpg`
   * `style.jpg`
3. Run all notebook cells sequentially.
4. The model will generate a stylized image.
5. Download the generated `output.jpg`.

---

## 📊 Results

### Content Image

Place your content image in the `images` folder.

### Style Image

Place your style image in the `images` folder.

### Generated Output

The generated image combines:

* Content from the original image
* Style from the artistic image

---

## 📸 Sample Output

| Content Image | Style Image | Generated Output |
| ------------- | ----------- | ---------------- |
| content.jpg   | style.jpg   | output.jpg       |

---

## 🎓 Concepts Demonstrated

* Deep Learning
* Transfer Learning
* Computer Vision
* Feature Extraction
* Convolutional Neural Networks (CNN)
* Neural Style Transfer

---

## 📈 Future Improvements

* Support multiple style images
* Real-time style transfer
* Higher resolution image generation
* Custom style weight adjustment
* Web-based user interface

---

## 🏆 Internship Task

Successfully implemented Neural Style Transfer using TensorFlow and VGG19 to blend the content of one image with the artistic style of another image.

---

## 👩‍💻 Author

Anamika T A
AI Intern – ProDigy InfoTech
