# Computer Vision Projects

This repository contains a collection of projects developed for the **Computer Vision course (MIARFID, UPV)**.  
Each project explores different aspects of computer vision, from image classification to segmentation, using both **classical** and **deep learning** approaches.

📄 Some reports and notebooks are in **Spanish**, but this README provides a summary in English.

---

## 📂 Projects

### 1. Flowers-102 Classification (CNNs vs Vision Transformers)
- **Report:** [`Practicas_Flowers_CV.pdf`](./Practicas_Flowers_CV.pdf) (Spanish)  
- **Goal:** Compare performance of **Convolutional Neural Networks (CNNs)** and **Vision Transformers (ViTs)** for fine-grained flower classification.  
- **Dataset:** [Oxford Flowers-102](https://www.robots.ox.ac.uk/~vgg/data/flowers/102/)  
- **Models:**  
  - CNNs: ResNet50, EfficientNet  
  - Transformers: ViT16, ViT32, Swin Transformer  
- **Key Findings:**  
  - CNNs achieved accuracies up to **92%** (EfficientNet).  
  - Vision Transformers outperformed CNNs, with **Swin Transformer reaching 99.1% accuracy**.  
  - Advanced augmentation (RandAugment, Label Smoothing) further improved generalization.  

---

### 2. Morphological Image Segmentation
- **Notebook:** [`Proyecto II Segmentación morfológica.ipynb`](./Proyecto%20II%20Segmentación%20morfológica.ipynb) (Spanish)  
- **Goal:** Apply **morphological operators** for segmentation tasks.  
- **Topics Covered:**  
  - Thresholding and preprocessing  
  - Dilation, erosion, opening, and closing  
  - Object segmentation using connected components  
  - Applications in separating overlapping shapes  

This project highlights the effectiveness of **classical computer vision** techniques in structured segmentation problems.

---

### 3. Cut It! – Interactive Segmentation
- **Notebook:** [`Cut_it.ipynb`](./Cut_it.ipynb) (English)  
- **Goal:** Implement an **interactive segmentation pipeline**.  
- **Features:**  
  - Region selection and cropping  
  - Mask generation  
  - Combination of manual selection with automatic refinement  

This project bridges **user interaction** with **computer vision tools**, showing how manual cues can enhance segmentation performance.

---

## 🛠️ Technologies Used

- **Python**  
- **PyTorch** / **Torchvision**  
- **scikit-learn**  
- **OpenCV**  
- **NumPy, Pandas, Matplotlib, Seaborn**  
- **timm** (Vision Transformer implementations)

---

## 👩‍💻 Author

**Ana Valentina López Chacón**  
Master in Artificial Intelligence, Pattern Recognition and Digital Imaging (MIARFID)  
Universitat Politècnica de València  

Bachelor in Applied Mathematics and Computer Science
Universidad del Rosario

---

## 📎 References

- Nilsback, M. E., & Zisserman, A. (2008). *Automated flower classification over a large number of classes.*  
- He, K., Zhang, X., Ren, S., & Sun, J. (2016). *Deep residual learning for image recognition (ResNet).*  
- Tan, M., & Le, Q. (2019). *EfficientNet: Rethinking model scaling for CNNs.*  
- Dosovitskiy, A., et al. (2020). *An image is worth 16x16 words: Vision Transformers.*  
- Liu, Z., et al. (2021). *Swin Transformer: Hierarchical vision transformer using shifted windows.*  

---

