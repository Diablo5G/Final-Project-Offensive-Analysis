## Student Guide: Final Project Week

### Overview

We are working as a Security Engineer for X-CORP, supporting the SOC infrastructure. The SOC Analysts have noticed some discrepancies with alerting in the Kibana system and the manager has asked the Security Engineering team to investigate. 

We will start by confirming that newly created Kibana alerts are working, after which we will monitor live traffic on the wire to detect any abnormalities that aren't reflected in the alerting system. 

We need to report back all our findings to both the SOC manager and the Engineering Manager with appropriate analysis.


### Instructions

This week, we will work on final project by completing the following tasks individually:

- **Defensive Security**: Implement alerts and thresholds we determined would be effective in Project 2.

- **Offensive Security**: Assess a vulnerable VM and verify that the Kibana rules work as expected.

- **Network Forensics**: Use Wireshark to analyze live malicious traffic on the wire.

In addition to the above, we will be assigned to a group by your instructor on Day 1. After you complete each of the reports individually, we will work in groups to create a presentation on one aspect of the project: defensive, offensive, or networking. We will be provided templates to work on this presentation.  

### Lab Environment 

This week's lab environment is an Azure Classroom Lab, containing a modified version of the Project 2 network. In particular, it includes the following machines:


| Name       | Function   | IP Address   | Operating System   |
|----------|----------|------------|------------------|
| Azure Machine. |Jump Box/Azure Cloud Environment  | 192.168.1.1   | Microsoft Windows RPC            |
| Kali. |webserver    |Threat Actor     |192.168.1.90            |Linux 5.4.0 
| ELK Stack |Data Digestion, Logging, Systems Analysis Intrusion Detection System    | 192.168.1.100 |Ubuntu 18.04.1 LTS            |
| Capstone. |Sending logs to ELK Stack/Apache Web Server. |192.168.1.105. |Ubuntu 18.04.1 LTS. |
| Target1 |Load Balancer |192.168.1.110  |Linux (Apache httpd 2.4.10 (Debian)). |
| Target2 |Load Balancer |192.168.1.115  |Linux (Apache httpd 2.4.10 (Debian)). |


This is a diagram of the network:

---

![Network Topology](https://github.com/Diablo5G/Final-Project-Offensive-Analysis/blob/main/Images/Target1/Final%20Project-Resurrected.jpg)

---


### Report and Presentation Templates

To complete the project, we filled out the reports and slide decks linked below.  

- **Reports:** The Defensive Report and the Offensive Report relates to the Days 1 and 2, and the Network Report relates to Day 3.

> As we work on these aspects, I had completed the reports which all cover three stages - **Defensive Security**, **Offensive Security** and **Network Forensics**:  [Final Engagement](https://github.com/Diablo5G/Final-Project-Offensive-Analysis/blob/main/Resources/Nina%20Herbold-Final%20Project%20Report.pdf)

- **Presentations:** Our group represent as Resurrected Team to present Offensive Presentation as linked below;

> [Offensive Presentation](https://github.com/Diablo5G/Final-Project-Offensive-Analysis/blob/main/Resources/Final%20Project%20-%20Offensive%20Presentation.pdf)

---

#### Special thanks:

© Trilogy Education Services, a 2U, Inc., Instructor Jerry Arnold and TAs; Matt, Jansen and Micheal.

© The University of Texas at Austin Boot Camp, The Cybersecurity program. 
