# 🚗 Victoria Road Trauma & Crash Analytics Portfolio

Note: Due to file size limitations, datasets used in this project is stored in zip format.

## 📊 Project Overview

This project analyzes comprehensive road crash data from the State Government of Victoria (Data.Vic) to identify hazardous road segments, uncover behavioral patterns, and evaluate the effectiveness of existing road infrastructure. By merging and exploring four relational datasets (Accident, Person, Vehicle, and Node/Location), this analysis translates raw incident reports into actionable insights for targeted infrastructure funding and public safety policy.

## 🔍 Part 1: Core Trend Analysis (Baseline Insights)

### 1. The Top 10 Most Hazardous Road Hotspots

Insight: The analysis reveals that major arterial roads and high-capacity highways dominate the top 10 list for severe (fatal and serious injury) crashes. This is primarily driven by the "exposure rate"—higher daily traffic volumes combined with complex merging behaviors.

Actionable Takeaway: Government funding for infrastructure should prioritize these specific corridors, focusing on grade separation, barrier installations, and dedicated turning lanes rather than localized neighborhood interventions.

### 2. Environmental Factors: Lighting & Visibility

Insight: While the majority of total crashes happen during daylight (due to sheer volume of cars on the road), the severity score of crashes spikes dramatically in "Dark - No Street Lights" conditions. Lack of visibility reduces driver reaction time, meaning collisions occur at higher speeds without braking mitigation.

Actionable Takeaway: Investing in smart LED street-lighting and highly reflective line-marking on rural or semi-rural fringes can yield a high return on investment for reducing fatal outcomes.

### 3. Demographic Vulnerability: Pedestrians vs. Vehicles

Insight: The age distribution charts highlight a stark contrast. Vehicle occupant crashes peak heavily in the younger demographics (18-25 years), often correlating with inexperience. However, pedestrian casualties show a much flatter or bimodal distribution, with elderly pedestrians (65+) representing a disproportionately high risk group for severe injuries due to physical frailty and slower crossing speeds.

Actionable Takeaway: Traffic calming measures and extended pedestrian crossing light durations are critical in areas with high aging populations.

### 4. The Impact of Speed Zones on Severity

Insight: The data overwhelmingly validates the physics of kinetic energy. While 40 km/h and 50 km/h zones see a high frequency of minor fender-benders, the percentage of crashes that result in death or serious injury jumps exponentially in 80 km/h and 100 km/h zones.

Actionable Takeaway: Expanding 40 km/h zones in dense commercial or school districts is highly effective. Even minor reductions in speed limits on rural arterials can drastically shift a crash outcome from "Fatal" to "Serious/Other Injury".

### 5. Seasonal Accident Trends

Insight: Crash volumes typically exhibit distinct seasonal peaks. Total crash frequencies often rise during the transition to Winter (May/June) as drivers adjust to wet roads, early dusk, and fog. Additionally, severe crash rates occasionally spike during the December holiday period due to highway travel fatigue and increased alcohol consumption.

Actionable Takeaway: Seasonal policing blitzes (e.g., breath-testing and fatigue stops) should be heavily ramped up dynamically to match these historical seasonal spikes.

## 🚀 Part 2: Advanced Behavioral & Infrastructure Analysis

### 6. Vehicle Fleet Age & Crash Survivability

Insight: Merging vehicle manufacturing years with occupant injury levels reveals a massive survivability gap. Occupants in vehicles built before 2010 suffer severe injuries at a significantly higher rate than those in post-2015 vehicles. Modern Advanced Driver Assistance Systems (ADAS)—such as auto-emergency braking, lane-keep assist, and advanced curtain airbags—are undeniably saving lives.

Actionable Takeaway: Subsidizing fleet modernization (e.g., "Cash for Clunkers" schemes) or mandating stricter safety standards for imported used cars could drastically lower the state's road trauma medical costs.

### 7. Accident Mechanics (DCA) at Varying Intersections

Insight: The mechanics of how cars crash depend heavily on road geometry. At Cross Intersections, the most severe crashes are "Cross Traffic / Right Angles" (T-bones), which are highly lethal due to weak side-door intrusion protection. Conversely, at T-Intersections, "Rear End" and "Right Turn" misjudgments dominate.

Actionable Takeaway: Cross intersections with high accident histories should be aggressively targeted for conversion into roundabouts, which physically eliminate the possibility of high-speed T-bone crashes by forcing traffic into a slower, parallel flow.

### 8. Vulnerable Road Users vs. Road Surface Conditions

Insight: Enclosed vehicles handle unpaved or gravel surfaces relatively well with modern ABS systems. However, vulnerable road users (Motorcyclists, Bicyclists, and E-scooters) face a staggering multiplier in severe injury risk on these surfaces. Loss of traction results in immediate ejections or slides without a protective vehicle cage.

Actionable Takeaway: Road maintenance prioritization must factor in the volume of local vulnerable users. Popular cycling or motorcycling tourist routes must be kept paved and free of edge drop-offs or loose gravel.

### 9. Time-Based Behavioral Dynamics (Peak vs. Late Night)

Insight: Splitting the data by time periods uncovers two completely different crash profiles. Weekday Peak hours are dominated by multi-vehicle rear-end collisions (high volume, low speed, low severity). Weekend Late Nights are dominated by single-vehicle crashes (e.g., "Left off carriageway into tree/pole") with incredibly high severity rates, strongly indicating driver fatigue, speeding, or intoxication.

Actionable Takeaway: Daytime infrastructure should focus on congestion management (smart traffic lights), while nighttime interventions require wire-rope safety barriers to catch cars leaving the road and targeted DUI enforcement.

### 10. The Effectiveness of Traffic Controls

Insight: Not all intersections are created equal. Intersections regulated only by "Giveway" signs or "No Control" exhibit the highest proportion of severe outcomes. Upgrading these to "Stop-Go Lights" drastically cuts the severity rate by forcing absolute compliance and separating conflicting traffic phases.

Actionable Takeaway: While expensive, upgrading high-risk "Giveway" intersections to fully signalized traffic lights provides a quantifiable, data-backed reduction in fatal collisions, easily justifying the capital expenditure.

## 🛠️ Technology & Skills Demonstrated

Languages: Python

Libraries: Pandas, NumPy, Matplotlib

Concepts: Relational Data Merging (Inner/Left Joins), Time-Series Analysis, Feature Engineering (Categorization/Binning), Demographic Profiling, Geospatial Concept Analysis.
