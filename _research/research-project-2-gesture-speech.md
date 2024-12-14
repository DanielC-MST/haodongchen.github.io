---
title: "Real-Time Multi-Modal Human–Robot Collaboration Using Gestures and Speech"
collection: research
type: "Research"
permalink: /research/research-project-2-gesture-speech
layout: single
slug: "research-project-2-gesture-speech"
image_width: "500"  # Custom width for this post's image
excerpt: "<div>
    <p>This project explores the development of a real-time, multi-modal Human–Robot Collaboration (HRC) system that leverages both gestures and speech for seamless interaction between humans and industrial robots. By integrating convolutional neural networks and advanced speech recognition algorithms, the system achieves high accuracy in gesture and speech recognition, enhancing the efficiency and intuitiveness of human-robot collaborations in manufacturing environments.</p>
    <div style='text-align: center;'>
            <img src='https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-2-human-robot-collaboration.jpg' alt='Example Image' width='400' />
    </div>
</div>"
---

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-2-human-robot-collaboration.jpg" alt="Human-Robot Collaboration" width="800" />
</div>

## Goals
- **Develop a Multi-Modal HRC System:** Create a real-time system that combines gesture and speech recognition to facilitate intuitive human-robot interactions on the factory floor.
- **Enhance Recognition Accuracy:** Utilize convolutional neural networks (CNNs) and improved speech recognition algorithms to achieve over 95% accuracy in recognizing 16 dynamic gestures and corresponding speech commands.
- **Integrate Parallel Processing:** Design a multi-threading architecture that enables simultaneous gesture and speech data processing, ensuring real-time responsiveness and efficiency.

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/research-project-human-robot-collaboration-goals.jpg" alt="Project Goals" width="700" />
</div>

## Key Contributions
- **Dynamic Gesture Design:** Created a set of 16 dynamic gestures categorized into iconic and deictic types, specifically tailored for robot calibration and operational commands.
- **Real-Time Motion History Image (MHI) Method:** Developed a real-time MHI generation technique to extract dynamic gesture features from multi-view RGB camera inputs, enabling effective feature representation for gesture recognition.
- **Convolutional Neural Network (CNN) for Gesture Recognition:** Built a robust CNN-based model that processes resized MHIs to accurately classify gestures with over 98% accuracy.
- **Enhanced Speech Recognition:** Improved an open-source speech recognizer by implementing spectral subtraction and fuzzy matching strategies, achieving over 95% accuracy for most speech commands even in noisy environments.
- **Multi-Threading Architecture:** Designed a seven-thread multi-processing framework that handles gesture and speech data collection, recognition, integration, and robot control simultaneously, ensuring real-time system performance.
- **System Integration Strategy:** Proposed an effective integration method that combines gesture and speech recognition results based on confidence levels and environmental noise, enhancing overall system reliability and robustness.
- **Comprehensive System Demonstration:** Implemented and demonstrated the HRC system using a 6-DOF robotic arm performing pick-and-place tasks, showcasing the practical applicability and efficiency of the developed system.

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/research-project-human-robot-collaboration-contributions.jpg" alt="Key Contributions" width="900" />
</div>

## Technologies Utilized
- **Machine Learning Models:** Convolutional Neural Networks (CNNs) for gesture recognition, spectral clustering, Gaussian Mixture Models (GMM), Random Forest, Support Vector Machines (SVM), and Fourier descriptors.
- **Speech Recognition:** Enhanced Google open-source speech recognizer with spectral subtraction and fuzzy matching techniques.
- **Software Development:** Python (using PyCharm), MATLAB, C++.
- **Hardware and Frameworks:** Logitech HD Webcam C920 for gesture and speech capture, 6-DOF e.DO robotic arm, multi-threading with Python API, NVIDIA GeForce GTX 1080Ti GPUs for accelerated processing.
- **Real-Time Processing:** Motion History Image (MHI) generation, multi-threading architecture for parallel task management, real-time control systems.
- **Data Structures:** FIFO queues for managing gesture and speech data streams.

<div style="text-align: center;">
    <img src="https://yourwebsite.com/images/research-project-human-robot-collaboration-technology.jpg" alt="Technologies Utilized" width="1400" />
</div>

## Impact
This project significantly advances the field of human–robot collaboration by providing a robust, real-time system that seamlessly integrates gesture and speech commands. The high accuracy in recognizing multiple gestures and speech commands reduces the reliance on manual interventions and enhances operational efficiency in manufacturing settings. Additionally, the multi-threading architecture ensures that the system remains responsive and reliable, even in dynamic and noisy environments. By enabling more natural and intuitive interactions between humans and robots, this research contributes to the broader adoption of collaborative robots (cobots) in industry, improving productivity and fostering safer working environments.

## Project Details

### Authors
- **Haodong Chen**
  - Department of Mechanical and Aerospace Engineering, Missouri University of Science and Technology, Rolla, MO 65409
  - Email: [h.chen@mst.edu](mailto:h.chen@mst.edu)
  
- **Ming C. Leu**
  - Department of Mechanical and Aerospace Engineering, Missouri University of Science and Technology, Rolla, MO 65409
  - Email: [mleu@mst.edu](mailto:mleu@mst.edu)
  
- **Zhaozheng Yin**
  - Department of Biomedical Informatics & Department of Computer Science, Stony Brook University, Stony Brook, NY 11794
  - Email: [zyin@cs.stonybrook.edu](mailto:zyin@cs.stonybrook.edu)

### Abstract
As artificial intelligence and industrial automation advance, Human–Robot Collaboration (HRC) systems with sophisticated interaction capabilities are becoming increasingly vital. This project designs and develops a real-time, multi-modal HRC system that utilizes both speech and gestures for effective communication between human workers and industrial robots. Sixteen dynamic gestures were crafted and a corresponding dataset was created and shared with the research community. A convolutional neural network (CNN) was employed for real-time gesture recognition using Motion History Images (MHI) and deep learning techniques. Additionally, an improved open-source speech recognizer was integrated to handle natural speech commands. An integration strategy combining gesture and speech recognition results was proposed, supported by a multi-threading architecture to manage concurrent tasks. Experimental results demonstrate the system's high accuracy and effectiveness, validating the feasibility of the proposed HRC system.

### Keywords
human–robot collaboration, gesture recognition, speech recognition, real-time, multi-modal, multiple threads

## References
*Please refer to the [full publication](https://doi.org/10.1115/1.4054297) for detailed references and further reading.*

---
