Healthcare Resource Optimization & Operational Risk Pipeline

## Project Executive Summary
This project analyzes a 100,000-row clinical dataset from 130 US hospitals to identify systemic operational bottlenecks. By evaluating the relationship between hospital stay lengths and 30-day readmission risks, this pipeline builds a foundation for predictive resource allocation and hospital overhead mitigation.

## Technical Stack & Tooling
* **Language:** Python 3.x
* **Development Environment:** Jupyter Notebook
* **Key Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, ucimlrepo
* **Strategic Modeling:** Predictive Classification, Feature Engineering

## Key Operational Insights
* The Non-Linear Bottleneck: Identified a critical operational risk peak between **Days 8 and 10**, where patient readmission probabilities exceed **50%**.
* The Efficiency Sweet Spot: Discovered an operational "sweet spot" on **Day 2** with a minimized relapse baseline of **22%**.
* Data Engineering: Engineered data-cleaning protocols to process variable data gaps ranging from 2% to 96% missingness (e.g., resolving severe missingness in tracking metrics) without distorting sample distributions.
* Predictive Modeling: Deployed an initial Random Forest Classifier to establish an operational baseline risk score, identifying clear paths for iterative feature engineering using clinical indicators.

## Repository Structure
* `/notebooks`: Contains the Jupyter Notebook mapping data cleaning, anomaly detection, visual profiling, and machine learning classification.

