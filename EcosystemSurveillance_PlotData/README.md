## Ecosystem Surveillance (AusPlots)

This section of the TERN's Data Skills Development Program contains tutorials and examples on how to access and use the data collected, assembled, and maintained by TERN's Ecosystem Surveillance platform. The data was  was collected as part of the *AusPlots Rangelands* monitoring program. The data can be easily extracted and prepared via the R package *ausplotsR* .

Contents include the following materials:

* *"'AusplotsR' Package and AusPlots Data Basics" (in 'AusPlots_BasicTutorial' folder)*: A tutorial exploring the use of the R package ‘ausplotsR’ to extract and prepare AusPlots data for visualisation and analysis. It shows how to download and install the 'ausplotsR' package, as well as how to use all its functions. Detailed explanations and examples are provided for the use of the arguments of all 'ausplotsR' functions. In addition, the tutorial covers how to manipulate (i.e. subset/filter and merge) and save the extracted AusPlots data. 

* *"Understanding and using the ‘ausplotsR’ package andAusPlots data" (in 'AusPlots_Tutorial' folder)*: A tutorial exploring the use of the R package ‘ausplotsR’ & the ‘ausplots’ data that can be downloaded with this package. It covers the *ausplotsR* functions in less detail than the previous tutorials (i.e. not all argument opttions are covered). However, this tutorial provides multiple examples of AusCover data manipulation, visualisation, and analysis.

* *"'ausplotsR' Examples" (in 'AusPlots_Examples' folder)*: A collection of scripts by Dr. Sam Munroe (TERN Ecosystem Surveillance and AusPlots program) with additional demonstrating examples of the use and application of the *ausplotsR* package and AusPlots data.


&nbsp;
### Rangelands

Rangelands include Grasslands, shrublands, woodlands, wetlands, and deserts that are grazed by domestic livestock or wild animals. They are characterized by vast spaces, old (often infertile) soils, highly variable (often low) rainfall, diverse and variable plant & animal communities. Rangelands ecosystems cover 81% of the Australian continent. They are understudied; with studies typically conducted at local/regional-scale, and with no standardisation across studies.


&nbsp;
### AusPlots Rangelands
AusPlots Rangelands is a plot-based surveillance monitoring program, undertaking baseline surveys of rangelands ecosystems across Australia. The aim of AusPlots is to establish and maintain a national network of permanent plots to enable consistent ecological assessment and ongoing monitoring.


&nbsp;
### ausplotsR

*ausplotsR* is an R package that greatly facilitates the extraction and preparation of AusPlots
Rangelands data. Once the data is extracted, and typically also prepared, with *ausplotsR* it can be explored, summarised, visualised, and analysed in R.   

*ausplotsR* currently includes six functions. One to extract live data, and five to prepare data for further processing (e.g. sumarising, visualisation and/or analysis).
