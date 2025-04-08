# Gearbox Fault Prediction Project

I developed this machine learning pipeline to predict gearbox conditions (healthy vs broken) using vibration sensor data. My implementation processes raw sensor readings, trains an XGBoost classifier, and delivers explainable predictions with comprehensive evaluation metrics.

## My Implementation Highlights
- **Data Processing Pipeline**: I designed a robust preprocessing workflow handling vibration data from multiple sensors (a1-a4) across various load conditions
- **Custom Model Training**: I implemented an XGBoost model with 10-fold cross validation for reliable performance estimation
- **Rigorous Evaluation**: I established an 80-15-5 train-test-validation split strategy with complete metrics reporting
- **Explainability Focus**: I integrated SHAP values and feature importance analysis to make the model's decisions interpretable
- **Automated Visualization**: I created automatic generation of key diagnostic plots for model performance assessment

## Technical Approach
1. **Data Preparation**:
   - Performed careful shuffling and stratified splitting
   - Implemented proper feature scaling

2. **Model Development**:
   - Optimized XGBoost hyperparameters
   - Incorporated cross-validation to prevent overfitting

3. **Evaluation Framework**:
   - Designed comprehensive metrics reporting
   - Generated confusion matrices and ROC curves

4. **Explainability**:
   - Added SHAP value analysis
   - Created feature importance visualizations

