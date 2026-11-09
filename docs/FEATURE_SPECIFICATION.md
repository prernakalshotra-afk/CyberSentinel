# CyberSentinel — Feature Specification

## 1. User Dashboard
- Display security overview.
- Show recent scans and alerts.
- Provide navigation to both intelligence modules.

## 2. PhishNet — Phishing Detection

### Input
- Website URL
- Email text

### Processing
- Validate input.
- Extract relevant features.
- Run phishing classification models.
- Calculate a risk score.

### Output
- Classification: Safe, Suspicious or High Risk.
- Risk score.
- Reasons behind the prediction.
- Scan timestamp.

## 3. ThreatLens — Security Log Intelligence

### Input
- Uploaded security log files.
- Supported formats: CSV and TXT initially.

### Processing
- Parse and validate log records.
- Extract event features.
- Detect unusual patterns.
- Classify suspicious events.

### Output
- Event severity.
- Anomaly score.
- Explanation of detected patterns.
- Incident summary.

## 4. Scan History
- Store previous scan results locally.
- Search and filter records.
- View individual reports.

## 5. Reports
- Generate incident summaries.
- Export reports in a readable format.

## 6. Offline Support
- Core detection features should work without internet.
- Online intelligence updates will be optional.

## 7. Limitations
- Predictions are risk indicators, not proof of an attack.
- Unknown threats may not always be detected.
- Results require careful interpretation.