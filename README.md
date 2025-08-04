# Insurance-customer-profiling-and-hypothesis-testing-

# Goal:  To analyze 1,338 health insurance records with 6 attributes and explore cost drivers. 
Column names: age, sex, bmi, children, smoker, region, and charges. 

NUMERICAL COLUMN ANALYSIS: 
  1. Minimum age is 18 years and maximum age is 64 years.
  2. Minimum charge for insurance plan is 1122 and maximum charge for insurance plan is 63770. Hence it has outlier values (10.3%).
  3. Only 16.59% people have normal BMI in the range (18.5 and 24.9).
  4. BMI has 9 outliers values (0.67%) . These may be due to rare health conditions.

CATEGORICAL COLUMN ANALYSIS: 
  1. A new column is formed based on BMI having values- 'Normal', 'Overweight', 'Obsese I', 'Obese II+'
  2. Almost equal number of male and female with slightly more males. 
  3. ~43% people have no children. 
  5. ~80 % of the population are smoker and 20 % are non smokers
  5. there are 4 regions in the database- southeast, southwest, northwest, northeast. regional data is fairly balanced, with slightly more customers in the southeast.

BIVARIATE ANALYSIS: 

  1. A new column is created based on age groups, which include- 18-25, 26-35, 36-45, 46-55, and 56-64.
  2. While analyzing charges and gender, Male population have variable insurance cost than females. While female member charges are more compact and closer to the median.
  3. Number of children alone don't affect insurance cost.

HYPOTHESIS TESTING ANALYSIS: 
  1. For analyzing relationship between smoking status and gender, Chi Squared test of independence is being used. and it was found from the Contingency table that, males(23.5%) are more likely to be smokers than females(17.4%).
  2. For analyzing relationship between BMI and Age columns, Pearson correlation is calculated. and from scatterplot it was found out that though there is statistically significant, but weak relationship between them.
     As age increases, BMI increases very slightly- the effect is minimal.
  3. For analyzing relationship between BMI and regions, One- Way ANOVA test is being used. It was found that atleast one region has different BMI.


BUSINESS RECOMMENDATIONS:
  1. Since every group has extreme cost individuals, for them company should launch 'OUTLIER AWARE RISK POOLING'.
  2. Introduce PREVENTIVE HEALTH PLANS (free checkups, fitness programs) for mid age adults.
  3. For 45+, consider higher base premium. 
  4. For older age people, create tiered premium plans by age bracket.
  5. Offer custom pricing for combinations, example, BMI >30 + smoker + age 45+ = very high risk group.
  6. People with 2-3 children can be targeted for family- focussed insurance plans.
  7. People with larger family, 4 or 5 children, need not be targeted. Child related claims can be considered separately.
  8. Since male tend to have higher and more variable cost than females, premium policy should be more gender centric with certain age- risk brackets.
  9. Smoking centric plans for males can be introduced like-
          a. higher base premium
           b. covers heart disease, cancer(specially lung), COPD, stroke
           c. annual health checkups included
           d. smoking cessation benefit: premium discounts after 1-2 years of quitting.
     








