---
title: "Fine-Grained Activity Classification in Assembly Based on Multi-Visual Modalities"
collection: research
type: "Research"
permalink: /research/research-project-3-fine-grained
layout: single
slug: "research-project-3-fine-grained"
image_width: "500px"  # Custom width for this post's image
excerpt: "<div>
    <p>This project focuses on the development of a fine-grained activity classification system in assembly environments using multi-visual modalities. By leveraging scene-level and temporal-level features through a two-stage neural network architecture, the system achieves high accuracy in recognizing and predicting continuous assembly activities. The creation of a specialized dataset and the integration of RGB and hand skeleton frames enhance the robustness and precision of activity recognition, contributing to improved productivity and quality control in smart manufacturing.</p>
    <div style='text-align: center;'>
            <img src='https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-3-fine-grained.jpg' alt='Fine-Grained Activity Classification' width=80% />
    </div>
</div>"
---

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-3-background.jpg" alt="Fine-Grained Activity Classification" width="800" />
</div>

## Goals
- **Develop a Fine-Grained Activity Classification System:** Create a system capable of recognizing and predicting detailed assembly activities with low inter-class variability in manufacturing environments.
- **Leverage Multi-Visual Modalities:** Utilize both RGB frames and hand skeleton frames to capture comprehensive scene-level and temporal-level features for accurate activity recognition.
- **Achieve High Accuracy and Real-Time Performance:** Design a two-stage neural network architecture that ensures over 99% accuracy on trimmed videos and over 91% accuracy on untrimmed, continuous activity videos in real-time scenarios.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-3-goal.jpg" alt="Project Goals" width="700" />
</div>

## Key Findings
- **Custom Dataset Creation:** Developed a dataset comprising 15 fine-grained activities specific to the assembly of a desktop carving machine, addressing the lack of manufacturing-specific fine-grained activity datasets.
- **Two-Stage Neural Network Architecture:** 
  - **Stage 1:** Feature Awareness Block that extracts scene-level features from RGB and hand skeleton frames using transfer learning with pre-trained VGG-16 models.
  - **Stage 2:** Recurrent Neural Network (LSTM) layers that learn temporal-level features from the extracted scene-level features.
- **Fusion Strategies:** Implemented fusion-before-RNN and fusion-after-RNN mechanisms to effectively combine RGB and skeleton frame features, with fusion-after-RNN yielding superior performance.
- **Prediction Model:** Designed a partial video observation method to predict upcoming activities, achieving over 97% accuracy using 50% of the activity onset information.
- **Real-Time Continuous Activity Recognition:** Developed a fusion recognition-prediction model capable of accurately recognizing continuous fine-grained activities in untrimmed videos with an average accuracy of 91.33%, operating faster than real-time.
- **Performance Benchmarking:** Demonstrated superior performance compared to state-of-the-art models on both the custom assembly dataset and the public UCF101 dataset, establishing a new baseline for continuous fine-grained activity recognition in assembly contexts.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-3-findings.jpg" alt="Key Contributions" width="900" />
</div>

## Technologies Utilized
- **Machine Learning Models:** 
  - **Convolutional Neural Networks (CNNs):** VGG-16 for feature extraction.
  - **Recurrent Neural Networks (RNNs):** Long Short-Term Memory (LSTM) for temporal feature learning.
- **Data Processing:**
  - **Motion History Images (MHI):** For capturing dynamic gesture features.
  - **Hand Skeleton Extraction:** Using MediaPipe for precise hand landmark detection.
- **Software Development:** Python, TensorFlow, Keras.
- **Hardware and Frameworks:** 
  - **Cameras:** Logitech C920 for high-resolution video capture.
  - **Computing:** NVIDIA GeForce RTX 3090 for accelerated deep learning model training and inference.
- **Data Structures:** FIFO queues for managing and processing video frame sequences.
- **Transfer Learning:** Applied to pre-trained VGG-16 models to enhance feature extraction from limited assembly activity data.


## Impact
This project advances the precision of activity recognition systems in manufacturing by enabling the classification of fine-grained assembly activities with high accuracy. The integration of multi-visual modalities (RGB and hand skeleton frames) and the development of a two-stage neural network architecture enhance the system's ability to discern subtle differences between similar activities, leading to better resource allocation, quality control, and safety measures in smart factories. The real-time performance ensures that the system can be effectively deployed in dynamic manufacturing environments, contributing to increased productivity and reduced operational costs. Additionally, the creation and sharing of a specialized dataset facilitate further research and development in the field of fine-grained activity recognition.

## Selected Publications
*Please refer to the [full publication](https://doi.org/10.1007/s10845-023-02152-x) for detailed references and further reading.*
1.Chen, H., Zendehdel, N., Leu, M.C. et al. Fine-grained activity classification in assembly based on multi-visual modalities. J Intell Manuf 35, 2215–2233 (2024). [doi](https://doi.org/10.1007/s10845-023-02152-x)
---
