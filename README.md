## Analyzing and predicting local states in Homogenization-localization problems using statistics, data science and ML approaches
Homogenization is one of the very common techniques used in micro and multiscale mechanics. Since many properties of a material at visible length-scale have their origin at lower lenghscale, we apply homogenization techniques in order to have an assessement of local property distribution. Estimating properties at lower length-scale is known as localization. We have showed in [another repository](https://github.com/helalme/DataDrivenMSE/tree/master/UncertaintyReductionInHomogenization) that homogenized properties might have uncertainties with high bias and variance, we also showed how to reduce these uncertainties usig machine learning techniques, avoiding huge computational cost. 

For better product design we need to have a very good assessement of the local states/properties as well. In this repository, we will show how to predict local states for a statistically equivalent RVE reducing uncertainties. We will use statistics, data science and machine learning techniques to analyze, visualize and predict local states with reasonable accuracies, which in turn reduce high computational cost.

For any simulation, we might have millions of local states at each time step depending on the size of the simulation domain. How to analyze, visualize and predict this kind of huge datasets will be shown in this repository. In general we can understand a large dataset with two approaches, 1. with mean+standard deviation,  and 2. with box+whiskers+outliers. The former one is less accurate than that of later. In this repo, we will use both approaches.   

Please have a look at individual Jupyter notebooks for details.
