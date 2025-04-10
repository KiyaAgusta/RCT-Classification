# Randomized Controlled Trials Classification

This repository was developed by **I Made Akira Ivandio Agusta (15406525),** Coventry University.

The **Randomized Controlled Trials Identification** notebook introduces an enhanced hierarchical model for RCT classification that combines PubMedBERT with convolutional neural networks, focal loss, and data augmentation.

The notebook cannot be previewed in GitHub due to the "loading" visualization within the notebook. If you want to see the **notebook preview**, you can access this [Google Colab Link](https://colab.research.google.com/drive/1Yhe6hl8rvtoCGjhvIJM9l8Wt4JM54WuI?usp=share_link).

The experiments are conducted on the **Bat4RCT** dataset. To run this notebook, you need to download the data from this [link](https://github.com/jennak22/Bat4RCT/blob/main/rct_data.zip), extract the zip file, and store it in the following path: **data/rct_data.txt**.

The resulting figures from the notebook are stored in the **figures** directory. The results demonstrated that the **enhanced PubMedBERT** achieves 89.69% precision and 87.00% recall (F1: 88.32%), compared to 86.41% precision and 89.00% recall (F1: 87.68%) for vanilla PubMedBERT.
