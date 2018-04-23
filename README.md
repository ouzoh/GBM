# Gradient Boosting

Gradient boosting is a machine learning technique for regression and classification, Which produces a prediction model in the form of an ensemble of weak prediction models, typically decision trees.

# Papers:

## A. [Gradient boosting machines, a tutorial](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3885826/pdf/fnbot-07-00021.pdf)
> When designing a model in domain-specific areas, one strategy is to build a model from theoryand adjust its parameters based on the observed data. Unfortunately, in most real-life situations such models are not available. The lack of a model can be circumvented if one applies non-parametric machine learning techniques like neural networks, support vector machines, or any other algorithm at one’s own discretion, to build a model directly from the data. These models are built in the supervised manner, which means that the data with the desired target variables has to be prepared beforehand.
>
> A different approach would be to build a bucket, or an ensemble of models for some particular learning task. One can consider building a set of “strong” models like neural networks, which can be further combined altogether to produce a better prediction. However, in practice, the ensemble approach relies on combining a large number of relatively weak simple models to obtain a stronger ensemble prediction. Most prominent examples of such machinelearning ensemble techniques are random forests (Breiman, 2001) and neural network ensembles (Hansen and Salamon, 1990)
>
> The common ensemble techniques like random forests rely on simple averaging of models in the ensesmble. The family of boosting methods is based on a different, **`constructive strategy of ensemble formation`**. **The main idea of boosting is to add new models to the ensemble sequentially. At each particular iteration, a new weak, base-learner model is trained with respect to the error of the whole ensemble learnt so far.** The first prominent boosting techniques were purely algorithm-driven, which made the detailed analysis of their properties and performance rather difficult (Schapire, 2002). This led to a number of speculations as to why these algorithms either outperformed every other method, or on the contrary, were inapplicable due to severe overfitting (Sewell, 2011).
>
> To establish a connection with the statistical framework, a gradient-descent based formulation of boosting methods was derived (Freund and Schapire, 1997; Friedman et al., 2000; Friedman, 2001. This formulation of boosting methods and the corresponding models were called the gradient boosting machines. This framework also provided the essential justifications of the model hyperparameters and established the methodological base for further gradient boosting model development.
>
> In **gradient boosting machines (GBMs)**, the learning procedure consecutively fits new models to provide a more accurate estimate of the response variable. The principle idea behind this algorithm is to construct the new base-learners to be maximally correlated with the negative gradient of the loss function, associated with the whole ensemble. If the error function is the classic squared-error loss, the learning procedure would result in consecutive error-fitting.

# Projects:

## A. [Can we predict flu deaths with Machine Learning and R?](https://shiring.github.io/machine_learning/2016/11/27/flu_outcome_ML_post)

1. **`There is no package called ‘RGtk2’`**\
`sudo apt-get install wajig`\
`wajig install libgtk2.0-dev` [[source]](https://stackoverflow.com/questions/28533667/error-on-installing-rattle-in-ubuntu?utm_medium=organic&utm_source=google_rich_qa&utm_campaign=google_rich_qa)

2. **`/usr/bin/ld: cannot find -lzlib`**\
 `ld -lzlib --verbose` \
 `sudo ln -s /usr/lib/lzlib.so.1.2.8 /usr/lib/libzlib.so` [[source]](https://stackoverflow.com/a/21647591/7541032)
