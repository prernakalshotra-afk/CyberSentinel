# CyberSentinel — System Architecture

## 1. Architecture Overview

CyberSentinel follows a modular, offline-first architecture.

## 2. Application Layers

### Presentation Layer
- Flutter UI
- Dashboard
- PhishNet screen
- ThreatLens screen
- Scan history

### Intelligence Layer
- URL classification model
- Email phishing classification model
- Security log anomaly detection model
- Risk scoring engine

### Data Layer
- SQLite local database
- Scan records
- Security event records
- Model metadata

## 3. Data Flow

User Input → Validation → AI/ML Model → Risk Analysis → Result Explanation → Local Storage → Dashboard

## 4. Model Development
Python will be used to prepare datasets, train models, evaluate performance and export compatible models.

## 5. Deployment
The Android application will use on-device inference wherever technically practical.

## 6. Security Principles
- No unnecessary collection of personal information.
- Local storage for scan history.
- Transparent explanations for detection results.
- Safe handling of untrusted URLs and logs.

## 7. Future Enhancements
- Optional threat intelligence updates.
- Advanced event correlation.
- Exportable incident reports.