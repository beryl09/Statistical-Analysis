# Statistical-Analysis
This report analyzes data from Colorado University’s student housing residential facilities,
focusing on demographic and behavioral factors that could influence the likelihood of violence
within campus facilities. The dataset includes observations on variables such as race, age,
gender, and incidents of violence, allowing for a comprehensive statistical examination of
potential risk factors.
Using data from a diverse group of students living in university housing, this study investigates
whether demographic attributes significantly contribute to variations in violence risks. Through a
two-way ANOVA, the research evaluates not only the independent effects of these factors but
also their interactions, particularly between age and gender. Despite prior assumptions that race,
age, or gender may play predictive roles, the findings reveal minimal direct impact, suggesting
that other contextual variables may be more significant in influencing violence probabilities.
This study aims to provide insights for improving campus safety policies, fostering an inclusive
and secure environment for all students. By showing gaps in the current understanding, it also
underscores the need for further research into broader social, psychological, and environmental
factors.
# Data Description
The dataset includes variables:
1.Violence: A numerical measure showing levels of violent incidents.
2.Race: Categorical variable denoting different racial groups.
3.Age: Age of individuals involved, between 17 to 30 years.
4.Gender (Male): Binary indicator for male participants.
Sample Size:
• 247 observations.
• Variance in levels of violence and demographic representation.
Statistical Approach
A two-way ANOVA was conducted to evaluate:
1.Independent effects of race, age, and gender on violence.
2. Interaction effects, particularly between age and gender.
Df Sum Sq Mean Sq F Value Pr(>F)
race 1 0.6 0.6379 0.229. 0.632
age 1 0.0 0.0358 0.013 0.910
male 1 0.8 0.7627 0.274 0.601
Age:male 1 0.2 0.2380 0.086 0.770
Residuals 247 687.0. 2.781
The analysis presented in the ANOVA table evaluates the effects of race, age, gender, and
their interaction (age: significantly greater risk of violence is in the case of intimate
partners, and more important for male victims:
**1. Race**: Of equal importance, there is no main effect for race on the probabilities of
violence (F= 0.229; p = 0.632). This means that there is a very small difference possible
between the two groups of means of violence with reference to the different racial
categories in this data set. There appears to be no impact of Race for differences in risk of
Violence.
**2. Age**: Similarly, the independent effect of age is also insignificant (F = 0.013, p = 0.910).
This implies to us that the age of the offenders does not have essential implication on
violence. In this dataset, age is not predicted as a contributing factor to the variation in risk
of violence.
**3. Gender (Male)**: The primary outcome of gender (male) to violence, though hypothesized
to be positive, is actually zero and least squares means also do not support this hypothesis
(F =0.274; p = 0.601). This implies that gender masculinity or femininity does not act as a
positive or negative predictor of violence risk in relation to other genders included in this
study.
4. **Interaction between Age and Gender (Age: [Male]**: Similarly, the age - gender
interaction term is also insignificant (F = 0.086; p= .770). This shows that indeed age has an
interaction effect with gender that is related to violence risk. In other words, the nature of
the relationship between age and violence risk seems to be generalizable across gender.
**5. Residuals:** Analyses of the residual sum of squares (687.0) and the mean square
(2.7814) reveal quite a large amount of variability left unaccounted for by the model. This
indicates that there may be other variables, which have not been included in the model,
affecting the risk of violence.
# Conclusion:
The ANOVA results indicate that race, age, gender, and their interaction (age: These (self-
reported, alcohol consumption and being male) do not significantly contribute to the risk of
violence in this dataset. Such results imply that other factors, probably beyond the range of
demographics under study, might provide a more accurate perspective on the
heterogeneity in the probability of violence. It is again required in future research to include
other potential predictor variables such as socioeconomic status, education level,
environmental factors or psycho-social factors as part of the model and therefore to obtain
a clearer picture of the antecedents of violence risk
