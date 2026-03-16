🐦 Is It a Bird? — Image Classifier with fastai
A beginner deep learning project that trains an image classifier to distinguish birds from non-birds using a pretrained ResNet-18 model and the fastai library.
📌 Overview
This notebook is inspired by the fast.ai Practical Deep Learning course. It demonstrates how to build a working image classifier in just a few lines of code using transfer learning — achieving ~94% accuracy without training from scratch.
🚀 What It Does

Searches and downloads training images using DuckDuckGo
Builds a dataset with fastai's DataBlock API
Fine-tunes a pretrained ResNet-18 model on bird vs. forest images
Evaluates model performance using error rate
Makes predictions on new images with confidence scores

🛠️ Tech Stack

Python
fastai
PyTorch
ResNet-18 (transfer learning)
Kaggle Notebooks

📊 Results
MetricValueEpochs3Error Rate~5.8%Accuracy~94.2%
📁 How to Run

Open the notebook in Kaggle
Enable Internet in the notebook settings
Click Run All

🌱 What I Learned

How to use transfer learning with a pretrained CNN
fastai's DataBlock API for building datasets
Fine-tuning vs. training from scratch
Reading training metrics (loss, error rate)
