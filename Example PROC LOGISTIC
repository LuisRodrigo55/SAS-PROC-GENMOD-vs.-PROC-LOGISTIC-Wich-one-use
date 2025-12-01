PROC LOGISTIC:
This function is ideal for Credit Scorecards, Risk Teams, Marketing Response Models; this function will automatically calculates Odds Ratios, and we can use the Area Under the Curve (AUC) instruction for measuring the model performance.

proc logistic data=Lib.YourDataHere descending plots(only)=roc;
    class Loan_Term / param=ref;
    model Default_Flag = Credit_Score Loan_Term;
    title "Example of a Credit Risk Model using PROC LOGISTIC";
run;
