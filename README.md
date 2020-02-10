# REGIONAL MODELS FOR PROTOTYPE-BASED CLASSIFICATION: A NOVEL PARADIGM

The global classification paradigm uses the entire training set for producing a single discriminating model for distinct classes. Alternatively, the cluster-based local classification approach
builds multiple discriminating models using smaller subsets of the training data. By considering these two paradigms as the extremes of a spectrum of possibilities, in this thesis, it is introduce a
novel two-stage framework for building pattern classification models based on the clustering of the self-organizing map (SOM) method (VESANTO et al., 2000). According to this technique,
data samples are submitted to the SOM as a preprocessing stage. Then, clustering algorithms (e.g. the K-means) are applied to the prototype vectors of the SOM aiming at organizing them
in well-defined regions. By applying this two-stage strategy to labeled data, it is show how to build accurate classifying models, henceforth referred to as regional classifiers, using the subset
of samples mapped to a specific cluster of SOM units. A comprehensive comparative study is carried out to evaluate the effectiveness of the proposed approach on several benchmarking data
sets, using linear models, i.e. least squares classifier with linear basis functions (LSC-LBF), and nonlinear ones, i.e. least squares support vector machine (LSSVM) with nonlinear kernel
functions. As an additional step on the training of cluster-based local and regional models, during the model validation phase, a set of twelve cluster validation metrics was used to assess their
ability to predict the best number of prototypes given a well-defined objective function. 

Keywords: Pattern recognition. Global and local models. Self-organizing maps. Clustering of
the SOM. Local Models. Regional models. Least Squares Support Vector Machine. K-means.
