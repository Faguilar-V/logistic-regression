# logistic-regretion
Logistic Regression model applied to horse clinic data set.
Source:

Table of contents

    Introduction
    Quick reference
    Methodology
    Dataset
    Training
    Results
    Conclusion
    Future work
    Acknowledgements
    Contact
    License


Introduction
Some regression algorithms can be used to classify. The Logistic regression or also called (Logit Regression) is very used to estimate the probability that an instance belongs to a particular class, that is, if we have a classifier that discriminates for example between whether a horse is going to die or not, by means of the estimate of its probability and it turns out that it is greater than 50% then it belongs to class 1 or if it is less then it is not. This turns the logistic regression into a binary classifier.

The data set is divided into two parts, the training set horse-colic.data and the test set horse-colic.test. These were obtained from the data repository of the UCI Machine Learning Repository.

Creators:

Mary McLeish & Matt Cecile
Department of Computer Science
University of Guelph
Guelph, Ontario, Canada N1G 2W1
mdmcleish '@' water.waterloo.edu

Donor:

Will Taylor (taylor '@' pluto.arc.nasa.gov)
Can obtain in this link: http://archive.ics.uci.edu/ml/machine-learning-databases/horse-colic/


The data set is divided
Data set information:

2 data files:
-- horse-colic.data: 300 training instances
-- horse-colic.test: 68 test instances

Possible class attributes: 24 (whether lesion is surgical)
-- others include: 23, 25, 26, and 27

Many Data types: (continuous, discrete, and nominal)



Quick reference
$conda create -n log-resgression
$conda activate log-resgression
$conda install -c anaconda jupyter
$conda install -c anaconda scikit-learn
$conda install -c anaconda pandas

$jupyter notebook
