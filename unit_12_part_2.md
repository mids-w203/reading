# Unit 12: Part 2
## Properties of the Classical Linear Model 

In this section, you will apply the requirements of data (i.e. assumptions) to learn about the guarantees that exist when data has particular attributes. 

In particular, you will learn that **if** the data used in an OLS regression is: 

1. i.i.d.; 
2. Has a linear conditional expectation; and, 
3. Has no *perfect* colinearity; 

**then** estimates from an OLS produce unbiased estimates that are as good as possible among the set of linear, unbiased estimators. 

In addition, **if** the data used in the regression: 

4. Is homoskedastic (meaning it has constant variance in all parts of the data); and, 
5. Has normally distributed errors after modeling; 

**then** the estimates for the uncertainty in the model estimates is also unbiased. 

Finally, in this section, you will learn that *Maximum Likelihood Estimation (MLE)* produces identical estimates to *OLS Regression*. *MLE* makes strong parametric assertions about the data-generating process; but these are no stronger than the assertions of the *CLM*. It is comforting, then, that these two different algorithms produce identical results.  