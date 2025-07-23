# Data_Driven_Methods_in_Neuroimaging

Rational: Practicing data_driven methods (e.g., ML and ANN) in neuroimaging with a 146 rsfMRI dataset, using MATLAB and Python

## Fellow Chart of Data Analysis
1. 146 resting State fMRI data (Parkinson vs Healthy population): Data Link: https://www.ppmi-info.org/
2. Pre-processing and denosing with CONN
3. Applying Mask from Harvard-Oxford atlas 
4. Perform ROI-to-ROI analysis for:
   
SensoriMotor.Lateral (L) (-55,-12,29)
SensoriMotor.Lateral (R) (56,-10,29)
SensoriMotor.Superior  (0,-31,67)
Visual.Medial (2,-79,12)
Visual.Occipital (0,-93,-4)
Visual.Lateral (L) (-37,-79,10)
Visual.Lateral (R) (38,-72,13)

5. Extract Functional Connectivity Features to excel shit (name PC_fC_cleaned.csv)
6. Visualizing Data: Identify Outliers, Normalization, Relationship Between Correlation Parameters (Visualization.ipynb)
7. Fitting Linear Models: (Classification.ipynb)
