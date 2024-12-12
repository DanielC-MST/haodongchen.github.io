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
            <img src='https://yourwebsite.com/images/fine-grained-activity-classification.jpg' alt='Fine-Grained Activity Classification' width='800' />
    </div>
</div>"
---

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/fine-grained-activity-classification.jpg" alt="Fine-Grained Activity Classification" width="800" />
</div>

## Goals
- **Develop a Fine-Grained Activity Classification System:** Create a system capable of recognizing and predicting detailed assembly activities with low inter-class variability in manufacturing environments.
- **Leverage Multi-Visual Modalities:** Utilize both RGB frames and hand skeleton frames to capture comprehensive scene-level and temporal-level features for accurate activity recognition.
- **Achieve High Accuracy and Real-Time Performance:** Design a two-stage neural network architecture that ensures over 99% accuracy on trimmed videos and over 91% accuracy on untrimmed, continuous activity videos in real-time scenarios.

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/fine-grained-activity-classification-goals.jpg" alt="Project Goals" width="700" />
</div>

## Key Contributions
- **Custom Dataset Creation:** Developed a dataset comprising 15 fine-grained activities specific to the assembly of a desktop carving machine, addressing the lack of manufacturing-specific fine-grained activity datasets.
- **Two-Stage Neural Network Architecture:** 
  - **Stage 1:** Feature Awareness Block that extracts scene-level features from RGB and hand skeleton frames using transfer learning with pre-trained VGG-16 models.
  - **Stage 2:** Recurrent Neural Network (LSTM) layers that learn temporal-level features from the extracted scene-level features.
- **Fusion Strategies:** Implemented fusion-before-RNN and fusion-after-RNN mechanisms to effectively combine RGB and skeleton frame features, with fusion-after-RNN yielding superior performance.
- **Prediction Model:** Designed a partial video observation method to predict upcoming activities, achieving over 97% accuracy using 50% of the activity onset information.
- **Real-Time Continuous Activity Recognition:** Developed a fusion recognition-prediction model capable of accurately recognizing continuous fine-grained activities in untrimmed videos with an average accuracy of 91.33%, operating faster than real-time.
- **Performance Benchmarking:** Demonstrated superior performance compared to state-of-the-art models on both the custom assembly dataset and the public UCF101 dataset, establishing a new baseline for continuous fine-grained activity recognition in assembly contexts.

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/fine-grained-activity-classification-contributions.jpg" alt="Key Contributions" width="900" />
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

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/fine-grained-activity-classification-technology.jpg" alt="Technologies Utilized" width="1400" />
</div>

## Impact
This project advances the precision of activity recognition systems in manufacturing by enabling the classification of fine-grained assembly activities with high accuracy. The integration of multi-visual modalities (RGB and hand skeleton frames) and the development of a two-stage neural network architecture enhance the system's ability to discern subtle differences between similar activities, leading to better resource allocation, quality control, and safety measures in smart factories. The real-time performance ensures that the system can be effectively deployed in dynamic manufacturing environments, contributing to increased productivity and reduced operational costs. Additionally, the creation and sharing of a specialized dataset facilitate further research and development in the field of fine-grained activity recognition.

## Project Details

### Authors
- **Haodong Chen**
  - Department of Mechanical and Aerospace Engineering, Missouri University of Science and Technology, Rolla, MO 65409, USA
  - Email: [h.chen@mst.edu](mailto:h.chen@mst.edu)
  
- **Niloofar Zendehdel**
  - Department of Mechanical and Aerospace Engineering, Missouri University of Science and Technology, Rolla, MO 65409, USA
  - Email: [n.zendehdel@mst.edu](mailto:n.zendehdel@mst.edu)
  
- **Ming-Chuan Leu**
  - Department of Mechanical and Aerospace Engineering, Missouri University of Science and Technology, Rolla, MO 65409, USA
  - Email: [mleu@mst.edu](mailto:mleu@mst.edu)
  
- **Zhaozheng Yin**
  - Department of Biomedical Informatics & Department of Computer Science, Stony Brook University, Stony Brook, NY 11794, USA
  - Email: [zyin@cs.stonybrook.edu](mailto:zyin@cs.stonybrook.edu)

### Abstract
Assembly activity recognition and prediction are pivotal for enhancing productivity, quality control, and safety in smart manufacturing environments. This study introduces a two-stage neural network architecture for the fine-grained classification of workers' assembly activities by leveraging both scene-level and temporal-level features extracted from multi-visual modalities, including RGB frames and hand skeleton data. The first stage employs transfer learning with pre-trained VGG-16 models to extract comprehensive scene-level features, which are then processed by LSTM layers in the second stage to capture temporal dynamics. A custom dataset comprising 15 fine-grained assembly activities was developed and utilized to train and evaluate the model, achieving over 99% accuracy on trimmed videos and over 91% accuracy on untrimmed, continuous activity videos. Additionally, a partial video observation method was proposed for predicting upcoming activities with high accuracy. Comparative experiments demonstrate the model's superiority over existing state-of-the-art methods on both the custom assembly dataset and the public UCF101 dataset, establishing a new benchmark for continuous fine-grained activity recognition in assembly contexts.

### Keywords
fine-grained activity, activity classification, assembly, multi-visual modality, real-time recognition, transfer learning

## References
*Please refer to the [full publication](https://doi.org/10.1007/s10845-023-02152-x) for detailed references and further reading.*

---
