# likelihood-ratio-imbalance-degree

Implementation of the paper- LRID: A new metric of multi-class imbalance degree based on likelihood-ratio test by Rui Zhu et. al.

A new measure of imbalance degree using likelihood ratio is introduced in order
to compute the extent of imbalance in a multi-class data set. Usually Imbalance Ratio (IR) is
used as a metric to measure extent of imbalance. However, it takes into consideration only the
highest majority class and the lowest minority class, thereby failing to capture any information
from the intermediate classes. Imbalance Degree (ID) is a metric was proposed while keeping
in mind that it has to consider the intermediate classes as well. But it requires us to choose a
distance metric that largely affected the results. It also assumes that data with more minority
classes are more imbalanced than data with less minority classes, which is not always true.
