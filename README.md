
# Skin Cancer Detection using Deep Learning

## Project Overview
This project develops a deep learning model for automated classification of dermatoscopic images into seven types of skin lesions using the HAM10000 dataset. The implementation uses transfer learning with ResNet50 and addresses class imbalance through strategic techniques.

## Project Structure
skin-cancer-detection/
├── Datasets/
│ └── HAM10000_images_full/ # Dermatoscopic images
├── HAM10000_metadata.tsv # Dataset metadata
├── skin_cancer_detection.ipynb # Main project notebook
├── pyproject.toml # Poetry dependencies
└── README.md


## Dataset
The HAM10000 ("Human Against Machine with 10000 training images") dataset contains 10,015 dermatoscopic images classified into 7 categories:
- akiec: Actinic keratoses and intraepithelial carcinoma
- bcc: Basal cell carcinoma  
- bkl: Benign keratosis-like lesions
- df: Dermatofibroma
- mel: Melanoma
- nv: Melanocytic nevi
- vasc: Vascular lesions

## Dependencies
This project uses **Poetry** for dependency management. Key dependencies include:
- TensorFlow 2.x
- scikit-learn
- pandas
- matplotlib
- seaborn
- Pillow

## Installation
```bash
# Clone repository
git clone [repository-url]
cd skin-cancer-detection

# Install dependencies using Poetry
poetry install

# Activate virtual environment
poetry shell