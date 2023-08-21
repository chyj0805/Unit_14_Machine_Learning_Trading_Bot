# Conclusions

·The Gradient Boosting model has significantly better training recall and F1-score for class -1.0, indicating that it can correctly identify instances of class -1.0 more effectively during training.

·The Gradient Boosting model also has higher training recall and F1-score for class 1.0, indicating better performance in identifying instances of class 1.0 during training.

·However, the SVM model performs better on the testing dataset in terms of precision, recall, and F1-score for class 1.0. It has a higher testing recall and F1-score for class 1.0, suggesting better performance in identifying instances of class 1.0 on the testing data.

·The SVM model has higher testing accuracy compared to the Gradient Boosting model.

In summary, both models have strengths and weaknesses. The Gradient Boosting model shows strong performance during training but struggles to generalize to the testing data, especially for class 1.0. The SVM model demonstrates better performance on the testing dataset, particularly in identifying instances of class 1.0.

For the SVM Model:

·During testing, Strategy Returns seem to slightly outperform Actual Returns, suggesting that when using the SVM model, the strategy's returns are slightly better than the actual returns.

·However, overall, the SVM model's performance doesn't seem significantly better than the baseline (actual returns), as both exhibit relatively small differences in cumulative returns, potentially with considerable fluctuations.

For the Gradient Boosting Model:

·During testing, Actual Returns demonstrate a significantly better performance than Strategy Returns, indicating that when employing the Gradient Boosting model, actual returns are notably superior to strategy returns.

·This could imply that the Gradient Boosting model's performance on the testing data might not be as expected, possibly due to inadequate generalization to the testing dataset.

In summary：

·The SVM model appears to have a slightly better performance in strategy returns during testing, but its overall performance might be on par with the baseline.

·he actual returns for the Gradient Boosting model notably outperform its strategy returns during testing, indicating potential issues with the model's performance on the testing dataset.