# April-25-g2-capstone-project

## About the dataset:

Original owner of data: pgurazada1 on Hugging Face

Data set information:
- Dataset Name: machine-failure-mlops-demo-logs
- Type: Structured tabular data
- Domain: Predictive maintenance / Machine failure detection
- Target Variable: prediction (imbalanced binary classification)
- Use Case: Detecting machine failure events from operational logs

Link to web page: https://huggingface.co/datasets/pgurazada1/machine-failure-mlops-demo-logs

Dataset Structure
The dataset is stored as a CSV file with the following columns:
- Air temperature [K]: Ambient air temperature around the machine in Kelvin.
- Process temperature [K]: Internal process temperature of the machine in Kelvin.
- Rotational speed [rpm]: Rotational speed of the machine shaft in revolutions per minute.
- Torque [Nm]: Torque applied to the machine shaft in Newton-meters.
- Tool wear [min]: Cumulative tool wear measured in minutes.
- Type: Machine type or category (categorical values: L, M, H).
- prediction: Target variable. 0 = normal operation, 1 = failure predicted.
