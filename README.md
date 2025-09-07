# VGG16 & VGG19 Transfer Learning on CIFAR-10

This project demonstrates **Transfer Learning** using **VGG16** and **VGG19** pre-trained models on the CIFAR-10 dataset.  
We freeze convolutional layers and add a custom classifier for fine-tuning on the small-scale dataset.

---

## 📌 Dataset
We use the built-in **CIFAR-10** dataset:
- **60,000 images** of size **32x32x3**
- **50,000 training samples**
- **10,000 testing samples**
- **10 classes**: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

---

## 📌 Requirements
Install the dependencies before running the scripts:

```bash
pip install tensorflow matplotlib seaborn scikit-learn pandas
