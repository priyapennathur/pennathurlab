---
date: 2012-01-01
slug: simple-image
title: Simple image thresholding
software_id: simpleimage
description: Simple method to calculate the threshold for segmenting an image
source: https://www.mathworks.com/matlabcentral/fileexchange/44291-simple-image-thresholding
---

This method first estimates a cutoff, then calculates the distribution of pixels within the cutoff in order to determine the final threshold. I have found this method to work well for fluorescence microscopy images in which most of the pixels are background and the background is approximately gaussian.
