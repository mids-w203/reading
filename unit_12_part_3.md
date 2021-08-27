# Unit 12: Part 3 
## Evaluating Whether Data Meets the CLM Requirements 

In this section, you will learn about how to test whether your data and model together meet the requirements of the *CLM* to produce reliable estimates. 

For each of the CLM assumptions, you will learn about how to test whether the data satisfies the assumption. 

One learning goal from this section is to be able to _anticipate_ what a problem in a model might look like, quickly make a plot, and evaluate the plots for this problem. This is an imprecise method that we'll refer to as _the ocular method_ -- literally "eyeball it" -- that encourages you to explore your data, rather than just run a test. 

As a backstop to this exploration, though, where appropriate we also provide you a statistical test. 

1. Each of the tests we conduct are variants of a statistical hypothesis test. By this we mean, each test produces a test statistic that has a known distribution under the null hypothesis. 
2. One should be quite careful about what we conclude if we *fail to reject the null hypothesis.* None of the tests in this section produce dispositive evidence that our data and model are "good to go!" for use under the CLM. 

Instead, the null hypothesis for each test is, "The data meets the assumption." This is **not** a strong position to argue from, because there are many ways to fail to reject a null hypothesis without the null hypothesis, in fact, being true: one could have too little data; one could have data with too much underlying variance; and a bevvy of other potential problems. 

## Code For This Section 

All of the code for this section is available on the datahub [[link here](https://r.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fmids-w203%2Fslides&urlpath=rstudio%2F&branch=master)]. Once you launch the datahub, navigate to `./slides/unit_12/clm_assessment.Rmd`. One might consider opening this code and working along with the lecture. After each lecture part -- about IID, perfect colinearilty, linear conditional expectation, homoskedastic errors, and then normally distributed errors -- there will be a short concept check where you will apply the method just demonstrated onto a different set of data. 


