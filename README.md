# School Dropout and Educational Performance in Brazil

Exploring how educational performance, development indicators and resource distribution relate to school dropout patterns across Brazilian states.

This project is part of my data portfolio as I transition into roles such as **Data Analyst, Business Intelligence Analyst, Analytics Consultant and Junior Data Scientist**.

The goal of the project is to demonstrate how a structured analytical workflow can be used to explore a real world problem, identify patterns in the data and translate results into **clear insights that can support better decisions**.


## Project Motivation

One of the aspects I enjoy most about working with data is the possibility of exploring complex real world systems and trying to understand what may be driving certain outcomes.

Education is an interesting area for this type of analysis because it combines multiple dimensions such as performance indicators, development levels and resource distribution.

In this project, I explore how different variables such as `nota_enem_media`, `renda_media_mensal`, `idh`, `escolas_publicas` and `escolas_privadas` relate to `evasao_escolar_percent`.

Although the dataset is small and simplified, the analysis illustrates the kind of **analytical thinking, problem structuring and insight generation** that are important in analytics and data roles.


## Dataset

The dataset contains educational and socioeconomic indicators for **10 Brazilian states**.

Main variables used in the analysis:

- `nota_enem_media`: average ENEM exam score
- `renda_media_mensal`: average monthly income
- `idh`: Human Development Index
- `escolas_publicas`: number of public schools
- `escolas_privadas`: number of private schools
- `evasao_escolar_percent`: school dropout percentage

These variables allow the exploration of relationships between **educational performance, development indicators and dropout patterns**.


## Tools and Skills Demonstrated

This project highlights both **technical skills** and **analytical reasoning**, which are important for roles in analytics and business intelligence.

Main tools and techniques used:

- **Python**
- **Pandas** for data manipulation
- **Seaborn and Matplotlib** for data visualization
- **Exploratory Data Analysis (EDA)**
- **Correlation analysis**
- **Regression modeling**
- **Decision Tree modeling**
- **Random Forest feature importance**
- **Data interpretation and analytical storytelling**

The project also demonstrates the ability to move from **raw data exploration to structured insights and conclusions**.


## Exploratory Analysis

The analysis begins with a visual exploration of key indicators across states.

Variables such as `nota_enem_media`, `renda_media_mensal` and `evasao_escolar_percent` show meaningful variation between states, suggesting differences in educational outcomes and system conditions.

![ENEM scores](Images/enem_scores.png)

**Figure**: Average ENEM score by state.

The Federal District has the highest score at **530**, while Amazonas has the lowest at **455**.


![Dropout rates](Images/dropout_rates.png)

**Figure**: School dropout percentage by state.

Dropout rates vary from **2.9%** to **7.3%**, indicating noticeable differences in student retention patterns.


## Correlation Patterns

Correlation analysis was used to explore relationships between variables.

The analysis suggests that:

- Higher values of `idh` tend to appear alongside **lower dropout rates**
- Higher `renda_media_mensal` tends to be associated with **higher academic performance**
- Educational performance and development indicators appear connected in the dataset

While this does not imply causality, these relationships help identify **possible drivers of educational outcomes**.


## State Comparison

To better illustrate the patterns, the states with the highest and lowest income levels were compared.

**Federal District**

- `renda_media_mensal`: 3500
- `nota_enem_media`: 530
- `evasao_escolar_percent`: 2.9

**Amazonas**

- `renda_media_mensal`: 1450
- `nota_enem_media`: 455
- `evasao_escolar_percent`: 7.3

This contrast highlights how differences in development indicators and academic performance may appear alongside differences in dropout patterns.


## Predictive Modeling

To complement the exploratory analysis, a predictive workflow was implemented to estimate `evasao_escolar_percent`.

Models used:

- Linear Regression
- Decision Tree Regressor
- Random Forest for feature importance

The purpose of this step was not to build a production model, but to demonstrate how predictive models can help identify variables that carry meaningful signal in the dataset.


## Feature Importance

Random Forest was used to estimate the relative importance of the variables when predicting dropout rates.

![Feature importance](Images/feature_importance.png)

**Figure**: Feature importance for predicting school dropout.

The most relevant variables in this dataset were:

- `escolas_privadas`: 0.262
- `nota_enem_media`: 0.247
- `idh`: 0.222
- `renda_media_mensal`: 0.219
- `escolas_publicas`: 0.049

This suggests that dropout patterns may be associated with a combination of **academic performance, development indicators and resource distribution**.


## Key Insights

Even with a simplified dataset, several patterns appear consistently across the analysis.

- `nota_enem_media` ranges from **455 to 530**, showing noticeable differences in educational performance
- `evasao_escolar_percent` ranges from **2.9% to 7.3%**, indicating meaningful variation in dropout patterns
- Higher `idh` and `renda_media_mensal` tend to appear alongside stronger academic performance
- The comparison between the Federal District and Amazonas highlights how development indicators and dropout patterns may move together
- Feature importance analysis suggests that `escolas_privadas`, `nota_enem_media`, `idh` and `renda_media_mensal` all carry relevant signal for predicting dropout

Taken together, the analysis suggests that school dropout patterns are likely influenced by **multiple factors rather than a single variable**.


## Data Governance Considerations

Even in exploratory projects, it is important to consider principles of **data governance and responsible analysis**.

In real education datasets, analysts must consider:

- data quality and reliability
- transparency of analytical methods
- proper interpretation of results
- responsible communication of findings

Although the dataset used here is simplified, the project follows the same analytical discipline applied in larger data environments.


## Limitations

Some limitations of the analysis include:

- the dataset is small and simplified
- the data is aggregated at the state level
- several potentially relevant variables are not included

Because of this, the results should be interpreted as **analytical exploration rather than definitive conclusions**.


## Future Improvements

Possible extensions of this project include:

- analyzing a larger real world dataset
- adding time series data
- including more education indicators
- building an interactive dashboard for decision makers


## About Me

I am currently transitioning into roles such as **Data Analyst, Business Intelligence Analyst and Junior Data Scientist**.

My background includes living and working in different countries, which helped me develop strong **analytical curiosity, adaptability and problem solving skills**.

Through projects like this one, I aim to demonstrate my ability to combine **technical tools, analytical reasoning and clear communication of insights**.
