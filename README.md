# 🛡️ Botnet PCAP Traffic Analysis

Network traffic investigation using statistical and behavioral analysis on a public botnet dataset.


## 📌 About This Project

This repository contains a structured network traffic analysis performed on a publicly available PCAP file.The objective was to determine whether an internal host exhibited automated or botnet-like communication patterns using packet inspection and statistical evaluation.The investigation focuses on traffic distribution, protocol usage, dominant hosts, and behavioral indicators.

## 📂 Dataset Details

File: botnet-capture-20110816-sogou.pcap
Format: PCAP (Ethernet)
Duration: 15 minutes 46 seconds
Total Packets: 20,663
Total Data Size: 18.5 MB

## 🔎 Source

The dataset is part of the CTU-13 botnet traffic collection developed by:

Czech Technical University in Prague
Stratosphere Laboratory

Official Dataset link: https://www.stratosphereips.org/datasets-ctu13

Official Dataset Reference:
CTU-13 Dataset

⚠️ The PCAP file is not included in this repository.Please obtain it from the official source.

## 🛠️ Tools Used

1. Wireshark
2. Protocol Hierarchy Analysis
3. IPv4 Conversation Statistics
4. TCP Stream Analysis
5. Traffic Asymmetry Evaluation
6. HTTP Request Inspection

## 🔍 What Was Analyzed?The investigation evaluated:

1. Dominant internal hosts
2. External communication patterns
3. Protocol distribution
4. HTTP request behavior
5. Traffic concentration
6. Indicators of automated activity

## 📊 Key Observations

Majority of outbound traffic originated from a single internal host.Communication was primarily HTTP over TCP.Repeated HTTP GET requests were observed toward multiple external endpoints.Traffic distribution was heavily concentrated toward one external IP address.Behavioral indicators suggested automated communication patterns.

## 🎯 Purpose

This project was completed to strengthen practical skills in:

1. Network traffic analysis
2. PCAP investigation
3. Behavioral anomaly detection
4. Command-and-control traffic identification
