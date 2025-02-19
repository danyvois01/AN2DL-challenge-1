# Blood Cell Classification

## Overview

This project tackles a **multi-class classification problem** involving **96x96 RGB images of blood cells**. The dataset consists of eight different cell types:

- **0**: Basophil
- **1**: Eosinophil
- **2**: Erythroblast
- **3**: Immature Granulocytes
- **4**: Lymphocyte
- **5**: Monocyte
- **6**: Neutrophil
- **7**: Platelet

We started with a simple **CNN from scratch** and progressively improved performance using **data augmentation, regularization, and transfer learning with fine-tuning**. Our final model, based on **ConvNeXtSmall**, achieved **97.66% validation accuracy**.

Key improvements include:

- **Data cleaning**: Removal of outliers.
- **Handling class imbalance**.
- **Advanced augmentation strategies**.
- **Fine-tuned pre-trained models**.

## Team

**LOS PINGUINOS**: Daniele Vozza, Francesco Tomasi, Zeno Peracchione, Lorenzo Galatea.

## How to Run

1. Install dependencies: `pip install -r requirements.txt`
2. Train the model: `python train.py`
3. Evaluate: `python evaluate.py`
4. Predict: `python predict.py --input images/test_sample.png`

## Acknowledgments

Thanks to **Politecnico di Milano** for providing the dataset and computing resources.

