---
date: 2020-09-07
slug: 2020-schoenbachler-pmparser
image: 2020-schoenbachler-pmparser.png
title: "pmparser and PMDB: resources for large-scale, open studies of the biomedical literature"
authors: Joshua L. Schoenbachler and Jacob J. Hughey
preprint_journal: bioRxiv
preprint_doi: 10.1101/2020.09.07.285924
short_ref: Schoenbachler and Hughey, bioRxiv
peer_reviewed: false
journal:
year:
doi:
pdf:
supp:
pmid:
reviews:
results: https://doi.org/10.5281/zenodo.4004909
software: /software/pmparser
member_ids: [schoenbachlerjl, hugheyjj]
software_ids: [pmparser]
---

# Abstract

PubMed is an invaluable resource for the biomedical community. Although PubMed is freely available, the existing API is not designed for large-scale analyses and the XML structure of the underlying data is inconvenient for complex queries. We developed an R package called pmparser to convert the data in PubMed to a relational database. Our implementation of the database, called PMDB, currently contains data on over 31 million PubMed Identifiers (PMIDs) and is updated regularly. Together, pmparser and PMDB can enable large-scale, reproducible, and transparent analyses of the biomedical literature. pmparser is licensed under GPL-2 and available at https://pmparser.hugheylab.org. PMDB is stored in PostgreSQL and compressed dumps are available on Zenodo ([https://doi.org/10.5281/zenodo.4008109](https://doi.org/10.5281/zenodo.4008109)).
