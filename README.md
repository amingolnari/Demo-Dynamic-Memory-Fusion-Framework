# [**Adaptive Real-Time Multi-Loss Function Optimization Using Dynamic Memory Fusion Framework: A Case Study on Breast Cancer Segmentation**](https://arxiv.org/pdf/2410.19745)  

---

Amin Golnari, Mostafa Diba. **"Adaptive Real-Time Multi-Loss Function Optimization Using Dynamic Memory Fusion Framework: A Case Study on Breast Cancer Segmentation"** Preprint. [https://doi.org/10.48550/arXiv.2410.19745](https://doi.org/10.48550/arXiv.2410.19745)


**Amin Golnari <sup>a<sup>**, **Mostafa Diba <sup>a<sup>** <br>
a) Faculty of Electrical Engineering, Shahrood University of Technology, Shahrood, Iran <br>

**Link to the preprint version:** [Click here](https://arxiv.org/pdf/2410.19745)

**Or You Can Run this Python Code on Google Colab:**    

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/amingolnari/Demo-Dynamic-Memory-Fusion-Framework/blob/main/DynamicMemoryFusion.ipynb)

**Compatibility:**
- TensorFlow: 2.17.0
- Keras: 3.4.1
- TensorFlow Datasets: 4.9.6

---

## **Framework Overview**

The **Dynamic Memory Fusion Framework** is an adaptive, real-time, multi-loss functions optimization framework designed to improve deep learning task performance.

This framework is based on deep learning and addresses the inefficiencies of manual tuning in multi-loss functions by dynamically adjusting loss weights during training. It utilizes historical loss data to update weights and integrates auxiliary loss functions that enhance model performance, especially in the early stages of training. Additionally, the **Class-Balanced Dice Loss** function is introduced to address the issue of class imbalance, which is crucial for accurate segmentation tasks.

---

## **Key Features:**

1. **Dynamic Weight Adjustment**:
   - The framework dynamically adjusts the weighting of multiple loss functions in real time based on historical loss values.
   - This adaptation ensures better performance across different training stages without the need for manual fine-tuning.

2. **Class-Balanced Dice Loss (CB-Dice)**:
   - A novel loss function that handles class imbalance by focusing more on underrepresented classes, improving the overall segmentation accuracy.

3. **Auxiliary Loss Functions**:
   - Auxiliary loss functions are employed to assist in the early stages of training, helping the model converge faster.

4. **Breast Ultrasound Dataset**:
   - The framework has been tested on breast ultrasound datasets, demonstrating improvements in segmentation accuracy and robustness across various metrics, such as Dice score and IoU (Intersection over Union).

---

## **Usage of CB-Dice Loss**

The **CB-Dice Loss** function is crucial in image segmentation where there is often a significant class imbalance. In this framework, the Dice loss function has been modified to prioritize underrepresented classes, ensuring better accuracy for minority class segmentation (e.g., cancerous regions in medical images).

---

If our work is helpful to you, please kindly cite our paper as:

    @article{GOLNARI2024DMF,
       title={Adaptive Real-Time Multi-Loss Function Optimization Using Dynamic Memory Fusion Framework: A Case Study on Breast Cancer Segmentation},
       author={Golnari, Amin and Diba, Mostafa},
       journal={arXiv preprint arXiv:2410.19745},
       year={2024},
       doi={https://doi.org/10.48550/arXiv.2410.19745}
    }
