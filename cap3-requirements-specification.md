# **Capítulo III: Requirements Specification**

## **3.1. User Stories**

User Stories describe system requirements from the end-user perspective, prioritizing the functionality and value that each action provides. In the **EnerSafe IoT project**, these stories focus on electrical risk prevention, real-time monitoring, and operational safety.

Each story defines the user, the objective, and includes acceptance criteria to validate system behavior.

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | :---: | :---: |
| E-1 | IoT Infrastructure Monitoring | Centralized monitoring of electrical infrastructure | N/A | N/A |
| US-1 | Overload Monitoring | As an operator, I want to detect overloads to prevent failures. | Given sensors, When overload detected, Then alert generated | E-1 |
| US-2 | Temperature Monitoring | As an operator, I want to monitor temperature to detect anomalies. | Given sensors, When threshold exceeded, Then alert | E-1 |
| US-3 | Vibration Monitoring | As a technician, I want to detect vibrations to identify faults. | Given sensors, When anomaly detected, Then log event | E-1 |
| US-4 | Humidity Monitoring | As an operator, I want to detect humidity to prevent corrosion. | Given sensors, When high humidity, Then alert | E-1 |
| US-5 | Real-Time Data | As an operator, I want real-time data to monitor status. | Given system, When accessed, Then live data displayed | E-1 |
| US-6 | Equipment Status | As an operator, I want to see equipment status. | Given system, When accessed, Then status shown | E-1 |
| US-7 | Historical Data | As an analyst, I want historical data for analysis. | Given data, When accessed, Then history shown | E-1 |
| US-8 | Data Collection | As a system, I want automatic data collection. | Given sensors, When active, Then data stored | E-1 |
| US-9 | Data Validation | As a system, I want to validate data. | Given data, When invalid, Then flagged | E-1 |
| US-10 | Data Export | As a manager, I want to export data. | Given data, When export, Then file generated | E-1 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-2 | Alert and Risk Management | Risk detection and alert system | N/A | N/A |
| US-11 | Alert Generation | As system, I want alerts for anomalies. | Given anomaly, When detected, Then alert | E-2 |
| US-12 | Mobile Alerts | As technician, I want alerts on phone. | Given alert, When triggered, Then push sent | E-2 |
| US-13 | Alert Priority | As manager, I want prioritized alerts. | Given alerts, When shown, Then ordered | E-2 |
| US-14 | Incident Reporting | As technician, I want report incidents. | Given incident, When reported, Then saved | E-2 |
| US-15 | Auto Notification | As system, I want notify stakeholders. | Given event, When occurs, Then notify | E-2 |
| US-16 | Alert Escalation | As system, I want escalate alerts. | Given unattended alert, Then escalate | E-2 |
| US-17 | Alert History | As user, I want view alerts. | Given history, When accessed, Then display | E-2 |
| US-18 | Risk Dashboard | As manager, I want risk panel. | Given alerts, When open, Then dashboard | E-2 |
| US-19 | Delay Alerts | As system, I want detect delays. | Given delay, When detected, Then alert | E-2 |
| US-20 | Incident Reports | As manager, I want reports. | Given incidents, When requested, Then report | E-2 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-3 | Predictive Maintenance | Data-driven maintenance system | N/A | N/A |
| US-21 | Data Storage | As system, I want store data. | Given data, When received, Then stored | E-3 |
| US-22 | Trend Analysis | As analyst, I want trends. | Given data, When analyzed, Then patterns | E-3 |
| US-23 | Failure Prediction | As system, I want predict failures. | Given data, When analyzed, Then prediction | E-3 |
| US-24 | Maintenance Planning | As manager, I want schedule maintenance. | Given risk, Then schedule | E-3 |
| US-25 | Maintenance Logs | As technician, I want logs. | Given task, When done, Then recorded | E-3 |
| US-26 | Equipment History | As user, I want history. | Given equipment, Then display | E-3 |
| US-27 | Health Indicators | As system, I want KPIs. | Given data, Then indicators | E-3 |
| US-28 | Maintenance Alerts | As system, I want alerts. | Given condition, Then notify | E-3 |
| US-29 | Optimization | As manager, I want optimize processes. | Given data, Then improve | E-3 |
| US-30 | Maintenance Reports | As manager, I want reports. | Given data, Then report | E-3 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-4 | Dashboard and Visualization | Data visualization and analytics | N/A | N/A |
| US-31 | General View | As manager, I want overview. | Given system, Then dashboard | E-4 |
| US-32 | Real-Time View | As operator, I want live data. | Given system, Then real-time | E-4 |
| US-33 | Filters | As user, I want filters. | Given data, Then filtered | E-4 |
| US-34 | Charts | As analyst, I want graphs. | Given data, Then charts | E-4 |
| US-35 | Alert Panel | As operator, I want alerts. | Given alerts, Then display | E-4 |
| US-36 | Event History | As user, I want events. | Given history, Then list | E-4 |
| US-37 | Export | As user, I want export. | Given data, Then file | E-4 |
| US-38 | Multiuser | As system, I want multi-access. | Given users, Then allow | E-4 |
| US-39 | Custom Dashboard | As user, I want customize. | Given config, Then apply | E-4 |
| US-40 | KPI Display | As manager, I want KPIs. | Given data, Then KPIs | E-4 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-5 | Mobile and Safety | Mobile and field operations | N/A | N/A |
| US-41 | Mobile Access | As technician, I want mobile app. | Given app, Then access | E-5 |
| US-42 | Protocols | As technician, I want protocols. | Given app, Then display | E-5 |
| US-43 | Simulations | As technician, I want simulations. | Given module, Then simulate | E-5 |
| US-44 | Risk Maps | As operator, I want maps. | Given data, Then map | E-5 |
| US-45 | Evacuation Routes | As technician, I want routes. | Given map, Then routes | E-5 |
| US-46 | Field Reports | As technician, I want report. | Given event, Then save | E-5 |
| US-47 | Offline Mode | As system, I want offline. | Given offline, Then sync | E-5 |
| US-48 | Push Notifications | As technician, I want alerts. | Given event, Then notify | E-5 |
| US-49 | GPS Tracking | As system, I want track. | Given device, Then track | E-5 |
| US-50 | Secure Access | As system, I want security. | Given login, Then allow | E-5 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-6 | Safety Culture | Organizational safety system | N/A | N/A |
| US-51 | Incident Report | As technician, I want report. | Given incident, Then stored | E-6 |
| US-52 | Risk Register | As user, I want risks. | Given risk, Then stored | E-6 |
| US-53 | Incentives | As company, I want incentives. | Given report, Then reward | E-6 |
| US-54 | Safety Evaluation | As manager, I want evaluate. | Given data, Then report | E-6 |
| US-55 | Training | As technician, I want training. | Given module, Then content | E-6 |
| US-56 | Audit | As auditor, I want audit. | Given data, Then report | E-6 |
| US-57 | Collaboration | As manager, I want share data. | Given authorization, Then share | E-6 |
| US-58 | Compliance | As system, I want compliance. | Given rules, Then validate | E-6 |
| US-59 | Awareness | As company, I want awareness. | Given system, Then improve | E-6 |

---

| Epic / Story ID | Title | Description | Acceptance Criteria | Related to (Epic ID) |
| :---: | ----- | ----- | ----- | :---: |
| E-7 | API and Integration | IoT system integration | N/A | N/A |
| US-60 | IoT API | As developer, I want API integration. | Given request, Then store data | E-7 |

---
## **3.2 Impact Mapping**

*Impact Mapping* was used as a strategic tool to connect business objectives with the expected actions and behaviors of users. This method allowed us to identify the main actors, their impact on achieving goals, and the deliverables necessary to drive those changes. In the context of **EnerSafe IoT**, the impact map facilitated alignment between *Business Goals* and the requirements of the IoT-based monitoring system, ensuring that each development directly contributes to improving electrical safety, operational efficiency, and risk prevention in the energy sector.

![Impact Mapping EnerSafe IoT](assets/images/chap3/Impact%20map%202.png)


## **3.3 Product Backlog**

The *Product Backlog* is the prioritized list of features, improvements, and technical requirements that guide the incremental development of the EnerSafe IoT system. It is based on the defined *User Stories* and aligned with the project’s objective of improving electrical safety through IoT monitoring and predictive maintenance.

---

### **Product Backlog Prioritization**

| #Orden | User Story ID | Title | Description | Story Points (1 / 2 / 3 / 5 / 8) |
| :---: | :---: | ----- | ----- | :---: |
| 1 | US-1 | Overload Monitoring | As an operator, I want to detect electrical overloads so that I can prevent critical failures. | 5 |
| 2 | US-2 | Temperature Monitoring | As an operator, I want to monitor equipment temperature so that I can detect anomalies. | 5 |
| 3 | US-3 | Vibration Monitoring | As a technician, I want to detect abnormal vibrations so that I can identify mechanical issues. | 5 |
| 4 | US-4 | Humidity Monitoring | As an operator, I want to monitor humidity levels so that I can prevent corrosion. | 5 |
| 5 | US-5 | Real-Time Visualization | As an operator, I want to visualize real-time data so that I can make quick decisions. | 5 |
| 6 | US-6 | Equipment Status | As an operator, I want to see equipment status so that I can detect failures immediately. | 3 |
| 7 | US-7 | Historical Data Access | As an analyst, I want to access historical data so that I can analyze trends. | 3 |
| 8 | US-8 | Automatic Data Collection | As a system, I want to collect sensor data automatically so that manual errors are reduced. | 3 |
| 9 | US-9 | Data Validation | As a system, I want to validate incoming data so that reliability is ensured. | 3 |
| 10 | US-10 | Data Export | As a manager, I want to export data so that I can analyze and share it. | 3 |
| 11 | US-11 | Alert Generation | As a system, I want to generate alerts so that risks are identified immediately. | 5 |
| 12 | US-12 | Mobile Alerts | As a technician, I want to receive alerts on my phone so that I can respond quickly. | 3 |
| 13 | US-13 | Alert Prioritization | As a manager, I want to prioritize alerts so that critical issues are addressed first. | 3 |
| 14 | US-14 | Incident Logging | As a technician, I want to log incidents so that events are documented. | 3 |
| 15 | US-15 | Automatic Notifications | As a system, I want to notify users automatically so that response time is reduced. | 3 |
| 16 | US-16 | Alert Escalation | As a system, I want to escalate unattended alerts so that they are not ignored. | 5 |
| 17 | US-17 | Alert History | As a user, I want to view alert history so that I can analyze past events. | 3 |
| 18 | US-18 | Risk Dashboard | As a manager, I want to visualize risks so that I can monitor system safety. | 5 |
| 19 | US-19 | Maintenance Delay Alerts | As a system, I want to detect maintenance delays so that risks are minimized. | 3 |
| 20 | US-20 | Incident Reports | As a manager, I want to generate reports so that I can evaluate performance. | 5 |
| 21 | US-21 | Data Storage | As a system, I want to store data so that it is available for future analysis. | 3 |
| 22 | US-22 | Trend Analysis | As an analyst, I want to identify patterns so that I can anticipate failures. | 5 |
| 23 | US-23 | Failure Prediction | As a system, I want to predict failures so that downtime is reduced. | 8 |
| 24 | US-24 | Maintenance Planning | As a manager, I want to schedule maintenance so that failures are prevented. | 5 |
| 25 | US-25 | Maintenance Logging | As a technician, I want to log maintenance activities so that I keep track of work done. | 3 |
| 26 | US-26 | Equipment History | As a user, I want to see equipment history so that I can evaluate performance. | 3 |
| 27 | US-27 | Health Indicators | As a system, I want to calculate health indicators so that equipment condition is evaluated. | 5 |
| 28 | US-28 | Maintenance Alerts | As a system, I want to notify maintenance needs so that failures are avoided. | 3 |
| 29 | US-29 | Maintenance Optimization | As a manager, I want to optimize maintenance processes so that costs are reduced. | 5 |
| 30 | US-30 | Maintenance Reports | As a manager, I want reports so that I can evaluate technical performance. | 5 |
| 31 | US-31 | System Overview Dashboard | As a manager, I want a general dashboard so that I understand system status. | 5 |
| 32 | US-32 | Live Monitoring Dashboard | As an operator, I want live monitoring so that I can react quickly. | 5 |
| 33 | US-33 | Data Filtering | As a user, I want to filter data so that I can analyze specific information. | 3 |
| 34 | US-34 | Analytical Charts | As an analyst, I want charts so that I can interpret trends easily. | 5 |
| 35 | US-35 | Alert Panel | As an operator, I want to see active alerts so that I can prioritize actions. | 3 |
| 36 | US-36 | Event History | As a user, I want to review events so that I can analyze past situations. | 3 |
| 37 | US-37 | Report Export | As a user, I want to export reports so that I can share them. | 3 |
| 38 | US-38 | Multi-user Access | As a system, I want multiple users so that collaboration is enabled. | 5 |
| 39 | US-39 | Custom Dashboard | As a user, I want to customize dashboards so that I improve usability. | 5 |
| 40 | US-40 | KPI Indicators | As a manager, I want KPIs so that I can evaluate performance. | 3 |
| 41 | US-41 | Mobile Access | As a technician, I want mobile access so that I can work in the field. | 5 |
| 42 | US-42 | Safety Protocols | As a technician, I want safety protocols so that I can act correctly. | 3 |
| 43 | US-43 | Safety Simulations | As a technician, I want simulations so that I improve emergency response. | 5 |
| 44 | US-44 | Risk Maps | As an operator, I want risk maps so that I can prevent accidents. | 5 |
| 45 | US-45 | Evacuation Routes | As a technician, I want evacuation routes so that I can act safely. | 3 |
| 46 | US-46 | Field Reporting | As a technician, I want to report from the field so that I improve response time. | 3 |
| 47 | US-47 | Offline Mode | As a system, I want offline functionality so that data is not lost. | 5 |
| 48 | US-48 | Push Notifications | As a technician, I want push notifications so that I receive alerts instantly. | 3 |
| 49 | US-49 | GPS Tracking | As a system, I want to track location so that operations are monitored. | 5 |
| 50 | US-50 | Secure Access | As a system, I want authentication so that data is protected. | 5 |
| 51 | US-51 | Incident Reporting | As a technician, I want to report safety incidents so that risks are reduced. | 3 |
| 52 | US-52 | Risk Registration | As a user, I want to register risks so that problems are anticipated. | 3 |
| 53 | US-53 | Incentive System | As a company, I want incentives so that safety culture is promoted. | 5 |
| 54 | US-54 | Safety Evaluation | As a manager, I want to evaluate safety so that processes improve. | 5 |
| 55 | US-55 | Digital Training | As a technician, I want digital training so that I improve my skills. | 5 |
| 56 | US-56 | System Audit | As an auditor, I want audit logs so that compliance is ensured. | 5 |
| 57 | US-57 | Data Sharing | As a manager, I want to share data so that collaboration improves. | 3 |
| 58 | US-58 | Regulatory Compliance | As a system, I want compliance control so that regulations are met. | 5 |
| 59 | US-59 | Safety Culture | As a company, I want to promote prevention so that accidents decrease. | 3 |
| 60 | US-60 | IoT API Integration | As a developer, I want API integration so that sensors sync in real time. | 5 |
