---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in GitHub, GitHub University, 2012
* M.E. in Mechanical Manufacture and Automation , Hefei University of Technology, 2014
* Ph.D. in Mechanical Engineering, Missouri University of Science and Technology, 8/2019 - 6/2024
<img src="images/haodongchen.jpg" alt="" width="650px"> 


Work experience
======
* 2023 Jan.-Jul.: Machine Learning Engineer
  * Peloton Interactive, New York, 441 9th Ave 6th, United States, 10001
  * Duties included:
    - Engaged in developing a cutting-edge system using AWS for Repetitive Action Counting (RepCount) and pose estimation in exercise routines, surpassing the state-of-the-art model by approximately 5%. This advancement provides users with in-depth insights into exercise patterns, enhancing progress tracking and workout optimization.
    - Improved Repetitive Action Counting (RepCount) by 5% by training a 3D pose model on real-world action data from over 100 human subjects, using machine learning methods such as Swin Transformer and attention mechanism.
    - Augmented the dataset by five-fold, employing techniques like flipping and rotation with OpenCV, enhancing data richness.
    - Addressed challenges in RepCount like camera view changes, over-counting, under-counting, etc., and conducted data visualization.
    - Boosted mAP by 8% in temporal action localization by designing a new point-level annotation with weakly-supervised learning. 
    - Technologies Utilized: Python, PyTorch, Tensorflow, Scikit-learn, AWS, Swin Transformer, attention mechanism, Google MediaPipe, OpenPose, etc.

  * Supervisor: Solmaz Hajmohammadi ([LinkedIn](https://www.linkedin.com/in/solmazhajmohammadi/))


* 2019 Aug. - 2024 May: Graduate Research Assistant
  * Missouri University of Science and Technology
  * Duties included:
    - Engaged in pioneering research on human activity recognition, human-computer interaction (HCI), and human-robot collaboration (HRC) systems using sensor-driven big data, on-site customized cognition, and augmented reality (AR) control structures. Key highlights: 
    – Recognition& Accuracy: 
    • Achieved 95% accuracy on instance segmentation of tools and parts using Mask RCNN, implemented object-oriented Python.
    • Achieved 99% accuracy of offline multi-modal assembly action recognition using using CNN (VGG16, ResNet 50, and Inception V3) and RNN (LSTM and GRU) with CUDA/GPU programming. 
    • Attained 99% accuracy in real-time gesture recognition and 95% accuracy in NLP under diverse background noise condition using CNN and Google Speech Recognizer.
    • Reached 95% accuracy on action recognition using inertial measurement unit (IMU) signals with TensorFlow and online assembly setp/sequence recognition using multi-view RGB camera inputs and fog computing. 
    • Implemented data augmentation through image processing and Generative Adversarial Networks (GANs) to amplify data from a limited dataset.
    • Optimize motion patterns using unsupervised methods, such as the spectral cluster and Gaussian Mixture Model (GMM).
    
    * System Development
    • Crafted an eye gaze-based HCI system using Tobii tracker, OpenCV, PyTorch, PyQt, and Matplotlib.
    • Designed an assembly action recognition and prediction system using Graph Neural Network (GNN) and YOLO.
    • Constructed and analyzed skeleton/pose action dataset of human subjects using Google MediaPipe, SQL, Python, and Pandas.
    • Designed an augmented reality (AR) assisted software interface for visual workforce training with CUDA/GPU programming.
    • Initiated a proposal for YOLO-driven wound tissue detection software, utilizing GANs for data augmentation.
    
    – Research & Mentorship
    • Reviewed current machine learning literature to guide research directions and endeavors.
    • Mentored eight undergraduate and master's students in the research team.
    • Produced and prepared over 10 presentations and research papers for publication with strong verbal and written communication skills.
    
    – Technologies Utilized: Python, C++, TensorFlow, PyTorch, Keras, OpenCV, Numpy, CNN, RNN, GitHub, CUDA, ROS, etc.
      * Supervisor: Professor Hub
  
Skills
======
* Programming Languages: Python, C++, MATLAB, SQL  
* Machine Learning Frameworks: TensorFlow, PyTorch, Keras, Scikit-learn
* Data Visualization & UI: Matplotlib, Pandas, PyQt
* AI & Computer Vision: Machine learning, Deep learning, Big data, Computer vision, HCI, HRC
* Model Architectures: CNN, RNN, GCN, VGG, ResNet, Inception, Mask-RCNN, YOLO, LSTM, GRU
* Cloud Computing: AWS EC2
*  Development Tools: Anaconda, CUDA, GPU programming, Google Colab, PyCharm, VS Code, Jupyter, Spyder
*  Operating Systems: Ubuntu, Linux, macOS, Windows
*  Embedded Systems & Robotics: Raspberry Pi, Nvidia Jetson Nano, ROS                     


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
