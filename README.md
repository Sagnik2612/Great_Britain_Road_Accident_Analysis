# Great Britain Road Accident Analysis (2019-2022)

An analytical deep-dive using **Tableau & Power BI** dashboards to assess, compare, and communicate road accident trends across the UK from **2019–2022**. This project was undertaken in response to a multi-agency directive to better understand accident dynamics and identify parameters that have contributed to the **reduction of road accidents and casualties**.

## Business Problem Statement

From 2019–2022, the UK witnessed significant fluctuations in road accident statistics. Multiple agencies including the **Road Safety Department, Police Forces, Ministry of Transport, and Emergency Services** demanded a comprehensive analytical dashboard to:

- Monitor year-on-year changes in **accidents and casualties**

- Measure the **effectiveness of interventions**

- Detect high-risk conditions, road types, and locations

- Communicate actionable trends for **policy updates and public safety campaigns**

## Stakeholder Requirements

As per the documents received-
- Separate dashboards were to be built for **Tableau (2019–2022)** and **Power BI (2021–2022)**
- Visuals must reflect breakdowns by:
  - **Accident severity**
  - **Weather & road surface conditions**
  - **Vehicle type**
  - **Location & time of day**
  - **Road types**
- Must include **primary KPIs, YoY comparisons, and map visualizations**

<a href="https://github.com/Sagnik2612/Great_Britain_Road_Accident_Analysis/blob/main/Requirements/Stakeholder_Requirements_Document%20(1).pdf"> View for full requirements </a>

## Tableau Dashboard (2019–2022)

Visualized in: `\Road_Accident_2020-2021.png` & `\Road_Accident_2021-2022.png`

- **Primary KPIs**: Accidents & Casualties (YoY drop visible)

- **Casualty Trends**: Monthly comparisons between 2021 & 2022 highlight a decline in late-year incidents

- **Vehicle-Type Casualties**: Car users formed the bulk (155K+), while agricultural vehicles showed the steepest decline (▼37%)

- **Road Surface Conditions**:

  - 67.4% of accidents happened on **dry roads**

  - 25.7% on **wet roads**
 
  ![2020-2021](https://github.com/Sagnik2612/Great_Britain_Road_Accident_Analysis/blob/main/Dashboards/Road_Accident_2020-2021.png)

- **Weather Impact**:

  - 80.7% of casualties occurred in **fine weather**

  - Only 2.9% in **snow/fog**, suggesting better driving behavior/advisories during extreme conditions


![2021-2022](https://github.com/Sagnik2612/Great_Britain_Road_Accident_Analysis/blob/main/Dashboards/Road_Accident_2021-2022.png)

- **Road Type Impact**:

  - 144K+ casualties on **single carriageways**

  - Far fewer on **slip roads, roundabouts, and one-way streets**


## Power BI Dashboard (2021–2022)

Visualized in: `\Road_Accident_Analysis_PowerBI.jpg`

- Added filters for **daylight vs. darkness, urban vs. rural**—not available in Tableau view

- **Casualty Timing**:

  - 73.8% of accidents occurred in **daylight**, highlighting need for better **urban planning**, not just night safety

- **Urban-Rural Divide**:

  - 61.9% urban, 38.1% rural—urban congestion playing a key role

- Heatmap shows **higher concentration of incidents in southern UK**, notably **London, Birmingham, and Manchester**

![2021-2022](https://github.com/Sagnik2612/Great_Britain_Road_Accident_Analysis/blob/main/Dashboards/Road_Accident_Analysis_PowerBI.jpg)


## Key Analysis Outcomes

| **Parameter**          | **Insight**                                       | **Impact**                                                      |
|------------------------|----------------------------------------------------|------------------------------------------------------------------|
| **YoY Trends**         | ▼11.7% Accidents, ▼11.9% Casualties (2021–22)     | Road safety campaigns showing measurable results                |
| **Fatal Casualties**   | ▼26.4%                                            | Emergency services response & safer roads saving lives          |
| **Vehicle Type**       | Agriculture ▼37%, Bikes ▼14%                      | Improved vehicle regulation & rural road safety                 |
| **Road Type**          | 73% casualties on single carriageways             | Indicates need for dual upgrades or better signage              |
| **Weather Conditions** | 81% accidents in fine weather                     | Accidents linked more to human error than poor conditions       |
| **Surface Conditions** | Wet surfaces responsible for 25%+                 | Calls for resurfacing & drainage improvement                    |
| **Time of Day**        | Daylight: 74%                                     | Better urban road design, not just night visibility             |
| **Urban vs Rural**     | Urban: 62%                                        | Urban density requires congestion solutions & better infrastructure |


