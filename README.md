# ENTERPRISE-CYBER-RISK-ANALYSIS-METRICS-REPORTING
Enterprise Cyber Risk Analysis &amp; Metrics Reporting This portfolio project demonstrates how technical cybersecurity findings can be translated into enterprise cyber risk analysis, measurable risk indicators, FAIR style risk quantification and executive level reporting.  

Using a fictional financial-services organization, I assessed the risk of credential theft and customer account compromise affecting an online banking platform. I then developed risk treatments, KPIs, KRIs, control effectiveness measures, a FAIR style Monte Carlo simulation, and a one page executive dashboard.

## Project objectives: 
identify a critical business asset and cyber risk scenario; assess likelihood and business impact; quantify financial exposure using FAIR concepts and Monte Carlo simulation; recommend risk treatment and security controls; measure residual risk using KPIs, KRIs, trends, and control effectiveness; and communicate the results through executive level reporting.
Important: All organizations, data, assumptions, financial values, and risk ratings in this project are fictional and were created for learning and portfolio purposes.
### Executive Cyber Risk Dashboard

<img width="1403" height="782" alt="image" src="https://github.com/user-attachments/assets/0c9664c9-0b6f-4478-81b5-820c2658e4b9" />

###

This dashboard provides an executive level view of the cyber risk scenario assessed in this project. The scenario focuses on credential theft leading to customer account compromise affecting a fictional financial institution's online banking platform.

#### The dashboard brings together the key elements of the risk assessment:
- Risk Overview: Identifies the critical asset, risk scenario, potential business impact, inherent risk, selected treatment strategy, and residual risk after controls.
- FAIR Quantification: Introduces financial risk quantification using loss event frequency and loss magnitude, supported by a 10,000 trial Monte Carlo simulation.
- Risk Metrics: Uses a KPI to measure MFA adoption, a KRI to monitor successful account compromises, and a control effectiveness metric to evaluate whether MFA is reducing account compromise risk.
- Risk Trend: Tracks account compromises alongside MFA coverage over time. In this fictional dataset, MFA coverage increases from 82% to 94%, while successful account compromises decrease from 12 to 6 per month.
- Management Decision: Provides a section for translating the technical findings into information leadership can use to evaluate residual risk against risk tolerance and determine whether additional treatment is required.
#### The purpose of this dashboard is to demonstrate how technical cybersecurity information can be transformed into measurable business risk information for executive decision making

### Risk Register 
<img width="1785" height="780" alt="image" src="https://github.com/user-attachments/assets/fc748b9a-eaf2-45c5-96f5-b62c22d89a1d" />

###

The Risk Register provides a structured view of the key cyber risks identified across critical business assets and shows how each risk is assessed, treated, owned, and monitored.
- Critical Assets & Risk Scenarios: Identifies assets such as the Online Banking Platform and Customer Data, along with risks including credential theft, DDoS attacks, and unauthorized data access.
- Risk Assessment: Evaluates each scenario based on likelihood and business impact to determine the inherent risk before security controls are considered.
- Risk Treatment: Documents the selected response and key controls, including MFA, suspicious login monitoring, DDoS protection, encryption, and access controls.
- Residual Risk: Shows the level of risk that remains after controls are implemented, allowing it to be compared with the organization's risk tolerance.
- Risk Ownership & Monitoring: Assigns responsibility to the appropriate security function and tracks whether the risk requires continued monitoring.
#### Purpose is to Create a centralized record for identifying, assessing, treating, assigning, and monitoring cyber risks, while supporting consistent risk reporting and informed decision making

### Risk Metrics & Trend Analysis
<img width="1716" height="778" alt="image" src="https://github.com/user-attachments/assets/d013edaf-8e34-49fe-8ce2-b3d1c4dc4d3e" />

###


This section tracks risk exposure, security performance, and control effectiveness over time to show whether the identified risk is improving or worsening.
- KPI – MFA Coverage: Measures security performance, increasing from 82% to 94%.
- KRI – Account Compromises: Tracks risk exposure, decreasing from 12 to 6 successful compromises per month.
- Suspicious Login Alerts: Monitors potentially risky authentication activity and increases from 420 to 560 alerts.
- Control Effectiveness: Compromises involving MFA enabled accounts decrease from 4 to 1, helping evaluate whether MFA is contributing to risk reduction.
- Trend Analysis: Compares MFA adoption with account compromises over time, showing higher MFA coverage alongside fewer successful compromises.
#### Purpose: Use measurable indicators and trends to monitor cyber risk, evaluate control effectiveness, and provide leadership with information to support risk based decisions.

### FAIR Risk Quantification Inputs
<img width="1074" height="781" alt="image" src="https://github.com/user-attachments/assets/e6e7db98-e36e-4588-8571-5ba7704195b7" />

###

This section uses FAIR (Factor Analysis of Information Risk) concepts to translate cyber risk into estimated financial exposure.
- Loss Event Frequency: Estimates how often the risk event could occur annually using low, most likely, and high assumptions.
- Primary Loss: Estimates direct costs such as fraud/reimbursement and incident response.
- Secondary Loss: Estimates indirect costs including regulatory/legal expenses and reputation/recovery costs.
- Range-Based Estimates: Low, most-likely, and high values account for uncertainty instead of relying on a single fixed estimate.
- Monte Carlo Input: These assumptions are used as inputs for the simulation to model a range of possible financial outcomes.
Purpose: Quantify cyber risk in financial terms so leadership can better understand the potential frequency and magnitude of loss and make informed risk treatment decisions.
