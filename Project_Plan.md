# Project Plan

## Load Data
- [x] **Load Data:**
  - [x] Import data from .xlsb
  - [x] Save as common format
  - [x] Validate data match on reload

## Exploratory Analysis
- [x] **Column Value Counts:** Identify the distribution of values in each column
- [x] **Autoprofile:** Utilize autoprofiling via ydata-profiling
- [x] **Autoprofile Split by Outcome/Class:** Generate separate autoprofiles by 12k ARR, current customer
- [x] **Identify Problem Variables:** Identify variables with high missing values, unusual distributions, or potential data quality issues

## Transform
- [x] **Clean up Problem Variables:** Address missing values, outliers, or any other issues identified during exploratory analysis
- [x] **Recode Categories:** Recode categorical variables as discussed earlier
- [x] **Automated Feature Engineering:** Use automated feature engineering tools (e.g., Featuretools)
- [x] **Statistical Feature Engineering:** Utilize self-organizing maps to cluster w/ high ARR, clusters/scores as output columns 

## Model Selection
- [x] **Data Splits:** Split data into training, validation, and test sets
- [x] **Evaluation Criteria:** Define evaluation metrics based on business goals
- [x] **Candidate Models:** Consider logistic regression, random forests, gradient boosting, and neural networks
- [x] **Crossfold Training:** Assess model performance robustness across different data subsets
- [x] **Feature Importance:** Analyze feature importance scores from different models
- [x] **Distribution on Unknown Class:** Examine how well models generalize to the unknown class
- [x] **Evaluate & Select Winner:** Evaluate model performance on the validation set and select the best-performing model

## Model Training
- [ ] **Full Training:** Train the selected model (or ensemble) on the entire training dataset
- [ ] **Distribution on Unknown Class:** Analyze model predictions on the unknown class in the test set
- [ ] **Implementation and Upkeep:** Provide recommendations on model implementation in a production environment

## Documentation
- [] **Documentation:** Document decisions, assumptions, challenges, and the overall process
