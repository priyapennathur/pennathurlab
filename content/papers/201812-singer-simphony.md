---
date: 2018-12-17
slug: singer-simphony
image: 2018-singer-simphony.png
title: "Simphony: simulating large-scale, rhythmic data"
authors: Jordan M. Singer, Darwin Y. Fu, and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/497859
short_ref: Singer et al., bioRxiv
peer_reviewed: false
journal: 
year: 
doi: 
pdf: 
supp: 
pmid: 
reviews: 
results: https://figshare.com/s/549da44928b243df47d5
software: /software/simphony/
member_ids: [singerjm, fudy, hugheyjj]
software_ids: [simphony]
---

# Abstract

Simulated data are invaluable for assessing a computational method’s ability to distinguish signal from noise. Although many biological systems show rhythmicity, there is no general-purpose tool to simulate large-scale, rhythmic data. Here we present Simphony, an R package for simulating data from experiments in which the abundances of rhythmic and non-rhythmic features (e.g., genes) are measured at multiple time points in multiple conditions. Simphony has parameters for specifying experimental design and each feature's rhythmic properties (e.g., shape, amplitude, and phase). In addition, Simphony can sample measurements from Gaussian and negative binomial distributions, the latter of which approximates read counts from next-generation sequencing data. We show an example of using Simphony to benchmark a method for detecting rhythms. Our results suggest that Simphony can aid experimental design and computational method development. Simphony is thoroughly documented and freely available at https://github.com/hugheylab/simphony.
