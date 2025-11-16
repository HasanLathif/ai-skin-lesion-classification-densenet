# Automated Multi-Class Skin Lesion Classification for Cancer Detection

**Tags:** `Data Science`, `AI/ML`, `Python`, `Computer Vision`, `TensorFlow`, `DenseNet`, `Transfer Learning`

> An AI-powered decision-support tool that classifies 7 types of skin lesions using a DenseNet121 model, achieving 86% accuracy on the HAM10000 dataset.

---
<img width="1521" height="809" alt="Image" src="https://github.com/user-attachments/assets/e69c775d-2e09-4468-b227-c413a4951c21" />

## 1. The Problem

Skin cancer is one of the most common and deadly cancers, but early diagnosis is key to survival. However, distinguishing between benign (harmless) and malignant (cancerous) skin lesions visually is extremely difficult, even for specialists, and access to dermatologists is limited.

## 2. Our Solution

For our "Pengolahan Sinyal Medis" (Medical Signal Processing) project, our team (Group 10) built a deep learning model to automatically classify skin lesions.

We used the public **HAM10000 dataset**, which contains over 10,000 images of 7 different classes of skin lesions (e.g., Melanoma, Basal cell carcinoma, Benign keratosis). We compared a baseline sequential CNN model against a state-of-the-art **DenseNet121** model using **transfer learning**. To handle the highly imbalanced dataset, we implemented data augmentation and class weighting.

**Result:** Our final DenseNet121 model achieved an **accuracy of 86%** on the test set, significantly outperforming the baseline model.

## 3. My Role & Key Contributions

I was a **Co-developer and AI Researcher** on this team project.

* Wrote Python code in the Jupyter Notebook (`Group_10_skin_lesion_classification_notebook_.ipynb`).
* Implemented the data augmentation and preprocessing pipeline.
* Helped build, train, and fine-tune the DenseNet121 transfer learning model using TensorFlow/Keras.
* Analyzed the model's performance, generating the confusion matrix and classification reports.
* Co-authored the final project report.

## 4. Technology Stack

* **Programming Language:** `Python`
* **Software & Libraries:** `Jupyter Notebook`, `Google Colab`, `TensorFlow`, `Keras`, `Scikit-learn`, `Pandas`, `Matplotlib`
* **Model:** `DenseNet121` (Transfer Learning)
* **Dataset:** `HAM10000`

## 5. Proof & Key Results

* **[Jupyter Notebook]:** The complete, runnable Google Colab notebook with all code for data loading, preprocessing, model training, and evaluation.
    * **[Code_skin_lesion_classification_notebook_Group_10]**
* **[Research Paper]:** The final report detailing the project's methodology, model comparison, and results.
    * **[Project Report_PSB_Group 10]**

## 6. Project Status

**Status: [Complete]**
*This project was successfully completed for the Pengolahan Sinyal Medis course.*
