# CyberSentinel — Machine Learning Model Plan

## 1. PhishNet Models

### Model A: URL Phishing Classifier
Objective: Identify potentially malicious URLs.

Initial features:
- URL length
- Number of special characters
- HTTPS indicator
- Domain structure
- Suspicious URL patterns

Model candidates:
- Logistic Regression
- Random Forest
- Gradient Boosting

### Model B: Email Phishing Classifier
Objective: Classify suspicious email content.

Initial features:
- Text patterns
- Suspicious links
- Urgency-related language
- Message structure

Model candidates:
- TF-IDF with Logistic Regression
- Naive Bayes

## 2. ThreatLens Model

### Security Log Anomaly Detector
Objective: Identify unusual patterns in security logs.

Initial features:
- Event type
- Timestamp
- Event frequency
- Failed authentication counts
- Unusual event sequences

Model candidates:
- Isolation Forest
- Random Forest for event classification

## 3. Model Evaluation

We will evaluate models using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

For imbalanced datasets, precision and recall will receive particular attention.

## 4. Development Workflow

Dataset Collection → Data Cleaning → Feature Engineering → Model Training → Evaluation → Model Export → Android Integration

## 5. Important Principle

Models will be trained and tested using documented datasets. Their performance will be measured before integration into CyberSentinel.