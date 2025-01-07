---
title: "Implementing Eye Movement Tracking for UAV Navigation"
collection: research
type: "Research"
permalink: /research/research-project-5-uav
layout: single
slug: "research-project-5-uav"
image_width: "500px"  # Custom width for this post's image
excerpt: "<div>
    <p>This project explores a novel approach to controlling unmanned aerial vehicles (UAVs) through electrooculography (EOG) based eye movement tracking. By developing an interface that translates eye movements into UAV navigation commands, the system integrates biometric technology into UAV control, offering precise and efficient maneuvering capabilities. The research demonstrates the potential of EOG in enhancing human-robot interaction, particularly benefiting individuals with mobility or communication challenges.</p>
    <div style='text-align: center;'>
            <img src='https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-5-uav.jpg' alt='Eye Movement Tracking for UAV Navigation' width= "800px" />
    </div>
</div>"
---
    
<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-5-background.jpg" alt="Eye Movement Tracking for UAV Navigation" width="800" />
</div>

## Goals
- **Develop an EOG-Based UAV Control Interface:** Create an interface that accurately translates eye movements into UAV navigation commands using electrooculography (EOG) signals.
- **Enhance Accessibility:** Provide a control mechanism for individuals with mobility or communication impairments, enabling intuitive and hands-free UAV operation.
- **Achieve Real-Time Performance:** Ensure the system processes EOG signals and responds with UAV movements in real-time, maintaining precision and efficiency in various environments.
- **Integrate Robust Noise Filtering:** Implement advanced filtering techniques to minimize noise and artifacts in EOG signals, enhancing the reliability of eye movement detection.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-5-goal.jpg" alt="Project Goals" width="700" />
</div>

## Key Findings
- **EOG Signal Acquisition and Processing:** Utilized the BioAmp EXG Pill analog front-end (AFE) board to acquire and amplify EOG signals, implementing bandpass filtering to isolate relevant eye movement frequencies.
- **Finite State Machine for Command Interpretation:** Developed a finite state machine and thresholding algorithm to categorize eye movements (left, right, neutral) and convert them into UAV control signals.
- **Real-Time UAV Control Implementation:** Successfully integrated the EOG-based control system with the DJI Tello UAV, enabling precise navigation commands transmitted via an internet connection.
- **Noise Minimization Techniques:** Applied Driven Right Leg (DRL) circuitry and bandpass filtering to reduce common-mode noise and artifacts, ensuring cleaner EOG signal acquisition.
- **User-Friendly Hardware Setup:** Designed a comprehensive hardware setup that includes electrode placement, signal amplification, and seamless communication between the EOG system and the UAV.
- **Demonstrated Practical Applications:** Showcased the system's effectiveness in real-world scenarios, highlighting its potential in assistive technology and intuitive human-robot interaction.

<div style="text-align: center;">
    <img src="https://DanielC-MST.github.io/haodongchen.github.io/images/research-project-5-findings.jpg" alt="Key Contributions" width="900" />
</div>

## Technologies Utilized
- **Electrooculography (EOG):** For capturing and interpreting eye movement signals.
- **Analog Front-End (AFE) Systems:** BioAmp EXG Pill board for signal acquisition and amplification.
- **Signal Processing:** Bandpass filtering and thresholding algorithms to clean and categorize EOG signals.
- **Finite State Machine (FSM):** For translating categorized eye movements into UAV control commands.
- **UAV Hardware:** DJI Tello UAV for demonstration of eye-controlled navigation.
- **Software Development:** Arduino for signal processing and command transmission, alongside custom scripts for real-time UAV control.
- **Hardware Components:** Silver electrodes for EOG signal detection, Logitech C920 webcam for potential additional tracking, and NVIDIA GeForce RTX 3090 for any computational needs.
- **Communication Protocols:** USB serial communication and Wi-Fi for transmitting control signals to the UAV.


## Impact
This project significantly advances the field of human-robot interaction by introducing an intuitive and accessible method for UAV control using eye movements. The integration of EOG technology into UAV navigation offers a hands-free control mechanism that is particularly beneficial for individuals with physical impairments, enhancing their ability to interact with and command drones. Furthermore, the real-time performance and high accuracy of the system demonstrate its viability for practical applications in various environments, including assistive technology, surveillance, and remote operations. By minimizing noise and ensuring reliable signal processing, the system sets a new standard for biometric-based UAV control interfaces, paving the way for future innovations in accessible robotics and intelligent automation.

## Selected Publications
1. Zendehdel, N, Chen, H, Song, YS, & Leu, MC. "Implementing Eye Movement Tracking for UAV Navigation." Proceedings of the 2024 International Symposium on Flexible Automation. 2024 International Symposium on Flexible Automation. Seattle, Washington, USA. July 21–24, 2024. V001T08A004. ASME. [doi](https://doi.org/10.1115/ISFA2024-140778)
