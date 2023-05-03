# School-District-Predictive-Model
School District Predictive Model for Metro and Micro Districts

The following data set is derived from the Stanford Education Data Archive (SEDA). In this analysis, I conducted data reduction using a principal component analysis to reduce given variables into fewer components. Then, I created a model to predict whether 3rd to 8th graders live in micropolitan or metropolitan districts in the United States based on the component analysis derived from the SEDA data set.

# Installation
To run the code, download the R package found at the following link: https://cran.r-project.org/.

# Usage
To run this code, the following R packages must be installed: 

library(tidyverse) #data science

library(dplyr) #data manipulation

library(corrplot) #visualization for the correlation matrix

library(psych) #toolbox for psychometric theory

library(facto extra) #we use this package to visualize principal component analysis

library(plyr) #download the package plyr to check frequency count of each class

library(caret) #Classification And REgression Training #simplifies the creation of predictive models

library(MASS) #Modern Applied Statistics with S

# Codebook
Variables in the original dataset can be labeled as follows:

sedametro: Metro/Micro ID

sedametroname: Metro/Micro Name

avg_test_all: Average Test Scores - All Students

avg_test_ecd: Average Test Scores - Economically Disadvantaged

avg_test_nec: Average Test Scores - Non Economically Disadvantaged

metro_or_micro: Is the area Metropolitan or Micropolitan

perurban: % Students in Urban Areas

perell: % Students English language learners

perspeced: % Students identified as special education

pernam: % Students Native American

perasn: % Students Asian

perhsp: % Students Hispanic

perblk: % Students Black 

perwht: % Students White 

perecd: % Students Economically Disadvantaged

totenrl: Total Enrollment Grade 3-8

perbaplus: % Population with Bachelors or Higher 

perunemp: % Population Unemployed 

perpoverty: % Population in Poverty

This codebook is renamed on this R markdown. Renamed variables are specified on the code (i.e. perell is renamed as Percent_English_Language_Learner).

# License
Official citation for the package can be found here:
R Team (2014). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. 2013: ISBN 3-900051-07-0.

# Contributing
Any contributions to this code, questions, or suggestions can be forward to the author at bhabika.joshi@vanderbilt.edu.

# Credits
Thank you to the Stanford Education Data Archive (SEDA) for providing access to this data set. 
