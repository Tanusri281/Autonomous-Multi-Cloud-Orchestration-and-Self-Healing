Autonomous Multi-Cloud Resource Orchestration and Self-Healing Infrastructure

Project Overview

This Design project explores an autonomous approach to resource orchestration and self-healing in multi-cloud environments. It aims to improve resource utilization, identify anomalous behavior, and support workload continuity through predictive analysis and simulated orchestration policies.

The current implementation focuses on workload analysis, CPU utilization prediction, anomaly detection, and the evaluation of orchestration policies under simulated cloud-failure scenarios.

Objectives

- Analyze virtual-machine workload traces.
- Predict CPU utilization using a machine-learning model.
- Detect anomalous VM behavior.
- Simulate cloud failures and resource orchestration decisions.
- Compare Static, Reactive, and Risk-Aware orchestration policies.
- Evaluate migration activity, resource capacity, and service availability.

Dataset

The implementation uses the Bitbrains fastStorage VM workload traces for workload analysis and model development.

The notebook includes preprocessing and VM-level data splitting for model evaluation.

Please refer to the dataset provider's terms and citation requirements before redistributing any dataset files.

Technologies Used

Python — implementation and data processing
Google Colab — notebook-based development and experiments
Pandas and NumPy — data preparation and analysis
Scikit-learn — machine-learning models
Matplotlib — visualization and performance comparison
Joblib — saving and loading trained models

Implemented Modules

1. Data preprocessing: Processes VM workload traces and prepares data for analysis.
2. CPU prediction:Trains and evaluates a Random Forest model against a persistence baseline.
3. Anomaly detection: Uses an Isolation Forest model to identify potentially anomalous behavior.
4. Multi-cloud simulation: Evaluates orchestration decisions under controlled workload and failure scenarios.
5. Policy comparison: Compares Static, Reactive, and Risk-Aware orchestration approaches.
6. Results validation: Checks simulation outputs, capacity records, migration activity, and availability metrics.
7. Visual analysis: Generates figures to support comparison of the orchestration policies.

Repository Contents

- `Multi_Cloud_Orchestration_Project.ipynb` — organized implementation notebook
- `README.md` — project overview and implementation documentation

Additional source files, trained models, experiment results, and dashboard files may be added as the repository is finalized.

Current Status

Implementation and experimentation: In progress / under validation.

The notebook documents the current implementation and recorded experiment outputs. A complete fresh-runtime execution and final validation are still required before the implementation is considered reproducible end to end.

Dashboard integration and final documentation are planned as subsequent steps.

Future Work

- Connect the implementation to an interactive dashboard.
- Improve integration between prediction, anomaly detection, and orchestration components.
- Validate the full pipeline in a clean runtime.
- Refine evaluation metrics, visualizations, and documentation.

Academic Project

This repository is maintained for academic review and project development. Results should be interpreted in the context of the implemented simulation and its assumptions.
