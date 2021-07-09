---
date: 2020-10-09
slug: dropkick
title: dropkick
software_id: dropkick
description: Automated cell filtering for single-cell RNA sequencing data
site: https://pypi.org/project/dropkick
source: https://github.com/KenLauLab/dropkick
docker: 
---

dropkick is a fully automated software tool for quality control and filtering of single-cell RNA sequencing (scRNA-seq) data, with a focus on excluding ambient barcodes and recovering real cells bordering the quality threshold. dropkick sets initial thresholds based on predictive global heuristics, then learns a gene-based representation of real cells and ambient barcodes, calculating a cell probability score for each barcode on a per-dataset basis. dropkick was developed primarily in [Ken Lau's lab](https://www.mc.vanderbilt.edu/vumcdept/cellbio/laulab/people.html).
