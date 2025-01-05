---
title: "A Gaze-Driven Manufacturing Assembly Assistant System with Integrated Step Recognition, Repetition Analysis, and Real-Time Feedback"
collection: research
type: "Research"
permalink: /research/research-project-7-gaze
layout: single
slug: "research-project-7-gaze"
image_width: "500px"  # Custom width for this post's image
excerpt: |
    <div>
        <p>This project presents an innovative gaze-driven assembly assistant system tailored for human-centered smart manufacturing. By integrating assembly step recognition using CNN and LSTM networks, repetitive action counting with Transformer networks, and real-time eye gaze estimation, the system provides dynamic visual assistance to enhance quality and productivity in manufacturing processes. The developed software interface offers contextual tool and part displays, detailed procedural instructions, and interactive guidance based on worker gaze, demonstrating significant improvements in assembly accuracy and operational efficiency.</p>
        <div style="text-align: center;">
                <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-7-gaze.jpg" alt="Gaze-Driven Assembly Assistant" width=800 />
        </div>
    </div>
---

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-7-background.jpg" alt="Gaze-Driven Assembly Assistant" width="800" />
</div>

## Goals
- **Develop a Gaze-Driven Assembly Assistance System:** Create a system that leverages eye gaze estimation to provide real-time visual assistance during assembly tasks.
- **Integrate Multi-Task Algorithms:** Combine assembly step recognition, repetitive action counting, and gaze estimation to enhance overall assembly performance.
- **Enhance Worker Productivity and Quality:** Offer detailed procedural instructions and tool usage guidance based on real-time recognition and gaze data.
- **Create a Comprehensive Dataset:** Develop a new dataset of repetitive assembly actions to support the training and evaluation of the proposed models.
- **Ensure Real-Time Performance:** Achieve real-time processing and feedback to provide immediate assistance to workers during assembly operations.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-7-goal.jpg" alt="Project Goals" width="700" />
</div>

## Key Findings
- **Dual-Task Integration:** Combined assembly step recognition with repetitive action counting and gaze estimation to provide a holistic assistance system.
- **Advanced Model Architectures:** Utilized Convolutional Neural Networks (CNN), Long Short-Term Memory (LSTM) networks, and Transformer networks to achieve high accuracy in step recognition and action counting.
- **Real-Time Gaze-Based Feedback:** Developed a gaze tracking mechanism that interacts with a software interface to display relevant tools, parts, and instructions based on worker focus.
- **Comprehensive Dataset Creation:** Introduced a new dataset comprising 9 assembly steps for desktop carving machine assembly, addressing the lack of fine-grained repetitive action datasets in manufacturing.
- **Superior Performance Metrics:** Achieved over 98% accuracy in assembly step recognition and significantly improved Mean Absolute Error (MAE) and Off-By-One Accuracy (OBOA) in repetitive action counting compared to state-of-the-art methods.
- **User-Friendly Software Interface:** Designed an intuitive interface that dynamically updates based on recognized assembly steps and worker gaze, enhancing ease of use and effectiveness.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-7-findings.jpg" alt="Technologies Utilized" width="1400" />
</div>

## Technologies Utilized
- **Convolutional Neural Networks (CNN):** For extracting spatial features from assembly step videos.
- **Long Short-Term Memory (LSTM) Networks:** To capture temporal dependencies in assembly step sequences.
- **Transformer Networks:** Employed for repetitive action counting, leveraging attention mechanisms for improved accuracy.
- **Google Mediapipe BlazePose:** Utilized for extracting 33 pose landmarks and calculating joint angles.
- **Gaze Tracking Hardware:** Tobii Gaze Tracker 5 for real-time eye gaze estimation.
- **Software Frameworks:** OpenCV for computer vision tasks and Qt Designer for designing the graphical user interface.
- **Data Augmentation Techniques:** Applied salt/pepper noise, brightness adjustments, and playback speed variations to enhance dataset robustness.
- **High-Performance Computing:** NVIDIA GeForce RTX 3090 for accelerated model training and real-time processing.
- **Programming Languages:** Python for algorithm development and model implementation.



## Impact
This project significantly enhances human-centered intelligent manufacturing by introducing a comprehensive gaze-driven assembly assistant system. The integration of assembly step recognition, repetitive action counting, and gaze estimation provides workers with real-time, contextual assistance, thereby improving the accuracy and efficiency of assembly tasks. The system's ability to dynamically display relevant tools, parts, and instructions based on worker gaze fosters a more intuitive and interactive assembly environment. Furthermore, the creation of a new, fine-grained dataset supports ongoing research and development in manufacturing automation. By addressing critical challenges such as the skills gap in manufacturing, this system not only boosts productivity but also contributes to safer and more ergonomic working conditions.

## References
*Please refer to the [full publication](https://ssrn.com/abstract=4972051) for detailed references and further reading.*

---
