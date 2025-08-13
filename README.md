# Network Anomaly Detection using Random Forests

## Overview

This project implements a machine learning solution for detecting network anomalies and potential security threats using Random Forest classification. Network anomaly detection identifies data points that deviate significantly from normal behavior patterns, which may indicate malicious activities, intrusions, or other security breaches.

## Dataset

The project uses a modified version of the NSL-KDD dataset, which is an improved version of the original KDD Cup 1999 dataset. NSL-KDD eliminates redundant entries and corrects imbalanced class distributions, making it a standard benchmark for intrusion detection systems.

The dataset contains network connection records with 41 features and includes both normal and attack traffic. Each record is labeled as either:
- Normal traffic
- DoS (Denial of Service) attacks
- Probe attacks (surveillance and scanning)
- Privilege escalation attacks
- Access attacks (unauthorized access attempts)

Dataset source: https://academy.hackthebox.com/storage/modules/292/KDD_dataset.zip
