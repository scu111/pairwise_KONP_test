This repository presents R Codes for a function (pairwise_konp_test) to perform pairwise comparisons for the K-sample Omnibus Non-Proportional Hazards (KONP) test (Gorfine et al., 2020 - https://journals.sagepub.com/doi/10.1177/0962280220907355). The KONP test is robust and powerful for hypotheses involving non-proportional hazards. An extra Cau test statistic is also modified in the procedure for use in both proportional and non-proportional hazards. The KONP test is implemented in the KONPSurv R package (https://cran.r-project.org/web/packages/KONPsurv/KONPsurv.pdf).

Pairwise_konp_test modifies the sourcecode of survminer::pairwise_survdiff (https://cran.r-project.org/web/packages/survminer/survminer.pdf). It takes the standard inputs for the KONPsurv::konp_test function in addition to a p.adjust.method call that allows users specify the p-value adjustment method (default = "bonferroni) and
a test-statistic call (default = likelihood ratio "LR") that allows users to specify what p-value to use in the Konp test.

Please email suggestions to solomonudochi@gmail.com.

Thank you.
