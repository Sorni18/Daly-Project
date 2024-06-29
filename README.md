# Daly-Project
## Introduction
After searching through different databases that met the demands and needs of this project, we finally found one that offered a large number of variables and observations, a fundamental aspect for its development.

This database provides information about DALYs in different populations between the years 1990 and 2019. DALYs, or "Disability-Adjusted Life Years," is a measure used in the fields of epidemiology and health to quantify the burden of a disease in a population, taking into account both mortality and morbidity caused by diseases or injuries.

Our database contains a total of 6,150 observations, where each observation corresponds to a country in a specific year. Each country is represented 30 times, as we have data from 1990 to 2019 for each one of them. Additionally, our database comprises 28 variables, 25 of which refer to DALY by type of disease, while the variables Entity, Code, and Year refer to the country, the code of said country, and the year respectively.

In the original database, there were missing data in the 'Code' attribute because values were measured for certain regions that had no assigned code. However, since we do not plan to analyze the data by geographical regions, we will conduct the analysis by countries.

Now we will proceed to outline the objectives. Initially, we did not have sufficient knowledge to adequately define the objectives to follow, which is why in the first database delivery, we could not adequately propose them. However, as the classes have progressed and we have been given different tools, we have been able to outline the following objectives:

* Reduce dimensionality and understand the nature of our database using PCA. This will help us understand the differences between countries according to the DALY values of different conditions.
* Group the classes to which the different countries belong using clustering, forming groups of variables with similar behavior, and thereby group countries based on their type.
* Confirm the clustering results using Fisher's discriminant analysis.
* Classify countries by level of development according to the Human Development Index (HDI) using PLS.

The remainder of the project is available in the various RMarkdown files, and the conclusions can be found in the directory named "Conclusions" within the file titled "Memoria".
