# Bach_Chorale_Harmony_Ensemble_technique
The dataset we use is Bach Chorale Harmony Data. The dataset contains information of 60 chorales which are divided into 5665 events, each event was described by event number, occurrence of 12 pitches (12 features), bass, meter and chord label.  Analyse the dataset and classify the Chord label by applying machine learning classification using ensemble techniques..

The reason to use the ensemble techniques to perform the multiclass classification as this make better predictions and achieve better performance than any single contributing model.This techniques combines the predictions from two or more models and improved the robustness or reliability in the average performance of a model.

Here we are using the max voting method of ensembling technique with the help of Voting Classifier using the Sklearn library .It is generally used for classification problems. In this technique, multiple models are used to make predictions for each data point. The predictions by each model are considered as a ‘vote’. The predictions which we get from the majority of the models are used as the final prediction.

We have used this approach for classification because its methodology utilizes the collective judgment of multiple classifiers for predicting data points and give the perfect accuracy.
