# Evaluating a Manufacturing Process (SQL Project)

## Project Overview
This project uses SQL to perform **Statistical Process Control (SPC)** on manufacturing line data. The goal is to analyze operational metrics, track product dimensions, and detect out-of-control processes or quality control bottlenecks to ensure compliance with manufacturing standards.

## Tech Skills Demonstrated
* **Query Language:** SQL (PostgreSQL)
* **Advanced SQL Techniques:** Window Functions (`OVER`, `PARTITION BY`), Subqueries, Aggregate Functions, and Boolean Logic Flags.
* **Domain Concepts:** Statistical Process Control (SPC), Quality Assurance, Upper/Lower Control Limits (UCL/LCL).

## Project Structure
* `query.sql` — Contains the primary SQL queries used to aggregate data and compute control metrics.
* `dataset/` — Sample dataset or schema description used for the evaluation.

## Key Insights & Implementation
* **Dynamic Control Limits:** Wrote queries utilizing window functions to calculate rolling averages and standard deviations across different operators and production lines.
* **Outlier Detection:** Engineered automated boolean logic checks to flag out-of-range dimensions, helping teams catch process drift early.

## How to Run the Code
1. Clone this repository to your local machine.
2. Load the schema and dataset into your preferred SQL environment (e.g., PostgreSQL, DBeaver, or MySQL Workbench).
3. Execute `query.sql` to view the step-by-step statistical evaluation.
