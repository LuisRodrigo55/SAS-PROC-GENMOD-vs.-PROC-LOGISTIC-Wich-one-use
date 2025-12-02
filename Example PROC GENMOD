PROC GENMOD:
This function is ideal for insurance pricing or complex correlated data, this function is mainly used if you need to analyze multiple loans from the same customer (Repeated Measures) using GEEs (Generalized Estimating Equations, it is a statistical method used when your data points are not independent (i.e., they are correlated)). Its important to notice that we must explicitly define the 'dist' and 'link' to make it behave like a logistic regression.

proc genmod data=Lib.YourDataHere descending;
    class Loan_Term;
    model Default_Flag = Credit_Score Loan_Term / dist=bin link=logit;
    title "Business Case 2: Credit Risk Model (PROC GENMOD)";
run;
