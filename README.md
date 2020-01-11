

# A comparison of Nystrom Method and Random Fourier Features
Both random Fourier features and the Nystrom method have been successfully applied to efficient kernel learning.  
In this work, we investigate the fundamental difference  between  these  two  approaches,  and  how  the  difference 
could  affect their generalization performances.Codes are borrowed from [Large Scale Kernel Methods ](https://maelfabien.github.io/machinelearning/largescale/).

## Author(s)

MADALI Nabil , Virgile Rennard ,Mélanie Karlsen.

## Functions

we study the efficiency of the proposed methods.
To verify our theoretical findings, we evaluate the empirical performance of the Nystrom method and 
random Fourier features for large-scale kernel learning on three data sets:
Including one for regression 

* `YearPredictionMSD.ipynb`: Prediction of the release year of a song from audio features. Songs are mostly western, commercial tracks ranging from 1922 to 2011, with a peak in the year 2000s.
	

And two for classification:
* `USPS.ipynb`: USPS digit database is one of the standard datasets for handwritten digit recognition. 
* `Gisette.ipynb`: GISETTE is a handwritten digit recognition problem. The problem is to separate the highly confusible digits '4' and '9'. This dataset is one of five datasets of the NIPS 2003 feature selection challenge.
## References

Maël Fabien. Large Scale Kernel Methods . [Website](https://maelfabien.github.io/machinelearning/largescale/#)

Tianbao Yang,Yu-Feng Li,Mehrdad Mahdavi,Rong Jin. Nystrom Method vs Random Fourier Features: A Theoretical and Empirical Comparison [Paper](http://dirk.eddelbuettel.com/papers/RcppArmadillo.pdf)

Zhang, Jian and May, Avner and Dao, Tri and Re, Christopher.Low-Precision Random Fourier Features for Memory-Constrained.arXiv preprint arXiv:1811.00155 Kernel Approximation

