This repository hosts the data used in my dissertation, for ease of access. In the folder titled `chapter2`, I have the data from my original repository at [https://github.com/kkostyszyn/PolishClustersData](https://github.com/kkostyszyn/PolishClustersData), updated with information from the new models and better organized. This includes:

1.	**acceptability\_master\_PWN** includes every cluster, a column designating with an 'x' if a cluster does NOT occur in the PWN dictionary (or a note if there is very limited use), and then the acceptability scores from the survey. Note that, for the survey, 0 means that a cluster was unacceptable for its given ending (endings have been removed). 
2.	**pol\_bigrams** is a collation of all **bigrams** in acceptability\_master\_PWN, appended with a boundary symbol \# at the beginning and end of each cluster.
3.	**illegal\_clusters**, which lists the average acceptability score for all the clusters in acceptability\_master\_PWN, as well as counting the number of illegal bigrams in each cluster.
4.	The folder **MaxEntInput** has files used to run with the Maximum Entropy learner (Hayes and Wilson, 2008).  
5.  The folder **BUFIAoutput** has the constraint outputs from running BUFIA (Chandlee et al., 2019; Rawski, 2021). 

The folder `chapter3`has the input files used to generate decision trees and perceptrons using WEKA. These lists were generated using the [https://github.com/unimorph/pol](Unimorph) conversion of the Słownik gramatyczny języka polskiego (Kirov et al., 2018; Saloni et al., 2015; Woliński and Kieraś; Calzolari et al., 2016).