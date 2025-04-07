📊 Vision Models Playground: CNNs vs Transformers

A comprehensive comparison of modern image classification models including CNN-based architectures (ResNet, MobileNet, EfficientNet) and Transformer-based models (ViT, Swin Transformer) on a custom multi-class dataset.
🧠 Project Objective

The goal of this project is to evaluate and compare the performance of various state-of-the-art deep learning models for image classification. We tested both convolutional neural networks and vision transformers to understand their strengths and trade-offs on a 7-class classification task.
📁 Models Compared

Model	Architecture Type	Validation Accuracy (%)
Swin Transformer	Vision Transformer	92.892
ViT (B-16)	Vision Transformer	90.897
MobileNet V3 (Large)	Lightweight CNN	89.152
EfficientNet B0	Scalable CNN	90.149
ResNet18	Classic CNN	89.152
Custom CNN	Baseline CNN	61.600
🛠️ Tech Stack

PyTorch
TorchVision
scikit-learn
Matplotlib / Seaborn
Jupyter Notebooks / Kaggle Notebooks
📈 Visualization

The Swin Transformer outperformed other models in validation accuracy, followed closely by ViT and EfficientNet B0.
