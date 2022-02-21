# <center>Data Mining and data wrangling.</center>
### This project is to show case my data preliminary pre-processing skills to bring down complex data formats to usable formats for better decision making and analytics which usually takes 70% of the time while working on in any data science project. This project doesn't include visualization, EDA, statistics or model development.

### <u>Use case</u>: 
1. SOAR is a Security Orchestration and automated response platform used by SOC analysts to drive the complete life cycle of a threat from alert generation till it's remediation. 
2. The first functionality of SOAR platform is recieving an alert. There after, SOC analyst creates a case out of the alert and fills list of check boxes, text boxes and drop downs for the same. Within those fields, there's an important field 'Threat Severity Level' that decides the priority of the threat. 
3. Usually the SOC analyst populates this field based on his/her experience and domain understanding. This manual process leads to incorrect prioritization of alerts because of the presence of false positives in the alerts and hence a lot of times threats causing more damange are attended later leading to huge loss of money, privacy and makes the institution vulnerable.

### Solution: This project is to make the life of a SOC analyst easier by automating assigning Threat Severity Level  to help them prioritize the alerts and attend high priority attacks first ignoring false positive alerts.

### Dataset:
1. Open source data: https://www.circl.lu/doc/misp/feed-osint/ This data is used by testers on SOAR platform to simulate life cycle of an alert. Complete information about the data and it's field is provided on https://www.circl.lu/doc/misp/
2. This data forms backend of the framework when alerts are generated.