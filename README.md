Calculation of statistical characteristics (mean, std, skewness, kurtosis, contrast, correlation, energy, homogeneity) from regions of interest (ROIs) from images with different texture.


Two images with different texture are selected:

Smaller regions of interest (ROIs) were manually cut from the above images with names: roiA1-10.jpg from imgA and roiB1-10.jpg from imgB.

The fA.txt and fB.txt fles contain the GLCM matrices from rois from imgA and imgB respectivelly. Each row corresponds to one of the rois and each column coresponds to: mean, std, skewness, kurtosis, contrast, correlation, energy, homogeneity.

The idea is to identify characteristics that differ between the two images with final goal to classify an new image according to te similarities it has with one of the above images.
