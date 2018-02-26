# Clustering
Clustering is the grouping of a particular set of objects based on their characteristics, aggregating them according to their similarities. Regarding to data mining, this metodology partitions the data implementing a specific join algorithm, most suitable for the desired information analysis. 
This clustering analysis allows an object not to be part of a cluster, or strictly belong to it, calling this type of grouping hard partitioning. In the other hand, soft partitioning states that every object belongs to a cluster in a determined degree. More specific divisions can be possible to create like objects belonging to multiple clusters, to force an object to participate in only one cluster or even construct hierarchical trees on group relationships.

There are several different ways to implement this partitioning, based on distinct models. Distinct algorithms are applied to each model, diferentiating it’s properties and results. These models are distinguished by their organization and type of relantionship between them. The most important ones are:

- Centralized - each cluster is represented by a single vector mean, and a object value is compared to these mean values
- Distributed – the cluster is built using statistical distributions
- Connectivity – he connectivity on these models is based on a distance function between elements
- Group – algorithms have only group information
- Graph – cluster organization and relationship between members is defined by a graph linked structure
- Density – members of the cluster are grouped by regions where observations are dense and similar
