## Machine Learning Project -- Credit Card Fraud
This project built a supervised extra tree model to shape the issue. 
### Two most significant achievements:
* Built a feature selection function based on the correlation coefficient matrix and data visualization, which effectively reduced **78%** of the noise (_28 features down to 6_) and maintained the overall model performance.
* Improved recall while maintaining precision by applying a customized algorithm and precision and recall curve.
### Several libraries' experiences:
* Demonstrated dataset manipulation use case through Numpy and Pandas.
* Demonstrated data visualization use cases through Seaborn, matplotlib, Plotly.
* Demonstrated model evaluation metrics use cases through classification reports, confusion matrix, precision and recall curve.
* Demonstrated resampling methods use cases through SMOTE and Random Sampler.
* Demonstrated model building, evaluation, hyperparameter tuning and pipeline workflow use cases through Sklearn.
* Demonstrated dimension reduction use cases through Autoencoder and UMAP.
### Libraries:
* Data process
  * Numpy
  * Pandas
* Data visualization
  * Matplotlib
  * Seaborn
  * Plotly
* Sampling
  * Pandas
    * Random sampling
  * Sklearn
    * Train test split
  * Imblearn
    * SMOTE
    * Random Sampler
* dimension reduction
  * UMAP
  * Autoencoder
* Model building & evaluation
  * Sklearn
    * Cross Validation
    * Grid search
    * Pipeline
    * Extra tree model
  * Classification report
  * Confusion matrix
  * Precision and recall curve
* Model selection
  * Pycaret
