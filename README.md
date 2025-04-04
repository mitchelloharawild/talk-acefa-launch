

<!-- README.md is generated from README.qmd. Please edit that file -->

# Probabilistic forecast combinations

Slides and notes for a presentation about ensembling and reconciliation
at the ACEFA launch event (2nd April 2025).

<!-- A recording of this presentation is available on YouTube here: <https://www.youtube.com/watch?v=> -->

<!-- [![](preview.jpg)](https://www.youtube.com/watch?v=) -->

#### Abstract

Forecast combination leverages the information captured by multiple
models to produce more accurate forecasts. There are several methods to
combine multiple forecasts effectively. Ensemble forecasting uses
forecasts of the same time series from various models, helping to
mitigate model misspecification by averaging predictions. Decomposition
forecasting combines forecasts from a time series that has been broken
down into simpler, individual components, making it easier to forecast
each part separately. Forecast reconciliation adjusts forecasts from
multiple related time series to ensure they adhere to a coherent
structure, thereby sharing information between the series. In this talk,
I will discuss each of these combination strategies in the context of
infectious disease forecasting, with demonstrations using the
distributional R package.

#### Structure

- Combining forecasts from multiple models
- Combining forecasts of a decomposition
- Combining forecasts from multiple series
- Statistical computing with the distributional package

### Format

- 12 minutes + 3 minutes questions
