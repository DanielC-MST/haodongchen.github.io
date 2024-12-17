---
title: "Instance Segmentation and Software Design for Real-Time Tool Detection and Human-Computer Interaction in Smart Manufacturing"
collection: research
type: "Research"
permalink: /research/research-project-instance-segmentation-software-design
layout: single
slug: "research-project-instance-segmentation-software-design"
image_width: "500px"  # Custom width for this post's image
excerpt: |
    <div>
        <p>This project focuses on the application of instance segmentation and robust software design in the realm of smart manufacturing and human-computer interaction (HCI). Leveraging advanced computer vision techniques, specifically You-Only-Look-Once (YOLO)v5 and Mask Region-Based Convolutional Neural Networks (Mask R-CNN), the system achieves real-time tool detection and interactive HCI using eye gaze recognition. The software interface, developed with PyQt and Python, integrates these models to provide dynamic visual assistance, enhancing productivity and accuracy in manufacturing processes.</p>
        <div style="text-align: center;">
                <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-1-1-instance-segmentation.jpg" alt="Instance Segmentation and Software Design" width=80% />
        </div>
    </div>
---

<div style="text-align: center;">
    <p><strong>Enhancing Smart Manufacturing and HCI through Instance Segmentation and Advanced Software Design</strong></p>
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-1-1-instance-segmentation.jpg" alt="Instance Segmentation and Software Design" width="800" />
</div>

## Goals
- **Optimize YOLOv5 for Real-Time Tool Detection:** Fine-tune the YOLOv5 algorithm to achieve high accuracy and efficiency in detecting and localizing various industrial tools within manufacturing environments.
- **Develop an Instance Segmentation Model Using Mask R-CNN:** Implement and train Mask R-CNN to accurately recognize and segment tools and parts, facilitating detailed analysis and interaction.
- **Design an Intuitive Software Interface:** Create a user-friendly interface using PyQt and Python that integrates YOLOv5 and Mask R-CNN models for seamless real-time tool detection and HCI based on eye gaze recognition.
- **Enhance Human-Computer Interaction with Eye Gaze Tracking:** Utilize eye gaze recognition to enable natural and contactless interaction with the software interface, improving operational efficiency and user experience.
- **Create and Annotate Comprehensive Datasets:** Develop and augment datasets of industrial tools and eye gaze behaviors to support the training and evaluation of the detection and segmentation models.
- **Ensure Real-Time Performance and Robustness:** Achieve real-time processing capabilities and maintain high accuracy under varying environmental conditions and tool orientations.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-1-1-goal.jpg" alt="Project Goals" width="700" />
</div>

## Key Findings
- **High-Precision Tool Detection:** The optimized YOLOv5 model achieved a mean average precision (mAP) of 98.3%, demonstrating exceptional accuracy in real-time tool detection within smart manufacturing settings.
- **Accurate Instance Segmentation:** The Mask R-CNN model attained an average accuracy of 99% in segmenting tools and parts, ensuring precise localization and differentiation of multiple instances within images.
- **Seamless Software Integration:** The PyQt and Python-based interface successfully integrated YOLOv5 and Mask R-CNN models, providing real-time visual feedback and enabling intuitive tool and part selection through eye gaze.
- **Robust Eye Gaze Recognition:** The eye gaze recognition system achieved an average accuracy of 99% within the recommended distance (40-60 cm) from the webcam, facilitating reliable HCI without the need for specialized hardware.
- **Enhanced Human-Computer Interaction:** The integration of eye gaze tracking with instance segmentation allowed for natural and efficient interaction with the software interface, improving user productivity and reducing operational errors.
- **Scalability and Flexibility:** The system maintained high performance across varying distances (up to 160 cm) and environmental conditions, showcasing its robustness and adaptability for real-world manufacturing environments.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-1-1-findings.jpg" alt="Key Findings" width="1400" />
</div>

## Technologies Utilized
- **You-Only-Look-Once (YOLO)v5:** Utilized for real-time object detection and localization of industrial tools with high precision and speed.
- **Mask Region-Based Convolutional Neural Network (Mask R-CNN):** Employed for detailed instance segmentation of tools and parts, enabling precise boundary delineation.
- **Convolutional Neural Networks (CNN):** Core architecture used in both YOLOv5 and Mask R-CNN for feature extraction and object recognition.
- **PyQt:** Framework used for designing the graphical user interface, providing a responsive and interactive software environment.
- **Python:** Primary programming language for algorithm development, model training, and system integration.
- **Dlib 68-Point Facial Landmark Detector:** Implemented for accurate face and eye landmark detection in the eye gaze recognition system.
- **OpenCV:** Utilized for image processing tasks, including preprocessing, augmentation, and real-time video capture.
- **Stochastic Gradient Descent (SGD) Optimizer:** Adopted for training the YOLOv5 model, optimizing hyperparameters like learning rate and momentum to enhance performance.
- **Data Augmentation Techniques:** Applied methods such as random flips, rotations, brightness adjustments, and noise addition to increase dataset diversity and model robustness.
- **NVIDIA GeForce RTX 3090:** Leveraged for high-performance computing needs, ensuring accelerated training and real-time processing capabilities.
- **Roboflow Platform:** Used for dataset annotation, enabling precise bounding box and polygon mask labeling for object detection and instance segmentation tasks.
- **Google Mediapipe BlazePose:** Integrated for extracting pose landmarks and calculating joint angles to assist in eye gaze interpretation.

## Impact
This project significantly advances the capabilities of smart manufacturing and human-computer interaction through the effective integration of instance segmentation and sophisticated software design. By optimizing YOLOv5 and implementing Mask R-CNN, the system achieves unparalleled accuracy in tool detection and segmentation, which is crucial for automation, quality control, and inventory management. The PyQt and Python-based software interface, enhanced with real-time eye gaze recognition, facilitates intuitive and hands-free interaction, thereby improving operational efficiency and reducing the cognitive load on workers. The robustness of the system under varying conditions ensures its reliability in real-world manufacturing environments, contributing to safer and more ergonomic working conditions. Additionally, the comprehensive datasets developed support ongoing research and can be leveraged for further advancements in computer vision applications within Industry 4.0.

## References
*Please refer to the [full publications](https://ssrn.com/abstract=4972051) for detailed references and further reading.*

1. Zendehdel, N., Chen, H., & Leu, M. C. (2023). Real-Time Tool Detection in Smart Manufacturing Using You-Only-Look-Once (YOLO)v5. *Manufacturing Letters*, 35, 1052-1059. https://doi.org/10.1016/j.mfglet.2023.1052

2. Chen, H., Zendehdel, N., Leu, M. C., & Yin, Z. (2023). Real-Time Human-Computer Interaction Using Eye Gazes. *Manufacturing Letters*, 35, 883–894. https://doi.org/10.1016/j.mfglet.2023.883
