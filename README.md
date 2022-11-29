[![hackmd-github-sync-badge](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg/badge)](https://hackmd.io/9tRVhSS2Q0-LSup9z3AZXg)  

Eco-Evo-Toolbox
===
###### tags: `Tutorials` `Ph.D project` `Evolution`

This repository serves a tentatively mission to note useful literatures/Apps/resources using in my researches about Ecology and Evolutionary Biology.  

## Statistics

### General topics
- [R package: performance](https://easystats.github.io/performance/index.html)  
    - A component of easystats-verse.
    - A all-in-one package that could help evaluate your model.

### Bayesian statistics
- [Podcast: Learning Bayesian Statistics](https://learnbayesstats.com/)
    - A podcast show that I frequently listen to during my jogging.  
    - I also benefit from it in learning English speaking and listening.  

- [Think Bayes 2nd edition](https://greenteapress.com/wp/think-bayes/)
    - I met this book while jogging and at the same time listening the podcast-Learning Bayesian Statistics. This book is a great self-study resource for people who want to learn bayesian statistics.  

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
    - Related refs: [Qian et al. (2010)](https://esajournals.onlinelibrary.wiley.com/doi/full/10.1890/09-1043.1)、[plotting tips from this blog post from Lionel R. Hertzog](https://biologyforfun.wordpress.com/2017/06/19/adding-group-level-predictors-in-glmm-using-lme4/?fbclid=IwAR1ej3wJfKMIFJk6PTfgFoRG2XD9XxCRxFdQ3bo-8OVFGvVfxqmALTmDwGc). 

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

### Exploratory data analysis (EDA)
- [rbloggers' post: explore: simplified exploratory data analysis (EDA) in R](https://www.r-bloggers.com/2022/09/explore-simplified-exploratory-data-analysis-eda-in-r/?fbclid=IwAR1tSK6_FVwq39ghlDBSJ6SL1gsgQfJNY8VtMIMnodJjYxGguUSTilJFzqQ)

### Multivariate statistical analysis
- [Factoextra R Package: Easy Multivariate Data Analyses and Elegant Visualization](http://www.sthda.com/english/wiki/factoextra-r-package-easy-multivariate-data-analyses-and-elegant-visualization)
    - Some tutorials:
        - [Stackoverflow: How to manually adjust the detail of points.](https://stackoverflow.com/questions/62119816/color-only-mean-group-of-pca)

- [PCA - Principal Component Analysis Essentials](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/112-pca-principal-component-analysis-essentials/)

- [Principal Component Analysis in R: prcomp vs princomp](http://www.sthda.com/english/articles/31-principal-component-methods-in-r-practical-guide/118-principal-component-analysis-in-r-prcomp-vs-princomp/)

### Time series analysis
- [Book: Applied time series analysis with R](https://smac-group.github.io/ts/index.html)

- [Book: Forecasting: Principles and Practice (3rd ed.)](https://otexts.com/fpp3/)
    - An example book of using "tidyverts" as the function of time series modelling.

- [Packages: tidyverts](https://tidyverts.org/)
    - A set of packages that work with tidyverse to perform time series analysis.

## Evolutionary biology

- [Book: Modern phylogenetic comparative methods and their application in evolutionary biology](https://link.springer.com/book/10.1007/978-3-662-43550-2?page=2#toc)

- [Araya-Ajoy et al. (2015)](https://besjournals.onlinelibrary.wiley.com/doi/full/10.1111/2041-210X.12430)
    - An article on using GLMMs to estimate the relative contribution of different components to the phenotypic traits.

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

## Theoretical ecology
- [Wikipedia: Eigenvalues and eienvectors](https://en.wikipedia.org/wiki/Eigenvalues_and_eigenvectors)

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

## Information visualization
* [NVSCheatSheet of graphic principles](https://github.com/GraphicsPrinciples/CheatSheet/blob/master/NVSCheatSheet.pdf?fbclid=IwAR0a74lWpqKZ-l1T6n1UQK-3Nyo0OuED0UUAxUW4dtiBtjbmIlRFxqwsLMQ)

## Insect-plant interaction related issue
* [LTER protocols](https://lter.kbs.msu.edu/protocols)
    * Protocols for the setting of LTER.
    * Useful references for measuring plant's traits and soil's properties.

