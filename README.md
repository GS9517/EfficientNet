# EfficientNet Aerial Landscape Classification

This project explores three variants of the EfficientNet model for classifying aerial landscapes. Each implementation varies in data augmentation strategies and training data balance:

1. **EfficientNet Only**  
   - *Colab Notebook*: [EfficientNet](https://colab.research.google.com/drive/1vb0Mf0KAx_fiG18x5mkMGxc-s8w4porl)

2. **EfficientNet with Data Augmentation**  
   - *Colab Notebook*: [EfficientNet_data_augmentation](https://colab.research.google.com/drive/1H3h1o_RVcPGgXxZJKOWYXItAemGnENAt)

3. **EfficientNet with Data Augmentation & Imbalanced Training Data**  
   - *Colab Notebook*: [EfficientNet_imbalanced_classification](https://colab.research.google.com/drive/16qRef_NmhOGHjToxiQYGk9IN3Pyf_TrO)

## Project Structure

- **efficientnet.py**  
  Implements the base EfficientNet architecture without additional data augmentation.

- **efficientnet_data_aug.py**  
  Enhances the EfficientNet model with a comprehensive data augmentation pipeline.

- **efficientnet_data_aug_imbalanced.py**  
  Extends the augmented model by introducing class imbalance in the training data to assess robustness.

## Requirements

- Python 3.7 or higher
- PyTorch 1.7.0 or higher & torchvision
- numpy 1.18 or higher
- matplotlib 3.1 or higher
- seaborn 0.11 or higher
- scikit-learn 0.24 or higher
- tqdm
- Pillow (PIL)
- kagglehub (for dataset download)
- Google Colab for cloud-based execution
