ROAD DAMAGE ANALYTICS AND AUTOMATED DETECTION USING DEEP LEARNING

Contribution: Faster R-CNN (CNN)

Architecture: Faster R-CNN with ResNet-50 FPN
Framework: PyTorch and Torchvision

Dataset:
- Training: 426 images
- Validation: 106 images
- Testing: 133 images

Experiments:
1. Baseline Faster R-CNN
2. Faster R-CNN with Data Augmentation

Selected Model: Experiment 2

Final Test Results:
- Precision: 0.7404
- Recall: 0.7726
- mAP@50: 0.7561
- mAP@50–95: 0.4689
- F1-score: 0.7565

The folder contains:
- Final Jupyter Notebook
- Baseline and augmented model checkpoints
- Experiment results and training histories
- Training and validation plots
- Prediction visualizations