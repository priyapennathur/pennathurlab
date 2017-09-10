---
date: 2017-02-01
slug: 2017-hughey-machine
image: 201701-hughey-machine.png
title: "Machine learning identifies a compact gene set for monitoring the circadian clock in human blood"
authors: Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/066126
short_ref: Hughey, Genome Med 2017
journal: Genome Medicine
year: 2017
doi: 10.1186/s13073-017-0406-4
pdf: 2017-hughey-machine.pdf
supp: 2017-hughey-machine-supp.pdf
pmid: 28241858
reviews: 2017-hughey-machine-reviews.pdf
results: https://dx.doi.org/10.6084/m9.figshare.3756375.v1
member_ids: hugheyjj
software_ids: [metapredict, zeitzeiger]
---

# Abstract

The circadian clock and the daily rhythms it produces are crucial for human health, but are often disrupted by the modern environment. At the same time, circadian rhythms may influence the efficacy and toxicity of therapeutics and the metabolic response to food intake. Developing treatments for circadian dysfunction, as well as optimizing the daily timing of treatments for other health conditions, will require a simple and accurate method to monitor the molecular state of the circadian clock. Here we used a recently developed method called ZeitZeiger to predict circadian time (CT, time of day according to the circadian clock) from genome-wide gene expression in human blood. In cross-validation on 498 samples from 60 individuals across three publicly available datasets, ZeitZeiger predicted CT in single samples with a median absolute error of 2.1 h. The predictor trained on all 498 samples used 15 genes, only two of which are part of the core circadian clock. By then applying ZeitZeiger to 475 additional samples from the same three datasets, we quantified how the circadian clock in the blood was affected by various perturbations to the sleep–wake and light–dark cycles. Finally, we extended ZeitZeiger (1) to handle intra-individual variation by making predictions based on multiple samples taken a known time apart, and (2) to handle inter-individual variation by personalizing predictions based on samples from the respective individual. Each of these strategies improved prediction of CT by ~20%. Our results are an important step towards precision circadian medicine. In addition, our generalizable extensions to ZeitZeiger may be applicable to the growing number of biological datasets that contain multiple observations per individual.
