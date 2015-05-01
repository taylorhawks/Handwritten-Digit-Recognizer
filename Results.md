# What does each variable do?
Gamma affects the accuracy of the SVC predictor. A low gamma means that one training sample has a low influence on the strenght of the prediction, and vice versa.
C influences the allowable error for the predictor in a SVC model.
Default accuracy is 94.5% given the starting variables.

# Changing gamma
When gamma is .01 as opposed to .0001, the SVC accuracy goes down to 65%
When gamma is .1, the SVC accuracy is 10%, which is pretty useless.  A guess would be just as good.
When gamma is 1, the SVC accuracy is <10%, which is worse than a guess.  Also, the 2 was incorrectly predicted as a 5.
A gamma value of 0 yields a SVC prediction of ~40% accuracy much better than .1 or 1, but not as good as .0001 from before.

#Changing the training sample
Accuracy decreases from .945 to .93 when training on the first 500 samples.
Accuracy is up to .99 when training on the first 1700 samples (out of 1797).
