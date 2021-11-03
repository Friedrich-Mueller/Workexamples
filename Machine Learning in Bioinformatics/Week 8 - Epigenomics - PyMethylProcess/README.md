This week’s task was to use the “PyMethylProcess” preprocessing pipeline for feature extraction, followed by the development(training) of two ML classifiers on the extracted features, which can be used to classify samples in the chosen dataset. The datasets have been filtered to represent only two classes.

For the evaluation of the models the R2 scores as well as the max errors metrics have been utilized, analogue to metrics used in the provided (by the paper) example notebook, to be able to compare the two models’ performance to the provided model from the original paper.

The two chosen estimators here are Ridge Regression and Linear Regression estimators.


The original Random Forests Regression was provided by  https://github.com/Christensen-LabDartmouth/PyMethylProcess/blob/master/example_scripts/machine_learning_example/MachineLearn
ingExample.ipynb

