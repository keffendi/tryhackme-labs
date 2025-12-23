# SOC Fundamentals (TryHackMe)

This project documents foundational Security Operations Center (SOC) concepts and the role of a Level 1 SOC analyst using the TryHackMe SOC Fundamentals room.

## Objective
To understand how a SOC operates, including analyst roles, alert triage concepts, and escalation processes in a simulated environment.

## Platform
TryHackMe – SOC Fundamentals room

---

## Task 1 – Introduction to SOC
**Description:**  
Introduces the concept of a Security Operations Center (SOC), its purpose, and the importance of monitoring and incident response.

**Evidence Screenshot:**  
![Task 1 Intro](Task1.png)

---

## Task 3 – People (SOC Roles)
**Description:**  
Overview of SOC team roles and responsibilities, including Level 1, Level 2, and Level 3 analysts, and support roles like Detection Engineers and SOC Managers.

**Evidence Screenshot:**  
![Task 3 Roles](Task3.png)

---

## Task 4 – Process (Alert Triage)
**Description:**  
Explains the alert triage process, including analyzing alerts, prioritizing by severity, answering the 5 Ws (What, When, Where, Who, Why), and escalating as needed.

**Evidence Screenshot:**  
![Task 4 Process](Task4.png)

---

## Task 6 – Practical Exercise: Port Scan Alert
**Description:**  
Simulated Level 1 analyst investigation of a port scanning alert. Reviewed SIEM logs, answered the 5 Ws, and validated the alert as authorized internal scanning.

**Evidence Screenshots:**  
![Task 6 Scenario](Task6.png)  
![Task 6 Alerts](SIEM-alerts.png)  
![Task 6 SIEM](SIEM-solution.png)  
![Task 6 Completed](Task6-success.png)  


**Analysis:**  
Logs showed repeated connection attempts across multiple ports from internal host 10.0.0.8.

**Action / Decision:**  
Alert validated as a false positive; no escalation required.

**Lesson Learned:**  
Verifying alerts against internal activities prevents unnecessary escalation and reduces analyst workload.

---

## Task 7 – Conclusion
**Description:**  
Summarizes key concepts learned, including SOC roles, alert triage process, and the importance of validating alerts before escalation.

**Evidence Screenshot:**  
![Task 7 Conclusion](Task7.png)

---

