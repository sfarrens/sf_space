---
title: Space variant deconvolution of galaxy survey images
category: pub
image: deconv.png
year: 2017
journal: A&A
authors: S. Farrens, J.-L.Starck, F. Ngolè Mboula
pdf: https://www.aanda.org/articles/aa/pdf/2017/05/aa29709-16.pdf
---
Removing the aberrations introduced by the Point Spread Function (PSF) is a fundamental aspect of astronomical image processing. The presence of noise in observed images makes deconvolution a nontrivial task that necessitates the use of regularisation. This task is particularly difficult when the PSF varies spatially as is the case for the Euclid telescope. New surveys will provide images containing thousand of galaxies and the deconvolution regularisation problem can be considered from a completely new perspective. In fact, one can assume that galaxies belong to a low-rank dimensional space. This work introduces the use of the low-rank matrix approximation as a regularisation prior for galaxy image deconvolution and compares its performance with a standard sparse regularisation technique. This new approach leads to a natural way to handle a space variant PSF. Deconvolution is performed using a Python code that implements a primal-dual splitting algorithm. The data set considered is a sample of 10 000 space-based galaxy images convolved with a known spatially varying Euclid-like PSF and including various levels of Gaussian additive noise. Performance is assessed by examining the deconvolved galaxy image pixels and shapes. The results demonstrate that for small samples of galaxies sparsity performs better in terms of pixel and shape recovery, while for larger samples of galaxies it is possible to obtain more accurate estimates of the galaxy shapes using the low-rank approximation.