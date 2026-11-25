# Problem-Set-5
# Right 93% of the Time

I simulated 10,000 loan applications to see how much a model's accuracy tells us when defaults are rare. I compared logistic regression, LASSO, Ridge, and a random forest, then looked at how much it costs to miss a default or turn away a good borrower.

## What I found

- Approving everyone was 92.35% accurate and caught zero defaults.
- Ridge had a ROC AUC of 0.781 and a PR AUC of 0.318. It was slightly more accurate than the random forest, but the paired test didn't show a significant difference (p = 0.678).
- At a cutoff of 14.29%, Ridge's estimated cost was 573.80 dollars per test application. Approving everyone cost 830.14 dollars per test application.

Open the notebook in Colab and choose Runtime > Run all. The notebook generates the data, so there's nothing else to download.
