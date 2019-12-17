# evaluation-metric
In the code we built a classifer to classify that the passenger survuve or not.
so the main problem in classification model is how to measure the accuracy of model compared to regression models.
well there are set of measure to judge the performance of a classification model
*Accuracy
*Precision
*Recall
*F1-Score
 These all uses the values of confusion matrix(not so confusing).
 see this image https://lh6.googleusercontent.com/yhbCKml74dnMDgZObLGn7xDY-KCoRNuMM6ElEAVIoprceJZaJ6vOOv3XHvN_-xjvwvUYs41CC5ElwvFf9fbvWNJQImsW5bSWTkQr4qbWghcup06x4I5red1BhcZQSpOXGD6VeRT4
 
 TP: True Positive: Predicted values correctly predicted as actual positive
FP: Predicted values incorrectly predicted an actual positive. i.e., Negative values predicted as positive
FN: False Negative: Positive values predicted as negative
TN: True Negative: Predicted values correctly predicted as an actual negative



Does Accuracy matter?
Not always, it may not be the right measure at times, especially if your Target class is not balanced (data is skewed).
Then you may consider additional metrics like Precision, Recall, F score (combined metric).

Precision:
It is the ‘Exactness’, ability of the model to return only relevant instances. 
If your use case/problem statement involves minimizing the False Positives.

recall:
It is the ‘Completeness’, ability of the model to identify all relevant instances, True Positive Rate, aka Sensitivity.
In the current scenario if your focus is to have the least False Negatives

F1 Measure
Harmonic mean of Precision & Recall, used to indicate a balance between Precision & Recall providing each equal weightage,
it ranges from 0 to 1.
F1 Score reaches its best value at 1 (perfect precision & recall) and worst at 0

for more  https://blog.floydhub.com/a-pirates-guide-to-accuracy-precision-recall-and-other-scores/#confusion-matrix
