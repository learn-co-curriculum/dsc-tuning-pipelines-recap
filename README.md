# Model Tuning and Pipelines - Recap

## Key Takeaways

The key takeaways from this section include:

* Machine learning ***pipelines*** create a nice workflow to combine data manipulations, preprocessing, and modeling
* Machine learning pipelines can be used along with ***grid search*** to evaluate several parameter settings 
  * Grid search can considerably blow up computation time when computing for several parameters along with cross-validation
  * Some models are very sensitive to hyperparameter changes, so they should be chosen with care, and even with big grids a good outcome isn't always guaranteed
* Machine learning pipelines can also be ***pickled*** so that they can be used in the future without re-training
* Model ***deployment*** can be something as simple as pickling a model, or a more complex approach like a ***cloud function*** that exposes model predictions through an HTTP API
