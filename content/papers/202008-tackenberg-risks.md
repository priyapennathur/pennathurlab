---
date: 2020-08-15
slug: 2020-tackenberg-risks
image: 2020-tackenberg-risks.png
title: "The risks of using the chi-square periodogram to estimate the period of biological rhythms"
authors: Michael C. Tackenberg and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/2020.08.14.251512
short_ref: Tackenberg and Hughey, bioRxiv
peer_reviewed: false
journal:
year:
doi:
pdf:
supp:
pmid:
reviews:
results: https://doi.org/10.6084/m9.figshare.12805082
software: /software/spectr
member_ids: [tackenbergmc, hugheyjj]
software_ids: [simphony, spectr]
---

# Abstract

The chi-square periodogram (CSP), developed over 40 years ago, continues to be one of the most popular methods to estimate the period of circadian (circa 24-h) rhythms. Previous work has indicated the CSP is sometimes less accurate than other methods, but understanding of why and under what conditions remains incomplete. Using simulated rhythmic time-courses, we found that the CSP is prone to underestimating the period in a manner that depends on the true period and the length of the time-course. This underestimation bias is most severe in short time-courses (e.g., 3 days), but is also visible in longer simulated time-courses (e.g., 12 days) and in experimental time-courses of mouse wheel-running. The bias is caused by discontinuities in the periodogram that are related to the number of time-points the CSP uses to calculate the observed variance for a given test period. By revising the calculation to avoid discontinuities, we developed a new version, the greedy CSP, that shows reduced bias and improved accuracy. Nonetheless, even the greedy CSP tended to be less accurate on our simulated time-courses than an alternative method, namely the Lomb-Scargle periodogram. Thus, although our study describes a major improvement to a classic method, it also suggests that users should generally avoid the CSP when estimating the period of biological rhythms.
