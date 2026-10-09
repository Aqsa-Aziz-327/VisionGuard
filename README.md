# VisionGuard: Intelligent CCTV-Based Employee Identification and Suspicious Activity Monitoring System

## Project Overview
VisionGuard is an intelligent, web-based CCTV monitoring system designed to enhance physical security in industrial, corporate, and academic environments. Leveraging existing CCTV infrastructure, VisionGuard automatically identifies enrolled employees using computer vision and detects rule-based suspicious activities in real time.

All security events are recorded in a centralized PostgreSQL database linked by Employee ID and full name, enabling authorized security personnel to search records, evaluate alert evidence, and generate comprehensive reports.

---

## Core Features & Objectives
* **Employee Identification:** Real-time facial recognition on CCTV streams using ArcFace and FAISS, targeting >= 90% Rank-1 accuracy.
* **Suspicious Activity Detection:** Rule-based detection for unauthorized entry, after-hours presence, loitering, and unknown person presence in restricted zones with a target recall of >= 85%.
* **Centralized Database:** Automated logging of sightings and security events associated with Employee ID and full name (or labeled as Unknown for non-enrolled individuals).
* **Web Dashboard:** Real-time security alerts delivered within 5 seconds, event status tracking (Pending, Confirmed, False Alarm), employee search, and exportable reports.
* **Security & Privacy:** Role-based access control (RBAC), system audit logging, and data retention policy management.

---

## Tech Stack

| Domain | Tools & Technologies |
| :--- | :--- |
| **Languages & Frameworks** | Python, FastAPI, JavaScript, React |
| **Database** | PostgreSQL |
| **Computer Vision & Tracking** | OpenCV, FFmpeg, Ultralytics YOLO, ByteTrack, InsightFace (SCRFD & ArcFace), FAISS |
| **Machine Learning & Runtime** | PyTorch, ONNX Runtime, scikit-learn |
| **Design, Testing & DevOps** | Figma, draw.io, pytest, CVAT, Docker, Git, GitHub |

---

## Project Contributors

| Name | Registration Number | Role |
| :--- | :--- | :--- |
| **Aqsa Aziz** | NUM-BSCS-2023-22 | Project Team Lead / Lead Developer |
| **Iqra Gul** | NUM-BSCS-2023-35 | Core Developer |
| **Aliya Ashraf** | NUM-BSCS-2023-08 | Core Developer |
| **Areeba Tahir** | NUM-BSCS-2024-15 | Core Developer |

---

## Academic Supervision

* **Requirement Provider / Project Supervisor:** Mr. Ammar Ahmad Khan (ammar.ahmad@namal.edu.pk)
* **Course Instructor / Evaluator:** Ms. Asiya Batool (asiya.batool@namal.edu.pk)
* **Department:** Department of Computer Sciences, Namal University, Mianwali

---
