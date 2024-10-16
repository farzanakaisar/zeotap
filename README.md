# zeotap
1.: Rule Engine with AST
This project implements a simple 3-tier rule engine using an Abstract Syntax Tree (AST) to determine user eligibility based on attributes like age, department, income, and experience.
Features
Dynamically creates and modifies rules.
Combines multiple rules into a single AST.
Efficient rule evaluation based on user data.
Structure
Node Class: Defines AST nodes with operators and operands.
API: Functions to create rules (create_rule) and combine them (combine_rules).
Evaluation: Evaluate user eligibility based on rule logic.
Usage
Define rule strings.
Convert rules into ASTs using create_rule().
Combine rules using combine_rules().
Evaluate rules using evaluate_rule().

2.: Real-Time Data Processing System for
Weather Monitoring with Rollups and Aggregates
Features
Real-time Weather Monitoring: Fetches data at regular intervals and stores it for analysis.
Rollups & Aggregates: Provides summaries such as average temperature per hour, daily high/low temperatures, and weather trends.
Visual Dashboards: Displays data visually using graphs and charts for easy interpretation of trends.
Threshold Alerts: Generates alerts if specific weather conditions exceed user-defined limits (e.g., extreme temperature or high wind speeds).
Installation Guide
Prerequisites
Python 3.x
Pip package manager
API key from OpenWeatherMap
PostgreSQL or Redis (for data storage)
Flask or Django for web development
