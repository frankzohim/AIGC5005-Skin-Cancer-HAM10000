# Skin Cancer Classification from Dermoscopic Images  
**AIGC 5005 – Final Project (Fall 2025)**  

Multi-class classification of 7 types of pigmented skin lesions using the HAM10000 dataset.

### Quick Links
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/frankzohim/AIGC5005-Skin-Cancer-HAM10000/blob/main/Skin_Cancer_HAM10000_Final.ipynb)

### Project Highlights
- Dataset: HAM10000 – 10,015 dermoscopic images (public, Harvard Dataverse)
- Classes: 7 highly imbalanced classes (melanoma, nevus, bcc, akiec, bkl, df, vasc)
- Model: EfficientNet-B3 (transfer learning) + data augmentation + class weighting
- Test Accuracy: 95.2% | Macro F1: 0.882 | Melanoma Recall: 0.91
- Interpretability: Grad-CAM heatmaps showing model focus on clinically relevant regions

### Repository Contents
- `Skin_Cancer_HAM10000_Final.ipynb` – Fully commented notebook with training, evaluation & Grad-CAM
- `proposal.pdf` – 1.5-page project proposal
- `final_report.pdf` – Complete 9-page report
- `requirements.txt` – All dependencies
- `data/` – Preprocessed & resized images (256×256, ~720 MB total)

### How to Run
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
pip install -r requirements.txt
jupyter notebook Skin_Cancer_HAM10000_Final.ipynb

**Team**  
• Franklin Fofe Zohim – n10000571  
• Nassor Mmanga Omar Dadi  – n01771186
