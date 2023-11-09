# CVTrack-Tutorials
ETRI SW-SoC CV Track Tutorials

---
**테크닉**
  - Data preprocessing and EDA
      - class distribution
      - handle class imbalance
          - over sampling, under sampling
      - fill missing values
      - normalization
  - **Data Augmentation**
      - **Albumentations**
        [Albumentations](https://albumentations.ai/)
      - **soft augmentation**
          - **Brightness,…**
          - **Flip,…**
      - **hard augmentation**
          - **CutOut**
          - **CutMix**
          - **Mixup**
          - **Random Erasing**,…
  - Good base model
      - Papers with Code - SOTA
        [Papers with Code](https://paperswithcode.com/)
      - OpenMMLab, PaddlePaddle, Detectron,…
      - **to improve model capacity…**
      - CNN vs **ViT**
        [ViT](https://arxiv.org/abs/2010.11929)
        [Transformer](https://arxiv.org/abs/1706.03762)
  - Dig, Dig, Dig,…
      - mixed-precision training (AMP)
      - Data cleansing
          - label smoothing
      - Batch size
      - K-fold cross validation
      - weight initialization
          - ~~simple random initailization~~
          - LeCun Initialization
          - **Xavier initialization ← Sigmoid, tanh**
          - **He Initialization ← ReLU**
          - **Bias 는 일반적으로 0으로 초기화**
      - learning rate scheduling and warmup
      - early stopping
  - Loss Function Optimization for “Class imbalanced label”
      - focal loss
      - dice loss
      - SparseMax loss
      - …
  - Evaluation and Error Analysis
      - MLFlow / WandB / Tensorboard,…
      - **Confusion matrix**
      - Grad CAM
  - **Model Ensemble**
      - Majority Voting
      - Bagging
      - Boosting
      - Weighted Probability Averaging,...
  - **Test Time Augmentation**
