# Smart-Skrewing-Dashboard
## Overview
This repository features dashboards for monitoring industrial tightening processes using an anonymized dataset (tightening_results_anon_extended.csv) with 108 records. It targets operators, technicians, and quality engineers with real-time, NOK analysis, trend, and process control visuals.

## Dashboards
Operator Real-Time Monitor: Shows step, torque, angle, time, and status.
<br> Technician NOK Analysis Dashboard: Tracks last 20 NOK operations and success rate.
<br> Technician Performance Trends Dashboard: Plots torque/angle trends with filters.
<br> Quality Engineer Process Control Dashboard: Offers I-MR and Run Charts for quality.
## Dataset
File: tightening_results_anon_extended.csv
<br> Records: 108
<br> Columns: 16 (e.g., Type, Status, Torque, Angle, Date, Time)
<br> Timeframe: Jan 15 - Mar 5, 2025
<br> Anonymized: Generic IDs (e.g., Unit_B1, ABC67890), torque 5.8-6.2 N.m, angle 10-400 Deg.
## Setup
Clone the repository
<br> git clone https://github.com/your-username/Smart-Skrewing-Dashboard.git

Load the CSV in Power BI, Tableau, or Python:
<br> df = pd.read_csv("tightening_results_anon_extended.csv")
## Usage
Recreate dashboards using column data.
<br> Customize with filters or predictive models (e.g., TensorFlow for NOK prediction).
## Skills
Data anonymization, dashboard design, statistical analysis.
## Contribute
Fork, enhance, or suggest improvements. Open an issue or PR!

## License
MIT License

## Contact
azouz.noussayba@gmail.com

Last Updated
10:56 AM CET, Monday, June 30, 2025
