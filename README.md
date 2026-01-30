# ecommerce-shopper-behavior
## a data analyst project for different purposes: demonstrating skills and learning


# E-commerce Shopper Behavior – Exploratory Data Analysis & Data Quality Assessment
## 1. Project background & objective

The original goal of this project was to create a portfolio-ready analytical case that demonstrates:

- exploratory data analysis (EDA) skills
- analytical reasoning and hypothesis-driven thinking
- the ability to assess data quality and business relevance
- clear documentation and communication of findings
- The dataset was sourced from Kaggle and is described as a synthetic, Amazon / Shopify–inspired e-commerce shopper behavior dataset.

## 2. Dataset overview

- Source: Kaggle
- Nature: Fully synthetic data
- Granularity: One record per customer (aggregated profile)
- Size: ~1,000,000 records
- Features: ~50 numerical and categorical variables
- The dataset intentionally contains no missing values and is cleanly structured.

## 3. Exploratory data analysis summary

During the EDA phase, several important characteristics of the dataset were identified.

### 3.1 Data completeness & structure

- No missing values across features
- Consistent data types
- No apparent data quality issues from a technical perspective
- From a purely technical standpoint, the dataset is well-formed.

### 3.2 Feature distributions

A large number of features exhibit uniform or near-uniform distributions across their value ranges.
Example:
- Household size values are evenly distributed between 1 and 10
This pattern is atypical for real-world customer or household data, where strong skews and dominant modes are usually present.

### 3.3 Relationships & correlations

Despite the large sample size and the high number of numerical features:

- Pairwise correlations between variables are close to zero
- No meaningful multivariate relationships emerged
- Feature interactions appear intentionally decorrelated
- This strongly suggests that the dataset does not encode underlying behavioral or economic mechanisms.

### 3.4 Documentation & interpretability

- No detailed data dictionary or feature generation logic is provided
- Feature meanings must be inferred from column names alone
- There is no clear linkage between features and real-world customer actions or processes
- This limits the ability to formulate and validate business hypotheses.

## 4. Analytical implications

From an analytical and business perspective, the dataset presents the following limitations:

- Lack of time dimension, preventing lifecycle or trend analysis
- Aggregated customer-level data with no transaction or event history
- Feature distributions and relationships inconsistent with real consumer behavior

As a result, while the dataset is suitable for:

- technical EDA demonstrations
- testing pipelines or visualization templates
- it is not well-suited for insight-driven business analysis or storytelling.

## 5. Decision & project scope adjustment

Based on the findings above, a conscious decision was made not to continue this dataset as a full analytical case study.

Instead, this project is intentionally concluded at the EDA stage and reframed as a:
- Data quality, realism, and suitability assessment of synthetic behavioral data
- This reflects a real-world analytical scenario where identifying data limitations early is a critical professional skill.