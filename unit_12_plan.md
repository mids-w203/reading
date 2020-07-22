# Unit 12: The *Classical Linear Model* 

 In this unit, you will learn about what is required to adapt a linear model fitted by OLS regression for use in smaller sets of data than we have used previously. 

 When we introduced OLS regression in earlier units we relied on large-sample properties and showed that because the *Central Limit Theorem* is so powerful, that under very general conditions OLS regression estimates a linear model that has several desirable properties: 
 
 1. It is a plug-in sample estimator for the BLP; 
 2. It produces consistent estimates for relationships between variables; and, 
 3. Through convergence in distribution that is guaranteed by the CLT, we can make statements statements about certainty and uncertainty that arises as a result of sampling. 

 In this unit, we're going to ask what happens if we use the same technique, but without relying on the CLT to generate these desirable properties. (If we haven't very much data, we can't rely on the CLT to work!) 
 
 Here is the broad takeaway: There are five conditions that we will enumerate in order from easiest for data to satisfy to hardest for data to satisfy. 

 1. If data meets the first three conditions [(1) i.i.d., (2) linear conditional mean; (3) no *perfect* colinearity], then even with limited data OLS regression produces estimates that are unbiased.
 2. If data *additionally* meets two more strict conditions [(4) homoskedasticity, (5) normally distributed errors] then we not only are estimates ubiased, but uncertainty estimates are also unbiased. 

 This weeks study is broken into **three** parts. 

 1. The **first** section introduces the conditions that we will evaluate about our data. This section should take fewer than **30** minutes to complete. 
 2. The **second** section works through the math and theory to show how the guarantees of OLS estimators change when different conditions for the data are met. This section should take about **60** minutes to complete. 
 3. The **third** section introduces checks and tests to evaluate whether data does, indeed, meet the requirements for estimates from the OLS estimator to be *meaningfully informative* about population parameters. 