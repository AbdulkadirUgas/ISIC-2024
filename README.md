# Skin Lesion Image Analysis for Early Detection of Skin Cancer Using Deep Learning  

## Overview  
This project applies deep learning techniques for early detection of skin cancer using medical imaging. By leveraging CNN-based and transformer-based models, the study enhances skin lesion classification and improves diagnostic accuracy.  

## Features  
- **Pretrained Deep Learning Models**: Uses EfficientNet-B7 (CNN) and EVA-02 (Vision Transformer).  
- **Stacking Approach**: Combines CNN and Transformer outputs with patient metadata.  
- **Data Augmentation & Preprocessing**: Improves generalization and reduces overfitting.  
- **Tabular Feature Engineering**: Extracts meaningful features from patient data.  
- **ISIC 2018 & 2024 Dataset**: Utilizes real-world skin lesion images for model training.  

## Methodology  
1. **Data Preprocessing & Augmentation**  
   - Resizing images to 224x224  
   - Applying transformations (rotation, flipping, contrast adjustment)  
2. **Feature Extraction & Classification**  
   - EfficientNet-B7 extracts image features  
   - EVA-02 Transformer enhances recognition  
   - Gradient Boosted Decision Trees (GBDT) refine classification  
3. **Evaluation Metrics**  
   - Accuracy, Precision, Recall, F1-Score  

## Results  
The model demonstrated high accuracy in distinguishing between malignant and benign lesions, outperforming traditional diagnostic techniques.  
