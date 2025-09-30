# Feature Engineering 
- Feature engineering is the process of using domain knowledge to extract features from raw data. These features can be used to improve the performance of machine learning algorithms.
<img width="594" height="295" alt="image" src="https://github.com/user-attachments/assets/c91c90c6-c021-498c-a366-3a6360416028" />

## Steps in Feature Engineering
Feature engineering can vary depending on the specific problem but the general steps are:
- Data Cleaning: Identify and correct errors or inconsistencies in the dataset to ensure data quality and reliability.
- Data Transformation: Transform raw data into a format suitable for modeling including scaling, normalization and encoding.
- Feature Extraction: Create new features by combining or deriving information from existing ones to provide more meaningful input to the model.
- Feature Selection: Choose the most relevant features for the model using techniques like correlation analysis, mutual information and stepwise regression.
- Feature Iteration: Continuously refine features based on model performance by adding, removing or modifying features for improvement.

## Processes involved in Feature Engineering
**1. Feature Creation**: Feature creation involves generating new features from domain knowledge or by observing patterns in the data. It can be:
- Domain-specific: Created based on industry knowledge like business rules.
- Data-driven: Derived by recognizing patterns in data.
- Synthetic: Formed by combining existing features.

**2. Feature Transformation**: Transformation adjusts features to improve model learning:
- Normalization & Scaling: Adjust the range of features for consistency.
- Encoding: Converts categorical data to numerical form i.e one-hot encoding.
- Mathematical transformations: Like logarithmic transformations for skewed data.
  
**3. Feature Extraction**: Extracting meaningful features can reduce dimensionality and improve model accuracy:
- Dimensionality reduction: Techniques like PCA reduce features while preserving important information.
- Aggregation & Combination: Summing or averaging features to simplify the model.
  
**4. Feature Selection**: Feature selection involves choosing a subset of relevant features to use:
- Filter methods: Based on statistical measures like correlation.
- Wrapper methods: Select based on model performance.
- Embedded methods: Feature selection integrated within model training.
  
**5. Feature Scaling**: Scaling ensures that all features contribute equally to the model:
- Min-Max scaling: Rescales values to a fixed range like 0 to 1.
- Standard scaling: Normalizes to have a mean of 0 and variance of 1.

*Source:* https://www.geeksforgeeks.org/machine-learning/what-is-feature-engineering/
