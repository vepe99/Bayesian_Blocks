# Bayesian_Blocks
The histogram representation is a powerful tool that is widely spread across many different fields, yet it is not an objective method since it heavily depends on the choice made for binning the data. Due to the different approaches one can use, the resulting distributions generated from the same underlying statistics could highlight different structures modifying the interpretation of the data. Different methods have been devised to overcome this issue: for example, Scott’s Rule [1] and the Freedman-Diaconis Rule [2] use the number of entries and a measure of the spread of the distribution to determine the number of bins with fixed width; Knuth’s Rule [3] consider the distribution’s structure to build bins that still have the same width; the “equal population” method enforce that each bin have similar numbers of entries, resulting in varying widths, but the location of the bin edges is chosen arbitrarily.
In contrast with them the Bayesian Block (BB) algorithm [4] [5] allows the bin widths to vary and determines the bin edges based on the structure of the distribution, making it parameter free.

1. ^ D. W. Scott, Biometrika 66, 605 (1979)
2. ^ D. Freedman and P. Daiconis, Zeitschrift f¨ur Wahrschein-lichkeitstheorie und verwandte Gebiete 57, 453 (1981)
3. ^ K. H. Knuth, (2006), arXiv:physics/0605197[physics.data-an]
4. ^ J. D. Scargle, Studies in Astronomical Time Series Analysis. V. Bayesian Blocks, a New Method to Analyze Structure in Photon Counting Data, 1998, arXiv:astro-ph/9711233.
5. ^ J. D. Scargle, J. P. Norris, B. Jackson, and J. Chiang, Astrophys. J. 764, 167 (2013), arXiv:1207.5578[astro-ph.IM]
