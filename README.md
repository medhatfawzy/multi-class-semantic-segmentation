# Multi Class Semantic Segmentation

### 1. Augmentation
Data augmentation is performed on the data to increase the number of records and make the model more generalized. The data is then saved to the disk to later be used for training.

### 2. Model
The eniter architecture of U-Net model is used to create this model. The model weights are saved and used later loaded to evaluate the model.

### 3. Ablation Study
Two blocks from the encoder and the decoder are removed and the sizes of the the remaining blocks are adjusted. Then another training process with the new architecture. The model is also saved and then loaded for evaluation.

### 4. Models Evaluation
In this notebook, I compare the two models and benchmark them on the test, train and validation datasets to measure their performance.
