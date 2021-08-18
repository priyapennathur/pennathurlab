---
date: 2019-05-23
slug: 2019-singer-simphony
image: 2019-singer-simphony.png
title: "Simphony: simulating large-scale, rhythmic data"
authors: Jordan M. Singer, Darwin Y. Fu, and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/497859
short_ref: Singer et al., PeerJ 2019
peer_reviewed: true
journal: PeerJ
year: 2019
doi: 10.7717/peerj.6985
pdf: 2019-singer-simphony.pdf
supp: 2019-singer-simphony-supp.zip
pmid: 31198637
reviews: https://peerj.com/articles/6985/reviews/
results: https://doi.org/10.6084/m9.figshare.7441355
software: /software/simphony/
member_ids: [singerjm, fudy, hugheyjj]
software_ids: [simphony]
---

# Abstract

Simulated data are invaluable for assessing a computational method’s ability to distinguish signal from noise. Although many biological systems show rhythmicity, there is no general-purpose tool to simulate large-scale, rhythmic data. Here we present Simphony, an R package for simulating data from experiments in which the abundances of rhythmic and non-rhythmic features (e.g., genes) are measured at multiple time points in multiple conditions. Simphony has parameters for specifying experimental design and each feature's rhythmic properties (e.g., amplitude and phase). In addition, Simphony can sample measurements from Gaussian and negative binomial distributions, the latter of which approximates read counts from RNA-seq data. We show an example of using Simphony to evaluate the accuracy of rhythm detection. Our results suggest that Simphony will aid experimental design and computational method development. Simphony is thoroughly documented and freely available at [https://github.com/hugheylab/simphony](https://github.com/hugheylab/simphony).
