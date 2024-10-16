# zeotap
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
