# Random forests for facial recognition
A brief introduction to random forests, illustrated with a Python 3 application in real-time facial recognition.

## Files
The work in this repository is summarized in [the pdf file introduction-random_forests.pdf](introduction-random_forests.pdf). This is a brief introduction to random forests. The document describes what random forests are, how and why they work, and what is their appeal. The document also describes the implementation and results of this repository's Python application using random forests for facial recognition. 

[introduction-random_forests.tex](introduction-random_forests.tex) is the LaTeX file used to generate [introduction-random_forests.pdf](introduction-random_forests.pdf).

[The pdf file presentation-random_forests.pdf](presentation-random_forests.pdf) is a set of slides for a presentation of the content in the above-described document, [introduction-random_forests.pdf](introduction-random_forests.pdf). 

[The pdf file random_forest_overfitting.pdf](random_forest_overfitting.pdf) is a brief refutation of a common hyperbolic claim regarding random forests -- namely, the claim that they do not overfit.

[random_forest_overfitting.rmd](random_forest_overfitting.rmd) is the R Markdown file used to generate [random_forest_overfitting.pdf](random_forest_overfitting.pdf).

[The Jupyter notebook facialRecognitionClassifier.ipynb](facialRecognitionClassifier.ipynb) contains the Python 3 code that learns a pair of faces (via a computer's webcam), trains a random forest classifier, and then uses this classifier to tag faces in real-time on a webcam stream. With minor modifications, this code could be used for any number of faces, rather than only on two. The code also generates a bar graph of the feature importances, thereby showing what are the most salient differences between the two faces on which the classifier is trained. Note that use of this code requires that one have installed both the OpenCV and Dlib Python libraries.

All other files in the repository are support files used in the creation of the above-listed files.
