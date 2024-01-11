# Aviation Data Exploratory Analysis

## 1. Project Overview

This data exploratory project focuses on analyzing aviation accident data from the National Transportation Safety Board (NTSB) to support the company's strategic investment in operating airplanes within commercial and private enterprises. The goal is to gain valuable insights into aviation incidents, identify patterns, and provide meaningful recommendations to major stakeholders of the investments.

## 2. Data Source

This aviation dataset is [dataset](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses) from the National Transportation Safety Board, including accident aviation data from 1962 to 2023 about civil aviation accidents about civil aviation accidents and selected incidents in the United States and international waters.

## 3. Data Overview

The table has 31 columns and 90348 data points, storing worldwide aviation accidents. These data fields include  details such as accident locations, date, injuries, contributing factors and probable causes reports. It not only includes airplanes' accidents data, but also other aircraft categories such as helicopter, balloon, gyrocraft, etc. 

## 4. Objectives
* Explore and analyze the dataset to identify safety trends in aviation industry, as well as patterns and factors contributing to aviation accidents.
* Identify the best aircraft makers with the safest models and engines by analyzing stats of fatal vs. non-fatal accidents.
* Identify areas for operational improvement and training focus based on historical accident patterns.
* Provide data-driven evidence to support confidence in the strategic investment ragarding safety and reliability of the aviation operations.

## 5. Key Questions

With this project, I will address specific questions such as:
* **What are the main causes of aviation accidents, and how can they be mitigated in our company's operations?
* **What specific measure should be used to compare different level of safety among different aviation makers, models and engine types?
* **What should we learn from past accidents to improve the safety and efficiency of our operations?

## 6. Stakeholders

The key stakeholders in this project include:
* Investors: Supporting strategic invesment decisions in aviation industry with data-driven insights
* Operational Teams: Recommending safety measures and trainings to improve operational efficiency and safety via our data analysis

## 7. Data Exploration and Safety Measure Methodology

For this project, I decided to only include airplane accident data and most of my analysis only include accidents occurred after 2000. The reason I limit my dataset including only data after 2000 is due to the changes of technology innovation in the aviation industry. With more current data, it is guaranteed that my analysis will only consider the current models and makers in the industry.

To determine the level of safety of a certain aircraft maker or model, I use the ratio of fatality/serious accidents over all the accidents it occurred in this dataset. The reason I use ratio rather than the raw data itself is due to a certain bias factor in the data. For instance, for lesser popular maker or model, it will mostly have low number of accidents; thus, its fatality injuries rate is also very low or even non-exist. However, due to its small sample, it is not safe to conclude that certain maker or model is safer than those with higher fatality but also with much more popularity in the industry. With higher popularity, a maker's products will be used by more airlines and customers; thus, it is also faced with higher fatality rate and accidents occurred.

## 8. Interactive Dashboard 

![Here is the link to my interactive dashboard](https://public.tableau.com/views/AviationAnalysis_17046894590710/Story1?:language=en-US&:display_count=n&:origin=viz_share_link)

## 8. Conclusion

Based on our exploratory analysis, there are three recommendations I have for our stakeholders include:
* Prioritize investing in the three aircraft makers, which have the lowest fatality/serious rate over all the accidents they experience, including Boeing, Airbus and McDonnell Douglas.
* Prioritize investing in reciprocating (one or two engines) and turbo fan (2 engines) for the company aircraft's fleet. These engines types appear to have the lowest fatality/serious rate out of all accidents they experienced.
* The dataset also shows that there is a high number of accidents occurred during the four major phases of flight including take-off, landing, cruise and maneuvering. In fact, maneuvering, cruise and take-off are the major phases in which lots of fatal/serious accidents occurred. My recommendation is to offer more trainings for our pilots regarding these four mentioned phases.




