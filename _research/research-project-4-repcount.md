---
title: "Repetitive Action Counting Through Joint Angle Analysis and Video Transformer Techniques"
collection: research
type: "Research"
permalink: /research/research-project-4-repcount
layout: single
slug: "research-project-4-repcount"
image_width: "500px"  # Custom width for this post's image
excerpt: |
    <div>
        <p>This project introduces an advanced method for repetitive action counting by integrating joint angle analysis with pose landmarks using Transformer networks. Addressing common challenges such as camera viewpoint variability, over-counting, under-counting, and sub-action differentiation, the proposed approach achieves superior performance on the RepCount dataset. By leveraging both skeletal data and joint angles, the system enhances the accuracy and robustness of action repetition detection, making significant strides in applications like fitness tracking, rehabilitation, and manufacturing operation monitoring.</p>
        <div style="text-align: center;">
                <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-4-repcount.jpg" alt="Repetitive Action Counting" width=100% />
        </div>
    </div>
---

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-4-background.jpg" alt="Repetitive Action Counting" width="800" />
</div>

## Goals
- **Enhance Repetitive Action Counting Accuracy:** Develop a method that integrates joint angles with pose landmarks to improve the precision of repetitive action counting in various applications.
- **Address Common Challenges:** Mitigate issues such as instability under varying camera viewpoints, over-counting, under-counting, and difficulty in distinguishing sub-actions through advanced analysis techniques.
- **Leverage Transformer Networks:** Utilize Transformer-based models to effectively capture temporal patterns and spatial relationships in action sequences.
- **Validate on Public Datasets:** Demonstrate the method's effectiveness by achieving superior performance metrics on the RepCount public dataset.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-4-goal.jpg" alt="Project Goals" width=50% />
</div>

## Key Findings
- **Integration of Joint Angles and Pose Landmarks:** Combined joint angle analysis with pose landmarks to provide a comprehensive understanding of human movements, enhancing action counting accuracy.
- **Transformer-Based Architecture:** Implemented a Transformer network to effectively model the temporal dynamics and spatial relationships in repetitive actions.
- **Improved Performance Metrics:** Achieved a Mean Absolute Error (MAE) of 0.211 and an Off-By-One Accuracy (OBOA) of 0.599 on the RepCount dataset, surpassing existing state-of-the-art methods.
- **Robustness to Environmental Variations:** Enhanced the model's stability under different camera viewpoints and various video effects, ensuring reliable performance across diverse scenarios.
- **Comprehensive Evaluation:** Conducted extensive experiments to validate the effectiveness of different joint angle configurations and their impact on repetitive action counting.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-4-findings.jpg" alt="Addressing the inability issue to stably deal with varying camera viewpoints" width="900" />
    <p><strong>Addressing the inability issue to stably deal with varying camera viewpoints</strong></p>
</div>

<div style="text-align: center;">

    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-4-findings_.jpg" alt="Addressing the under-counting issue" width="900" />
    <p><strong>Addressing the under-counting issue</strong></p>
</div>

## Technologies Utilized
- **Pose Estimation:** Employed Google Mediapipe BlazePose model to extract 33 pose landmarks with high accuracy.
- **Joint Angle Calculation:** Computed five key joint angles (elbow, shoulder, hip, knee, ankle) from the pose landmarks to capture movement dynamics.
- **Transformer Networks:** Utilized Transformer-based models for processing skeletal and joint angle data, enabling effective temporal pattern recognition.
- **Video Processing:** Applied advanced video transformer techniques to handle varying camera viewpoints and video effects.
- **Data Acquisition and Annotation:** Corrected and refined annotations on the RepCount dataset to ensure data integrity and reliability.
- **Software and Frameworks:** Python, TensorFlow, Keras, and other deep learning libraries for model development and training.
- **Hardware Setup:** High-performance computing resources including NVIDIA GeForce RTX 3090 for accelerated training and inference.

## Impact
This project significantly advances the field of repetitive action counting by introducing a robust method that combines joint angle analysis with pose landmarks using Transformer networks. The improved accuracy and robustness of the system have substantial implications for various applications:
- **Fitness and Rehabilitation:** Enhances the effectiveness of training and rehabilitation programs by ensuring accurate tracking of exercise repetitions.
- **Manufacturing Monitoring:** Provides reliable monitoring of assembly operations, ensuring consistency and quality in manufacturing processes.
- **Human-Computer Interaction:** Facilitates more accurate and intuitive interaction systems that rely on repetitive action recognition.
- **Assistive Technologies:** Benefits individuals with physical impairments by providing precise action counting, aiding in therapy and daily activities.

The method's ability to handle environmental variations and differentiate sub-actions makes it a versatile tool for real-world applications, paving the way for future innovations in action recognition and monitoring systems.


## References
*Please refer to the for detailed references and further reading.*
1.Chen, H, Zendehdel, N, Leu, MC, Moniruzzaman, M, Yin, Z, & Hajmohammadi, S. "Repetitive Action Counting Through Joint Angle Analysis and Video Transformer Techniques." Proceedings of the 2024 International Symposium on Flexible Automation. 2024 International Symposium on Flexible Automation. Seattle, Washington, USA. July 21–24, 2024. V001T08A003. ASME. [doi](https://doi.org/10.1115/ISFA2024-140665)
[full publication](https://asmedigitalcollection.asme.org/flexibleautomation/article-pdf/ISFA2024-140665/REPETITIVE_ACTION_COUNTING_THROUGH_JOINT_ANGLE_ANALYSIS_AND_VIDEO_TRANSFORMER_TECHNIQUES.pdf) 

---
