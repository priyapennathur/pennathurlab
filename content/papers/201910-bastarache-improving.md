---
date: 2019-10-14
slug: 2019-bastarache-improving
image: 2019-bastarache-improving.png
title: "Improving the phenotype risk score as a scalable approach to identifying patients with Mendelian disease"
authors: Lisa Bastarache, Jacob J. Hughey, Jeffrey A. Goldstein, Julie A. Bastarache, Satya Das, Neil Charles Zaki, Chenjie Zeng, Leigh Anne Tang, Dan M. Roden, and Joshua C. Denny
preprint_journal: 
preprint_doi: 
short_ref: Bastarache et al., J Am Med Inform Assoc 2019
peer_reviewed: true
journal: Journal of the American Medical Informatics Association
year: 2019
doi: 10.1093/jamia/ocz179
pdf: 2019-bastarache-improving.pdf
supp: 2019-bastarache-improving-supp.zip
pmid: 31609419
reviews: 
results: 
software: 
member_ids: hugheyjj
software_ids: 
---

# Abstract

**Objective:** The Phenotype Risk Score (PheRS) is a method to detect Mendelian disease patterns using phenotypes from the electronic health record (EHR). We compared the performance of different approaches mapping
EHR phenotypes to Mendelian disease features.

**Materials and Methods:** PheRS utilizes Mendelian diseases descriptions annotated with Human Phenotype Ontology (HPO) terms. In previous work, we presented a map linking phecodes (based on International Classification of
Diseases [ICD]-Ninth Revision) to HPO terms. For this study, we integrated ICD-Tenth Revision codes and lab data.
We also created a new map between HPO terms using customized groupings of ICD codes. We compared the performance with cases and controls for 16 Mendelian diseases using 2.5 million de-identified medical records.

**Results:** PheRS effectively distinguished cases from controls for all 15 positive controls and all approaches
tested (P < 4⋅10<sup>-16</sup>). Adding lab data led to a statistically significant improvement for 4 of 14 diseases. The custom ICD groupings improved specificity, leading to an average 8% increase for precision at 100 (-2% to 22%).
Eight of 10 adults with cystic fibrosis tested had PheRS in the 95th percentile prior to diagnosis.

**Discussion:** Both phecodes and custom ICD groupings were able to detect differences between affected cases
and controls at the population level. The ICD map showed better precision for the highest scoring individuals.
Adding lab data improved performance at detecting population-level differences.

**Conclusions:** PheRS is a scalable method to study Mendelian disease at the population level using electronic
health record data and can potentially be used to find patients with undiagnosed Mendelian disease.
