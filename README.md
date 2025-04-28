# Business Problem

Your company is expanding in to new industries to diversify its portfolio. Specifically, they are interested in purchasing and operating airplanes for commercial and private enterprises, but do not know anything about the potential risks of aircraft. You are charged with determining which aircraft are the lowest risk for the company to start this new business endeavor. You must then translate your findings into actionable insights that the head of the new aviation division can use to help decide which aircraft to purchase.

# Project Overview
This project analyzes aviation accidents to identify patterns and risk factors based on aircraft make, category, injury severity, and phase of flight.
The main goal is to offer data-driven recommendations that can help improve operational safety.

# Technologies Used

Python (Pandas, Matplotlib, Seaborn)
Tableau (for advanced visualizations)
Jupyter Notebook
Anaconda (Environment management)

# Data Source

Aviation Accident Data (CSV format)
Columns include: Event.Date, Make, Model, Aircraft.Category, Injury.Severity, Broad.phase.of.flight, Total.Fatal.Injuries, etc.

# Data processing

Handled missing/invalid values (e.g., empty fields, NaNs).
Standardized date formats.
Created new feature like:
Total_Injured = Sum of fatal, serious, and minor injuries.
Extracted Year for time-based analysis.

# Key Analyses

Top 5 Makes with Highest Total Injuries: Trends observed over the years.
Accident Frequency by Phase of Flight: Visualized and compared across aircraft categories.
Fatality Proportions by Phase of Flight: Analyzed how fatalities are distributed across different flight phases.
Risk by Aircraft Make: Identified low-risk manufacturers (e.g., BELL).

# Visualizations

Line graphs (Total injuries over time by Make).
Bar plots (Accidents by Phase of Flight and Aircraft Category).
Stacked bar charts (Proportion of fatalities).
Tableau Dashboards (for deeper interactive insights).

# Recommendations
Prioritize safer aircraft models like BELL where operational flexibility allows.
Focus on critical flight phases such as Landing and Takeoff, which show higher accident rates.
Enhance pilot training and operational checks during high-risk phases.

# Next Steps
Expand dataset to include recent years for updated trends.
Build a predictive model to estimate accident risk based on conditions.
Explore weather conditions impact on accident severity.

# How to Use
Clone this repository.
Open the Jupyter Notebook or scripts.
Install required libraries (pip install pandas matplotlib seaborn).
Run the code and explore the visualizations.
Check Tableau dashboards for interactive insights.

Name: Jedidah

Email: kathurejedidah37@gmail.com

LinkedIn: [Your LinkedIn Profile] (optional)