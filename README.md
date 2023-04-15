# ASC-noisy

[![DOI](http://img.shields.io/badge/doi-10.1016/j.patrec.2019.08.020-36648B.svg)](https://doi.org/10.1016/j.patrec.2019.08.020)
[![Paper](http://img.shields.io/badge/arXiv-2302.11298-b31b1b.svg)](https://arxiv.org/abs/2302.11298)
[![Papers with Code](http://img.shields.io/badge/PaperswithCode-2302.11298-21cbce.svg)](https://paperswithcode.com/paper/approximate-spectral-clustering-density-based)

## 	Approximate spectral clustering density-based similarity for noisy datasets
This is an implementation for the following paper:
```bibtex
@article{ALSHAMMARI2019155,
	title = {Approximate spectral clustering density-based similarity for noisy datasets},
	journal = {Pattern Recognition Letters},
	volume = {128},
	pages = {155-161},
	year = {2019},
	doi = {https://doi.org/10.1016/j.patrec.2019.08.020},
	author = {Mashaan Alshammari and Masahiro Takatsuka}
}
```

## How to use:

Run BATCH_Points.m which will execute the following:
1.	PRE_Points.m to load toy data, csv files are the groundtruth labels.
2.	RUN_Points.m to perform spectral clustering with CONN filtering.
3.	POST_Points.m to compute the accuracy of clustering

---
Provided by Mashaan Alshammari<br/>
mashaan14 at gmail dot com<br/>
mashaan dot awad at outlook dot com<br/>
September 23, 2019.
