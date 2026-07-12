## Principles of My Statistical Practice

by Christopher Tong

UNDER CONSTRUCTION!!!

### Statistical inferences do not quantify uncertainty; at best they put a lower bound on uncertainty. Uncertainty is best probed further empirically, with more and better data.

I argued for this position at length in [my 2019 paper](https://doi.org/10.1080/00031305.2018.1518264).  Briefly, unless the study design and statistical analysis plan (including the intended statistical model) are prespecified prior to data collection, model uncertainty will not be accounted for in the statistical inferences.  Thus the possibly largest source of uncertainty will not be reflected in the outputs of the fitted statistical model.  Model uncertainty must then be explored empirically by comparing the fitted model's implictations with more and better data.

The reason for this is alluded to in an earlier principle, [The better the model fit, the worse the model's ability to generalize beyond the data](https://github.com/hydrodynamicstability/Perspectives-on-Applied-Statistics/blob/gh-pages/overfitting.md).  However, in most research, the analyst must carry out iterative model building, model criticism, and model selection in order to better characterize the data generating process.  This necessary process inevitably results in a loss of control of the statistical properties of any inferences from the "final model", such as error rates and coverage probabilities.

Statistics as a discipline has achieved success to a large extent by promulgating the illusion that its methodology can be used to properly characterize (and thus tame) uncertainty.  This is only approximately true in highly controlled situations such as acceptance sampling in quality control, or phased clinical trials complying with ICH E8, for the reasons stated above.  The perennial and unresolvable debates over the discipline's "foundations" (i.e., frequentist vs. Bayesian vs. likelihoodist, etc.) are fundamentally ideological, and have distracted attention from the model uncertainty issues which they fail to address.


“Notions of significance tests, confidence intervals, posterior intervals and all the formal apparatus of inference are valuable tools to be used as guides, but not in a mechanical way; they indicate the uncertainty that would apply under somewhat idealized, maybe very idealized, conditions and as such are often lower bounds to real uncertainty.”

  - Sir David R. Cox (2001)


"In summary, a statement of statistical reliability attempts to present to the reader a lower limit (or an upper limit) above which (or below which) he may assume rationally, with a stated risk, that the results of bigger samples would fall, if freed of important persistent operational blemishes.  It should present any information that might help the reader to form his own opinion concerning the validity of conclusions likely to be drawn from the results.

"Evaluation of the statistical reliability of a set of results is not mere calculation of standard errors and confidence limits.  The statistician must go far beyond the statistical methods in textbooks.  He must evaluate uncertainty in terms of possible uses of the data.  Some of this writing is not statistical, but draws on assistance from the expert in the subject-matter."

  - W. Edwards Deming (1965)

### References

D. R. Cox, 2001:  Comment on L. Breiman, Statistical modeling: the two cultures. *Statistical Science*, 16: 199-231.

W. E. Deming, 1965: Principles of professional statistical practice. Annals of Mathematical Statistics, 36: 1883-1900.

C. Tong, 2019: Statistical inference enables bad science; statistical thinking enables good science. American Statistician, 73, sup 1: 246-261.

---

#### Disclaimers

The content on this site was developed solely on my personal time. The views expressed are solely my own, and do not necessarily represent the views, policies, or opinions of my employer or any organization with which I am affiliated.

(c) 2026 by Christopher Tong, except for quoted material
