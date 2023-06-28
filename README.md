# Medical Cost Prediction
Predicting customer engagement using machine learning.

## Introduction

Medical expenses are one of the signifi cant recurring expenses in human life. The rising cost of healthcare is anessential concern for many individuals and families. It’s common knowledge that one lifestyle and variousphysical parameters dictate diseases or ailments one can have, and these ailments dictate medical expenses.According to multiple studies, signifi cant factors contributing to higher personal medical care expenses includesmoking, aging, and BMI. In this study, we aim to fi nd a correlation between personal medical expenses anddiff erent factors and compare them. Then we use the prominent attributes as predictors to predict medical costsby creating linear regression models and comparing them using ANOVA. Our fi ndings will provide insights into thefactors driving medical costs and inform strategies for managing healthcare expenses.

## Conclusion

In conclusion, the fi nal model we developed has a good fi t for the data with an adjusted R-squared value of0.8382. The model includes variables such as age, BMI, BMI squared, factor(children), factor(smoker),factor(region), and an interaction term between BMI and factor(smoker). The model equation shows that chargesincrease with age, BMI, and the number of children. Charges are higher for smokers, and there are diff erences incharges based on region.
However, it is important to note that the normality assumption was violated in the model, indicating that the errorsare not normally distributed. To address this issue, we tried several transformations, including Scaling the data,the Box-Cox transformation, square root transformation, exponential transformation, and inverse transformationbut none were successful in satisfying the normality assumption. This suggests that there may be other factorsthat are not captured in the model that infl uence medical charges.
Future recommendations could include exploring more advanced techniques such as non-parametric regressionor ensemble models (like GLM) to improve the model’s performance. Additionally, collecting more data andincluding additional variables could also improve the model’s accuracy.
Overall, our model provides a useful tool for estimating medical charges based on several important predictorvariables.

## References

1. Dataset: Choi, M. (2018, February 21). Medical Cost Personal Datasets. Kaggle. Retrieved March 15, 2023,from
https://www.kaggle.com/datasets/mirichoi0218/insurance
(https://www.kaggle.com/datasets/mirichoi0218/insurance)
2. Moran, J. L., Solomon, P. J., Peisach, A. R., & Martin, J. (2007). New models for old questions: generalizedlinear models for cost prediction. Journal of evaluation in clinical practice, 13(3), 381-389.
3. Dalpiaz, D. (n.d.). Applied Statistics with R. Chapter 14 Transformations. Retrieved April 4, 2023, from
https://book.stat420.org/transformations.html (https://book.stat420.org/transformations.html)
