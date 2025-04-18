# daksh-net
Network Traffic Anomaly Detection using Google Gemini
Introduction
This project focuses on automated detection of anomalies in network traffic data using Google Gemini, a large language model (LLM). The goal is to analyze network packet captures, identify suspicious patterns, and provide actionable security insights. The solution is designed for cybersecurity teams to quickly detect potential threats such as ARP poisoning, network scanning, and protocol misuse.

Tech Stack

Python 3

pandas (for data processing)

Google Generative AI (Gemini API)

Jupyter Notebook

Features

Automated loading and preprocessing of network traffic data (CSV format)

Extraction of statistical features (packet counts, unique sources/destinations, protocol distribution)

Detection of network anomalies using Google Gemini LLM

Severity classification for each detected anomaly

Detailed investigation steps and recommendations for each finding

JSON-formatted output for easy integration with other tools
