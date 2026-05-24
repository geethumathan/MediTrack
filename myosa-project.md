---
publishDate: 2026-05-24T00:00:00Z
title: MediTrack
excerpt: Smart medication adherence monitoring system using MYOSA IoT sensors and intelligent behavior tracking.
image: cover-image.jpg

tags:
  - IoT
  - Healthcare
  - Medication
---

> Smart medication monitoring system that tracks real usage behavior and improves adherence.

---

## Overview

MediTrack is a smart medication monitoring system built using the MYOSA IoT platform. The system helps patients maintain proper medication habits by tracking real medicine usage behavior instead of only sending reminders.

The project uses sensors to detect when a medicine container is opened and verifies real interaction using motion sensing. The system identifies whether medication was taken on time, delayed, or missed.

MediTrack is designed for:
- Elderly patients
- Chronic disease patients
- Caregivers
- Home healthcare monitoring

The goal of the system is to improve long-term medication adherence and reduce missed doses through intelligent monitoring and feedback.

---

## Demo / Examples

### Images

<p align="center">
  <img src="/assets/images/myosa-project/project-image.jpg" width="800"><br/>
  <i>Project image caption</i>
</p>

### Videos

<video controls width="100%">
  <source src="/demo-video.mp4" type="video/mp4">
</video>

---
## Features (Detailed)

### 1. Medication Usage Detection
The magnetic reed switch detects when the medicine container is opened or closed.

### 2. Motion Verification
The MPU6050 motion sensor confirms actual interaction with the medicine container and prevents false detections.

### 3. Smart Adherence Tracking
The system checks whether medication was taken:
- On time
- Delayed
- Missed

### 4. OLED Status Display
The OLED screen displays medication status and adherence information in real time.

### 5. Alert System
A buzzer alerts the user when medication is missed or delayed.

### 6. IoT-Based Monitoring
The MYOSA ESP32 board processes sensor data and can support wireless monitoring and future dashboard integration.


## Usage Instructions

```bash
python main.py
```

---

## Tech Stack

* Python
* Arduino
* Flask
* OpenCV

---

## Requirements / Installation

```bash
pip install flask opencv-python
```

---

## File Structure

```plaintext
/myosa-project
  ├── main.py
  ├── project-image.jpg
  ├── demo-video.mp4
  └── myosa-project.md
```

---

## License

MIT License

---

## Contribution Notes

Contributions and improvements are welcome.