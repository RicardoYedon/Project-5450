Hypothesis:

Null Hypothesis (H₀): The advanced models do not significantly improve RMSE compared to the baseline RMSE of 1.0581.
Alternative Hypothesis (H₁): The advanced models significantly improve RMSE over the baseline.
Expectation:

If the advanced models achieve an RMSE substantially lower than 1.0581, and statistical tests (e.g., paired t-tests) show p-values less than 0.05, we can reject the null hypothesis in favor of the alternative.
Performance Goals for Advanced Models
K-NN Model:

Target RMSE: Aim for an RMSE lower than 1.0581.
Strategies to Improve Performance:
Tune the number of neighbors (k) for optimal results.
Experiment with different similarity metrics (e.g., cosine, Pearson correlation).
SVD Model:

Target RMSE: Aim for an even lower RMSE than the K-NN model.
Strategies to Improve Performance:
Adjust the number of latent factors (k) in SVD.
Implement regularization techniques to prevent overfitting.

