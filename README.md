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

