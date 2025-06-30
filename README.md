# Smart-Skrewing-Dashboard

# Overview
This repository features dashboards for monitoring industrial tightening processes using an anonymized dataset (`tightening_results_anon_extended.csv`) with 500 records. It targets operators, technicians, and quality engineers with real-time, NOK analysis, trend, and process control visuals.

# Dashboards
- **Operator Real-Time Monitor**: Shows step, torque, angle, time, and status.
- **Technician NOK Analysis Dashboard**: Tracks last 20 NOK operations and success rate.
- **Technician Performance Trends Dashboard**: Plots torque/angle trends with filters.
- **Quality Engineer Process Control Dashboard**: Offers I-MR and Run Charts for quality.

# Dataset
- **File**: `data/tightening_results_anon_extended.csv` (included)
- **Records**: 500
- **Columns**: 16 (e.g., Type, Status, Torque, Angle, Date, Time)
- **Timeframe**: Jan 15 - Mar 5, 2025
- **Anonymized**: Generic IDs (e.g., Unit_B1, ABC67890), torque 5.8-6.2 N.m, angle 10-400 Deg.

# Setup
1. Clone the repo:
   ```bash
   # Clone the repository
   git clone https://github.com/noussayba-azouz/Smart-Skrewing-Dashboard.git
