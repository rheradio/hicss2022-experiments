# A Rule Learning Approach for Detecting Faults in Highly Configurable Software Systems from Uniform Random Samples

This repository includes the material needed to reproduce the experiments corresponding to the paper:

Ruben Heradio, David Fernandez-Amoros, Victoria Ruiz, and Manuel J. Cobo. *A Rule Learning Approach for Detecting Faults in Highly Configurable Software Systems from Uniform Random Samples*. Hawaii International Conference on System Sciences (HICSS), 2022. Hawaii, USA.

In it, the [JHipster dataset](https://github.com/xdevroey/jhipster-dataset) is analyzed with the following rule induction engines: AQ, CN2, LEM2, PART, and RIPPER

## Abstract

Software systems tend to become more and more configurable to satisfy the demands of their increasingly variated customers. Testing exhaustively the correctness of highly configurable software is infeasible in most cases because the space of possible configurations is typically colossal. This paper proposes addressing this challenge by (i) working with a representative sample of the configurations, i.e., a uniform random sample, and (ii) processing the results of testing the sample with a rule induction system that extracts the faults that cause the tests to fail. The paper (i) gives a concrete implementation of the approach, (ii) compares the performance of the rule learning algorithms AQ, CN2, LEM2, PART, and RIPPER, and (iii) provides empirical evidence supporting our procedure.

## Acknowledgements

This work has been supported by (i) the Spanish Ministry of Science, Innovation and Universities, under~grants with reference DPI2016-77677-P and PID2019-105381GA-I00, and (ii) the Community of Madrid, under the research network CAM ROBOCITY2030-DIH-CM S2018/NMT-4331.

## Summary

This repository is organized into three directories:

* [script](https://github.com/rheradio/hicss2022-experiments/tree/main/script) includes the [R](https://cran.r-project.org/) script we wrote to run the experiments. Note that the script uses [R Markdown](https://rmarkdown.rstudio.com/).
* [dataset](https://github.com/rheradio/hicss2022-experiments/tree/main/dataset) includes the JHipster dataset.
* [report](https://github.com/rheradio/hicss2022-experiments/tree/main/report) includes the [final HTML report](https://htmlpreview.github.io/?https://github.com/rheradio/hicss2022-experiments/blob/main/report/hicss_2020_report.html) generated with our script.

 
