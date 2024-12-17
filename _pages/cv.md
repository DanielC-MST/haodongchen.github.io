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
* B.S. in Vehicle Engineering, Hefei University of Technology, 9/2012-6/2016
* M.E. in Mechanical Manufacture and Automation, Hefei University of Technology, 9/2016-6/2019
* Ph.D. in Mechanical Engineering, Missouri University of Science and Technology, 8/2019 - 5/2024

Work experience
======
* 2024 May.-Present.: Post Doctoral Associate
  *  University of Maryland, Department of Mechanical Engineering, College Park, MD, US
  *  Duties included:
      * Designed a web-based application using TypeScript (frontend) and Python (backend) to enable online machine learning education.
      *	Collaborated with international companies to implement AI-driven solutions, improving process optimization.
      *	Developed proposals for projects with Siemens, Microsoft, and KU Leuven for NSF, NIST, and DOE.
      *	Developed similarity-based learning models using PHM datasets to predict equipment failures and optimize maintenance schedules.
      *	Implemented domain adaptation techniques with the CWRU dataset to enhance model generalization across diverse industrial settings.
      *	Taught Industrial AI course to PhD and Master students, covering AI models, PHM, and machine learning in smart manufacturing

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

  
Skills
======
* Programming Languages: Python, C++, MATLAB, SQL, JaveScript, TypeScript  
* Machine Learning Frameworks: TensorFlow, PyTorch, Keras, Scikit-learn
* Data Visualization & UI: Matplotlib, Pandas, PyQt
* AI & Computer Vision: Machine learning, Deep learning, Big data, Computer vision, HCI, HRC
* Model Architectures: CNN, RNN, GCN, VGG, ResNet, Inception, Mask-RCNN, YOLO, LSTM, GRU
* Cloud Computing: AWS EC2
*  Development Tools: Anaconda, CUDA, GPU programming, Google Colab, PyCharm, VS Code, Jupyter, Spyder
*  Operating Systems: Ubuntu, Linux, macOS, Windows
*  Embedded Systems & Robotics: Raspberry Pi, Nvidia Jetson Nano, ROS                     


**Journal Review Activities**
======
•	Engineering Applications of Artificial Intelligence (EAAI)

•	IEEE Transactions on Circuits and Systems for Video Technology (TCSVT)

•	Journal of Intelligent Manufacturing

•	ASME Journal of Computing and Information Science in Engineering

•	ASME Journal of Engineering and Science in Medical Diagnostics and Therapy 

•	ASME Journal of Mechanisms and Robotics

•	ASME Open Journal of Engineering Journal of Intelligent Manufacturing Science China Technological Sciences

•	ASME International Mechanical Engineering Congress & Exposition (IMECE) 2019 - 2023 Conference

•	International Conference on Computer Science and Application Engineering (CSAE) 2019

Teaching
======
* Industrial Artificial Intelligence (ENME691, University of Maryland, Fall 2024)

  
Research
======
  <ul>{% for post in site.research %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
News
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
