# Time Series Forecasting: Comparative Analysis of ARIMA and SARIMAX for GDP per Capita

## Executive Summary

This project conducts a structured comparative analysis between ARIMA and SARIMAX models to forecast GDP per capita. The objective is not only to generate predictions, but to evaluate model adequacy through systematic diagnostic testing, parameter selection discipline, and forecast stability assessment.

The study highlights how structural components such as seasonality influence predictive performance and demonstrates a rigorous econometric workflow suitable for macroeconomic time series analysis.

---

## Research Objective

Macroeconomic forecasting requires models capable of capturing stochastic trends and potential seasonal patterns embedded within time-indexed data. While ARIMA serves as a foundational benchmark for non-seasonal processes, SARIMAX extends the framework by incorporating seasonal structures.

This project evaluates whether seasonal augmentation materially improves forecast reliability and statistical validity.

---

## Data Description

The dataset consists of historical GDP per capita observations structured as a univariate time series. The time index enables modeling of long-run growth dynamics and underlying autoregressive behavior.

All preprocessing steps ensure chronological consistency and data integrity prior to model estimation.

---

## Methodological Approach

The analysis follows a disciplined econometric pipeline:

### 1. Exploratory Time Series Analysis
- Visualization of long-term trend behavior  
- Variance inspection  
- Preliminary structural assessment  

### 2. Stationarity Assessment
- Augmented Dickey–Fuller (ADF) testing  
- Differencing to achieve stationarity when necessary  

### 3. Model Specification
- ARIMA (p, d, q) as baseline specification  
- SARIMAX (p, d, q)(P, D, Q, s) to capture seasonal components  

Parameter selection is guided by autocorrelation (ACF) and partial autocorrelation (PACF) diagnostics, supported by information criteria evaluation.

### 4. Diagnostic Validation
- Residual analysis  
- Serial correlation testing  
- AIC and BIC comparison  
- Stability verification  

### 5. Forecast Generation and Evaluation
- Out-of-sample forecasting  
- Predicted versus observed comparison  
- Performance consistency assessment  

---

## Tools and Implementation

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  

All modeling procedures are implemented using reproducible notebook-based analysis.

---

## Key Findings

The results indicate that model performance is conditional on the structural characteristics of the data. In the presence of meaningful seasonal dynamics, SARIMAX improves forecasting stability and reduces residual autocorrelation. When seasonal effects are limited, ARIMA provides competitive performance with a more parsimonious structure.

These findings reinforce the importance of model diagnostics and structural assessment rather than relying solely on automated model selection.

---

## Business Interpretation

From a business and strategic analysis perspective, GDP per capita forecasting provides structured insight into long-term economic trajectory. Reliable projections support macro-level planning, investment feasibility assessment, and risk evaluation.

Model selection plays a critical role in ensuring forecast credibility. Overfitting seasonal components in structurally non-seasonal data may increase variance, while underfitting meaningful seasonal dynamics reduces predictive reliability. Therefore, model choice must balance statistical adequacy with structural realism.

This comparative framework demonstrates how analytical rigor supports informed economic decision-making rather than relying solely on automated forecasting outputs.

---

## Deliverables

This project produces the following analytical outputs:

- Structured time series diagnostic evaluation  
- Comparative ARIMA and SARIMAX performance metrics  
- Residual behavior validation  
- Out-of-sample forecast projections  
- Model selection justification based on statistical evidence  

These deliverables reflect a decision-oriented forecasting workflow suitable for business and policy-level analysis.

---

## Final Recommendation

Based on residual diagnostics, information criteria comparison, and forecast stability assessment, the selected model demonstrates stronger statistical adequacy and predictive consistency.

The recommendation prioritizes robustness and interpretability over unnecessary structural complexity, ensuring practical applicability for macroeconomic forecasting contexts.

---

## Reproducibility

To replicate the analysis:

Clone the repository:

git clone https://github.com/saabrinazada-web/time-series-forecasting.git

Install required libraries:

pip install pandas numpy matplotlib statsmodels

Open the notebook in Jupyter Notebook or Google Colab and execute the cells sequentially.

---

## Contributions

- Structured macroeconomic forecasting workflow  
- Comparative econometric model evaluation  
- Diagnostic-driven model validation  
- Interpretable and reproducible forecasting results  

---

## Future Extensions

- Time series cross-validation  
- Hyperparameter optimization  
- Integration of exogenous macroeconomic indicators  
- Extended robustness benchmarking

---

## Repository Structure

- main: Final validated forecasting framework and business-ready recommendation  
- analysis: Exploratory modeling, parameter experimentation, and preliminary evaluation  
