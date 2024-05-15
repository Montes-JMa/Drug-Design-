# Drug-Design
In this repository, you will find the instructions to generate new molecules using genetic algorithms based on chemical similarity.   

# Python (Selenium) to predict ADMETox properties  
Likewise, there is code that allows using the [SwissADME](http://www.swissadme.ch/) server to calculate ADMETox properties for each of the molecules.  

# Data Filtering  
There is a code that allows you to filter the data frames according to the desired characteristics. By default, there are parameters to select molecules directed at membrane proteins of the central nervous system.

# Chemical Similarity and Dimension reduction   
Similarity algorithms through the use of multiple fingerprints and t-SNE algorithm.  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Software and Libraries
[LigBuilder V3](http://www.pkumdl.cn:8080/ligbuilder3/intro.html)  
[OpenEye](https://www.eyesopen.com/academic-licensing)  
[MayaChemTools FPs](http://www.mayachemtools.org/Download.html)  
[Obabel](https://open-babel.readthedocs.io/en/latest/Installation/install.html)  
  

### Python
selenium                           4.14.0             
selenium-manager          4.14.0               
pandas                              2.1.1
plotly                                 5.9.0
rdkit                                   2020.09.3
scikit-learn                       1.2.2 


### R
library(reshape)  
library(rcdk)  
library(fingerprint)  
library(ggplot2)  
 
