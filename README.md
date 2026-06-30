
# 🖼️ Image Captioning using CLIP

## Overview

**Image Captioning using CLIP (Sentence Transformers)**

This project demonstrates an image captioning and image-text similarity system using the **CLIP (Contrastive Language-Image Pretraining)** model from the **Sentence Transformers** library. The model encodes both images and text into a shared embedding space, compares their similarity, and predicts the most relevant caption from a predefined list.

### The notebook demonstrates how multimodal AI models can understand the relationship between images and text through similarity matching.

---

## Features

* Load and preprocess input images.
* Encode images using the CLIP model.
* Encode multiple candidate captions.
* Compute image-text similarity scores.
* Predict the caption with the highest similarity.
* Visualize the image along with the predicted caption.

---

## Technologies Used

* Python
* Jupyter Notebook
* Sentence Transformers
* CLIP (ViT-B-32)
* NumPy
* Pillow (PIL)
* Matplotlib

---

## Project Structure

```
Image-Captioning/
│
├── Image_Captioning.ipynb   # Main notebook
├── images/                  # Sample images (optional)
├── README.md                # Project documentation
└── requirements.txt         # Project dependencies (optional)
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Image-Captioning.git
cd Image-Captioning
```

Install the required packages:

```bash
pip install sentence-transformers pillow matplotlib numpy
```

---

## How to Run

1. Open `Image_Captioning.ipynb`.
2. Install the required dependencies.
3. Load an image.
4. Define a list of candidate captions.
5. Run all notebook cells.
6. View the predicted caption displayed with the image.

---

## How It Works

1. The CLIP model converts the input image into a feature embedding.
2. Candidate captions are converted into text embeddings.
3. Similarity scores between the image and each caption are computed.
4. The caption with the highest similarity score is selected as the prediction.

---

## Applications

* Image Retrieval
* Image Captioning
* Visual Search
* Content Recommendation
* Multimedia Understanding
* AI-powered Image Analysis

---

## Future Improvements

* Generate captions instead of selecting from predefined ones.
* Integrate BLIP or BLIP-2 for generative captioning.
* Build a web application using Streamlit or Flask.
* Support batch image captioning.
* Improve performance with larger datasets.

---

## Author

**Your Name**

GitHub: https://github.com/your-username

---

## License

This project is licensed under the MIT License.

