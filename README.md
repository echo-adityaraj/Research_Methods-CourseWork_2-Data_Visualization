
NHS Hospital Admission : Visual Design
-------------------------------------------
Name : Aditya Raj , Student ID : 20804661
-------------------------------------------

Overview
-------------------------------------------
My project explores NHS hospital admissions data from 2018–19 to 2022–23. 
Using advanced visualizations in Python, I analysed how emergency admissions changed across diagnosis categories before, during, and after the 2020–21 lockdown. 
The main visualizations I used were a heatmap, a hierarchical treemap, and a parallel coordinates plot.
--------------------------------------------

Visual Analysis of NHS Hospital Admissions Before, During, and After the COVID-19 Lockdown
--------------------------------------------

a)Visual Design Type: Parallel Coordinates Plot, Hierarchical Treemap, Heatmap.

b) Name of Tool: Python in Jupyter Notebook using Pandas, Plotly, NumPy and OpenPyXL.

c) Focus Cohort (Years, Age Groups, Genders): The visualization focuses on the NHS hospital admission spreadsheets.
The years include are 2018-19,2019-20,2020-21,2021-22 and 2022-23. The abstraction levels used are Primary Diagnosis 3 Character and Primary Diagnosis 4 Character.

d) Variables: The main variables used are diagnosis code, diagnosis description, emergency admissions, total admissions, mean age, mean length of stay, mean waiting time and year.

e) Visual Mappings: 
(i) Heatmap: rows = 3-character diagnosis categories, columns = years, colour = percentage change relative to 2018-19, hover = raw emergency admission values.
(ii) Treemap: hierarchy = 3-character diagnosis category to 4-character diagnosis subcategory, rectangle size = emergency admission in 2018-19, rectangle colour = percentage change in 2020-21 relative to 2018-19.
(iii) Parallel Coordinates Plot: axes = the five yearly admission values plus total admissions, mean age, mean length of stay and mean waiting time; each line = one selected diagnosis category; line colour = percentage change in 2020-21 relative to 2018-19.

f) Unique Observation: The three visualizations together show that the effect of the COVID-19 period on hospital emergency admissions was not uniform across diagnosis categories. 
The heatmap shows which high frequency 3-character diagnosis groups declined sharply in 2020-21 and whether they recovered by 2022-23. 
The treemap shows that some of the most affected subcategories were also large pre-lockdown categories, meaning major disruption occurred in high burden areas rather than only in rare conditions. 
The parallel coordinates plot adds a multivariate view, showing that categories with similar admission volumes can still differ substantially in mean age, mean waiting time and mean length of stay. 
Overall, the visual analysis suggests that burden, disruption and recovery varied significantly across diagnosis groups.

g) Data Preparation: Five yearly NHS hospital admissions spreadsheets were loaded: 2018-19, 2019-20, 2020-21, 2021-22 and 2022-23. Data was extracted from the Primary Diagnosis 3 Character and Primary Diagnosis 4 Character sheets. 
Column names were cleaned and standardized; blank rows, total rows and missing values were handled; numeric fields were converted and NaN values were removed or filled appropriately. Diagnosis descriptions were retained so that the graphics remain human readable. 
The 3-character and 4-character hierarchy was constructed for the treemap and percentage changes relative to 2018-19 were calculated for temporal comparison.
