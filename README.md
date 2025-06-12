# alzheimer-3d-mri-detection
Deep learning-based classification of Alzheimer’s disease stages using 3D MRI volumes from the OASIS-1 dataset.

### 🧠 Alzheimer's Disease Detection Using 3D MRI (OASIS-1)
This project explores the use of 3D convolutional neural networks (CNNs) to classify Alzheimer's disease stages from T1-weighted MRI volumes, based on the OASIS-1 dataset.

#### 📁 Files
- `Detection_of_Alzheimer’s_Disease_Using_Clinical_and_MRI_Data_from_OASIS_1.ipynb`: Full Colab notebook with preprocessing, model training, and evaluation.
- Processed .npy volumes

#### MRI Preprocessed Data Access
Due to GitHub's file size limits, the full MRI volume datasets are hosted externally:
- [Download OASIS-1 Normalized MRI](https://drive.google.com/drive/folders/1D5ylMDdsx8S2oUIuLB_9Pz2X1SRGm9MM?usp=drive_link)
- [Download OASIS-1 Stripped MRI](https://drive.google.com/drive/folders/1D5ylMDdsx8S2oUIuLB_9Pz2X1SRGm9MM?usp=drive_link)

#### 🧪 Features
- 3D MRI preprocessing (normalization, skull stripping)
- PyTorch Dataset and 3D CNN architecture
- Validation accuracy of 87.23% on cleaned MRI data
- Loss/accuracy tracking per epoch with detailed explanation

#### 🔮 Future Work
Combining tabular clinical features with MRI scans could enhance performance, though this direction remains outside the scope of the current work.

#### 📚 Dataset
- [OASIS-1: Open Access Series of Imaging Studies](https://www.oasis-brains.org/)

#### 💡 Author
Evica Dojovska
