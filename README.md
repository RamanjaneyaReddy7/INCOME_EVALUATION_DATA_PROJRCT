**INCOME_EVALUATION_DATA**
This dashboard provides a deep dive into income distribution and disparities across different occupations, education levels, sex, marital status, and relationships using the Income Evaluation Dataset. The analysis is segmented demographically and geographically to provide actionable socio-economic insights.
**Dataset Overview:**
The dataset income evaluation data contains 32,561 records with 15 columns. It is related to income classification, where the target variable is income, indicating whether a person's income is <=50k or  >50k.
The income evaluation dataset contains structured tabular data with a mix of categorical and numerical data.
 Numerical Data's are  age, fnlwgt, education-num ,capital-gain, capital-loss, hours-per-week.
Data set contains two types categorical data's  one is Nominal and  another is Cardinal.
Nominal data are work class, marital-status, occupation, relationship, race, sex ,native-country.

**Top Section:** Income by Education, Sex, and Occupation
**Visual Type:** Grouped Bar Charts (6 categories for occupations)
Each chart presents income count by education level with color-coded bars representing female (pink) and male (orange) for the following occupations:

Admin-clerical
Craft-repair
Exec-managerial
Farming-fishing
Handlers-cleaners
Machine-op-inspct

**📌 Key Observations:**
Higher Education = Higher Income: Particularly evident in Exec-managerial roles, where bachelor's and "some-college" levels dominate.
Gender Disparities: Males tend to occupy higher income brackets more frequently than females across all occupations.
**Occupation-Specific Trends:**
Craft-repair & Machine-ops show more income parity between education levels.
Admin-clerical roles show modest income regardless of gender or education.

**🧮 KPI Cards (Top Right):**
0.89K – Average of capital-gain
0.08K – Average of capital-loss
These show the financial variables contributing to income classification, reflecting how additional assets or losses impact overall economic standing.

**Filters on the Right:**
Interactivity via slicers for user-driven analysis:
Demographics: Sex, Age
Geography: Native Country
Race
Income Groups
Examples shown: Female selected, multiple countries like Canada, China, England, etc.

**🔹 Bottom Section:** Income by Marital Status and Relationship
Visual Type: 100% Stacked Column Chart
X-axis: Marital Status
Color segments: Relationship categories (e.g., Husband, Wife, Not-in-family, Own-child, etc.)

**📌 Key Observations:**
Married-civ-spouse: Dominated by husband and wife roles, with higher income counts.
Never-married: Shows higher presence of not-in-family and own-child, suggesting younger and possibly less financially established individuals.
Divorced & Widowed: More diverse relationship statuses like unmarried and not-in-family, often associated with lower income tiers.

**🔸 Additional Filters (Bottom Right):**
Native Country Segments: Visual segmentation by country (e.g., Cuba, Ecuador, El-Salvador), color-coded for distinction.

**Insights & Value**
Gender & Income Gaps: Consistently visible across occupations, males have higher income frequency.
Education’s Role: Directly correlates with better income opportunities, especially in managerial positions.
Marital Status Dynamics: Being married (particularly in traditional roles like husband/wife) strongly correlates with higher income representation.
Country & Race Factors: Can be filtered to evaluate how income varies across ethnic and national backgrounds, offering a rich base for diversity-focused policy analysis.
