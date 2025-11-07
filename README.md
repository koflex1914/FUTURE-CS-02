# FUTURE_CS_02 – SOC Task 2: Security Alert Monitoring & Incident Response


This repository contains my work for Task 2 of my cybersecurity internship.
The objective was to analyze simulated security logs using a SIEM tool (Splunk Enterprise), detect suspicious activity, classify incidents, and generate a report with recommendations.



## 🧠 What I Did
Used Splunk Cloud to ingest and analyze structured .txt log data
Wrote custom SPL queries to detect security incidents
Identified and classified multiple malware threats (Trojan, Ransomware, Rootkit, etc.)
Created an incident response report detailing the findings
Recommended remediation actions based on the alerts



## 📁 Files in This Repo

### File	Description
Future_Interns_SOC Task2_sample_logs.txt - The sample log file uploaded to Splunk

incident_report.md - Full incident response report with findings and recommendations

Malware Detection.png malware detected.png - Screenshot showing malware detection in Splunk

Failed Login.png FAILED LOGIN.png  - Screenshot showing failed login attempts



## 🧾 Sample SPL (Search Processing Language) Query Used
source="SOC_Task2_Sample_Logs.txt" host="vbox" index="soc_task2" sourcetype="CS  SOC CSV" | head 100
| search threat=malware detected
I also used the spl to extract fields like user, ip, action, and threat to support analysis.

## Preview;
<img width="1919" height="1037" alt="image" src="https://github.com/user-attachments/assets/824656d6-90c2-4c5a-8561-2a53a1f2b83d" />

<img width="1919" height="894" alt="image" src="https://github.com/user-attachments/assets/266a50df-989d-4161-8bff-5dd164dc44e4" />


## ✅ Skills Gained
SIEM operation (Splunk Enterprise)

Writing and executing SPL queries

Field extraction

Log analysis and threat detection

Writing a professional incident response report
