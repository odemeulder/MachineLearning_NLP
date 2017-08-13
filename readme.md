This is a basic proof of concept I put together while learning a bit about Machine Learning and Natural Language Processing.

I am using Python, Pandas, SciKit, a Porter stemmer, Pipelines. Analazing a big dataset of Amazon movie reviews, I develop a model to analyze the sentiment in the reviews.

The original dataset came from here: https://github.com/yods/storm-ml-play/tree/master/vwtraining/aclImdb

The data I uploaded in this repository have some pre-processing done already to separate the data into a training set and a test set and positive and negative review.

You should be able to run this in Jupyter notebook. Note that line 16 takes a very long time, as it is trying to optimize different set of parameters.

Some of the components used:
* Gridsearch to optimize parameters
* Pipeline to run a pipeline (obviously)
* Porterstemmer to stem the words
* Scikit and Sklearn to do the heavy lifting

The last step applies to the model to different reviews that were not in the original data set.
