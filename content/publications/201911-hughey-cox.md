---
date: 2019-11-04
slug: 2019-hughey-cox
image: 2019-hughey-cox.png
title: "Cox regression increases power to detect genotype-phenotype associations in genomic studies using the electronic health record"
authors: Jacob J. Hughey, Seth D. Rhoades, Darwin Y. Fu, Lisa Bastarache, Joshua C. Denny, and Qingxia Chen
preprint_journal: bioRxiv
preprint_doi: 10.1101/599910
short_ref: Hughey et al., BMC Genomics 2019
peer_reviewed: true
journal: BMC Genomics
year: 2019
doi: 10.1186/s12864-019-6192-1
pdf: 2019-hughey-cox.pdf
supp: 2019-hughey-cox-supp.zip
pmid: 31684865
reviews: 2019-hughey-cox-reviews.pdf
results: https://doi.org/10.6084/m9.figshare.7881146
software: 
member_ids: [hugheyjj, rhoadessd, fudy]
software_ids: 
---

# Abstract

**Background:** The growth of DNA biobanks linked to data from electronic health records (EHRs) has enabled the discovery of numerous associations between genomic variants and clinical phenotypes. Nonetheless, although clinical data are generally longitudinal, standard approaches for detecting genotype-phenotype associations in such linked data, notably logistic regression,do not naturally account for variation in the period of follow-up or the time at which an event occurs. Here we explored the advantages of quantifying associations using Cox proportional hazards regression, which can account for the age at which a patient first visited the healthcare system (left truncation) and the age at which a patient either last visited the healthcare system or acquired a particular phenotype (right censoring).

**Results:** In comprehensive simulations, we found that, compared to logistic regression, Cox regression had greater power at equivalent Type I error. We then scanned for genotype-phenotype associations using logistic regression and Cox regression on 50 phenotypes derived from the EHRs of 49,792 genotyped individuals. Consistent with the findings from our simulations, Cox regression had approximately 10% greater relative sensitivity for detecting known associations from the NHGRI-EBI GWAS Catalog. In terms of effect sizes, the hazard ratios estimated by Cox regression were strongly correlated with the odds ratios estimated by logistic regression.

**Conclusions:** As longitudinal health-related data continue to grow, Cox regression may improve our ability to identify the genetic basis for a wide range of human phenotypes.
