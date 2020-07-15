# Fraud-Detection-in-Healthcare

The visualization aids in solving the problem of frauds in the healthcare industry by identifying anomalous prescribers.
The data is provided by CMS and is aggregated at the prescriber level.

The visualization consists of three views, wherein the first view presents an overview of the prescribers and is exploratory in nature.
![snap](https://github.com/mohannishant6/Detecting-Frauds-in-Healthcare/blob/master/images/screen1.jpg)

After understanding the data, I make clusters of prescribers. Using K-means algorithm, I find 5 to be the optimum number of clusters.

The second view of the dashboard provides more detail into key features of all the clusters. 
![snap](https://github.com/mohannishant6/Detecting-Frauds-in-Healthcare/blob/master/images/screen2.jpg)
Viewer has the option to alter the metrics using a drop-down list of features giving top 3 specialties of each cluster.
It can be seen evidently that cluster 4 is indeed suspicious as it has highest costs across categories.

Finally, we dive deeper into the cluster 4 to identify outliers.
![snap](https://github.com/mohannishant6/Detecting-Frauds-in-Healthcare/blob/master/images/screen3.jpg)
Identifying these outliers is the end objective of this visualization and therefore is exploratory. 

While the visualization is successful in identifying an outlier prescriber, a domain expert is still needed to identify false positives. Having said that, the visualization still helps in reducing the number of prescribers to be inspected.

Link to Viz: https://public.tableau.com/views/DetectingFraudsinHealthcare/Story1?:display_count=y&:origin=viz_share_link

Link to Video Demo: https://youtu.be/XSvFYj-UmtM

