# Consumer-Consensus-to-Individual-Preference-Repository
Research on how consumer-rating aggregation affects predictive accuracy, personalization, and retail analytics using machine learning.
# From Consumer Consensus to Individual Preference: How Rating Aggregation Shapes Predictive Accuracy in Online Consumer Reviews

## Research Description

This research examines how aggregating online consumer ratings influences predictive accuracy and the interpretation of consumer preferences. Using **1,048,340 BeerAdvocate reviews covering 42,716 beers and 28,761 reviewers**, the study investigates differences between individual review-level evaluations and aggregated product-level ratings.

The study employs **Linear Regression, Random Forest, and validation-weighted ensemble models**, evaluated under a beer-disjoint training, validation, and testing framework to prevent product-level information leakage. Predictive performance is assessed using Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and the coefficient of determination (R²).

### Key Findings

- **Aggregation improves apparent predictability:** The aggregated ensemble achieved RMSE = 0.280 and R² = 0.790, compared with RMSE = 0.405 and R² = 0.682 for individual reviews.
- **Sensory attributes matter:** Taste, palate, and aroma were important predictors of overall consumer ratings.
- **Substantial unexplained variation remains:** Variance-component analysis attributed 28.9% of rating variability to beer identity, 7.0% to reviewer identity, and 64.1% to residual review-level variation.
- **Robustness was demonstrated:** A sensitivity analysis involving 998,669 reviews across 14,530 beers with at least five reviews confirmed that the aggregated representation retained lower prediction error after excluding sparsely reviewed products.

### Research Contribution

The findings demonstrate that **high predictive accuracy for aggregated product ratings does not necessarily imply accurate prediction of individual consumer preferences**. Aggregation changes the observational unit and smooths review-level variability, highlighting the importance of aligning predictive evaluation with the intended decision-making context.

The research contributes to **retail analytics, consumer behaviour, recommender systems, machine learning, and explainable data-driven decision support**.

### Repository Contents

The repository supports reproducible research through analytical scripts, preprocessing documentation, model configurations, evaluation procedures, sensitivity-analysis outputs, and supporting research materials.

**Author:** Siyanbola Hakeem Opeyemi  
**Version:** 1.0.0  
**Licence:** CC BY 4.0

**Keywords:** Consumer Reviews, Rating Aggregation, Consumer Preferences, Retail Analytics, Machine Learning, Random Forest, Ensemble Learning, Recommender Systems.
Zenodo DOI — Version 1.0.0 - https://doi.org/10.5281/zenodo.23238507
