---
title: "Instance Segmentation for Enhanced UAV Navigation and Smart Manufacturing"
collection: research
type: "Research"
permalink: /research/research-project-instance-segmentation
layout: single
slug: "research-project-instance-segmentation"
image_width: "500px"  # Custom width for this post's image
excerpt: |
    <div>
        <p>This project explores the integration of advanced instance segmentation techniques in two critical areas: Unmanned Aerial Vehicle (UAV) navigation through eye movement tracking and real-time tool detection in smart manufacturing using the You-Only-Look-Once (YOLO)v5 algorithm. By leveraging Electrooculography (EOG) for intuitive UAV control and optimizing YOLOv5 for precise tool detection, the system enhances both human-robot interaction and operational efficiency in manufacturing environments.</p>
        <div style="text-align: center;">
                <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-instance-segmentation.jpg" alt="Instance Segmentation Integration" width=80% />
        </div>
    </div>
---

<div style="text-align: center;">
    <p><strong>Instance Segmentation Integration in UAV Navigation and Smart Manufacturing</strong></p>
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-instance-segmentation-background.jpg" alt="Instance Segmentation Integration" width="800" />
</div>

## Goals
- **Integrate Instance Segmentation in UAV Navigation:** Enhance UAV control systems by incorporating instance segmentation to accurately interpret eye movement data for precise navigation commands.
- **Optimize YOLOv5 for Real-Time Tool Detection:** Fine-tune the YOLOv5 algorithm to achieve high accuracy and efficiency in detecting and segmenting tools within smart manufacturing environments.
- **Enhance Human-Robot Interaction:** Utilize instance segmentation to improve the responsiveness and accuracy of human-robot collaborative systems in both navigation and manufacturing settings.
- **Develop Comprehensive Datasets:** Create and annotate datasets that support the training and evaluation of instance segmentation models for both UAV navigation and tool detection applications.
- **Ensure Real-Time Processing and Feedback:** Achieve real-time performance in both UAV navigation and tool detection systems to provide immediate and actionable feedback to users and robots.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-instance-segmentation-goal.jpg" alt="Project Goals" width="700" />
</div>

## Key Findings
- **Enhanced Navigation Precision:** The integration of instance segmentation with EOG-based eye movement tracking significantly improved the accuracy of UAV navigation commands, reducing command errors by 15%.
- **High-Accuracy Tool Detection:** Optimized YOLOv5 achieved a mean average precision (mAP) of 98.3% in tool detection, with precise segmentation of multiple tool instances within manufacturing environments.
- **Improved Human-Robot Collaboration:** Instance segmentation facilitated more accurate interpretation of human intentions and tool interactions, enhancing the efficiency and safety of collaborative tasks.
- **Comprehensive Dataset Utilization:** The development and augmentation of specialized datasets enabled the training of robust instance segmentation models capable of handling diverse tool types and eye movement patterns.
- **Real-Time Operational Efficiency:** Both UAV navigation and tool detection systems demonstrated real-time processing capabilities, ensuring immediate responsiveness and minimizing latency in dynamic environments.
- **Robustness Against Environmental Variations:** Instance segmentation models maintained high performance despite variations in lighting, tool orientations, and background complexities, ensuring reliability in real-world applications.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-instance-segmentation-findings.jpg" alt="Key Findings" width="1400" />
</div>

## Technologies Utilized
- **Electrooculography (EOG):** For capturing and processing eye movement data to translate gaze directions into UAV navigation commands.
- **Instance Segmentation Algorithms:** Applied advanced instance segmentation techniques to accurately delineate and classify objects within images.
- **You-Only-Look-Once (YOLO)v5:** Optimized for real-time tool detection and segmentation in smart manufacturing settings.
- **Convolutional Neural Networks (CNN):** Employed for feature extraction in both UAV navigation and tool detection models.
- **Long Short-Term Memory (LSTM) Networks:** Utilized to capture temporal dependencies in eye movement sequences for more accurate UAV control.
- **Transformer Networks:** Leveraged for repetitive action counting and enhancing the attention mechanism in instance segmentation tasks.
- **Google Mediapipe BlazePose:** Used for extracting pose landmarks and calculating joint angles to assist in interpreting eye movements.
- **Tobii Gaze Tracker 5:** Integrated for real-time eye gaze estimation, providing accurate input for instance segmentation models.
- **OpenCV:** Utilized for various computer vision tasks, including image preprocessing and augmentation.
- **Qt Designer:** Employed for designing intuitive graphical user interfaces that interact with the instance segmentation models.
- **Data Augmentation Techniques:** Applied techniques such as salt/pepper noise, brightness adjustments, and rotation to enhance model robustness.
- **High-Performance Computing:** NVIDIA GeForce RTX 3090 GPUs used for accelerated training and real-time processing of instance segmentation models.
- **Programming Languages:** Python for algorithm development, model training, and system integration.

## Impact
The integration of instance segmentation into both UAV navigation and smart manufacturing has led to significant advancements in accuracy, efficiency, and human-robot interaction. In UAV navigation, instance segmentation enhanced the interpretation of EOG-based eye movements, enabling more precise and reliable control of UAVs, which is particularly beneficial for individuals with mobility impairments. In the manufacturing sector, the optimized YOLOv5 model demonstrated exceptional tool detection and segmentation capabilities, facilitating improved automation, inventory management, and quality control. Furthermore, the real-time performance of these systems ensures immediate feedback and responsiveness, fostering safer and more ergonomic working conditions. The comprehensive datasets developed for this project support ongoing research and development, paving the way for further innovations in instance segmentation and its applications in diverse technological landscapes.

## References
*Please refer to the [full publication](https://ssrn.com/abstract=4972051) for detailed references and further reading.*

---
