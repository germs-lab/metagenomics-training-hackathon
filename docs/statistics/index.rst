===================================================
Statistics and visualization - Comparative Analyses
===================================================

* Metadata integration
* Sample comparison
* Ecological measurements/indexes
* Multivariate and comparative statistics
* Machine Learning

Links to resources that cover several for the above topics
----------------------------------------------------------
* `STAMP <https://www.dropbox.com/s/e8e6p62k92s1fo9/>`_
* `Dutilh <http://www.nbic.nl/uploads/media/Day3_Dutilh_Comparative_metagenomics_2013.pdf>`_
* `Luis Pedro <http://mybinder.org/repo/luispedro/StructureFunctionOceanTutorial>`_
* `Stuart Jones EDAMAME <https://github.com/edamame-course/2015-tutorials/blob/master/final/2015-06-27-Jones_R.md>`_
* `BPA CSIRO <https://github.com/BPA-CSIRO-Workshops/metagenomics-module-vis/blob/master/handout/vis.tex>`_

Learning objectives
-------------------

Normalization / appropriate comparisons
---------------------------------------
* basic: applying DeSEQ for normalization
* more advanced: raise awareness and discuss the possible limitations of DeSEQ and rarefaction for metagenomics analysis

Ecological measurements/indexes
-------------------------------
Alpha diversity (Chao, Simpson, etc. )
* basic: knowing that alpha diversity refers to diversity of a single sample. Understanding what the inputs are, that it can be computed/reasoned at different taxonomic levels (species, genus, …). Ability use some software package to compute. 
* More advanced: Interpreting the values, knowing which measures are more robust to low abundance taxa, different sampling depths, &c. Understanding the effects of “dark matter” when using reference based methods (ie, microbes that do not match the reference being employed would not be counted towards diversity). 
* Advanced: knowing the formulas and understanding the underlying ecological/mathematical assumptions.

beta diversity (bray curtis distances, Unifrac etc,)
* Basic: knowing that beta diversity refers to diversity across samples (differing definitions in the field). SImilar to alpha diversity, can be computed at different taxonomic (or functional) levels. Ability to use a software package. 
* Intermediate: Understanding the effects of different normalization procedures.

Multivariate statistics (Differential expression, comparison)
-------------------------------------------------------------
* general statistics knowledge, unspecific to metagenomics (p-values, multiple comparison correction, difference between statistical significance and effect size, training/testing split in machine learning). 
* Knowing how auto-correlation can lead to spurious correlations (ecological studies). 
* More advanced: knowing which methods attempt to correct for auto-correlation and how to apply them in software.

Machine Learning
----------------

*Basic: knowing that an ordination plot represents distance between samples in a low dimensional space. Knowing that the output represents the input distance matrix (i.e., different input matrices would lead to different results: see discussion on beta diversity). Being able to generate a plot in software. 
*Intermediate: knowing what the “fraction of explained variance” represents. Advanced: understanding the difference between the different methods.


