## Principles of My Statistical Practice

by Christopher Tong

UNDER CONSTRUCTION!!!

### The better the model fit, the worse the model's ability to generalize beyond the data.

This principle applies whenever the data themselves are used to influence the form of the model to be fit, i.e., the statistical model has not been prespecified.  It is particularly apt in procedures such as using forward or backward stepwise variable selection in regression modeling, as noted by Freedman (1983) and Harrell (2001), among many others.  Indeed, the problem has been known since at least the 1970s (e.g., Mosteller & Tukey, 1977; Leamer, 1978).

Bert Gunter and I explained this issue at greater length in our 2017 [critique](https://doi.org/10.1111/j.1740-9713.2017.01057.x) of frequentist inference.  Similar arguments apply to Bayesian and likelihoodist inference, due to the Likelihood Principle.  See also my [2019 paper](https://doi.org/10.1080/00031305.2018.1518264) for additional discussion and references.

---

“Using the data to guide the data analysis is almost as dangerous as not doing so.”

  - Frank E. Harrell, Jr. (2001)


### References

D. Freedman, 1983:  A note on screening regression equations.    *American Statistician*, 37:  152-155.

B. Gunter and C. Tong, 2017:  What are the odds!?  The "airport fallacy" and statistical inference.  *Significance*, 14 (4):  38-41.

F. E. Harrell, Jr., 2001:  *Regression Modeling Strategies, with Applications to Linear Models, Logistic Regression, and Survival Analysis*. Springer.

E. E. Leamer, 1978:  *Specification Searches: Ad Hoc Inference with Nonexperimental Data*.  Wiley.

F. Mosteller and J. W. Tukey, 1977:  *Data Analysis and Regression*.  Addison-Wesley.

C. Tong, 2019: Statistical inference enables bad science; statistical thinking enables good science. *American Statistician,* 73, Sup 1: 246-261.

---

#### Disclaimers

The content on this site was developed solely on my personal time. The views expressed are solely my own, and do not necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.

(c) 2026 by Christopher Tong, except for quoted material
