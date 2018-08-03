---
date: 2018-07-31
slug: 2018-hu-metacyto
image: 2018-hu-metacyto.jpg
title: "MetaCyto: A Tool for Automated Meta-analysis of Mass and Flow Cytometry Data"
authors: Zicheng Hu, Chethan Jujjavarapu, Jacob J. Hughey, Sandra Andorf, Hao-Chih Lee, Pier Federico Gherardini, Matthew H. Spitzer, Cristel G. Thomas, John Campbell, Patrick Dunn, Jeff Wiser, Brian A. Kidd, Joel T. Dudley, Garry P. Nolan, Sanchita Bhattacharya, and Atul J. Butte
preprint_journal: bioRxiv
preprint_doi: 10.1101/130948
short_ref: Hu et al., Cell Rep 2018
peer_reviewed: true
journal: Cell Reports
year: 2018
doi: 10.1016/j.celrep.2018.07.003
pdf: 2018-hu-metacyto.pdf
supp: 2018-hu-metacyto-supp.pdf
pmid: 30067990
results: https://github.com/hzc363/MetaCyto_Paper_Code
software: https://doi.org/doi:10.18129/B9.bioc.MetaCyto
member_ids: hugheyjj
software_ids: 
---

# Abstract

While meta-analysis has demonstrated increased statistical power and more robust estimations in studies, the application of this commonly accepted methodology to cytometry data has been challenging. Different cytometry studies often involve diverse sets of markers. Moreover, the detected values of the same marker are inconsistent between studies due to different experimental designs and cytometer configurations. As a result, the cell subsets identified by existing auto-gating methods cannot be directly compared across studies. We developed MetaCyto for automated meta-analysis of both flow and mass cytometry (CyTOF) data. By combining clustering methods with a silhouette scanning method, MetaCyto is able to identify commonly labeled cell subsets across studies, thus enabling meta-analysis. Applying MetaCyto across a set of ten heterogeneous cytometry studies totaling 2,926 samples enabled us to identify multiple cell populations exhibiting differences in abundance between demographic groups. Software is released to the public through Bioconductor (http://bioconductor.org/packages/release/bioc/html/MetaCyto.html).
