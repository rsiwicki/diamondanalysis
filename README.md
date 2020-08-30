# diamondanalysis

The following analysis was created to investigate 3 questions regarding the Diamond business and designed to utilise the CRISP-DM process:

Oftentimes people without knowledge assume the larger a diamond (carat) the more valuable it is, this is not always true and can it be demonstrated easily in a visual that can be interpreted by a layman?
Are there any other surprising patterns?
Can a predictive model of price be created with a good level of accuracy that utilises both numerical and categorical qualities of Diamonds?

Note: The underlying data was obtained from Kaggle in order to prove the potential of such a model; however, its likely the prices stated do not reflect the market conditions of 2020.

The project uses the following libraries - numpy, pandas, scikit learn and seaborn.

The project discovers that it is possible build an accurage predictor, finds an interesting clustering of carat sizes and explores some visualisations of the data.


# CRISP-DM

The CRISP-DM process requires utilising the following stages in order to achieve a solution. In the case of this study the stages followed a somewhat iterative cycles of the CRISP-DM stages as both knowledge and analysis progressed. For example, initial exploratory stages of Business Understanding and Data Understanding were iterative, particularly all stages prior to applying the regression model as charts were produced, examined then some new insight gained that engendered more business questions.

# Business Understanding

Basic business understanding about the Diamond market was developed through general research and previous attendance of a lecture by De Beers.

# Data Understanding

Understanding the initial data was straightforward once incubment business understanding was appllied - the grading of stones is relatively standard and the data reflected this 

# Prepare Data

The obtained data was relatively clean upon aquisition, some pre-processing to remove a spurious identity column was applied. 

# Data Modeling

Modelling was straightforward and used scikit regression model with both test and training data sets.

# Evaluate the Results

The results obtained from the predictor were very accurate; however, business understanding highlights that perhaps the data given the seemingly low prices was somewhat out of date.

The strata of carats found in the study where suprising in such that a potentially man-made effect was so clear. Further understanding of the business is required to explore that further.

Production of simple charts using Seaborn to illustrate the increased complexity of the market (above laymans knowledge at least) was straightforward.



