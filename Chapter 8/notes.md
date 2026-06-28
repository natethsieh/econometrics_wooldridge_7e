Questions
- Need to review: 
    - What are the functional differences between t-distribution, chi-square distribution, F distribution, and Z-distribution? What do they look like, how are they related, and what are they used for / to describe?
    - LM-statistic?

Notes 
- Interesting, heteroskedasticity does not create bias. So why is it a Gauss Markov assumption? Because it invalidates the t-test and F-test. Because it affects the *variance* and the standard errors
- You can make your estimates and test results robust to heteroskedasticity through a variety of technical avenues (foe example, Wooldridge approved methodology for SEs is to make a degrees-of-freedom adjustment)
- It is possible to obtain a *better* estimator than OLS when form of heteroskedsticity is known. No longer the BLUE
    - Woh, tell me more...
- A test for heteroskedasticity is the Breusch-Pagan Test, which is basically broken up into three steps: 1) run a standard OLS regression, 2) regress the residuals against the dependent variable, and 3) get a p-value (t, F, or LM, depending on degrees of freedom) that will tell you if the errors can be predicted and therefore are not constant, and thus heteroskedasticity exists.. nice
- 