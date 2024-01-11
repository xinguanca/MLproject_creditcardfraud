## Machine Learning Project -- Credit Card Fraud
This project built a supervised extra tree model to shape the issue and improve recall with a relatively high precision. 
### Two most significant achievements are listed below
* Built a feature selection function based on the correlation coefficient matrix, which effectively reduced **78%** of the noise (_28 features down to 6_) and maintained the overall model performance
* Improved recall while maintaining precision by applying a customized algorithm and precision and recall curve
### Several other libraries' experience are listed below
* Demonstrated Numpy and Pandas use cases through dataset manipulation
* Demonstrated data visualization use cases through Seaborn, matplotlib
* Demonstrated model evaluation metrics use cases, such as classification reports, confusion matrix, precision and recall curve
* Demonstrated resampling methods use cases, such as SMOTE and Random Sampler
* Demonstrated Sklearn use cases in model building, evaluation, hyperparameter tuning and pipeline workflow
* Demonstrated Autoencoder, UMAP and Plotly use cases
### Libs used in this project:
* Data process
  * Numpy
  * Pandas
* Data visualization
  * Matplotlib
  * Seaborn
  * Plotly
  * UMAP
* Sampling
  * Pandas
    * Random sampling
  * Sklearn
    * Train test split
  * Imblearn
    * SMOTE
    * Random Sampler
* Model building & evaluation
  * Sklearn
    * Cross Validation
    * Grid search
    * Pipeline
    * Extra tree model
    * Autoencoder
  * Classification report
  * Confusion matrix
  * Precision and recall curve
* Model selection
  * Pycaret
