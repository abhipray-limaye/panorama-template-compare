# Panorama Template Comparison Tool

A browser-based utility for Palo Alto Panorama administrators 
to detect configuration drift and discrepancies across 
Panorama templates — without any live API interaction.

## 🔍 Problem It Solves
In large Panorama environments, templates across device groups 
can drift over time due to manual changes, failed pushes, or 
inconsistent updates. Identifying these discrepancies manually 
is time-consuming and error-prone.

## ⚙️ How It Works
1. Export XML backup from Panorama
2. Open the tool locally in any browser
3. Upload the XML file
4. Tool parses and compares template configurations
5. Discrepancies displayed on screen and exported to CSV

## 🛡️ Safety First
- Runs entirely in the browser — no server, no API calls
- No live connection to Panorama at any point
- Safe to use in production environments

## 📋 Output
- On-screen summary of configuration differences
- CSV export for remediation tracking and change management

## 🧰 Built With
- HTML · JavaScript · XML parsing

## 📌 Use Case
- Panorama template audits
- Pre-migration configuration validation
- Change management documentation
- Compliance verification across firewall estates

## 👤 Author
Abhipray Limaye — Senior Cloud & Network Security Specialist  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-abhipray--limaye-blue)](https://linkedin.com/in/abhipray-limaye)
