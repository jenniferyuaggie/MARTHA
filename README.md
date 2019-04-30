# MARTHA: Microsoft Malware Detection
## CSCE 633 Spring 2019 Course Project

Welcome to our codebase for project MARTHA. We have been working on the [2019 Microsoft Malware detection](https://www.kaggle.com/c/microsoft-malware-prediction) challenge; our solution falls short to the winning team solution by only 3% (public score).

You can find the following information here:

* EDA: our visualization efforts for explanatory data analysis.
* Models: all source files for training different types of models.
  - Baseline_SVM.ipynb: code we used to train a soft-margin SVM (realized by scikit-learn SGD package, for online training)
  - Light-GBM-Tuning.ipynb: code that we used to tune the lightGBM model. Two variations are considered here.
  - example1.py: code for Neural Network models
  - example2.py: code for Neural Network models
  - light_gbm_on_stratified_k_folds_malwares.ipynb: code for the baseline lightGBM model using stratified 5 folds.
  - results_aggregation.py: code that we used to aggregate the results together.

Due to Github storage constraint, trained prediction files are not shared here. Reports are available upon request.

### Any questions?

Please submit a pull request.
