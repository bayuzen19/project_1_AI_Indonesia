# project_1_AI_Indonesia
[link dataset](https://drive.google.com/drive/folders/1aeEHgCQtE119mY5JjIwVBys0LR0P8SxJ?hl=id)

## Welcom to my first Project At AI Indonesia Bootcamp.
In this session, I created an architectural model based on GoogleNet or InceptionV3

## Result
![Accuracy](https://github.com/bayuzen19/project_1_AI_Indonesia/blob/main/assets/accuracy_history.png)
From this figure, we can observe that our model has good accuracy and does not appear to have overfitting.

## Evaluation
![Confussion Matrix](https://github.com/bayuzen19/project_1_AI_Indonesia/blob/main/assets/confussion_matrix.png)

However, upon reviewing the confusion matrix, it is evident that the model we built predicts all pictures as female. Therefore, the model is unable to generalize and distinguish between male and female accurately.

![Confussion Matrix](https://github.com/bayuzen19/project_1_AI_Indonesia/blob/main/assets/after_adjusted_threshold.png)

After attempting to find the best threshold, I discovered that the optimal threshold is 0.1. Implementing this threshold yields the following scores:
- Recall: 0.5
- Precision: 0.45
- F1 score: 0.48

## Improvement
For the next steps in this project, there is a need to enhance the processing process to improve the model's performance.
