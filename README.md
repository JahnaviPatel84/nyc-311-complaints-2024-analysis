# NYC 311 Public Service Insight Platform – 2024

This project delivers a scalable, cloud-based reporting solution to surface operational insights from over **3.45 million NYC 311 service requests** submitted during 2024. Designed to support executive stakeholders, city planners, and public service teams, the platform enables real-time monitoring of urban service demand and responsiveness through an interactive dashboard powered by BigQuery and Looker Studio.

---

## Overview

Each year, millions of New Yorkers turn to 311 to report issues related to noise, parking, sanitation, and public safety. This project organizes that signal-rich dataset into a decision-support system transforming raw complaints into a living operational layer that informs planning, prioritization, and public accountability.

---

## Key Findings

* **Brooklyn** received the highest volume of 311 service requests in 2024  
* A total of **3,458,170 complaints** were filed, averaging **9,474 complaints per day**  
* **Illegal Parking** was the most commonly reported issue citywide  
* Other top complaint types included **Noise - Residential**, **Heat/Hot Water**, and **Blocked Driveway**  
* The **New York City Police Department (NYPD)** and the **Department of Housing Preservation and Development (HPD)** handled the majority of service requests, followed by the **Department of Sanitation (DSNY)** and the **Department of Transportation (DOT)**  
* Complaint activity was highest in the **Afternoon** and **Evening**, with minimal volume during Early Morning hours  
* Trends remained relatively stable throughout the year, with expected seasonal fluctuations

These insights are delivered through an interactive interface, filterable by borough, agency, complaint type, and time dimension.

---

## Solution Architecture

| Layer         | Technology                        |
| ------------- | --------------------------------- |
| Data Source   | NYC Open Data (311 Requests 2024) |
| Processing    | Python (Pandas, datetime parsing) |
| Storage       | Google Cloud Storage (GCS)        |
| Query Engine  | Google BigQuery                   |
| Visualization | Looker Studio                     |

---

## Functional Capabilities

* Complaint volume and resolution time metrics across agencies
* Temporal patterns by hour, day, and month
* Dynamic filtering by borough, agency, complaint type
* Geospatial mapping via lat/lon fields
* Fully hosted in a cloud-native analytics stack

---

## Impact Potential

* Enables data-informed decisions around **staffing, outreach, and agency resourcing**
* Highlights **bottlenecks and trends** in complaint handling
* Brings **transparency and clarity** to public operations
* Designed to support year-over-year tracking and future anomaly detection

---

## Access the Dashboard
![NYC 311 Dashboard Preview](dashboard_preview.png)

[View the Interactive NYC 311 Complaints Dashboard – 2024] *https://lookerstudio.google.com/s/pXw4xt_BvLQ*
