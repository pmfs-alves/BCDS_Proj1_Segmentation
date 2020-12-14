# BCDS_Proj1_Segmentation
A Customer Segmentation project. 

A lot of messy code still needs to be cleaned but we managed to perform a great job on a fairly unknown dataset, on a very fast pace. 
The intention was to  produce a proof of concept 

A customer segmentation project for marketing purposes on an 4*Hotel. Going from origination customer segmentation to data driven segmentation.

Business Knowledge was important, and allowed us to avoid pitfalls.

Due to high cardinality, top nationalities were kept, the rest were grouped to obtain relevant groups using geographical distribution, also smaller special requests were  aggregated by area of request.

Outlier removal was followed by a [Yeo-Johnson transformation](https://en.wikipedia.org/wiki/Power_transform#Yeo%E2%80%93Johnson_transformation) similar to Box-Cox but allowing negative values for y.

After some more standard processing steps analyzing clustering metrics led us to approach a 5 cluster solution. 

For proof of concept, onlye a Kmeans clusterign was required, with a focus on pre-processing

In the end, we were able to clearly define 5 different clusters, with business value, pointing to 5 different customer behaviours, that could be used by marketing to understand their needs.

They were explained in the delivered report.
