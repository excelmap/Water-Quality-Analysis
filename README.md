# Water-Quality-Analysis
Summary of Water Potability Dataset:
The dataset contains information about various water quality parameters that determine whether water is potable or not. After cleaning and analyzing the data, the following key points were observed:
1.	Data Structure:
a.	Total samples: 3,276 rows.
b.	Features: 9 numeric variables (e.g., pH, hardness, solids) and 1 binary target variable (Potability).
c.	Missing values: The dataset had missing values in columns like ph, Sulfate, and Trihalomethanes, which were handled by imputing the mean of the respective columns.
2.	Key Findings:
a.	pH: Potable water generally has a more balanced pH range compared to non-potable water, which exhibits a broader and more variable pH.
b.	Hardness: Similar distribution in potable and non-potable water, but non-potable water shows a slightly wider range.
c.	Solids: Non-potable water has a slightly higher concentration of dissolved solids, though both categories cover a wide range.
d.	Chloramines: Potable water tends to have a more consistent chloramine concentration, while non-potable water has higher variance.
e. Sulfate: Potable water typically contains lower sulfate concentrations compared to non-potable water.
f. Conductivity: Conductivity levels are fairly similar between potable and non-potable water, though non-potable water has more extreme values.
g. 	Organic Carbon: Organic carbon levels in non-potable water tend to show greater variability.
h. 	Trihalomethanes: Potable water generally has lower concentrations, while non-potable water has a broader range with higher concentrations.
i.	Turbidity: Both groups exhibit similar turbidity levels, though non-potable water has more outliers.
3.	Correlation Analysis:
   The correlation matrix showed weak linear relationships between most features, except for a moderate correlation between Chloramines and Turbidity (0.32), indicating that these two variables may be somewhat interrelated.
