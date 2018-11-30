---
date: 2018-11-25
slug: singer-limorhyde
image: 2018-singer-limorhyde.png
title: "LimoRhyde: a flexible approach for differential analysis of rhythmic transcriptome data"
authors: Jordan M. Singer and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/283622
short_ref: Singer and Hughey, J Biol Rhythms 2018
peer_reviewed: true
journal: Journal of Biological Rhythms
year: 2018
doi: 10.1177/0748730418813785
pdf: 2018-singer-limorhyde.pdf
supp: 2018-singer-limorhyde-supp.zip
pmid: 30472909
reviews: 2018-singer-limorhyde-reviews.pdf
results: https://doi.org/10.6084/m9.figshare.5945569
software: /software/limorhyde/
member_ids: [hugheyjj, singerjm]
software_ids: [metapredict, zeitzeiger, limorhyde]
---

# Abstract

Unraveling the effects of genetic or environmental perturbations on biological rhythms requires detecting changes in rhythmicity across multiple conditions. Although methods to detect rhythmicity in genome-scale data are well established, methods to detect changes in rhythmicity or changes in average expression between experimental conditions are often ad hoc and statistically unreliable. Here we present LimoRhyde (linear models for rhythmicity, design), a flexible approach for analyzing transcriptome data from circadian systems. Borrowing from cosinor regression, LimoRhyde decomposes circadian or zeitgeber time into multiple components to fit a linear model to the expression of each gene. The linear model can accommodate any number of additional experimental variables, whether discrete or continuous, making it straightforward to detect differential rhythmicity and differential expression using state-of-the-art methods for analyzing microarray and RNA-seq data. In this approach, differential rhythmicity corresponds to a statistical interaction between an experimental variable and circadian time, whereas differential expression corresponds to the main effect of an experimental variable while accounting for circadian time. To validate LimoRhyde’s performance, we applied it to simulated data. To demonstrate LimoRhyde’s versatility, we applied it to murine and human circadian transcriptome datasets acquired under various experimental designs. Our results show how LimoRhyde systematizes the analysis of such data, and suggest that LimoRhyde could prove valuable for assessing how circadian systems respond to perturbations.
