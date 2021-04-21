# Improving Land Cover Classificastion Using Genetic Programming for Feature Construction

This repository contains eight of the nine datasets used in the "Improving Land Cover Classificastion Using Genetic Programming for Feature Construction" paper.


@Article{rs13091623,
AUTHOR = {Batista, João E. and Cabral, Ana I. R. and Vasconcelos, Maria J. P. and Vanneschi, Leonardo and Silva, Sara},
TITLE = {Improving Land Cover Classification Using Genetic Programming for Feature Construction},
JOURNAL = {Remote Sensing},
VOLUME = {13},
YEAR = {2021},
NUMBER = {9},
ARTICLE-NUMBER = {1623},
URL = {https://www.mdpi.com/2072-4292/13/9/1623},
ISSN = {2072-4292},
ABSTRACT = {Genetic programming (GP) is a powerful machine learning (ML) algorithm that can produce readable white-box models. Although successfully used for solving an array of problems in different scientific areas, GP is still not well known in the field of remote sensing. The M3GP algorithm, a variant of the standard GP algorithm, performs feature construction by evolving hyperfeatures from the original ones. In this work, we use the M3GP algorithm on several sets of satellite images over different countries to create hyperfeatures from satellite bands to improve the classification of land cover types. We add the evolved hyperfeatures to the reference datasets and observe a significant improvement of the performance of three state-of-the-art ML algorithms (decision trees, random forests, and XGBoost) on multiclass classifications and no significant effect on the binary classifications. We show that adding the M3GP hyperfeatures to the reference datasets brings better results than adding the well-known spectral indices NDVI, NDWI, and NBR. We also compare the performance of the M3GP hyperfeatures in the binary classification problems with those created by other feature construction methods such as FFX and EFS.},
DOI = {10.3390/rs13091623}
}


The eight datasets are divided in seven folders, one for each dataset (IM-3 is included in IM-10's folder).
In these folders, you can see a description of the satellite images and the reference paper for each dataset.

The Mz6 was not included in this repository since it is proprietary.
