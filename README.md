**Trends in Conflict**

Here is the code that goes with my Master Thesis at the University of Tilburg, December 2021.

BE SURE TO DOWNLOAD THE DATASET AND INSTALL ALL THE NECESSARY LIBRARIES BEFOREHAND!!

The complete list of libraries used in every file can be found at the top of each Notebook.

Download the csv file at: https://ucdp.uu.se/downloads/index.html#ged_global for the UCDP Georeferenced Event Dataset (GED) Global version 21.1 and make sure to add it to your current directory

q1-2.Rmd is a Notebook that contains the code belonging to the Exploratory Data Analysis (EDA) section of the thesis.
q3-5.Rmd is a Notebook that contains the code belonging to the Social Network Analysis (SNA) section of the thesis.
q6-clust.Rmd is a Notebook that contains the code belonging to the Cluster Analysis (CA) section of the thesis.

All files have also been published as html files in case of any issues.

The network graph is added as an html file accessible through https://ka-thesis.github.io/conflict/network.html/




The libraries and additional sources used are listed here:

**Libraries Used**

**EDA**

readr: https://www.rdocumentation.org/packages/readr/versions/1.3.1 
dplyr: https://www.rdocumentation.org/packages/dplyr/versions/0.7.8 
ggplot2: https://ggplot2.tidyverse.org/ 
ggmap: https://www.rdocumentation.org/packages/ggmap/versions/3.0.0

**SNA**

readr: https://www.rdocumentation.org/packages/readr/versions/1.3.1 
dplyr: https://www.rdocumentation.org/packages/dplyr/versions/0.7.8 
ggplot2: https://ggplot2.tidyverse.org/

_Inferring and Analysing the Network_
network: https://cran.r-project.org/web/packages/network/index.html 
igraph: https://igraph.org/r/ 
centiserve: https://www.centiserver.org/rpackage/ tidygraph: https://www.rdocumentation.org/packages/tidygraph/versions/1.2.0

_Visualising the Network_
networkD3: https://www.rdocumentation.org/packages/networkD3/versions/0.4 
visNetwork: https://www.rdocumentation.org/packages/visNetwork/versions/2.1.0 
htmlwidgets: https://www.htmlwidgets.org/ 
ggraph: https://cran.r-project.org/web/packages/ggraph/index.html

**CA**

readr: https://www.rdocumentation.org/packages/readr/versions/1.3.1 
dplyr: https://www.rdocumentation.org/packages/dplyr/versions/0.7.8 
ggplot2: https://ggplot2.tidyverse.org/

_Clustering_
clustertend (Hopkins statistic): https://rdrr.io/cran/clustertend/ 
factoextra (Elbow method): https://www.rdocumentation.org/packages/factoextra/versions/1.0.7 
stats (kmeans Clustering): https://www.rdocumentation.org/packages/stats/versions/3.6.2

_Word cloud_
wordcloud: https://www.rdocumentation.org/packages/wordcloud/versions/2.6 
RColorBrewer: https://cran.r-project.org/web/packages/RColorBrewer/index.html 
wordcloud2: https://cran.r-project.org/web/packages/wordcloud2/index.html 
tm: https://cran.r-project.org/web/packages/tm/index.html

**Other Sources Used**
**EDA**

For creating a grid with multiple plots:
Haaf, S. (2019, April 03). Easy multi-panel plots in R using facet_wrap() and facet_grid() from ggplot2. Retrieved from http://zevross.com/blog/2019/04/02/easy-multi-panel-plots-in-r-using-facet_wrap-and-facet_grid-from-ggplot2/

For creating a map in R:
Hadley Wickham, D. N. (n.d.). 6 Maps. Retrieved December 02, 2021, from https://ggplot2-book.org/maps.html

For ordering a horizontal bar chart:
Gregory Saxton, & Gavin Simpson (n.d.). Ordering of bars in ggplot. Retrieved from https://stackoverflow.com/questions/5967593/ordering-of-bars-in-ggplot

**SNA**
Jesse Sadler. (2017, October 25). Introduction to Network Analysis with R. Retrieved from https://www.jessesadler.com/post/network-analysis-with-r/

Bradley, B. (2021, May 25). From igraph to visNetwork. Retrieved from https://towardsdatascience.com/from-igraph-to-visnetwork-7bc5a76fdeec

**CA**
For the word clouds:
Rul, C. V. (2019, October 20). How to Generate Word Clouds in R. Retrieved from https://towardsdatascience.com/create-a-word-cloud-with-r-bde3e7422e8a
