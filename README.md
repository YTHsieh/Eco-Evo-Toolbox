---
title: Eco-Evo-Toolbox
tags: [Tutorials, Ph.D project, Evolution, Ecology, Note]

---

---
title: 'Eco-Evo-Toolbox'
disqus: hackmd
---

[![hackmd-github-sync-badge](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg/badge)](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg)  

Eco-Evo-Toolbox
===
###### tags: `Tutorials` `Ph.D project` `Evolution` `Ecology` `Note`

This repository serves a tentatively mission to note useful literatures/Apps/resources using in my researches about Ecology and Evolutionary Biology.  
This repo would periodically synchronize to the [github repo](https://github.com/YTHsieh/Eco-Evo-Toolbox) aswell.  

## Table of Contents

[TOC]

## Statistics

### General topics
- [R package: performance](https://easystats.github.io/performance/index.html)  
    - A component of easystats-verse.
    - A all-in-one package that could help evaluate your model.  

- Nested variables in regression models
    - See the following posts for explanation and solutions.
        - [Cross Validated: How do you deal with "nested" variables in a regression model?](https://stats.stackexchange.com/questions/372257/how-do-you-deal-with-nested-variables-in-a-regression-model)
        - [StackExchange: Including the interaction but not the main effects in a model](https://stats.stackexchange.com/questions/11009/including-the-interaction-but-not-the-main-effects-in-a-model)
        - [Stackoverflow: Why do I get NA coefficients and how does `lm` drop reference level for interaction](https://stackoverflow.com/questions/40723196/why-do-i-get-na-coefficients-and-how-does-lm-drop-reference-level-for-interact)
        - Using GLMMs, estimating coefficients in each group.

- [Bolder, B. M. (2008) Ecological models and data in R. Princeton University Press](https://www.degruyter.com/document/doi/10.1515/9781400840908/html#overview)
    - A good and general book for all parts of statistics, or said, "models", no matter it was a statistical model or mechanistic model. Must read.
    - Also contains introduction and comparison about bayesian methods.
    - Suggested chapters by Grainger et al. (2022):
        - Ch 6, 7: Introduction to maximum likelihood.  
        - Ch 3: Detailed description of basic functional forms and control parameters.  
        - Appendix: Algebra and calculus basics.  
        - Ch 4: Probability theory and distribution.   

- [e-Book: Statistical Inference via Data Science by Chester Ismay and Albert Y. Kim](https://moderndive.github.io/moderndive_labs/static/previous_versions/v0.6.0/index.html)
    - Found on 2023, Nov. 21.
    - Haven't read it yet, but some figures and illustrations that from a glance did catch my eye.

- [e-Book: Interpretable Machine Learning - A guide for making black box models explainable by Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)
    - Add on Nov. 26, 2023.
    - This book seems to contain some "causal inference" part, but haven't been read carefully yet.

### Bootstrapping
- [Medium post: Ditch p-values. Use Bootstrap confidence intervals instead](https://towardsdatascience.com/ditch-p-values-use-bootstrap-confidence-intervals-instead-bba56322b522)  

- [Vedio: 4 Reasons Non-Parametric Bootstrapped Regression (via tidymodels) is Better then Ordinary Regression by 
yuzaR Data Science on Youtube](https://youtu.be/sjCxIHVGkdE?feature=shared)
    - I'm sure that I watched this vedio for knowing how to plot confidence intervals in the early September, 2023; but couldn't remember why, probably after I finished collecting some data and wanted to test some relationship using bootstrapping.  
        - Revist this vedio on November 23, 2023 because I finally thought of that I have seen this before.  
    - This vedio teached you how to do a very simple but super useful bootstrapped linear regression!
    
- [Rblogger's post: understanding bootstrap confidence interval output from the r boot package](https://www.r-bloggers.com/2019/09/understanding-bootstrap-confidence-interval-output-from-the-r-boot-package/)
    - This post kindly and detailly explain the different setting in "type=" argument of function: boot.ci. Also see the references listed below the boot.ci official document.

- [Medium post: Bootstrapping vs. Permutation Testing: Theoretical and experimental comparison using Python Yevgeniy (Gene) Mishchenko](https://towardsdatascience.com/bootstrapping-vs-permutation-testing-a30237795970)
 
### Bayesian statistics
- [Podcast: Learning Bayesian Statistics](https://learnbayesstats.com/)
    - A podcast show that I frequently listen to during my jogging.  
    - I also benefit from it in learning English speaking and listening.  

- [Think Bayes 2nd edition](https://greenteapress.com/wp/think-bayes/)
    - I met this book while jogging and at the same time listening the podcast-Learning Bayesian Statistics. This book is a great self-study resource for people who want to learn bayesian statistics.  

- [R package: brms](https://paul-buerkner.github.io/brms/index.html)
    * Also see the github page for [this package](https://github.com/paul-buerkner/brms).

- [R package: tidybayes](https://mjskay.github.io/tidybayes/)
    - Plotting uncertainty for bayesian models.

- [Gompert, Z., Flaxman, S.M., Feder, J.L., Chevin, L.-M. and Nosil, P. (2022), Laplace's demon in biology: Models of evolutionary prediction. Evolution, 76: 2794-2810. https://doi.org/10.1111/evo.14628](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.14628)
    - Also for "Evolutionary biology".

- [McElreath, R. (2016, 2020) Statistical rethinking: a bayesian course with examples in R and Stan. CRC Press.](https://xcelab.net/rm/statistical-rethinking/)
    - Known by reading [Grainger, T. N. et al. (2022) The American Naturalist, 199(1): 1–20.](https://www.journals.uchicago.edu/doi/abs/10.1086/717206?casa_token=mQ9Ef-cyjb8AAAAA:zZOJrJwoAUPPy3JgPQbU4DRSFRsmKAmWy_KpV9pbOXBE2fZD9StzmWWAcs2Du1FBXnzWRyIfuBM)
    - And also some implementations using other packages by others (some are also listed in the author's website):
        - [e-Book: Statistical Rethinking with brms, ggplot2, and the tidyverse ver 1.0.1 by A Solomon Kurz](https://bookdown.org/ajkurz/Statistical_Rethinking_recoded/)

### GLM (Generalized linear models)
- [Blog post: Generalized Linear Models (GLMs) by Tim Newbold](https://timnewbold.github.io/teaching_resources/GLMs.html)

### GEEs (Generalized estimating equations)
- [A good discussion on Researchgate about the difference between GEEs and GLMMs](https://www.researchgate.net/post/When_do_you_apply_GLMM_vs_GEE)  

### GLMMs (Generalized linear mixed models)
- [Review paper: Generalized linear mixed models: a practical guide for ecology and evolution](https://www.sciencedirect.com/science/article/abs/pii/S0169534709000196)  
- [R package: visreg](https://pbreheny.github.io/visreg/index.html)  
    - Useful package to visualize the results of GLMMs.  
    - Some useful discussion on this package:
        - [The difference between the conditional plot and the contrast plot.](https://stats.stackexchange.com/questions/520774/questions-concerning-visualizing-model-results-with-the-r-package-visreg?newreg=01ebcc3086574df3bc45ecf94685129b)
- [Introduction of mixed models with R](https://m-clark.github.io/mixed-models-with-R/)  
- [Mixed Models for Agriculture in R](https://schmidtpaul.github.io/MMFAIR/)
- [Book: Mixed effects models and extensions in ecology with R](https://rd.springer.com/book/10.1007/978-0-387-87458-6?page=1#toc)
    - This book contains the introduction and also several examples for the use of analysis. The best thing for me is they include what you should write in your paper.  
- [R package: emmeans](https://cran.r-project.org/web/packages/emmeans/index.html)
    - Some discussion about the t.test method in pairs().
        - [1](https://stats.stackexchange.com/questions/369619/how-are-the-degrees-of-freedom-in-the-emmeans-package-calculated-r)
        - [2](https://stats.stackexchange.com/questions/487929/default-pairwise-test-in-emmeans)
- [Blog: Confidence intervals for GLMs](https://fromthebottomoftheheap.net/2018/12/10/confidence-intervals-for-glms/)
    - Discussion about how to correctly calculate confidence intervals for GLM-related models.  
- Methods about confidence intervals
    - c.f. [Puth et al. (2015)](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.12382), [the documentation of "confint.glmmTMB"](https://rdrr.io/cran/glmmTMB/man/confint.glmmTMB.html), 
[this post of "Toward Data Science"](https://towardsdatascience.com/five-confidence-intervals-for-proportions-that-you-should-know-about-7ff5484c024f)

- [R package: report](https://easystats.github.io/report/?fbclid=IwAR1AeXw_RFsG1MNDqE7NGEbSIQldKkZ1QHp7t3G-wKOTC3cme2Op6GstgDg)
    - A component of easystats-verse.
    - An automated statistical report generator, used by plugging in a model-like object.  

- [Applied statistics for experimental biology](https://www.middleprofessor.com/files/applied-biostatistics_bookdown/_book/)
    - Another online-book for the biostatistics. Good practices and examples are inside, including the decision making processes.

- [An example about how to plot the model effect of the mixed model](https://stackoverflow.com/questions/33763089/plotting-predicted-values-from-lmer-as-a-single-plot)

- [R package: partR2](https://cran.r-project.org/web/packages/partR2/index.html)
    - Refs: [Stoffel et al. (2021)](https://peerj.com/articles/11414/#p-20)

- [Book: An introduction to multilevel modeling techniques-MLM and SEM Approaches](https://www.taylorfrancis.com/books/mono/10.4324/9780429060274/introduction-multilevel-modeling-techniques-ronald-heck-scott-thomas)
    - Although multilevel modeling and GLMMs should be treated as synonyms, they often represent the different aspects of the regression method itself. This book gives the introduction of the "multilevel part".  

- [Book: Data analysis using regression and multilevel/hierarchical models](https://books.google.com.tw/books?hl=zh-TW&lr=&id=c9xLKzZWoZ4C&oi=fnd&pg=PR17&dq=Gelmen+2007+hierarchical+regression&ots=bcR7P3Rtlg&sig=ACk0iGPIQS0T7MxeXDiOnWACiy4&redir_esc=y#v=onepage&q=Gelmen%202007%20hierarchical%20regression&f=false)
    - A clear book about the multilevel reality of GLMMs. Worth reading!   
    - The corresponding [R package: arm](https://cran.r-project.org/web/packages/arm/index.html).
        - Still works on Nov. 17, 2022.
    - Related refs: [Qian et al. (2010)](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/09-1043.1)、[plotting tips from this blog post from Lionel R. Hertzog](https://biologyforfun.wordpress.com/2017/06/19/adding-group-level-predictors-in-glmm-using-lme4/?fbclid=IwAR1ej3wJfKMIFJk6PTfgFoRG2XD9XxCRxFdQ3bo-8OVFGvVfxqmALTmDwGc)、[Journal article: Cressie et al. (2009)](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/07-0744.1)、
[Book: Qian (2016)](https://www.taylorfrancis.com/books/mono/10.1201/9781315370262/environmental-ecological-statistics-song-qian).
    - Noted chapters:
        - Ch13.4, p. 287: Correlations between group-level intercepts and slopes.
            - Using mean-adjusted of x preditor, trying to solve the correlation issue.
            - Also see Hox et al. (2018):
                - Ch1.2, p. 4: Why do we need special multilevel analysis techniques?
                - Ch4.2, p. 46: Centering and standardizing explanatory variables


- [Book: Hox et al. (2018) Multilevel Analysis, Techniques and Applications, 3rd edition](https://www.taylorfrancis.com/books/mono/10.4324/9781315650982/multilevel-analysis-joop-hox-mirjam-moerbeek-rens-van-de-schoot)  

- Multivariate generalized linear mixed model
    - This is another big topic, and here I only attach some blogs or papers that address this topic.
        - [Multivariate analysis with mixed modeling tools in R by Ben Bolker (one of the authors of package: lme4)](https://rpubs.com/bbolker/3336)
            - [With a discussion on stackexchange.](https://stats.stackexchange.com/questions/10429/fitting-multivariate-linear-mixed-model-in-r)
        - [R package: mcglm](https://cran.r-project.org/web/packages/mcglm/index.html)  

- [Blog post: Introduction to Multilevel Model and Interactions](https://psu-psychology.github.io/r-bootcamp-2019/talks/RBootcamp_MLMInteractions_2019_0820_Final2.html)
- [RPubs: Multilevel models 2](https://rpubs.com/corey_sparks/70812)  

- [Stackexchange: REML or ML to compare two mixed effects models with differing fixed effects -](https://stats.stackexchange.com/questions/116770/reml-or-ml-to-compare-two-mixed-effects-models-with-differing-fixed-effects-but)  

- [Towardsdatascience: Maximum likelihood (ML) vs. REML by Nikolay Oskolkov](https://towardsdatascience.com/maximum-likelihood-ml-vs-reml-78cf79bef2cf)  

- [Confidence intervals from bootMer in R, and pros/cons of different interval types [duplicate]](https://stats.stackexchange.com/questions/344012/confidence-intervals-from-bootmer-in-r-and-pros-cons-of-different-interval-type)  
    - Also see the link on the top for more discussion.  
    - The below posts also talk about the use of bootMer.  
        - [Stackoverflow: R: obtain coefficients&CI from bootstrapping mixed-effect model results](https://stackoverflow.com/questions/39358438/r-obtain-coefficientsci-from-bootstrapping-mixed-effect-model-results)  
        - [Datascience+: Introduction to bootstrap with applications to mixed-effect models](https://datascienceplus.com/introduction-to-bootstrap-with-applications-to-mixed-effect-models/)  

- [Medium: When Mixed Effects (Hierarchical) Models Fail: Pooling and Uncertainty](https://towardsdatascience.com/when-mixed-effects-hierarchical-models-fail-pooling-and-uncertainty-77e667823ae8)
    - This post gives a clear introduction and great animation for the working of "partial pooling".
    - Also it provide codes and simple introduction of plotting and package: brms.

- [Medium: How linear mixed model works? And how to understand LMM through Bayesian lenses (by Nikolay Oskolkov)](https://towardsdatascience.com/how-linear-mixed-model-works-350950a82911)
    - Also contains a set of codes for bootstrapping (which works like R package: citools that boot the C.I. of predictions).

- lmer's issue: failed to converge due to negative eigenvalue.
    - See discussion in [this post](https://stats.stackexchange.com/questions/242109/model-failed-to-converge-warning-in-lmer) and [this post](https://stackoverflow.com/questions/70537291/lmer-model-failed-to-converge-with-1-negative-eigenvalue).

- [Stackexchange: What is the difference btw fixed effect, random effect and mixed effect models?](https://stats.stackexchange.com/questions/4700/what-is-the-difference-between-fixed-effect-random-effect-and-mixed-effect-mode)

- [McNeish, D., & Kelley, K. (2019). Fixed effects models versus mixed effects models for clustered data: Reviewing the approaches, disentangling the differences, and making recommendations. Psychological Methods, 24(1), 20–35.](https://doi.org/10.1037/met0000182)  
    - Known from listening [podcast: quantitude (S2E29: Multilevel models -- The often unnecessary green monster](https://quantitudepod.org/s2e29-multilevel-models-the-often-unnecessary-green-monster/)).

- Papers on how many group numbers should be used in the LMM?  
    - [Gomes (2022) PeerJ 10:e12794.](https://peerj.com/articles/12794/)  
    - [Oberpriller et al. (2022) Ecology and Evolution 12(7): e9062.](https://onlinelibrary.wiley.com/doi/10.1002/ece3.9062)  
        - See guides and power analysis of LM v.s. LMM.
    - [StackExchange: What is the minimum recommended number of groups for a random effects factor?](https://stats.stackexchange.com/questions/37647/what-is-the-minimum-recommended-number-of-groups-for-a-random-effects-factor)
        - See discussion inside that detailly quoted Gelman and Hill (2007) for the controversial views. 
    - [e-Book: Data Analysis in R by Steve Midway](https://bookdown.org/steve_midway/DAR/random-effects.html)
        - See the analogy / statements inside for the feeling about the minimum number of classes, and also the introduction of GLMM.

- Papers on the violation of assumptions.
    - [Schielzeth et al. (2020) Robustness of linear mixed-effects models to violations of distributional assumptions. Methods Ecol Evol. 11: 1141– 1152.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13434)
        - Feat. Shinichi Nakagawa.

- [R package: DHARMa](https://cran.r-project.org/web/packages/DHARMa/index.html)
    * Known from listening podcast: Learning Bayesian Statistics.
    * A package that help you evaluate your model.

- [R package: bootmlm](https://github.com/marklhc/bootmlm)
    * See [this paper](https://www.tandfonline.com/doi/full/10.1080/00273171.2020.1746902?scroll=top&needAccess=true&role=tab) for the use of this package.
    * Note: This package is still under development.

- [R package: merTools](https://cran.r-project.org/web/packages/merTools/index.html)

### Exploratory data analysis (EDA)
- [rbloggers' post: explore: simplified exploratory data analysis (EDA) in R](https://www.r-bloggers.com/2022/09/explore-simplified-exploratory-data-analysis-eda-in-r/?fbclid=IwAR1tSK6_FVwq39ghlDBSJ6SL1gsgQfJNY8VtMIMnodJjYxGguUSTilJFzqQ)

- [R package: DataExplorer](https://cran.r-project.org/web/packages/DataExplorer/)

### Multivariate statistical analysis
- [Factoextra R Package: Easy Multivariate Data Analyses and Elegant Visualization](http://www.sthda.com/english/wiki/factoextra-r-package-easy-multivariate-data-analyses-and-elegant-visualization)
    - Some tutorials:
        - [Stackoverflow: How to manually adjust the detail of points.](https://stackoverflow.com/questions/62119816/color-only-mean-group-of-pca)

- [PCA - Principal Component Analysis Essentials](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/112-pca-principal-component-analysis-essentials/)

- [Principal Component Analysis in R: prcomp vs princomp](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/118-principal-component-analysis-in-r-prcomp-vs-princomp/)

- [Cross Validated: Can principal component analysis be applied to datasets containing a mix of continuous and categorical variables?](https://stats.stackexchange.com/questions/5774/can-principal-component-analysis-be-applied-to-datasets-containing-a-mix-of-cont)
    - With recommended [R package: FactoMineR](https://cran.r-project.org/web/packages/FactoMineR/index.html).

### Time series analysis
- [Book: Applied time series analysis with R](https://smac-group.github.io/ts/index.html)

- [Book: Forecasting: Principles and Practice (3rd ed.)](https://otexts.com/fpp3/)
    - An example book of using "tidyverts" as the function of time series modelling.

- [Packages: tidyverts](https://tidyverts.org/)
    - A set of packages that work with tidyverse to perform time series analysis.
    - Examples:
        - [Blog post: Climate change: Modeling 140+ years of temperature data with tsibble and fable](https://rethinking.rbind.io/2019/01/21/140-years/)
        - [Blog post: Tidy time series data using tsibbles by Rob J Hyndman](https://robjhyndman.com/hyndsight/tsibbles/)

## Causal inference
### General topics
- **In general**
    - I used to think causal inference as a component of modern statistics, but decided to separate it as a different mathematical tool (at least for now). Part of "causal inference (SCM framework, *sensu stricto*)" use statistical language, and also contains other tools makes it have the ability to think real questions in a different view. I agree with them both, so I would like to treat them equally (2024, Jan. 08).

- [Blog post by Andrew Heiss: Ways to close backdoors in DAGs](https://www.andrewheiss.com/blog/2020/02/25/closing-backdoors-dags/)
    - Added on 2024, Feb. 05.
    - A workablle examples for closing backdoors in DAGs using linear model. Easy to read (took 25 mins for me, after I read 《The Book of Why》.)

- [Huntington-Klein, N. 2022. The Effect: An Introduction to Research Design and Causality, 1st edt. Chapman and Hall/CRC.](https://theeffectbook.net/index.html)
    - Added on 2024, Feb. 06.
    - 《The Effect Book》
    - This links to the web-version of the book.
    - Introduce statstics in a causal taste.
    - Notes:
        - See [Ch13](https://theeffectbook.net/ch-StatisticalAdjustment.html#polynomials) for the interpretation of effect size in polynomial regression (2024, Feb. 06).

- [Causal Inference in R](https://www.r-causal.org/)
    - Added on 2024, Feb. 06.
    - Notes:
        - See [Ch5](https://www.r-causal.org/chapters/05-dags) for examples about kinds of DAGs.

- [R CRAN Task View: Causal Inference](https://cran.r-project.org/web/views/CausalInference.html#rct)
    - Added on 2024, Feb. 08.
    - R packages list for causal inference.

- [Pearl, J. 2010. An introduction to causal inference. The International Journal of Biostatistics 6(2): 7.](https://www.degruyter.com/document/doi/10.2202/1557-4679.1203/html)
    - Added on 2024, Feb. 27.
    - An illustration aims to unify and synthesize different frameworks in the modern causal inference within the SCM framework.

- [Pearl, J. 2009. Causality: Models, reasoning, and inference; 2nd edition](https://bayes.cs.ucla.edu/BOOK-2K/)
    - Added on 2025, Jan. 05.
    - Notes:
        - A must written book in the future (2025, Jan. 05).
        - Also see the [Primer, which was published in 2016](https://bayes.cs.ucla.edu/PRIMER/).

### Popular science book
- [The Book of Why: The New Science of Cause and Effect](http://bayes.cs.ucla.edu/WHY/)
    - Added on 2024, Jan. 08.
    - Keywords: SCM, DAGs.
    - This is a popular science book written by Judea Pearl to introduce his work and the history of causal inference.
    - Chinese version is at [here](https://www.books.com.tw/products/0010825178) (中譯：因果革命：人工智慧的大未來).
    - Debates happens btw Andrew Gelman and Judea Pearl
        - See [this post on Medium](https://vishakh.medium.com/empiricism-and-scientific-change-in-judea-pearls-the-book-of-why-5e77c02a9d8b) for a good book review and a comment about the debate.

### Interaction and effect modification

- [Attia, J. et al. 2022. A proposal for capturing interaction and effect modification using DAGs. International Journal of Epidemiology 51: 1047–1053.](https://academic.oup.com/ije/article/51/4/1047/6607680)
    - Added on 2024, Jan. 16.
    - This paper discuss how to include a statistical "interaction term" in the DAG, and also other issues when doing these.
    - Also see these articles for references:
        - [Nilsson et al. 2021. Int J Epidemiol](https://academic.oup.com/ije/article/50/2/613/5998421?login=false)

### Mediation

- [eBook: A Guide on Data Analysis - Ch34 - Mediation](https://bookdown.org/mike/data_analysis/mediation.html)
    - Added on 2024, Feb. 08.
    - Also includes other topics on data analysis and causal inference.

- [VanderWeele, T. J. 2016. Mediation Analysis: A Practitioner's Guide. Annual Review of Public Health 37: 17–32.](https://www.annualreviews.org/doi/10.1146/annurev-publhealth-032315-021402)
    - Added on 2024, Feb. 08 (Not read yet).

- [Imai, K., Keele, L., Tingley, D., Yamamoto, T. 2011. Unpacking the Black Box of Causality: Learning about Causal Mechanisms from Experimental and Observational Studies. American Political Science Review 105(4):765-789.](https://www.cambridge.org/core/journals/american-political-science-review/article/unpacking-the-black-box-of-causality-learning-about-causal-mechanisms-from-experimental-and-observational-studies/9D2ACE9F784B99A30216D216FBF88553#article)
    - Added on 2024, Feb. 25.
    - Introduce the concept and the use of R package: mediation.

### Other modelling framework with DAGs

- [Arnold, K. F. et al. 2019. DAG-informed regression modelling, agent-based modelling and microsimulation modelling: a critical comparison of methods for causal inference. International Journal of Epidemiology 48: 243–253.](https://academic.oup.com/ije/article/48/1/243/5231935)
    - Added on 2024, Jan. 16 (Not read yet).

### Structured equation modelling

- **In general**
    - SEM has it's causal foundation ([Pearl, 2011](https://escholarship.org/uc/item/490131xj)), so that it's hard to decide where it should be placed in this repo (either in the **Causal inference** section or **Statistics**). I put it here to emphasize its potential to be explained causally.

- [RPubs's post: Intro to structural equation modeling by Chris Halsch & Danielle Salcido (Modified by Ari Grele)](https://rpubs.com/Agrele/SEM)
    - Added on 2024, Feb. 28
    - This is a very friendly post on performing your first SEM.
    - Also see these articles for references:
        - [Lefcheck JS (2016) piecewiseSEM. Methods in Ecology and Evolution](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12512)
            - Notes:
                - [The differences between SEM and CFA.](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12512#:~:text=Because%20piecewise%20SEM%20does%20not%20yet%20incorporate%20latent%20or%20composite%20variables%2C%20it%20is%20often%20and%20more%20correctly%20referred%20to%20as%20confirmatory%20path%20analysis.)
        - [Bollen and Pearl (2013) Book chapter: Eight myths about causality and SEM.](https://link.springer.com/chapter/10.1007/978-94-007-6094-3_15#Sec3)
            - This one gives some historical view on the origin of SEM.

- [eBook: An introduction to structural equation modeling in R by Jonathan S. Lefcheck](https://jslefche.github.io/sem_book/)
    - Added on 2024, Feb. 28.
    - This is a keep-updating book written by the developer of R package: piecewiseSEM, which covers the toturial and working examples about the package.

- [Discussion: On the implementation of SEM in package: brms (one of the so called Bayesian-SEM)](https://github.com/paul-buerkner/brms/issues/303)
    - Added on 2024, Mar. 15.
    - Also see: 
        - [RPubs post: Bayesian SEM with BRMS by Jarrett Byrnes on 2017, Dec. 20](https://rpubs.com/jebyrnes/brms_bayes_sem)

## Evolutionary biology

- [Book: Modern phylogenetic comparative methods and their application in evolutionary biology](https://link.springer.com/book/10.1007/978-3-662-43550-2?page=2#toc)

- [Araya-Ajoy et al. (2015)](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12430)
    - An article on using GLMMs to estimate the relative contribution of different components to the phenotypic traits.

- [Book: Walsh & Lynch (2018) Evolution and selection of quantitative traits](https://academic.oup.com/book/40062)

- [Book: Grant & Grant (2014) 40 years of evolution Darwin's finches on Daphne Major Island](https://www.degruyter.com/document/doi/10.1515/9781400851300/html#contents)

## Species distribution models

## Other GIS related methods
* [QGIS](https://www.qgis.org/en/site/)
    * An oper-source GIS software with GUI.
* [Downloading and exploring raster data using R package: raster](https://emilypiche.github.io/BIO381/raster.html)
* [R package: maptiles](https://github.com/riatelab/maptiles)
    * This package downloads, composes and displays tiles from a large number of providers (e.g. OpenStreetMap, Stamen, Esri, CARTO, or Thunderforest).  
* [R-spatial](https://r-spatial.org/)
    * This project works on making R as a better and more convenient environment to do the spatiotemporal analysis. Several packages were developed, and also the news and blog post were released as guides.
* [R as GIS for Economists](https://tmieno2.github.io/R-as-GIS-for-Economists/)  
    * This online book gives a detail of many real world GIS analytic scenarios using R.  
    * e.g. [Extracting Values from Raster Layers for Vector Data](https://tmieno2.github.io/R-as-GIS-for-Economists/extracting-values-from-raster-layers-for-vector-data.html)
* [GDAL-Geotiff's introduction](https://gdal.org/drivers/raster/gtiff.html)
    * [The discussion about compression algorithm](https://gis.stackexchange.com/questions/1104/should-gdal-be-set-to-produce-geotiff-files-with-compression-which-algorithm-sh)  
* [R package: terra](https://cran.r-project.org/web/packages/terra/index.html)
    * The function: focal()
        * [This post](https://gis.stackexchange.com/questions/443159/r-focal-function-terra-vs-raster) discuss the use of focal() to perform the grid-wide calculation by a 2D moving window.
            * Still works on July 24, 2023.  
* [R package: rgee](https://r-spatial.github.io/rgee/)
    - Added on 2024, May 21.
        - Note:
            - "rgee is an R binding package for calling [Google Earth Engine](https://earthengine.google.com/) API from within R."
            - [rgee examples](https://csaybar.github.io/rgee-examples/)

## Theoretical ecology
- [Wikipedia: Eigenvalues and eienvectors](https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors)
- [Caswell (2001) Matrix Population Models](https://global.oup.com/academic/product/matrix-population-models-9780878931217?cc=tw&lang=en&)
- [Ellner, S. P. (2016) Data-driven Modelling of Structured Populations: A Practical Guide to the Integral Projection Model. Springer.](https://link.springer.com/book/10.1007/978-3-319-28893-2)
    - Added on 2024, Jan. 16.

- [eBook: lefko3 - Creating and analyzing matrix projection models in R](https://bookdown.org/cdorm/lefko3gentle/)
    - Added on 2024, Apr. 01.
    - Note:
        - Including IPM.
        - Including life table response experiments ([LTRE](https://bookdown.org/cdorm/lefko3gentle/ltre.html)).

- [Case (2000) An illustrated guide to theoretical ecology](https://global.oup.com/ushe/product/an-illustrated-guide-to-theoretical-ecology-9780195085129?cc=tw&lang=en&)
- [Dercole & Rinaldi (2008) Analysis of Evolutionary Processes: The Adaptive Dynamics Approach and Its Applications](https://press.princeton.edu/books/hardcover/9780691120065/analysis-of-evolutionary-processes)
    - Note: 
        - This framework is also introduced in Doebeli (2012) p. 227–242 in Svensson & Calsbeek (eds.) **The Adaptive landscape in evolutionary biology**.
- [Ohgushi et al. (eds.)(2012) Trait-Mediated Indirect Interactions
Ecological and Evolutionary Perspectives](https://www.cambridge.org/cn/academic/subjects/life-sciences/ecology-and-conservation/trait-mediated-indirect-interactions-ecological-and-evolutionary-perspectives?format=PB&isbn=9780521173131)
- [Otto & Day (2007) A biologist's guide to mathematical modeling in Ecology and Evolution](https://press.princeton.edu/books/hardcover/9780691123448/a-biologists-guide-to-mathematical-modeling-in-ecology-and-evolution)
- [Kooijman-SALM (2010) Dynamic energy budget theory for metabolic organisation, 3rd edition. Cambridge Press.](https://www.cambridge.org/core/books/dynamic-energy-budget-theory-for-metabolic-organisation/A50EC7C47CEAEE4100A24BE0DAD537DB)
    - Note:
        - There is an interesting analogy about DEB—[Nisbet et al. (2010)](https://royalsocietypublishing.org/doi/abs/10.1098/rstb.2010.0167): "... We conclude that a bioenergetic model serving solely as a ‘regression’ connecting organismal performance to the history of its environment can rest on simpler representations than those of standard DEB."  
- [Grimm, V. & Railsback, S. F. (2005) Individual-based modeling and ecology. Princeton University Press. 428 pp.](https://press.princeton.edu/books/paperback/9780691096667/individual-based-modeling-and-ecology)  

## Systematics

## Apps for collaboration
* [hackmd](https://hackmd.io/)
    * Online platform for markdown editing. Useful in taking notes.  
* Google workspace
* [Overleaf](https://www.overleaf.com/)
    * Online apps for Latex writing and collaboration.  
* Notion
* [Git](https://git-scm.com/)
    * Use with Github.
    * Ref: [Commit Often, Perfect Later, Publish Once: Git Best Practices](https://sethrobertson.github.io/GitBestPractices/#pubonce).
* [Github](https://github.com/)
* Google meet
    * [How long the meeting code is valid?](https://workspaceupdates.googleblog.com/2021/05/check-when-your-google-meet-meeting.html)  
    * [The introduction of "Quick access" function.](https://support.google.com/a/users/answer/9846862?hl=zh-Hant&co=GENIE.Platform%3DDesktop#zippy=%2C%E5%A6%82%E4%BD%95%E9%96%8B%E5%95%9F%E6%88%96%E9%97%9C%E9%96%89%E5%BF%AB%E9%80%9F%E5%AD%98%E5%8F%96%E5%8A%9F%E8%83%BD)  
    * [Tutorials for controling slides from multiple participants](https://graduatestu-evo.blogspot.com/2022/05/blog-post.html)
    * Note:
        * I suggest to create meet room in the Google calendar, because it gives us more ability to control the settings.
* Colab
    * [Stackoverflow: How to save R output in google colab?](https://stackoverflow.com/questions/64708511/saving-r-output-in-google-colab)
* [Rstudio workbench](https://www.rstudio.com/products/workbench/)

## References management
* [Zotero](https://www.zotero.org/)
    * [Zotero Keyboard Shortcuts](https://www.zotero.org/support/kb/keyboard_shortcuts) is the official document for the KB shortcuts.
        * Remember that:
            * 1. Select a item, and then hold on / click "Ctrl" would hightlight the folder which this item belongs to; double clicks the "Ctrl" would cancel the highlights.

## Resources for programming language  
* [The Epidemiologist R Handbook](https://epirhandbook.com/en/index.html)
* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)
    * One of the series of rmarkdown books written by the author, [Yihui Xie](https://yihui.org/).  
    * Systematic answers about rmarkdown issues would be found in these online-books.
* [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/)
    * One of the series of rmarkdown books written by the author.  
* [R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)
    * One of the series of rmarkdown books written by the author.  
* [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
    * One of the series of rmarkdown books written by the author.  
* [R package: rstatix](https://rpkgs.datanovia.com/rstatix/index.html)
    * This package contains many useful functions for statistical works in R; working fine with "pipe" operator.
        * See the links at the bottom and [this post](https://www.datanovia.com/en/blog/how-to-add-p-values-to-ggplot-facets/) for good references of adding statistical results on a ggplot-object.
            * e.g. the use of rstatix and [ggpubr](https://rpkgs.datanovia.com/ggpubr/) including manually adding p-values.  
* [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/index.html)  
* [Add CLD (letters for significance) to a ggplot-object](https://schmidtpaul.github.io/DSFAIR/compactletterdisplay.html)  
    * This website also gives many good examples for statistical practice and plotting.  
    * Also see these articles for references: [Lin et al. (2021)](https://datadryad.org/stash/dataset/doi:10.5061/dryad.q573n5tgj)  
* [Big Book of R](https://www.bigbookofr.com/index.html)  
    * A big collection of useful R-related concepts and resources. Just get into it and try to search anything you are interested in.
* [CRAN Task View: High-Performance and Parallel Computing with R](https://cran.r-project.org/web/views/HighPerformanceComputing.html)
* [R package: lubridate](https://lubridate.tidyverse.org/)
* [R package: ggsci](https://cran.r-project.org/web/packages/ggsci/)
* [StackExchange: Opening .nb in other software or exporting to other languages](https://mathematica.stackexchange.com/questions/28409/opening-nb-in-other-software-or-exporting-to-other-languages)
    * For software: Mathematica.
* [R package: tidymodels](https://www.tidymodels.org/)
    * Including [package: rsample](https://rsample.tidymodels.org/index.html), which could be use for bootstrapping.
* [R package: ggdist](https://mjskay.github.io/ggdist/)
    * Plotting uncertainty for frequentist models.
* [R package: ggridges](https://cran.r-project.org/web/packages/ggridges/)
    * Suggested by GCHsu on 20230713.
    * Plotting the distribution of data through multiple dimensions (e.g. space and time.)
* [R package: ciTools](https://cran.r-project.org/web/packages/ciTools/index.html)
    * Function to add C.I. in the data range.
* [R package: tryCatchLog](https://cran.r-project.org/web/packages/tryCatchLog/index.html)
    * A better package for handling try-Catch mechanisms in R.
        * This package support using [R package: futile.logger](https://cran.r-project.org/web/packages/futile.logger/index.html) to perform logging utility.
* [R package: Webshot](https://cran.r-project.org/web/packages/webshot/index.html)
    * See the URL tag inside for the better introduction.
* [Book: Gillespie C. 2021. Efficient R programming (e-book)](https://csgillespie.github.io/efficientR/)
    * Although not haven't read yet, the title seems good and interesting! (2023, September 05)

* [Code Folding and Sections in the RStudio IDE by Posit Support](https://support.posit.co/hc/en-us/articles/200484568-Code-Folding-and-Sections-in-the-RStudio-IDE)
    * Useful when you want to navigate through your Rscripts / codes.

## Information visualization
* [NVSCheatSheet of graphic principles](https://github.com/GraphicsPrinciples/CheatSheet/blob/master/NVSCheatSheet.pdf?fbclid=IwAR0a74lWpqKZ-l1T6n1UQK-3Nyo0OuED0UUAxUW4dtiBtjbmIlRFxqwsLMQ)
* [BBC Visual and Data Journalism cookbook for R graphics](https://bbc.github.io/rcookbook/)
    * [Corresponding R package: bbplot](https://github.com/bbc/bbplot)
* [R package: wesanderson](https://github.com/karthik/wesanderson)
* [Plotly Chart Studio](https://chart-studio.plotly.com/create/?fbclid=IwAR0GkNrRZR_ClX9j5FweGapWV3lcxxrUlyIMnIvyAXGIKNlpaHUMCfsb7-M#/)
    * An online platform for quickly accessing plotly library. It's useful when you want to take a glance about your data, but couldn't access R at that time.
* Good figures for illustration!
    * [Annual average temperature map.png by Robert A. Rohde (Berkeley Earth) on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Annual_Average_Temperature_Map.png)  
        * With land data only.  
    * [Annual average temperature map.jpg by Robert A. Rohde (Berkeley Earth) on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Annual_Average_Temperature_Map.jpg)  
        * Including ocean data.
    * [Global digital elevation model.jpg by NASA on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Global_Digital_Elevation_Model.jpg)

## Writing
- [The Chicago Manual of Style Online](https://www.chicagomanualofstyle.org/home.html)

## Insect-plant interaction related issue
* [LTER protocols](https://lter.kbs.msu.edu/protocols)
    * Protocols for the setting of LTER.
    * Useful references for measuring plant's traits and soil's properties.
* [PhenoCam](https://phenocam.nau.edu/webcam/)
    * Phenology monitoring network based on webcams.

## Open databases/datasets
- [2022 iThome 鐵人賽：細數台灣公民該知道的 25 個開放資料庫](https://ithelp.ithome.com.tw/users/20103852/ironman/5889)
- [中華民國內政部營建署城鄉發展分署：全國土地使用分區資料查詢系統](https://luz.tcd.gov.tw/web/)
    - Although I didn't find the way to export the layers, the platform actually perform convenient searching functions for the user. E.g. Searching the area of a certain school is quite easy in this platform.
- [中華民國內政部國土測繪中心：國土利用現況調查成果資訊專區](https://www.nlsc.gov.tw/cl.aspx?n=13705)

## Audio signal processing 
- [CLT: ffmpeg](https://ffmpeg.org/)
    - The indroduction on the site: A complete, cross-platform solution to record, convert and stream audio and video.
    - Open-sourced.
    - See these posts for the usage guide
        - [Download and Combine Media Segments of a HLS Stream Locally Using FFMpeg](https://www.codementor.io/@chuksdurugo/download-and-combine-media-segments-of-a-hls-stream-locally-using-ffmpeg-150zo6t775)
        - [Stack overflow: saving frames from webcam stream](https://stackoverflow.com/questions/53980367/saving-frames-from-webcam-stream)
        - [StackExchange: How to download portion of video with youtube-dl command?](https://unix.stackexchange.com/questions/230481/how-to-download-portion-of-video-with-youtube-dl-command)

## Image processing
- [eBook: Vincent Mazet, “Basics of image processing” University of Strasbourg, 2020-2023.](https://vincmazet.github.io/bip/index.html)
    - Theories about image processing with computer.

- Technical guides about table extraction in pdf files
    - [Medium: A table detection, cell recognition and text extraction algorithm to convert tables in images to excel files](https://towardsdatascience.com/a-table-detection-cell-recognition-and-text-extraction-algorithm-to-convert-tables-to-excel-files-902edcf289ec)

:::info
**Find this document incomplete or need to update?** Let me know your suggestions!
:::---
title: 'Eco-Evo-Toolbox'
disqus: hackmd
---

[![hackmd-github-sync-badge](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg/badge)](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg)  

Eco-Evo-Toolbox
===
###### tags: `Tutorials` `Ph.D project` `Evolution` `Ecology` `Note`

This repository serves a tentatively mission to note useful literatures/Apps/resources using in my researches about Ecology and Evolutionary Biology.  
This repo would periodically synchronize to the [github repo](https://github.com/YTHsieh/Eco-Evo-Toolbox) aswell.  

## Table of Contents

[TOC]

## Statistics

### General topics
- [R package: performance](https://easystats.github.io/performance/index.html)  
    - A component of easystats-verse.
    - A all-in-one package that could help evaluate your model.  

- Nested variables in regression models
    - See the following posts for explanation and solutions.
        - [Cross Validated: How do you deal with "nested" variables in a regression model?](https://stats.stackexchange.com/questions/372257/how-do-you-deal-with-nested-variables-in-a-regression-model)
        - [StackExchange: Including the interaction but not the main effects in a model](https://stats.stackexchange.com/questions/11009/including-the-interaction-but-not-the-main-effects-in-a-model)
        - [Stackoverflow: Why do I get NA coefficients and how does `lm` drop reference level for interaction](https://stackoverflow.com/questions/40723196/why-do-i-get-na-coefficients-and-how-does-lm-drop-reference-level-for-interact)
        - Using GLMMs, estimating coefficients in each group.

- [Bolder, B. M. (2008) Ecological models and data in R. Princeton University Press](https://www.degruyter.com/document/doi/10.1515/9781400840908/html#overview)
    - A good and general book for all parts of statistics, or said, "models", no matter it was a statistical model or mechanistic model. Must read.
    - Also contains introduction and comparison about bayesian methods.
    - Suggested chapters by Grainger et al. (2022):
        - Ch 6, 7: Introduction to maximum likelihood.  
        - Ch 3: Detailed description of basic functional forms and control parameters.  
        - Appendix: Algebra and calculus basics.  
        - Ch 4: Probability theory and distribution.   

- [e-Book: Statistical Inference via Data Science by Chester Ismay and Albert Y. Kim](https://moderndive.github.io/moderndive_labs/static/previous_versions/v0.6.0/index.html)
    - Found on 2023, Nov. 21.
    - Haven't read it yet, but some figures and illustrations that from a glance did catch my eye.

- [e-Book: Interpretable Machine Learning - A guide for making black box models explainable by Christoph Molnar](https://christophm.github.io/interpretable-ml-book/)
    - Add on Nov. 26, 2023.
    - This book seems to contain some "causal inference" part, but haven't been read carefully yet.

### Bootstrapping
- [Medium post: Ditch p-values. Use Bootstrap confidence intervals instead](https://towardsdatascience.com/ditch-p-values-use-bootstrap-confidence-intervals-instead-bba56322b522)  

- [Vedio: 4 Reasons Non-Parametric Bootstrapped Regression (via tidymodels) is Better then Ordinary Regression by 
yuzaR Data Science on Youtube](https://youtu.be/sjCxIHVGkdE?feature=shared)
    - I'm sure that I watched this vedio for knowing how to plot confidence intervals in the early September, 2023; but couldn't remember why, probably after I finished collecting some data and wanted to test some relationship using bootstrapping.  
        - Revist this vedio on November 23, 2023 because I finally thought of that I have seen this before.  
    - This vedio teached you how to do a very simple but super useful bootstrapped linear regression!
    
- [Rblogger's post: understanding bootstrap confidence interval output from the r boot package](https://www.r-bloggers.com/2019/09/understanding-bootstrap-confidence-interval-output-from-the-r-boot-package/)
    - This post kindly and detailly explain the different setting in "type=" argument of function: boot.ci. Also see the references listed below the boot.ci official document.

- [Medium post: Bootstrapping vs. Permutation Testing: Theoretical and experimental comparison using Python Yevgeniy (Gene) Mishchenko](https://towardsdatascience.com/bootstrapping-vs-permutation-testing-a30237795970)
 
### Bayesian statistics
- [Podcast: Learning Bayesian Statistics](https://learnbayesstats.com/)
    - A podcast show that I frequently listen to during my jogging.  
    - I also benefit from it in learning English speaking and listening.  

- [Think Bayes 2nd edition](https://greenteapress.com/wp/think-bayes/)
    - I met this book while jogging and at the same time listening the podcast-Learning Bayesian Statistics. This book is a great self-study resource for people who want to learn bayesian statistics.  

- [R package: brms](https://paul-buerkner.github.io/brms/index.html)
    * Also see the github page for [this package](https://github.com/paul-buerkner/brms).

- [R package: tidybayes](https://mjskay.github.io/tidybayes/)
    - Plotting uncertainty for bayesian models.

- [Gompert, Z., Flaxman, S.M., Feder, J.L., Chevin, L.-M. and Nosil, P. (2022), Laplace's demon in biology: Models of evolutionary prediction. Evolution, 76: 2794-2810. https://doi.org/10.1111/evo.14628](https://onlinelibrary.wiley.com/doi/full/10.1111/evo.14628)
    - Also for "Evolutionary biology".

- [McElreath, R. (2016, 2020) Statistical rethinking: a bayesian course with examples in R and Stan. CRC Press.](https://xcelab.net/rm/statistical-rethinking/)
    - Known by reading [Grainger, T. N. et al. (2022) The American Naturalist, 199(1): 1–20.](https://www.journals.uchicago.edu/doi/abs/10.1086/717206?casa_token=mQ9Ef-cyjb8AAAAA:zZOJrJwoAUPPy3JgPQbU4DRSFRsmKAmWy_KpV9pbOXBE2fZD9StzmWWAcs2Du1FBXnzWRyIfuBM)
    - And also some implementations using other packages by others (some are also listed in the author's website):
        - [e-Book: Statistical Rethinking with brms, ggplot2, and the tidyverse ver 1.0.1 by A Solomon Kurz](https://bookdown.org/ajkurz/Statistical_Rethinking_recoded/)

### GLM (Generalized linear models)
- [Blog post: Generalized Linear Models (GLMs) by Tim Newbold](https://timnewbold.github.io/teaching_resources/GLMs.html)

### GEEs (Generalized estimating equations)
- [A good discussion on Researchgate about the difference between GEEs and GLMMs](https://www.researchgate.net/post/When_do_you_apply_GLMM_vs_GEE)  

### GLMMs (Generalized linear mixed models)
- [Review paper: Generalized linear mixed models: a practical guide for ecology and evolution](https://www.sciencedirect.com/science/article/abs/pii/S0169534709000196)  
- [R package: visreg](https://pbreheny.github.io/visreg/index.html)  
    - Useful package to visualize the results of GLMMs.  
    - Some useful discussion on this package:
        - [The difference between the conditional plot and the contrast plot.](https://stats.stackexchange.com/questions/520774/questions-concerning-visualizing-model-results-with-the-r-package-visreg?newreg=01ebcc3086574df3bc45ecf94685129b)
- [Introduction of mixed models with R](https://m-clark.github.io/mixed-models-with-R/)  
- [Mixed Models for Agriculture in R](https://schmidtpaul.github.io/MMFAIR/)
- [Book: Mixed effects models and extensions in ecology with R](https://rd.springer.com/book/10.1007/978-0-387-87458-6?page=1#toc)
    - This book contains the introduction and also several examples for the use of analysis. The best thing for me is they include what you should write in your paper.  
- [R package: emmeans](https://cran.r-project.org/web/packages/emmeans/index.html)
    - Some discussion about the t.test method in pairs().
        - [1](https://stats.stackexchange.com/questions/369619/how-are-the-degrees-of-freedom-in-the-emmeans-package-calculated-r)
        - [2](https://stats.stackexchange.com/questions/487929/default-pairwise-test-in-emmeans)
- [Blog: Confidence intervals for GLMs](https://fromthebottomoftheheap.net/2018/12/10/confidence-intervals-for-glms/)
    - Discussion about how to correctly calculate confidence intervals for GLM-related models.  
- Methods about confidence intervals
    - c.f. [Puth et al. (2015)](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2656.12382), [the documentation of "confint.glmmTMB"](https://rdrr.io/cran/glmmTMB/man/confint.glmmTMB.html), 
[this post of "Toward Data Science"](https://towardsdatascience.com/five-confidence-intervals-for-proportions-that-you-should-know-about-7ff5484c024f)

- [R package: report](https://easystats.github.io/report/?fbclid=IwAR1AeXw_RFsG1MNDqE7NGEbSIQldKkZ1QHp7t3G-wKOTC3cme2Op6GstgDg)
    - A component of easystats-verse.
    - An automated statistical report generator, used by plugging in a model-like object.  

- [Applied statistics for experimental biology](https://www.middleprofessor.com/files/applied-biostatistics_bookdown/_book/)
    - Another online-book for the biostatistics. Good practices and examples are inside, including the decision making processes.

- [An example about how to plot the model effect of the mixed model](https://stackoverflow.com/questions/33763089/plotting-predicted-values-from-lmer-as-a-single-plot)

- [R package: partR2](https://cran.r-project.org/web/packages/partR2/index.html)
    - Refs: [Stoffel et al. (2021)](https://peerj.com/articles/11414/#p-20)

- [Book: An introduction to multilevel modeling techniques-MLM and SEM Approaches](https://www.taylorfrancis.com/books/mono/10.4324/9780429060274/introduction-multilevel-modeling-techniques-ronald-heck-scott-thomas)
    - Although multilevel modeling and GLMMs should be treated as synonyms, they often represent the different aspects of the regression method itself. This book gives the introduction of the "multilevel part".  

- [Book: Data analysis using regression and multilevel/hierarchical models](https://books.google.com.tw/books?hl=zh-TW&lr=&id=c9xLKzZWoZ4C&oi=fnd&pg=PR17&dq=Gelmen+2007+hierarchical+regression&ots=bcR7P3Rtlg&sig=ACk0iGPIQS0T7MxeXDiOnWACiy4&redir_esc=y#v=onepage&q=Gelmen%202007%20hierarchical%20regression&f=false)
    - A clear book about the multilevel reality of GLMMs. Worth reading!   
    - The corresponding [R package: arm](https://cran.r-project.org/web/packages/arm/index.html).
        - Still works on Nov. 17, 2022.
    - Related refs: [Qian et al. (2010)](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/09-1043.1)、[plotting tips from this blog post from Lionel R. Hertzog](https://biologyforfun.wordpress.com/2017/06/19/adding-group-level-predictors-in-glmm-using-lme4/?fbclid=IwAR1ej3wJfKMIFJk6PTfgFoRG2XD9XxCRxFdQ3bo-8OVFGvVfxqmALTmDwGc)、[Journal article: Cressie et al. (2009)](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/07-0744.1)、
[Book: Qian (2016)](https://www.taylorfrancis.com/books/mono/10.1201/9781315370262/environmental-ecological-statistics-song-qian).
    - Noted chapters:
        - Ch13.4, p. 287: Correlations between group-level intercepts and slopes.
            - Using mean-adjusted of x preditor, trying to solve the correlation issue.
            - Also see Hox et al. (2018):
                - Ch1.2, p. 4: Why do we need special multilevel analysis techniques?
                - Ch4.2, p. 46: Centering and standardizing explanatory variables


- [Book: Hox et al. (2018) Multilevel Analysis, Techniques and Applications, 3rd edition](https://www.taylorfrancis.com/books/mono/10.4324/9781315650982/multilevel-analysis-joop-hox-mirjam-moerbeek-rens-van-de-schoot)  

- Multivariate generalized linear mixed model
    - This is another big topic, and here I only attach some blogs or papers that address this topic.
        - [Multivariate analysis with mixed modeling tools in R by Ben Bolker (one of the authors of package: lme4)](https://rpubs.com/bbolker/3336)
            - [With a discussion on stackexchange.](https://stats.stackexchange.com/questions/10429/fitting-multivariate-linear-mixed-model-in-r)
        - [R package: mcglm](https://cran.r-project.org/web/packages/mcglm/index.html)  

- [Blog post: Introduction to Multilevel Model and Interactions](https://psu-psychology.github.io/r-bootcamp-2019/talks/RBootcamp_MLMInteractions_2019_0820_Final2.html)
- [RPubs: Multilevel models 2](https://rpubs.com/corey_sparks/70812)  

- [Stackexchange: REML or ML to compare two mixed effects models with differing fixed effects -](https://stats.stackexchange.com/questions/116770/reml-or-ml-to-compare-two-mixed-effects-models-with-differing-fixed-effects-but)  

- [Towardsdatascience: Maximum likelihood (ML) vs. REML by Nikolay Oskolkov](https://towardsdatascience.com/maximum-likelihood-ml-vs-reml-78cf79bef2cf)  

- [Confidence intervals from bootMer in R, and pros/cons of different interval types [duplicate]](https://stats.stackexchange.com/questions/344012/confidence-intervals-from-bootmer-in-r-and-pros-cons-of-different-interval-type)  
    - Also see the link on the top for more discussion.  
    - The below posts also talk about the use of bootMer.  
        - [Stackoverflow: R: obtain coefficients&CI from bootstrapping mixed-effect model results](https://stackoverflow.com/questions/39358438/r-obtain-coefficientsci-from-bootstrapping-mixed-effect-model-results)  
        - [Datascience+: Introduction to bootstrap with applications to mixed-effect models](https://datascienceplus.com/introduction-to-bootstrap-with-applications-to-mixed-effect-models/)  

- [Medium: When Mixed Effects (Hierarchical) Models Fail: Pooling and Uncertainty](https://towardsdatascience.com/when-mixed-effects-hierarchical-models-fail-pooling-and-uncertainty-77e667823ae8)
    - This post gives a clear introduction and great animation for the working of "partial pooling".
    - Also it provide codes and simple introduction of plotting and package: brms.

- [Medium: How linear mixed model works? And how to understand LMM through Bayesian lenses (by Nikolay Oskolkov)](https://towardsdatascience.com/how-linear-mixed-model-works-350950a82911)
    - Also contains a set of codes for bootstrapping (which works like R package: citools that boot the C.I. of predictions).

- lmer's issue: failed to converge due to negative eigenvalue.
    - See discussion in [this post](https://stats.stackexchange.com/questions/242109/model-failed-to-converge-warning-in-lmer) and [this post](https://stackoverflow.com/questions/70537291/lmer-model-failed-to-converge-with-1-negative-eigenvalue).

- [Stackexchange: What is the difference btw fixed effect, random effect and mixed effect models?](https://stats.stackexchange.com/questions/4700/what-is-the-difference-between-fixed-effect-random-effect-and-mixed-effect-mode)

- [McNeish, D., & Kelley, K. (2019). Fixed effects models versus mixed effects models for clustered data: Reviewing the approaches, disentangling the differences, and making recommendations. Psychological Methods, 24(1), 20–35.](https://doi.org/10.1037/met0000182)  
    - Known from listening [podcast: quantitude (S2E29: Multilevel models -- The often unnecessary green monster](https://quantitudepod.org/s2e29-multilevel-models-the-often-unnecessary-green-monster/)).

- Papers on how many group numbers should be used in the LMM?  
    - [Gomes (2022) PeerJ 10:e12794.](https://peerj.com/articles/12794/)  
    - [Oberpriller et al. (2022) Ecology and Evolution 12(7): e9062.](https://onlinelibrary.wiley.com/doi/10.1002/ece3.9062)  
        - See guides and power analysis of LM v.s. LMM.
    - [StackExchange: What is the minimum recommended number of groups for a random effects factor?](https://stats.stackexchange.com/questions/37647/what-is-the-minimum-recommended-number-of-groups-for-a-random-effects-factor)
        - See discussion inside that detailly quoted Gelman and Hill (2007) for the controversial views. 
    - [e-Book: Data Analysis in R by Steve Midway](https://bookdown.org/steve_midway/DAR/random-effects.html)
        - See the analogy / statements inside for the feeling about the minimum number of classes, and also the introduction of GLMM.

- Papers on the violation of assumptions.
    - [Schielzeth et al. (2020) Robustness of linear mixed-effects models to violations of distributional assumptions. Methods Ecol Evol. 11: 1141– 1152.](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.13434)
        - Feat. Shinichi Nakagawa.

- [R package: DHARMa](https://cran.r-project.org/web/packages/DHARMa/index.html)
    * Known from listening podcast: Learning Bayesian Statistics.
    * A package that help you evaluate your model.

- [R package: bootmlm](https://github.com/marklhc/bootmlm)
    * See [this paper](https://www.tandfonline.com/doi/full/10.1080/00273171.2020.1746902?scroll=top&needAccess=true&role=tab) for the use of this package.
    * Note: This package is still under development.

- [R package: merTools](https://cran.r-project.org/web/packages/merTools/index.html)

### Exploratory data analysis (EDA)
- [rbloggers' post: explore: simplified exploratory data analysis (EDA) in R](https://www.r-bloggers.com/2022/09/explore-simplified-exploratory-data-analysis-eda-in-r/?fbclid=IwAR1tSK6_FVwq39ghlDBSJ6SL1gsgQfJNY8VtMIMnodJjYxGguUSTilJFzqQ)

- [R package: DataExplorer](https://cran.r-project.org/web/packages/DataExplorer/)

### Multivariate statistical analysis
- [Factoextra R Package: Easy Multivariate Data Analyses and Elegant Visualization](http://www.sthda.com/english/wiki/factoextra-r-package-easy-multivariate-data-analyses-and-elegant-visualization)
    - Some tutorials:
        - [Stackoverflow: How to manually adjust the detail of points.](https://stackoverflow.com/questions/62119816/color-only-mean-group-of-pca)

- [PCA - Principal Component Analysis Essentials](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/112-pca-principal-component-analysis-essentials/)

- [Principal Component Analysis in R: prcomp vs princomp](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/118-principal-component-analysis-in-r-prcomp-vs-princomp/)

- [Cross Validated: Can principal component analysis be applied to datasets containing a mix of continuous and categorical variables?](https://stats.stackexchange.com/questions/5774/can-principal-component-analysis-be-applied-to-datasets-containing-a-mix-of-cont)
    - With recommended [R package: FactoMineR](https://cran.r-project.org/web/packages/FactoMineR/index.html).

### Time series analysis
- [Book: Applied time series analysis with R](https://smac-group.github.io/ts/index.html)

- [Book: Forecasting: Principles and Practice (3rd ed.)](https://otexts.com/fpp3/)
    - An example book of using "tidyverts" as the function of time series modelling.

- [Packages: tidyverts](https://tidyverts.org/)
    - A set of packages that work with tidyverse to perform time series analysis.
    - Examples:
        - [Blog post: Climate change: Modeling 140+ years of temperature data with tsibble and fable](https://rethinking.rbind.io/2019/01/21/140-years/)
        - [Blog post: Tidy time series data using tsibbles by Rob J Hyndman](https://robjhyndman.com/hyndsight/tsibbles/)

## Causal inference
### General topics
- **In general**
    - I used to think causal inference as a component of modern statistics, but decided to separate it as a different mathematical tool (at least for now). Part of "causal inference (SCM framework, *sensu stricto*)" use statistical language, and also contains other tools makes it have the ability to think real questions in a different view. I agree with them both, so I would like to treat them equally (2024, Jan. 08).

- [Blog post by Andrew Heiss: Ways to close backdoors in DAGs](https://www.andrewheiss.com/blog/2020/02/25/closing-backdoors-dags/)
    - Added on 2024, Feb. 05.
    - A workablle examples for closing backdoors in DAGs using linear model. Easy to read (took 25 mins for me, after I read 《The Book of Why》.)

- [Huntington-Klein, N. 2022. The Effect: An Introduction to Research Design and Causality, 1st edt. Chapman and Hall/CRC.](https://theeffectbook.net/index.html)
    - Added on 2024, Feb. 06.
    - 《The Effect Book》
    - This links to the web-version of the book.
    - Introduce statstics in a causal taste.
    - Notes:
        - See [Ch13](https://theeffectbook.net/ch-StatisticalAdjustment.html#polynomials) for the interpretation of effect size in polynomial regression (2024, Feb. 06).

- [Causal Inference in R](https://www.r-causal.org/)
    - Added on 2024, Feb. 06.
    - Notes:
        - See [Ch5](https://www.r-causal.org/chapters/05-dags) for examples about kinds of DAGs.

- [R CRAN Task View: Causal Inference](https://cran.r-project.org/web/views/CausalInference.html#rct)
    - Added on 2024, Feb. 08.
    - R packages list for causal inference.

- [Pearl, J. 2010. An introduction to causal inference. The International Journal of Biostatistics 6(2): 7.](https://www.degruyter.com/document/doi/10.2202/1557-4679.1203/html)
    - Added on 2024, Feb. 27.
    - An illustration aims to unify and synthesize different frameworks in the modern causal inference within the SCM framework.

- [Pearl, J. 2009. Causality: Models, reasoning, and inference; 2nd edition](https://bayes.cs.ucla.edu/BOOK-2K/)
    - Added on 2025, Jan. 05.
    - Notes:
        - A must written book in the future (2025, Jan. 05).
        - Also see the [Primer, which was published in 2016](https://bayes.cs.ucla.edu/PRIMER/).

### Popular science book
- [The Book of Why: The New Science of Cause and Effect](http://bayes.cs.ucla.edu/WHY/)
    - Added on 2024, Jan. 08.
    - Keywords: SCM, DAGs.
    - This is a popular science book written by Judea Pearl to introduce his work and the history of causal inference.
    - Chinese version is at [here](https://www.books.com.tw/products/0010825178) (中譯：因果革命：人工智慧的大未來).
    - Debates happens btw Andrew Gelman and Judea Pearl
        - See [this post on Medium](https://vishakh.medium.com/empiricism-and-scientific-change-in-judea-pearls-the-book-of-why-5e77c02a9d8b) for a good book review and a comment about the debate.

### Interaction and effect modification

- [Attia, J. et al. 2022. A proposal for capturing interaction and effect modification using DAGs. International Journal of Epidemiology 51: 1047–1053.](https://academic.oup.com/ije/article/51/4/1047/6607680)
    - Added on 2024, Jan. 16.
    - This paper discuss how to include a statistical "interaction term" in the DAG, and also other issues when doing these.
    - Also see these articles for references:
        - [Nilsson et al. 2021. Int J Epidemiol](https://academic.oup.com/ije/article/50/2/613/5998421?login=false)

### Mediation

- [eBook: A Guide on Data Analysis - Ch34 - Mediation](https://bookdown.org/mike/data_analysis/mediation.html)
    - Added on 2024, Feb. 08.
    - Also includes other topics on data analysis and causal inference.

- [VanderWeele, T. J. 2016. Mediation Analysis: A Practitioner's Guide. Annual Review of Public Health 37: 17–32.](https://www.annualreviews.org/doi/10.1146/annurev-publhealth-032315-021402)
    - Added on 2024, Feb. 08 (Not read yet).

- [Imai, K., Keele, L., Tingley, D., Yamamoto, T. 2011. Unpacking the Black Box of Causality: Learning about Causal Mechanisms from Experimental and Observational Studies. American Political Science Review 105(4):765-789.](https://www.cambridge.org/core/journals/american-political-science-review/article/unpacking-the-black-box-of-causality-learning-about-causal-mechanisms-from-experimental-and-observational-studies/9D2ACE9F784B99A30216D216FBF88553#article)
    - Added on 2024, Feb. 25.
    - Introduce the concept and the use of R package: mediation.

### Other modelling framework with DAGs

- [Arnold, K. F. et al. 2019. DAG-informed regression modelling, agent-based modelling and microsimulation modelling: a critical comparison of methods for causal inference. International Journal of Epidemiology 48: 243–253.](https://academic.oup.com/ije/article/48/1/243/5231935)
    - Added on 2024, Jan. 16 (Not read yet).

### Structured equation modelling

- **In general**
    - SEM has it's causal foundation ([Pearl, 2011](https://escholarship.org/uc/item/490131xj)), so that it's hard to decide where it should be placed in this repo (either in the **Causal inference** section or **Statistics**). I put it here to emphasize its potential to be explained causally.

- [RPubs's post: Intro to structural equation modeling by Chris Halsch & Danielle Salcido (Modified by Ari Grele)](https://rpubs.com/Agrele/SEM)
    - Added on 2024, Feb. 28
    - This is a very friendly post on performing your first SEM.
    - Also see these articles for references:
        - [Lefcheck JS (2016) piecewiseSEM. Methods in Ecology and Evolution](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12512)
            - Notes:
                - [The differences between SEM and CFA.](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.12512#:~:text=Because%20piecewise%20SEM%20does%20not%20yet%20incorporate%20latent%20or%20composite%20variables%2C%20it%20is%20often%20and%20more%20correctly%20referred%20to%20as%20confirmatory%20path%20analysis.)
        - [Bollen and Pearl (2013) Book chapter: Eight myths about causality and SEM.](https://link.springer.com/chapter/10.1007/978-94-007-6094-3_15#Sec3)
            - This one gives some historical view on the origin of SEM.

- [eBook: An introduction to structural equation modeling in R by Jonathan S. Lefcheck](https://jslefche.github.io/sem_book/)
    - Added on 2024, Feb. 28.
    - This is a keep-updating book written by the developer of R package: piecewiseSEM, which covers the toturial and working examples about the package.

- [Discussion: On the implementation of SEM in package: brms (one of the so called Bayesian-SEM)](https://github.com/paul-buerkner/brms/issues/303)
    - Added on 2024, Mar. 15.
    - Also see: 
        - [RPubs post: Bayesian SEM with BRMS by Jarrett Byrnes on 2017, Dec. 20](https://rpubs.com/jebyrnes/brms_bayes_sem)

## Evolutionary biology

- [Book: Modern phylogenetic comparative methods and their application in evolutionary biology](https://link.springer.com/book/10.1007/978-3-662-43550-2?page=2#toc)

- [Araya-Ajoy et al. (2015)](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12430)
    - An article on using GLMMs to estimate the relative contribution of different components to the phenotypic traits.

- [Book: Walsh & Lynch (2018) Evolution and selection of quantitative traits](https://academic.oup.com/book/40062)

- [Book: Grant & Grant (2014) 40 years of evolution Darwin's finches on Daphne Major Island](https://www.degruyter.com/document/doi/10.1515/9781400851300/html#contents)

## Species distribution models

## Other GIS related methods
* [QGIS](https://www.qgis.org/en/site/)
    * An oper-source GIS software with GUI.
* [Downloading and exploring raster data using R package: raster](https://emilypiche.github.io/BIO381/raster.html)
* [R package: maptiles](https://github.com/riatelab/maptiles)
    * This package downloads, composes and displays tiles from a large number of providers (e.g. OpenStreetMap, Stamen, Esri, CARTO, or Thunderforest).  
* [R-spatial](https://r-spatial.org/)
    * This project works on making R as a better and more convenient environment to do the spatiotemporal analysis. Several packages were developed, and also the news and blog post were released as guides.
* [R as GIS for Economists](https://tmieno2.github.io/R-as-GIS-for-Economists/)  
    * This online book gives a detail of many real world GIS analytic scenarios using R.  
    * e.g. [Extracting Values from Raster Layers for Vector Data](https://tmieno2.github.io/R-as-GIS-for-Economists/extracting-values-from-raster-layers-for-vector-data.html)
* [GDAL-Geotiff's introduction](https://gdal.org/drivers/raster/gtiff.html)
    * [The discussion about compression algorithm](https://gis.stackexchange.com/questions/1104/should-gdal-be-set-to-produce-geotiff-files-with-compression-which-algorithm-sh)  
* [R package: terra](https://cran.r-project.org/web/packages/terra/index.html)
    * The function: focal()
        * [This post](https://gis.stackexchange.com/questions/443159/r-focal-function-terra-vs-raster) discuss the use of focal() to perform the grid-wide calculation by a 2D moving window.
            * Still works on July 24, 2023.  
* [R package: rgee](https://r-spatial.github.io/rgee/)
    - Added on 2024, May 21.
        - Note:
            - "rgee is an R binding package for calling [Google Earth Engine](https://earthengine.google.com/) API from within R."
            - [rgee examples](https://csaybar.github.io/rgee-examples/)

## Theoretical ecology
- [Wikipedia: Eigenvalues and eienvectors](https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors)
- [Caswell (2001) Matrix Population Models](https://global.oup.com/academic/product/matrix-population-models-9780878931217?cc=tw&lang=en&)
- [Ellner, S. P. (2016) Data-driven Modelling of Structured Populations: A Practical Guide to the Integral Projection Model. Springer.](https://link.springer.com/book/10.1007/978-3-319-28893-2)
    - Added on 2024, Jan. 16.

- [eBook: lefko3 - Creating and analyzing matrix projection models in R](https://bookdown.org/cdorm/lefko3gentle/)
    - Added on 2024, Apr. 01.
    - Note:
        - Including IPM.
        - Including life table response experiments ([LTRE](https://bookdown.org/cdorm/lefko3gentle/ltre.html)).

- [Case (2000) An illustrated guide to theoretical ecology](https://global.oup.com/ushe/product/an-illustrated-guide-to-theoretical-ecology-9780195085129?cc=tw&lang=en&)
- [Dercole & Rinaldi (2008) Analysis of Evolutionary Processes: The Adaptive Dynamics Approach and Its Applications](https://press.princeton.edu/books/hardcover/9780691120065/analysis-of-evolutionary-processes)
    - Note: 
        - This framework is also introduced in Doebeli (2012) p. 227–242 in Svensson & Calsbeek (eds.) **The Adaptive landscape in evolutionary biology**.
- [Ohgushi et al. (eds.)(2012) Trait-Mediated Indirect Interactions
Ecological and Evolutionary Perspectives](https://www.cambridge.org/cn/academic/subjects/life-sciences/ecology-and-conservation/trait-mediated-indirect-interactions-ecological-and-evolutionary-perspectives?format=PB&isbn=9780521173131)
- [Otto & Day (2007) A biologist's guide to mathematical modeling in Ecology and Evolution](https://press.princeton.edu/books/hardcover/9780691123448/a-biologists-guide-to-mathematical-modeling-in-ecology-and-evolution)
- [Kooijman-SALM (2010) Dynamic energy budget theory for metabolic organisation, 3rd edition. Cambridge Press.](https://www.cambridge.org/core/books/dynamic-energy-budget-theory-for-metabolic-organisation/A50EC7C47CEAEE4100A24BE0DAD537DB)
    - Note:
        - There is an interesting analogy about DEB—[Nisbet et al. (2010)](https://royalsocietypublishing.org/doi/abs/10.1098/rstb.2010.0167): "... We conclude that a bioenergetic model serving solely as a ‘regression’ connecting organismal performance to the history of its environment can rest on simpler representations than those of standard DEB."  
- [Grimm, V. & Railsback, S. F. (2005) Individual-based modeling and ecology. Princeton University Press. 428 pp.](https://press.princeton.edu/books/paperback/9780691096667/individual-based-modeling-and-ecology)  

## Systematics

## Apps for collaboration
* [hackmd](https://hackmd.io/)
    * Online platform for markdown editing. Useful in taking notes.  
* Google workspace
* [Overleaf](https://www.overleaf.com/)
    * Online apps for Latex writing and collaboration.  
* Notion
* [Git](https://git-scm.com/)
    * Use with Github.
    * Ref: [Commit Often, Perfect Later, Publish Once: Git Best Practices](https://sethrobertson.github.io/GitBestPractices/#pubonce).
* [Github](https://github.com/)
* Google meet
    * [How long the meeting code is valid?](https://workspaceupdates.googleblog.com/2021/05/check-when-your-google-meet-meeting.html)  
    * [The introduction of "Quick access" function.](https://support.google.com/a/users/answer/9846862?hl=zh-Hant&co=GENIE.Platform%3DDesktop#zippy=%2C%E5%A6%82%E4%BD%95%E9%96%8B%E5%95%9F%E6%88%96%E9%97%9C%E9%96%89%E5%BF%AB%E9%80%9F%E5%AD%98%E5%8F%96%E5%8A%9F%E8%83%BD)  
    * [Tutorials for controling slides from multiple participants](https://graduatestu-evo.blogspot.com/2022/05/blog-post.html)
    * Note:
        * I suggest to create meet room in the Google calendar, because it gives us more ability to control the settings.
* Colab
    * [Stackoverflow: How to save R output in google colab?](https://stackoverflow.com/questions/64708511/saving-r-output-in-google-colab)
* [Rstudio workbench](https://www.rstudio.com/products/workbench/)

## References management
* [Zotero](https://www.zotero.org/)
    * [Zotero Keyboard Shortcuts](https://www.zotero.org/support/kb/keyboard_shortcuts) is the official document for the KB shortcuts.
        * Remember that:
            * 1. Select a item, and then hold on / click "Ctrl" would hightlight the folder which this item belongs to; double clicks the "Ctrl" would cancel the highlights.

## Resources for programming language  
* [The Epidemiologist R Handbook](https://epirhandbook.com/en/index.html)
* [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/)
    * One of the series of rmarkdown books written by the author, [Yihui Xie](https://yihui.org/).  
    * Systematic answers about rmarkdown issues would be found in these online-books.
* [blogdown: Creating Websites with R Markdown](https://bookdown.org/yihui/blogdown/)
    * One of the series of rmarkdown books written by the author.  
* [R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)
    * One of the series of rmarkdown books written by the author.  
* [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/)
    * One of the series of rmarkdown books written by the author.  
* [R package: rstatix](https://rpkgs.datanovia.com/rstatix/index.html)
    * This package contains many useful functions for statistical works in R; working fine with "pipe" operator.
        * See the links at the bottom and [this post](https://www.datanovia.com/en/blog/how-to-add-p-values-to-ggplot-facets/) for good references of adding statistical results on a ggplot-object.
            * e.g. the use of rstatix and [ggpubr](https://rpkgs.datanovia.com/ggpubr/) including manually adding p-values.  
* [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/index.html)  
* [Add CLD (letters for significance) to a ggplot-object](https://schmidtpaul.github.io/DSFAIR/compactletterdisplay.html)  
    * This website also gives many good examples for statistical practice and plotting.  
    * Also see these articles for references: [Lin et al. (2021)](https://datadryad.org/stash/dataset/doi:10.5061/dryad.q573n5tgj)  
* [Big Book of R](https://www.bigbookofr.com/index.html)  
    * A big collection of useful R-related concepts and resources. Just get into it and try to search anything you are interested in.
* [CRAN Task View: High-Performance and Parallel Computing with R](https://cran.r-project.org/web/views/HighPerformanceComputing.html)
* [R package: lubridate](https://lubridate.tidyverse.org/)
* [R package: ggsci](https://cran.r-project.org/web/packages/ggsci/)
* [StackExchange: Opening .nb in other software or exporting to other languages](https://mathematica.stackexchange.com/questions/28409/opening-nb-in-other-software-or-exporting-to-other-languages)
    * For software: Mathematica.
* [R package: tidymodels](https://www.tidymodels.org/)
    * Including [package: rsample](https://rsample.tidymodels.org/index.html), which could be use for bootstrapping.
* [R package: ggdist](https://mjskay.github.io/ggdist/)
    * Plotting uncertainty for frequentist models.
* [R package: ggridges](https://cran.r-project.org/web/packages/ggridges/)
    * Suggested by GCHsu on 20230713.
    * Plotting the distribution of data through multiple dimensions (e.g. space and time.)
* [R package: ciTools](https://cran.r-project.org/web/packages/ciTools/index.html)
    * Function to add C.I. in the data range.
* [R package: tryCatchLog](https://cran.r-project.org/web/packages/tryCatchLog/index.html)
    * A better package for handling try-Catch mechanisms in R.
        * This package support using [R package: futile.logger](https://cran.r-project.org/web/packages/futile.logger/index.html) to perform logging utility.
* [R package: Webshot](https://cran.r-project.org/web/packages/webshot/index.html)
    * See the URL tag inside for the better introduction.
* [Book: Gillespie C. 2021. Efficient R programming (e-book)](https://csgillespie.github.io/efficientR/)
    * Although not haven't read yet, the title seems good and interesting! (2023, September 05)

* [Code Folding and Sections in the RStudio IDE by Posit Support](https://support.posit.co/hc/en-us/articles/200484568-Code-Folding-and-Sections-in-the-RStudio-IDE)
    * Useful when you want to navigate through your Rscripts / codes.

## Information visualization
* [NVSCheatSheet of graphic principles](https://github.com/GraphicsPrinciples/CheatSheet/blob/master/NVSCheatSheet.pdf?fbclid=IwAR0a74lWpqKZ-l1T6n1UQK-3Nyo0OuED0UUAxUW4dtiBtjbmIlRFxqwsLMQ)
* [BBC Visual and Data Journalism cookbook for R graphics](https://bbc.github.io/rcookbook/)
    * [Corresponding R package: bbplot](https://github.com/bbc/bbplot)
* [R package: wesanderson](https://github.com/karthik/wesanderson)
* [Plotly Chart Studio](https://chart-studio.plotly.com/create/?fbclid=IwAR0GkNrRZR_ClX9j5FweGapWV3lcxxrUlyIMnIvyAXGIKNlpaHUMCfsb7-M#/)
    * An online platform for quickly accessing plotly library. It's useful when you want to take a glance about your data, but couldn't access R at that time.
* Good figures for illustration!
    * [Annual average temperature map.png by Robert A. Rohde (Berkeley Earth) on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Annual_Average_Temperature_Map.png)  
        * With land data only.  
    * [Annual average temperature map.jpg by Robert A. Rohde (Berkeley Earth) on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Annual_Average_Temperature_Map.jpg)  
        * Including ocean data.
    * [Global digital elevation model.jpg by NASA on Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Global_Digital_Elevation_Model.jpg)

## Writing
- [The Chicago Manual of Style Online](https://www.chicagomanualofstyle.org/home.html)

## Insect-plant interaction related issue
* [LTER protocols](https://lter.kbs.msu.edu/protocols)
    * Protocols for the setting of LTER.
    * Useful references for measuring plant's traits and soil's properties.
* [PhenoCam](https://phenocam.nau.edu/webcam/)
    * Phenology monitoring network based on webcams.

## Open databases/datasets
- [2022 iThome 鐵人賽：細數台灣公民該知道的 25 個開放資料庫](https://ithelp.ithome.com.tw/users/20103852/ironman/5889)
- [中華民國內政部營建署城鄉發展分署：全國土地使用分區資料查詢系統](https://luz.tcd.gov.tw/web/)
    - Although I didn't find the way to export the layers, the platform actually perform convenient searching functions for the user. E.g. Searching the area of a certain school is quite easy in this platform.
- [中華民國內政部國土測繪中心：國土利用現況調查成果資訊專區](https://www.nlsc.gov.tw/cl.aspx?n=13705)

## Audio signal processing 
- [CLT: ffmpeg](https://ffmpeg.org/)
    - The indroduction on the site: A complete, cross-platform solution to record, convert and stream audio and video.
    - Open-sourced.
    - See these posts for the usage guide
        - [Download and Combine Media Segments of a HLS Stream Locally Using FFMpeg](https://www.codementor.io/@chuksdurugo/download-and-combine-media-segments-of-a-hls-stream-locally-using-ffmpeg-150zo6t775)
        - [Stack overflow: saving frames from webcam stream](https://stackoverflow.com/questions/53980367/saving-frames-from-webcam-stream)
        - [StackExchange: How to download portion of video with youtube-dl command?](https://unix.stackexchange.com/questions/230481/how-to-download-portion-of-video-with-youtube-dl-command)

## Image processing
- [eBook: Vincent Mazet, “Basics of image processing” University of Strasbourg, 2020-2023.](https://vincmazet.github.io/bip/index.html)
    - Theories about image processing with computer.

- Technical guides about table extraction in pdf files
    - [Medium: A table detection, cell recognition and text extraction algorithm to convert tables in images to excel files](https://towardsdatascience.com/a-table-detection-cell-recognition-and-text-extraction-algorithm-to-convert-tables-to-excel-files-902edcf289ec)

:::info
**Find this document incomplete or need to update?** Let me know your suggestions!
:::