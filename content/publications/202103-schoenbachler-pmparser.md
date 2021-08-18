---
date: 2021-03-11
slug: 2021-schoenbachler-pmparser
image: 2021-schoenbachler-pmparser.png
title: "pmparser and PMDB: resources for large-scale, open studies of the biomedical literature"
authors: Joshua L. Schoenbachler and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/2020.09.07.285924
short_ref: Schoenbachler and Hughey, PeerJ 2021
peer_reviewed: true
journal: PeerJ
year: 2021
doi: 10.7717/peerj.11071
pdf: 2021-schoenbachler-pmparser.pdf
supp: 2021-schoenbachler-pmparser-supp.zip
pmid: 33763309
reviews: https://peerj.com/articles/11071/reviews/
results: https://doi.org/10.5281/zenodo.4004909
software: /software/pmparser
member_ids: [schoenbachlerjl, hugheyjj]
software_ids: [pmparser]
---

# Abstract

PubMed is an invaluable resource for the biomedical community. Although PubMed is freely available, the existing API is not designed for large-scale analyses and the XML structure of the underlying data is inconvenient for complex queries. We developed an R package called pmparser to convert the data in PubMed to a relational database. Our implementation of the database, called PMDB, currently contains data on over 31 million PubMed Identifiers (PMIDs) and is updated regularly. Together, pmparser and PMDB can enable large-scale, reproducible, and transparent analyses of the biomedical literature. pmparser is licensed under GPL-2 and available at https://pmparser.hugheylab.org. PMDB is available in both PostgreSQL (https://doi.org/10.5281/zenodo.4008109) and Google BigQuery (https://console.cloud.google.com/bigquery?project=pmdb-bq&d=pmdb).
