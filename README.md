# Neural_Networks

### Original Model Results:
- Loss: 8.1631
- Accuracy: 47.08%
- Time per epoch: 168ms
- Time per step: 627us


### Alternative Model 1 Results:
- Loss: 0.5733
- Accuracy: 73.21%
- Time per epoch: 235ms
- Time per step: 877us


### Alternative Model 2 Results:
- Loss: 0.5543
- Accuracy: 73.13%
- Time per epoch: 246ms
- Time per step: 918us

### Comparison
- The original model has the highest loss at 8.1631, which suggests it might not be fitting the data well. Model 2 has a slightly lower loss compared to Model 1.
- The original model has an accuracy of 47.08%, which is significantly lower than the two alternative models.The alternative models have very similar accuracies, both around 73%.
- The original model is the fastest with 168ms/epoch. Model 2 is the slowest with 246ms/epoch and Model 1 is in the middle at 235ms/epoch.
- The original model is the fastest per step, followed by Model 1, and then Model 2.
- If we were to prioritize accuracy over computation time, Alternative Model 1 is the best choice as it has the highest accuracy. However, if you're looking for the quickest model, the Original Model is the fastest, but with a significant trade-off in accuracy and loss.