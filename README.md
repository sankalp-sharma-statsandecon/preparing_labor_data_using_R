# preparing_labor_data_using_R

Data Preparation with R – Instructions


Files you will need for this question: 

(1)	NAICS 2017 – Statistics Canada: Description of the North American Industry Classification System (NAICS). 
All you would need to understand this assignment is, how the NAICS is works as a hierarchical structure for defining industries at different levels of aggregation. For example (see page 491), a 2-digit NAICS industry (e.g., 23 - Construction) is a composed of a some 3-digit NAICS industries (236 - Construction of buildings, 237 - Heavy and civil engineering construction, and a few more 3-digit NAICS industries). Similarly, a 3-digit NAICS industry (e.g., 236 - Construction of buildings), is composed of 4-digit NAICS industries (2361 - Residential building construction and 2362 - Non-residential building construction).

(2) Raw data: 15 CSV files beginning with RTRA. These files contain employment data by industry at different level of aggregation; 2-digit NAICS, 3-digit NAICS, and 4-digit NAICS. The column names in these files mean as follows: 
o	SYEAR: Survey year
o	SMTH: Survey month
o	NAICS: Industry name and/or associated NAICS code
o	EMPLOYMENT_: Employment in that industry in B.C. 

(3)	LMO Detailed Industries by NAICS: This is an excel file for mapping the RTRA data to the desired data. The first column of this file has a list of 61 industries that we frequently use in our branch. The second column has their NAICS definitions. 
