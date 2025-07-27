**README: Aircraft Risk Analysis Project

**Project Overview

This project analyzes aviation incident data to identify the safest aircraft models for a company entering the aviation business. The analysis focuses on risk metrics across operational factors to support data-driven investment decisions.

**Project Details
•	Student Name: Michael Mumina Kasimu
•	Pace: Part Time
•	Project Review Date: 27/07/2025 23:59:59
•	Instructor: Fidelis Wanalwenge
•	Blog Post URL: [To be added]

***Project Structure
text
project/


├***data/
│   ├***Aviation_Data.csv            # Raw dataset
│   ├***cleaned_data.xlsx            # Cleaned dataset
│   └***cleaned_data_Metrics.xlsx    # Calculated risk metrics
├*** analysis.ipynb                   # Jupyter notebook with full analysis
└*** README.md                        # This file

***Key Analysis Steps

1. **Data Preparation

    •	Loaded and cleaned aviation incident data
    •	Handled missing values in critical fields (Make, Model, Injuries, Damage)
    •	Filtered relevant columns for analysis
    
2. ***Risk Metrics Calculation

Developed three core safety metrics:

   ****Fatality Risk: Fatalities per incident
   ****Damage Risk: Probability of severe damage
   ****Overall Risk: Weighted composite score (0-100 scale)
   
3. **Operational Analysis

Examined three key operational factors:
    ****Engine Type: Distribution among safest aircraft
    ****Phase of Flight: When incidents occur
    ****Purpose of Flight: Primary use cases
    
4. **Visualization

Created multiple visualizations including:

    •	Safety score comparisons
    •	Operational factor distributions
    •	Interactive treemaps of phase/make risk
    •	Fatality rate scatter plots
    
**Key Findings

    1.	Safest Aircraft: Boeing 787 ranked safest based on metrics
    2.	Engine Types: Turbofan/jet engines dominate safest models
    3.	High-Risk Phases: Takeoff, maneuvering and landing account for 72% of incidents
    4.	Avoid: Piston engines and amateur-built aircraft showed higher risks
    
**Recommendations

    1.	Prioritize: Turbofan/jet aircraft (Cessna 208, Pilatus PC-12)
    2.	Training Focus: Takeoff/landing procedures
    3.	Avoid: Models with Overall Risk score > 65
    4.	Consider: FAR Part 135 certified aircraft for stricter standards
    
**How to Use

    1.	Run analysis.ipynb to reproduce analysis
    2.	Review cleaned_data_Metrics.xlsx for complete risk scores
    3.	See visualizations for operational insights

**Technology Dependencies
    •	Python 3.8+
    •	Pandas, Matplotlib, Seaborn, Plotly
    •	Jupyter Notebook

**Contact

For questions, contact Michael Mumina Kasimu at donmumina@gmail.com
________________________________________

