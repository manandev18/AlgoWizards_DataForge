# 🎨 ArtIQ - Art Style Classification using Deep Learning

ArtIQ is a deep learning project that classifies artworks into different art styles based on visual features like strokes, colors, and composition patterns.  
The goal is to enable machines to recognize and understand artistic styles the way human experts do!

---

## 📚 Dataset
- **Source:** [WikiArt Dataset](https://www.kaggle.com/datasets/sivarazadi/wikiart-art-movementsstyles)
- **Total Images:** 42,500+
- **Number of Classes (Art Styles):** 13

Art Styles:
- Academic Art
- Art Nouveau
- Baroque
- Expressionism
- Japanese Art
- Neoclassicism
- Primitivism
- Realism
- Renaissance
- Rococo
- Romanticism
- Symbolism
- Western Medieval

---


## ⚙️ Model Architecture
- **Base Model:** ResNet18 (without pretrained weights)
- **Modified Final Layer:** 13 output neurons (one for each art style)
- **Optimizer:** Adam
- **Loss Function:** CrossEntropyLoss
- **Training Epochs:** 5 (can be increased for better performance)

---

## 🚀 How to Run
1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
