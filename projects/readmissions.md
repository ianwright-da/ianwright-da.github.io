---
layout: project
type: project
image: "../img/readmissions/readmission-thumb.png"
title: "Hospital Readmissions Delta Analysis Dashboard"
date: 2023
published: true
labels:
  - Tableau
  - Data Visualizations
summary: "A Tableau dashboard created to assist a  hospital chain in identifying and troubleshooting underperforming hospitals."
---

<img class="img-fluid" src="../img/readmissions/readmission-header.png">

In the medical industry, unplanned patient readmissions are such a problem that a government agency, the Centers for Medicare and Medicaid Services (CMS) monitors readmissions and fines hospital with excessive readmissions. This dashboard was created to assist executive leaders at a (hypothetical) national hospital chain to identify hospitals that underperform with respect to readmissions and strategize around reducing readmissions at these hospitals using demographic and medical data for readmitted patients.

To identify hospitals in need of intervention, the dashboard incorporates an internal company dataset of patient information for 10,000 patients and an external dataset maintained by CMS containing hospital-level data for 3,000 hospitals nationwide. Both datasets contain data allowing for the calculation of state-level averages for readmission rates by aggregating patient-level or hospital-level data. However, these averages are not directly comparable since the data sets report data for different medical conditions.

Since we would expect that different medical conditions would have different distributions of readmission rates, the dashboard employs a delta analysis approach, comparing the standardized distance from the mean for each state in each dataset to identify states in which company hospitals are underperforming compared to their peers.

[Click here](https://public.tableau.com/views/HospitalReadmissionDeltaDashboard/Instructions?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link) to view the dashboard on Tableau Public. Dashboard includes instructions for a suggested analytical approach and a link to a short video presentation demonstrating the dashboard intended for audiences with a non-quanitative background. 


<hr>

