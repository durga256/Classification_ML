# Classification_ML
Dataset used:<br />
<a href="https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29">Drug Consumption Quantified</a><br />
The above dataset shows the drug consumption pattern of different personality types and their Big Five personality traits. Several Machine Learning algorithms are deployed to improve accuracy of the predictions.<br />
Machine Learning Algorithms used:
<ul>
  <li>Support Vector Machine</li>
  <li>Decision Tree</li>
  <li>KNN Classifier</li>
  <li>Random Forest Classfier</li>
</ul>
Confusion matrix is constructed for 6 drugs using 4 different algorithms. 
<br />Example of one such matrix where the prediction was made whether a user consumes LSD or not
<p align="center"><img src="https://drive.google.com/uc?export=view&id=1B34Zn0UWag87uUJWdZgrQEaVHMVFyiaO" alt="ConfusionMatrix"></p>
Here TN denotes - True Negative, TP - True Positive, FN - False Negative, FP  - False Positive. As desired, we have sufficiently high rates of True negative and True positive leading to an accuracy rate of 83 %.
<br />Similar tests have been run across multiple drugs using multiple algorithms in this project
