# Facial Landmark-Based Authentication System Using Machine Learning

## Overview

This project presents a privacy-focused facial authentication system designed for secure single-user verification. The system performs authentication completely offline using facial landmark analysis, One-Class SVM, and Euclidean distance verification.

Unlike traditional cloud-based facial recognition systems, all biometric processing occurs locally on the device, ensuring user privacy and data security.

## Problem Statement

Most existing facial authentication systems depend on cloud services, require large datasets, and raise privacy concerns. This project aims to provide a lightweight, offline, and secure authentication solution suitable for personal devices and edge computing environments.

## Key Features

* Offline authentication
* Facial landmark extraction using MediaPipe FaceMesh
* One-Class SVM-based user verification
* Euclidean distance similarity matching
* Privacy-preserving local processing
* Lightweight and suitable for edge devices
* No cloud dependency

## Technologies Used

* Python
* Machine Learning
* OpenCV
* MediaPipe FaceMesh
* Scikit-Learn
* NumPy

## System Workflow

1. Capture facial image using camera
2. Extract 468 facial landmarks
3. Generate facial feature vectors
4. Verify user using One-Class SVM
5. Perform Euclidean distance matching
6. Grant or deny access

## Applications

* Laptop and PC authentication
* Smart door locks
* Secure application access
* Vehicle access control
* Personal biometric security systems

## Future Enhancements

* Real-time liveness detection
* Mobile application integration
* Multi-factor authentication
* Deep learning-based verification

## Project Status

Currently this repository contains the project report. Source code and implementation files will be added in future updates.

## Author

Akshitha Anyam

