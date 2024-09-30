# [**Adaptive Real-Time Multi-Objective Optimization Using Dynamic Memory Fusion Loss Framework: A Case Study on Breast Cancer Segmentation**](https://www.researchgate.net/profile/Amin-Golnari)

---

Amin Golnari, Mostafa Diba. **"Adaptive Real-Time Multi-Objective Optimization Using Dynamic Memory Fusion Loss Framework: A Case Study on Breast Cancer Segmentation"** Preprint. []()


**Amin Golnari <sup>a<sup>**, **Mostafa Diba <sup>a<sup>** <br>
a) Faculty of Electrical & Robotics, Shahrood University of Technology, Shahrood, Iran <br>

**Link to the preprint version on ResearchGate:** [Click here](https://www.researchgate.net/profile/Amin-Golnari)

**Or You Can Run this Python Code on Google Colab:**    

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amingolnari/Demo-Dynamic-Memory-Fusion-Framework/blob/main/DynamicMemoryFusion.ipynb)

---

## **Framework Overview**

The **Dynamic Memory Fusion Loss Framework** is an adaptive, real-time, multi-objective optimization framework designed to improve segmentation performance, particularly in tasks involving medical imaging such as **breast cancer segmentation**.

This framework is based on deep learning and addresses the inefficiencies of manual tuning in multi-objective loss functions by dynamically adjusting loss weights during training. It utilizes historical loss data to update weights and integrates auxiliary loss functions that enhance model performance, especially in the early stages of training. Additionally, the **Class Balanced Dice Loss** function addresses the issue of class imbalance, which is crucial for accurate segmentation in medical datasets.

---

## **Key Features:**

1. **Dynamic Weight Adjustment**:
   - The framework dynamically adjusts the weighting of multiple loss functions in real time based on historical loss values.
   - This adaptation ensures better performance across different training stages without the need for manual fine-tuning.

2. **Class Balanced Dice Loss**:
   - A novel loss function that handles class imbalance by focusing more on underrepresented classes, improving the overall segmentation accuracy.

3. **Auxiliary Loss Functions**:
   - Auxiliary loss functions are employed to assist in the early stages of training, helping the model converge faster.

4. **Breast Ultrasound Dataset**:
   - The framework has been tested on breast ultrasound datasets, demonstrating improvements in segmentation accuracy and robustness across various metrics, such as Dice score and IoU (Intersection over Union).

---

## **Usage of Class Balanced Dice Loss**

The **Class Balanced Dice Loss** function is crucial in medical image segmentation where there is often a significant class imbalance. In this framework, the Dice loss function has been modified to prioritize underrepresented classes, ensuring better accuracy for minority class segmentation (e.g., cancerous regions in ultrasound images).
