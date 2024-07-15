# 5breaker

Intel Unnati Industry Training- Summer 2024

Team - 5breaker

Participants -  
1. Mounish (Team Lead)

2. S Olive Keran

3. Ronal Roy

4. Justin Joseph

5. Luzvan Vimalnathan


# INNOVATIVE MONITORING SYSTEM FOR TELEICU PATIENTS USING VIDEO PROCESSING AND DEEP LEARNING 


## Table of Contents
- [Description](#description)
- [Dataset](#-dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Model Performance](#model-performance)
- [Future Work](#-future-work)

## Description
- People Detection Model: Identifies various people in the ICU Room (nurse, intensivist, family member, patient).
- Movement Detection Model: Detects patient movement to alert healthcare professionals.

##  Dataset

The data for this project was primarily sourced from various YouTube videos, which provided a diverse range of ICU scenarios. This rich dataset allowed us to create a robust and versatile ICU monitoring system.

1. **Statement 1**: For the purpose of detecting individuals in the ICU, we used the full ICU room video data. This comprehensive dataset enabled us to train our model to identify various people in the ICU room, such as nurses, doctors, patients, and family members.

A subset of this data is publicly available on my github repo for further exploration and use. You can access it [here](https://github.com/hemantkumar76/Innovative-Monitoring-System-for-TeleICU-Patients-Using-Video-Processing-and-Deep-Learning/tree/main/Video%20Data).

## Project Structure
<pre>
ICU Monitoring System/
├── Statement1/
│   ├── data/
│   ├── models/
│   ├── notebooks/
│   └── Statement_1.ipynb
├── Statement2/
│   ├── data/
│   ├── models/
│   ├── notebooks/
│   └── Statement_2.ipynb
├── Video Data/
│   ├── video1.mp4
│   └── video2.mp4
├── LICENSE
├── Problem_Statement.pdf
├── README.md
└── requirements.txt
</pre>

## Installation
To install the necessary dependencies, run:
```bash
pip install -r requirements.txt
```

We utilized a diverse tech stack to build this project:

- **YOLOv8**: Used for object detection and classification.
- **Python**: Served as the primary language for scripting and model development.
- **OpenCV**: Handled video processing tasks.
- **NumPy**: Facilitated numerical operations.
- **Streamlit**: Enabled us to create the web application interface.
- **PyTorch**: Assisted in loading and running the YOLO models.
- **Roboflow**: Managed dataset labeling and organization.

##  Model Performance

Our model has demonstrated excellent performance in detecting ICU personnel and patient movements. Here are the results:

### Statement 1 Results:

- Precision (B): 0.9947373506120167
- Recall (B): 0.9438166761139646
- mAP50 (B): 0.995
- mAP50-95 (B): 0.550242144587505
- Fitness: 0.5947179301287545

## Future Work

While the current system effectively identifies ICU personnel and detects patient movements, there are several avenues for future improvements:

- **Enhanced Detection Models**: We plan to integrate more advanced models or improve existing models to increase accuracy and reduce false positives.
- **Real-Time Monitoring**: We aim to implement real-time video processing to provide immediate alerts and notifications to healthcare professionals.
- **Expanded Dataset**: We intend to collect more diverse and comprehensive datasets to improve model robustness and adaptability to various ICU environments.
- **User Interface Enhancements**: We look forward to improving the user interface to provide more detailed analytics and visualization tools for healthcare providers.
- **Integration with Hospital Systems**: We aspire to connect the monitoring system with hospital management systems for seamless data integration and better patient management.
